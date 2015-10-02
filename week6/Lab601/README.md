# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
+![570610615](https://fbcdn-sphotos-c-a.akamaihd.net/hphotos-ak-xat1/v/t35.0-12/12084796_1090193911031590_988775296_o.jpg?oh=115cd36890f6b67fd3aeebc3a0d42113&oe=56109C00&__gda__=1443931797_8d200a2f2612543ef597a143ce0187fb)
2. Detail explaination about the identified pattern and all the parcipants
-
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
  +![570610615](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xap1/v/t35.0-12/12082811_1090195864364728_437084225_o.jpg?oh=8a4d22a6892a4f2e196e1788d093ce31&oe=5610F31C&__gda__=1443928329_26392d1f4939cc0151036fbbafb4a270)
  - Test the new requirment by modifying the main function and show the result.
  +![570610615](https://scontent-hkg3-1.xx.fbcdn.net/hphotos-xpa1/v/t34.0-12/12071881_1090196811031300_1236306132_n.jpg?oh=01d6e5229706eab9d77a9a7f883bf721&oe=56108CE0)
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


 
