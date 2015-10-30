# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
	 ![570610618](http://www.mx7.com/i/aa3/QTzU0g.jpg)
2. Detail explaination about the identified pattern and all the parcipants
        - Pattern : Abstract Factory (Provide an interface for creating families of related objects)
	- Abstract Factory : ContinentFactory (declares an interface for operations that create abstract products)
        - Concrete Factory : AfricaFactory, AmericaFactory (implements the operations to create concrete product objects)
        - Abstract Product : Herbivore, Carnivore (declare an interface for a type of product object)
        - Product : Wildebeest, Bison, Wolf, Lion (created by the oncreteFactory and implements the AbstractProduct)
        - Client : AnimalWorld (creates a new object by asking a prototype to clone itself)
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
      ![570610618](http://www.mx7.com/i/e24/TwNUaq.jpg)
  - Test the new requirment by modifying the main function and show the result.
      ![570610618](http://www.mx7.com/i/e68/jdavdm.png)
  - Show the main function and snippet of C# code that is related to the process.
    ContinentFactory asian = new AsianFactory();      
	world = new AnimalWorld(asian);      
	world.RunFoodChain();
	class AsianFactory : ContinentFactory      
	{	 
	    public override Herbivore CreateHerbivore()	 
     	    { 	   
	      return new Elephant();	
	    }	
	    public override Carnivore CreateCarnivore()	 
	    {	   
	      return new Tiger();
	    }       
	}       
	class Elephant : Herbivore       
	{       
	}       
	class Tiger : Carnivore       
	{	 
	  public override void Eat(Herbivore h)	 
	  {	    
	    // Eat Elephant            
	    Console.WriteLine(this.GetType().Name + " eats " + h.GetType().Name);         
	  }	
	}
