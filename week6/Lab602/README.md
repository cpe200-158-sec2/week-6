# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
   = ![570610609](http://www.mx7.com/i/aa5/6sN5cp.jpg)	
2. Detail explaination about the identified pattern and all the parcipants
   = Its pattern is a Factory Medthod because subclasses can	decide which class to instantiate and can define an interface for creating an object.
	>>> Its participants <<<
	- Product : class Page
	- ConcreteProduct : class skillspage, class EducationPage, class ExperiencePage, class IntroductionPage, class ResultsPage, class ConclusionPage, class SummaryPage, class BibliographyPage
	- Creator : class Document
	- ConcreteCreator : class Resume, class Report

