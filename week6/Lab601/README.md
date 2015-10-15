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
![570610555](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpt1/v/t35.0-12/12116077_1052621251457003_1748200746_o.jpg?oh=88f34084b0e07f284d454c3174be4b34&oe=561CD43B&__gda__=1444704784_f4b2def57e4877a5c4c7b18b6166e1da)
  - Test the new requirment by modifying the main function and show the result.
![570610555](https://fbcdn-sphotos-g-a.akamaihd.net/hphotos-ak-xta1/v/t34.0-12/12077366_1052623094790152_821833890_n.jpg?oh=65d0a5190d33743051b0eb041c5b16b8&oe=561CD045&__gda__=1444713145_2f0b9c04da622f119726694271facb20)
  - Show the main function and snippet of C# code that is related to the process.
![570610555](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpt1/v/t34.0-12/12067866_1052623598123435_283131417_n.jpg?oh=5b47c78cf95f23e125aeed1ed6ce2869&oe=5610FB99)
![570610555](https://fbcdn-sphotos-a-a.akamaihd.net/hphotos-ak-xat1/v/t34.0-12/12048870_1052626441456484_512508214_n.jpg?oh=0d8961a743e5433255d5d390e978574b&oe=561CCD64&__gda__=1444723633_afb800f219429005b593c3071022b923)
![570610555](https://scontent-kul1-1.xx.fbcdn.net/hphotos-xpt1/v/t34.0-12/12086963_1052626801456448_1170272364_n.jpg?oh=278039df931656eeb30b6b86435b8105&oe=561BB6A2)
