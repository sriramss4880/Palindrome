# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1: Start

Step 2: Create a class and declare two variable with string datatype

Step 3: Loop over the entire string and reverse it

Step 4: Use if condition to check whether the string and the reversed string is equal or not

Step 5: print palindrome if it's equal else print not a palindrome.

Step 6: stop the program
## Program:
Name : ARUN KUMAR SUKDEV CHAVAN

Reg.No : 212222230013
```
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine("Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--) //String Reverse  
            {
                revs += s[i].ToString();
            }
            if (revs == s) // Checking whether string is palindrome or not  
            {
                Console.WriteLine("String is Palindrome\nEntered String Was {0} and reverse string is {1}", s, revs);
            }
            else
            {
                Console.WriteLine("String is not Palindrome\nEntered String Was {0} and reverse string is {1}", s, revs);
            }
            Console.ReadKey();
        }
    }
}
```

## Output:
![exp02](https://github.com/arunkumarsukdevchavan/Palindrome/assets/118343978/74e362aa-71e4-400b-8c34-4e5e6bb4c544)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
