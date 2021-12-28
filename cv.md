# Anastasia Yepihova

## Novice Web Developer

## Contact information:
### Phone: #### +375 (33) 664-91-73
### Email: #### anastasiayepihova@gmail.com
### Telegram: #### @userAna
### Instagram: #### nastya_epihova

## Aim:
My aim at the moment is to study Frontend development. This is a fascinating, thought-provoking, creative industry, I have always wanted to realize myself in this area. I plan to work and develop in this field in the future.

## Skills:
* HTML5, CCS
* JavaScript Basics, Python, C#
* Git, GitHub
* VS Code, Microsoft VS

## Code example:
Определить, является ли строка палиндромом. Палиндром – это число, слово или фраза, одинаково читающиеся в обоих направления.

``` C#
using System;
using System.Linq;

namespace ConsoleApp1
{
    class Program
    {
        static bool IsPalindrome(string str)
        {
            return str == new string(str.Reverse().ToArray());
        }

        static void Main()
        {
            
            Console.Write("Введите строку: ");
            var str = Console.ReadLine();
            var result = IsPalindrome(str);
            var message = "Является ли строка '" + str + "' палиндромом: " + result;

            Console.WriteLine(message);

            Console.ReadKey();

        }
    }
}

```

## Education
Completed basic general education, at this time I'm studying at a college in the specialty "Information technology software".

## Languages:
* English - Intermediate
* Russian - Native
* Ukrainian - Upper Intermediate
* Belarusian - Native
* Lithuanian - Beginner
* Polish - Beginner