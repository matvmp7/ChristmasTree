using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ChristmasTree
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter the number of lines: ");
            int num = int.Parse(Console.ReadLine());
            int i = 0, x = 0, j = 0, l = 0, m = 0, sharp = 0, space = 0;

            for (i = 1; i <= num; i++)
            {
                sharp = i * 2 - 1;
                space = i + num - sharp;
                for (x = 0; x < space; x++)
                {
                    Console.Write(" ");
                }
                for (j = 0; j < sharp; j++)
                {
                    Console.Write("#");
                }
                Console.Write("\n");
            }
            for (l = 0; l < 3; l++) 
            {
                for (m = 0; m < (num * 2 + 1) / 2; m++)
                {
                    Console.Write(" ");
                }
                Console.Write("#\n");
            }
            Console.ReadLine();
        }
    }
}
