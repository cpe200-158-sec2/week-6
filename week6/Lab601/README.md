# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
	= ![570610609](http://www.mx7.com/i/677/WGAPf1.jpg)
2. Detail explaination about the identified pattern and all the parcipants
	= It is Abstract Factory Medthod 
		- class ContinentFactory is AbstractFactory
		- class AmericaFactory and AfricaFactory are ConcreteFactory
		- class AnimalWorld is Client
		- class Herbivore and Carnivore are AbstractProduct
		- class Wildebeest,Bison,Wolf,Lion are Product
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
	= ![570610609](http://www.mx7.com/i/e03/AAfzY5.jpg)
  - Test the new requirment by modifying the main function and show the result.
	= ![570610609](http://www.mx7.com/i/c7f/gYyHjz.jpg)
  - Show the main function and snippet of C# code that is related to the process.
	
	class MainApp
  {
    public static void Main()
    {
      ContinentFactory africa = new AfricaFactory();
      AnimalWorld world = new AnimalWorld(africa);
      world.RunFoodChain();
 
      ContinentFactory america = new AmericaFactory();
      world = new AnimalWorld(america);
      world.RunFoodChain();

      ContinentFactory asia = new AsiaFactory();
      world = new AnimalWorld(asia);
      world.RunFoodChain();
            // Wait for user input
      Console.ReadKey();
    }

