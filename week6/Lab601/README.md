# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
+![570610615](https://fbcdn-sphotos-c-a.akamaihd.net/hphotos-ak-xat1/v/t35.0-12/12084796_1090193911031590_988775296_o.jpg?oh=d21148c1efe422be9a5e7895b0dfff73&oe=5621BF80&__gda__=1445054997_fd9f31221a12b88ffe9a77ef673b5898)
2. Detail explaination about the identified pattern and all the parcipants
-
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
  +![570610615](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xap1/v/t35.0-12/12082811_1090195864364728_437084225_o.jpg?oh=57d0ed4ce305860a5ac7d0bd14c1439f&oe=5622BF5C&__gda__=1445051529_f82ea3936fc7ccf517a90411c9edb7e4)
  - Test the new requirment by modifying the main function and show the result.
  +![570610615](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpa1/v/t34.0-12/12071881_1090196811031300_1236306132_n.jpg?oh=3e4ec2bd9b2666365d1a5264909f5310&oe=5621B060)
  - Show the main function and snippet of C# code that is related to the process.
  
  class MainApp
  {
    public static void Main()
    {
      ContinentFactory africa = new AfricaFactory();
      AnimalWorld world = new AnimalWorld(africa);
      world.RunFoodChain();
 
      ContinentFactory america = new AmericaFactory();
      world = new AnimalWorld(america);
      world.RunFoodChain();

      ContinentFactory asian = new AsianFactory();
      world = new AnimalWorld(asian);
      world.RunFoodChain();
 
      // Wait for user input
      Console.ReadKey();
    }
  }


 
