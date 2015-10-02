# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610544](http://www.mediafire.com/convkey/553a/ja05cd8oc0asdcazg.jpg)

2. Detail explaination about the identified pattern and all the parcipants
    รูปแบบของโปรแกรมเป็นแบบ Abstract Factory 
    โดย - ContinentFactory เป็น abstract Function 
        - AficaFactory และ AmericaFactory เป็น ConcreteFactory 
        - Herbivore และ Carnivore เป็น Abstract Product
        - lion wolf เป็น Product ที่สืบทอดมาจาก Carnivore
        - wildebeest bison เป็น Product ที่สืบทอดมาจาก Herbivore
        - AnimalWorld เป็น client 

  ContinentFactory is an Abstract Class consisted only with Abstract Method; resemble to Abstract Factory.
  AfricaFactory and AmericaFactory both are Concrete Factory that implement ContinentFactory.
  Herbivore and Carnivore are Abstract Product providing interface for product object.
  Bison, Wildebeest, Lion and Wolf are Product implementing methods and created by Concrete Factory.
  AnimalWorld is Client that configure/assign variables and methods.

3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
![570610544](http://www.mediafire.com/convkey/3e82/be1rhwgo2c4j5cfzg.jpg)
  - Test the new requirment by modifying the main function and show the result.
![570610544](http://www.mediafire.com/convkey/5abf/yoiavyi83bcgfygzg.jpg)
  - Show the main function and snippet of C# code that is related to the process.
![570610544](http://www.mediafire.com/convkey/4ab9/1lpq186n74s9d4ozg.jpg)
![570610544](http://www.mediafire.com/convkey/2c73/yd79n64221s1xbzzg.jpg)

