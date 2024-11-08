using System;

public class Program
{
    public static void Main(string[] args)
    {
        // Simple "Hello, World!" program
        Console.WriteLine("Hello, World!");

        // Get user input
        Console.WriteLine("Enter your name:");
        string name = Console.ReadLine();
        Console.WriteLine($"Hello, {name}!");

        // Basic arithmetic
        int num1 = 5;
        int num2 = 10;
        int sum = num1 + num2;
        Console.WriteLine($"Sum of {num1} and {num2} is: {sum}");

        // Conditional statement (if-else)
        if (sum > 10)
        {
            Console.WriteLine("Sum is greater than 10");
        }
        else
        {
            Console.WriteLine("Sum is not greater than 10");
        }

        // Loop (for loop)
        for (int i = 0; i < 5; i++)
        {
            Console.WriteLine($"Iteration {i + 1}");
        }

        // Arrays
        int[] numbers = { 1, 2, 3, 4, 5 };
        Console.WriteLine("Numbers in the array:");
        foreach (int number in numbers)
        {
            Console.WriteLine(number);
        }
    }
}
