# dsoncode
random code
using System;

class Program
{
    static void Main(string[] args)
    {
        // Greet the user
        Console.WriteLine("Hello! What's your job?");
        
        // Read the user input
        string userName = Console.ReadLine();

        // Display a personalized message
        Console.WriteLine("Hello, " + userName + "! Welcome to C# programming.");

        // Ask for the user's age
        Console.WriteLine("How old are you?");
        
        // Read the age as a string, then convert it to an integer
        int userAge = Convert.ToInt32(Console.ReadLine());

        // Display a message based on the user's age
        if (userAge >= 18)
        {
            Console.WriteLine("You are an adult.");
        }
        else
        {
            Console.WriteLine("You are a minor.");
        }

        // End of program message
        Console.WriteLine("Press any key to exit.");
        Console.ReadKey(); // Wait for the user to press a key before closing
    }
}
