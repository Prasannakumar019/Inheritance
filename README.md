# Inheritance

## Aim:
 To write a C# program to print some messages using hierarchical inheritance
 
## Algorithm:

## Program:
```
using System;
namespace abc
{
    class Tyre
    {
        public Tyre()
        {
            Console.Write("Tyre has been inserted ");
        }
    }
    class Scooter : Tyre
    {
        public void display()
        {

            Console.Write("For the scooter ");
        }

    }
    class Car : Tyre
    {
        public void display()
        {

            Console.Write("For the car ");
        }

    }

    public class yz
    {
        public static void Main(string[] args)
        {
            Scooter s1 = new Scooter();
            s1.display();
            Console.WriteLine();
            Car c1 = new Car();

            c1.display();
        }
    }

}
```


## Output:
![image](https://user-images.githubusercontent.com/75235090/172824796-aa4cd9b4-5448-4714-85fe-6844683a1ffa.png)


## Result
Thus a C# program to print some messages using hierarchical inheritance has implemented successfully
