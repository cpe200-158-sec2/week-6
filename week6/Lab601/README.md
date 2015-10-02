# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xta1/v/t35.0-12/12116231_1052620774790384_760509384_o.jpg?oh=46850649e3efeef7c631f09c044153e0&oe=56108575)
2. Detail explaination about the identified pattern and all the parcipants

  +รูปแบบ Abstract Factory

  +Class ContinentFactory เป็น Abstract Class

  +class AfricaFactory และ AmericaFactory เป็น ConcreteFactory

  +มีAbstrat Product คือ class Herbivore และ Carnivore 

  +class  wildebeest และ bison เป็นclassที่สืบทอดจาก Herbivore ส่วนclass lion และwolfเป็นclassที่สืบทอดจากCarnivore

  +มีClient คือ AnimalWorld

3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
![570610555](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpt1/v/t35.0-12/12116077_1052621251457003_1748200746_o.jpg?oh=978b7e5a6cb4fba93fb5fe044e9f246f&oe=5610F6BB&__gda__=1443927184_4fdda67eed73bda079b44b6636175989)
  - Test the new requirment by modifying the main function and show the result.
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xta1/v/t34.0-12/12077366_1052623094790152_821833890_n.jpg?oh=0395bf38f37135819627c29e003271b9&oe=5610F2C5)
  - Show the main function and snippet of C# code that is related to the process.
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpt1/v/t34.0-12/12067866_1052623598123435_283131417_n.jpg?oh=5b47c78cf95f23e125aeed1ed6ce2869&oe=5610FB99)
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xat1/v/t34.0-12/12048870_1052626441456484_512508214_n.jpg?oh=bf24e1668993a4cc8237913f03f78893&oe=5610EFE4)
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpt1/v/t34.0-12/12086963_1052626801456448_1170272364_n.jpg?oh=72f0aba9f70e5148828f914946663c9b&oe=561081E2)
