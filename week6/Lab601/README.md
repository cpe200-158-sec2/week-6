# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610612](https://scontent-kul1-1.xx.fbcdn.net/hphotos-xfp1/v/t34.0-12/12166928_536848943137219_234569148_n.jpg?oh=bd3a17446ac9d602a070507bac619e0d&oe=561EE4EB)

2. Detail explaination about the identified pattern and all the parcipants
  - Pattern : Abstract Factory (Provide an interface for creating families of related objects)
  - Abstract Factory : ContinentFactory (declares an interface for operations that create abstract products)
  - Concrete Factory : AfricaFactory, AmericaFactory (implements the operations to create concrete product objects)
  - Abstract Product : Herbivore, Carnivore (declare an interface for a type of product object)
  - Product : Wildebeest, Bison, Wolf, Lion (created by the oncreteFactory and implements the AbstractProduct)
  - Client : AnimalWorld (creates a new object by asking a prototype to clone itself)
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
   ![570610612](https://fbcdn-sphotos-e-a.akamaihd.net/hphotos-ak-xal1/v/t35.0-12/12163036_536862173135896_1830157103_o.jpg?oh=3df1a851cc6520dc2f9f429e07bbe44b&oe=561DE30D&__gda__=1444856026_63e75b5ef5a210d4ca4b18371fc16e9a)
  - Test the new requirment by modifying the main function and show the result.
    ![570610612](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xfp1/v/t34.0-12/12166788_536848946470552_699070204_n.jpg?oh=159e660e14c9b771215d992a5028937a&oe=561E0CAF&__gda__=1444858309_7c250e7f5d54bab7a706685483e60e89)
  - Show the main function and snippet of C# code that is related to the process.
   ![570610612](https://scontent-kul1-1.xx.fbcdn.net/hphotos-xta1/v/t34.0-12/12166440_536850056470441_1393802823_n.jpg?oh=df7b2d9f8c3626b1b8973299132eb8cd&oe=561DB846)

