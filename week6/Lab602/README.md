# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
   ![570610544](http://www.mediafire.com/convkey/db3d/0j4spnt1nr74t9zzg.jpg)
2. Detail explaination about the identified pattern and all the parcipants

      รูปแบบของโปรแกรมเป็นแบบ Abstract Factory

      โดย -Abstract class Document เป็น abstract Factory ทำหน้าที่ประกาศ interface สำหรับการสร้าง product

         - class Report และ Resume เป็น ConcreteFactory คือ class ที่สืบทอดมาจาก Document และมีการสร้าง Product

         - Abstract class Page เป็น Abstract Product ทำหน้าที่ประกาศ Interface สำหรับชนิดของ product นั้น ๆ

         - class BibliographyPage , SummaryPage , ConclusionPage , ResultsPage , IntroductionPage ,
          SkillPage , EducationPage , ExperiencePage เป็น Product ที่สืบทอดมาจาก Page
        
