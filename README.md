# UsersInput






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

using System;

class Exercise7
{
    public static void Main(string[] args)
    {
        int num1, num2;

        Console.WriteLine("Input the first number ");
        num1 = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine("Input the second number ");
        num2 = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine(num1 + num2);
        Console.WriteLine(num1 - num2);
        Console.WriteLine(num1 * num2);
        Console.WriteLine(num1 / num2);
        Console.WriteLine(num1 % num2);

        Console.ReadLine();

    }
}
