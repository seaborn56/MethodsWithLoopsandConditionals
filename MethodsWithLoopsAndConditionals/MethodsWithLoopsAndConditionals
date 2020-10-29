using System;

namespace MethodsWithLoopsAndConditionals
{
    class Program
    {
        static void Main(string[] args)
        {
            //Counter();

            //PauseConsole();
           
            //CounterThree();

            //PauseConsole();

            //int userNum1 = GetUserNumber();
            //int userNum2 = GetUserNumber();
            //bool areEqual = EqualChecker(userNum1, userNum2);
            //Console.WriteLine($"{userNum1} is equal to {userNum2}: {areEqual}");

            //PauseConsole();

            //EvenOrOdd(userNum1);

            //PauseConsole();

            //userNum1 = GetUserNumber();

            //PositiveOrNegative(userNum1);

            Console.Write("Please tell me your age and we will tell you if you can vote!");

            int age;
            while (int.TryParse(Console.ReadLine(), out age));
            {
                Console.WriteLine("Could not compute, try again");

            }
            AgeChecker(age);
       }

        private static void AgeChecker(int userAge)
        {
            if (userAge >=18)
            {
                Console.WriteLine("You may vote!");
            }
            else
            {
                Console.WriteLine("Too young try again when older!");
            }
        }



        private static void PositiveOrNegative(int num1)
        {
            if (num1 > 0)
            {
                Console.WriteLine("The number is positive");
            }
            else
                Console.WriteLine("the number is negative");

        }




        private static void EvenOrOdd(int userNumber)
        {
            if (userNumber % 2 == 0)
            {
                Console.WriteLine($"{userNumber} is even!!");
            }
            else if (userNumber % 2 != 0)
            {
                Console.WriteLine($"{userNumber} is odd!!!");
            }
            else
            {
                Console.WriteLine("I have no clue what that is! Maybe it Zero??");
            }


        }



        private static int GetUserNumber()
        {
            Console.Write("Give me a number: ");
            int userNumer = int.Parse(Console.ReadLine());

            return userNumer;

        }

        private static bool EqualChecker(int num1, int num2)
        {
            return num1 = num2;
        }

        private static void CounterThree();
        {

            for (int i = 3, i <= 999; i += 3)
            {
                Console.WriteLine(i);
            }

        }

        private static void Counter()
        {

            int goal = -1000;

            for (int i =1000; i >=goal; i--)
            {
                Console.WriteLine(i);
            }

        }

        private static void PauseConsole()
    {
        //Console.WriteLine();
        //Console.ReadLine();

    }
    }
}
