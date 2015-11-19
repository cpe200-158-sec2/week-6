# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
  ![570610581](http://www.mx7.com/i/507/ZEgQdH.jpg)
2. Detail explaination about the identified pattern and all the parcipants
   It is a Factory method pattern because It defines an interface for creating an object and let subclasses decide which class to instantiate
   Product : Page (defines the interface of objects the factory method creates)
   ConcreteProduct : SkillsPage, EducationPage, ExperiencePage, IntroductionPage, ResultsPage, ConclusionPage, SummaryPage, and BibliographyPage (implements the Product interface) 
   Creator : Document (declare the factory method, which returns an object of type Product)
   ConcreteCreator : Resume and Report (overrides the factory method to return an instance of a ConcreteProduct)
