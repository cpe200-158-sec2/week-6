# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
	![570610588](https://raw.githubusercontent.com/cpe200-158-sec2-0588/week-6/master/week6/AnimalWorldv2.png)

2. Detail explaination about the identified pattern and all the parcipants
	The pattern of the program is Factory Abstract Method. Interface must be defined for creating an object and inherit to subclass.

3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
	![570610588](https://raw.githubusercontent.com/cpe200-158-sec2-0588/week-6/7496bbbb2ad104f5193a9fcadf98bcc6f6791349/week6/AnimalWorldwithAsian.png)

  - Test the new requirment by modifying the main function and show the result.
	![570610588](https://raw.githubusercontent.com/cpe200-158-sec2-0588/week-6/d392e996cfff9d0873f0d1ab0fd497d916e714fc/test.jpg)

  - Show the main function and snippet of C# code that is related to the process.
	ContinentFactory asia = new AsianFactory();
    world = new AnimalWorld(asia);
    world.RunFoodChain();
