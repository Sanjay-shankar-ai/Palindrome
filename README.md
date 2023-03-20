# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:

### Step1:
Start the program.

### Step2:
Create a class and declare two variable with string datatype.

### Step3:
Loop over the entire string and reverse it.

### Step4:
Use if condition to check whether the string and the reversed string is equal or not.

### Step5:
Print palindrome if it's equal else print not a palindrome.

### Step6:
End the program.

## Program:
```
Delevoped By : sanjay s
Reg No: 212221230086
```
```
using System;
namespace exp2
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, rev = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                rev += s[i];
            }
            if (rev == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```
## Output:
![2023-03-20 (4)](https://user-images.githubusercontent.com/94231938/226283517-33a972d9-8094-4a6b-88a0-a20eab0bb8b8.png)

![2023-03-20](https://user-images.githubusercontent.com/94231938/226283010-4a56e0d8-47f4-4747-b2aa-5f5c8d8de147.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
