# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610564](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xap1/v/t34.0-12/12077405_891275027616423_1246979541_n.jpg?oh=e483735ef79dc2749b26aed5e8c7e03d&oe=5610D87E)

2. Detail explaination about the identified pattern and all the parcipants
  - ContinentFactory is an Abstract Class consisted only with Abstract Method; resemble to *Abstract Factory*.
  - AfricaFactory and AmericaFactory both are *Concrete Factory* that implement ContinentFactory.
  - Herbivore and Carnivore are *Abstract Product* providing interface for product object.
  - Bison, Wildebeest, Lion and Wolf are *Product* implementing methods and created by *Concrete Factory*.
  - AnimalWorld is *Client* that configure/assign variables and methods.
  
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
![570610564](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpa1/v/t35.0-12/12085247_891280237615902_516991075_o.jpg?oh=d1699ac3a853700f0cc38cdd584dfd11&oe=560FD4AD)
  - Test the new requirment by modifying the main function and show the result.
  - Show the main function and snippet of C# code that is related to the process.
![570610564](https://fbcdn-sphotos-b-a.akamaihd.net/hphotos-ak-xal1/v/t34.0-12/12092681_891280404282552_1408138374_n.jpg?oh=bf1f2f644a89efa3efb6ad943bd84e80&oe=561098F5&__gda__=1443955106_1a1d13f3afe2027848ddce0faecb5655) ![570610564](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xlt1/v/t34.0-12/12084085_891280780949181_822341951_n.jpg?oh=7d20bb6639b3239af0590b27d9a4d8ef&oe=561099EF)
