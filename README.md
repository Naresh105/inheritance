# inheritance
using System;

// Base class
class Animal
{
    public void Eat()
    {
        Console.WriteLine("This animal is eating.");
    }
}

// Derived class
class Dog : Animal
{
    public void Bark()
    {
        Console.WriteLine("The dog is barking.");
    }
}

class Program
{
    static void Main()
    {
        // Create an object of the derived class
        Dog myDog = new Dog();

        // Call methods from both base and derived classes
        myDog.Eat();  // Inherited method from Animal class
        myDog.Bark(); // Method from Dog class
    }
}
