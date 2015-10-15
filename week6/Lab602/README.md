# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610555](https://fbcdn-sphotos-g-a.akamaihd.net/hphotos-ak-xtf1/v/t35.0-12/12165310_1059369627448832_1293918079_o.jpg?oh=02f10a3741530262c087e8d918feff2a&oe=5622C00F&__gda__=1445045227_0538bfeb53caedeb767f926ea02226c8)

2. Detail explaination about the identified pattern and all the parcipants
Ans:
  - Page เป็น abtract classซึ่งเป็นabstract product โดยมีproductมาสืบทอด คือ class BibliographyPage , SummaryPage , ConclusionPage , ResultsPage , IntroductionPage ,SkillPage , EducationPage และ ExperiencePage 
  - Abstract class Document เป็น Abstract Factory โดยมี class Report และ class Resume ซึ่งเป็น ConcreteFactory มาสืบทอด
