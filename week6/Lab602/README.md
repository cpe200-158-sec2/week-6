# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
	![570610565](https://www.dropbox.com/s/7immefjijfp6xdw/lab602.jpg?dl=0)
2. Detail explaination about the identified pattern and all the parcipants
	1. Document as AbstractFactory for declares an interface for operations that create abstract group-of-page types (Resume, Report).

	2. Resume and Report as ConcreteFactory for implements the operations to create concrete Page objects (Type-of-Page like exp, edu, skill, etc.).

	3. Page as AbstractProduct for declare an interface for a type of Page objects.

	4. Type-of-Page like exp, edu, skill, etc. as Product for defines a page objects to be created by the concrete factory (Resume, Report) and implements the AbstractProduct (Page) interface.