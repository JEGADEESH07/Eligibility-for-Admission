# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

Step 1: Create a new Class named admission.
Step 2: Create variable of respective data types to store marks & name.
Step 3: Calculate the total and store it.
Step 4: The Conditions for admission are: 1.Marks in maths >= 65 & Marks in physics >=55 & Marks in chemistry >=50 2.Total marks in all three subjects >= 180 or total in maths and physics >= 140
Step 5: Using Nested to check whether the person is eligible for admission based on the above conditions.
Step 6: Print the status for admission.
Step 7: End of the program.

## Program:
```c#

using System;

namespace EngineeringAdmission
{
    class Program
    {
        static void Main(string[] args)
        {
            int maths, physics, chemistry;
            Console.WriteLine("Welcome to Engineering Admission Eligibility Checker");

            Console.Write("Enter Math marks: ");
            maths = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Physics marks: ");
            physics = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Chemistry marks: ");
            chemistry = Convert.ToInt32(Console.ReadLine());

            int totalMarks = maths + physics + chemistry;

            if (maths >= 65 && physics >= 55 && chemistry >= 50)
            {
                if (totalMarks >= 180)
                {
                    Console.WriteLine("Congratulations! You are eligible for admission.");

                }
                else
                {
                    Console.WriteLine("Sorry, you are not eligible for admission.");

                }
            }
            else
            {
                Console.WriteLine("Sorry, you are not eligible for admission.");

            }
        }
    }
}


```



## Output:
![image](https://github.com/JEGADEESH07/Eligibility-for-Admission/assets/113497131/337f6f35-f218-43fb-a14b-7543cba2466b)
![image](https://github.com/JEGADEESH07/Eligibility-for-Admission/assets/113497131/46bbcd87-4d32-4c0e-9781-356db4d0ef5f)



## Result:
A C# program is written to find the eligibility for admission to an engineering course and has been successfully executed.
