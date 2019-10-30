# MultiplicationOfNumbersUsersInput






using System;

public class Exercise6
{
    public static void Main(string[] args)
    {
        int numx, numy, numz;
        Console.Write("Input the first number ");
        numx = Convert.ToInt32(Console.ReadLine());
        

        Console.Write("Input the second number ");
        numy = Convert.ToInt32(Console.ReadLine());
      

        Console.Write("Input the third number ");
        numz = Convert.ToInt32(Console.ReadLine());
 

        Console.WriteLine(numx * numy * numz);

    }
}
