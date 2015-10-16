# Lab602: Identify design pattern and participants from program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# program. 

## Submission: a written report which contains

1. A class diagram of the original source code
   ![570610564](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpa1/v/l/t34.0-12/12166364_896494280427831_499748899_n.jpg?oh=4226b215e599acd26e04d2083a6630ff&oe=562265CD)
2. Detail explaination about the identified pattern and all the parcipants
  - รูปแบบของโปรแกรมเป็น Factory Method
- Document เป็น Factory ทำหน้าที่สร้าง Concrete Factory ของ Class อื่นๆ
- Report Resume เป็น Concrete Factory ที่สร้างขึ้นจาก Factory ที่ชื่อว่า Document
- Page เป็น Abstract Product ให้กับ Concrete Productตัวอื่นๆ
- และ SkillPage EducationPage ResultPage...etc คือ Concrete Product
