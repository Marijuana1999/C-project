using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Calculator
{
    class Program
    {
        static void Main(string[] args)
        {

            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40, 1);
            Console.Write("╔═══════════════════════════════════════════╗");
            Console.SetCursorPosition(40, 2);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 3);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 4);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 5);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 6);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 7);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 8);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 9);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 10);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 11);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 12);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 13);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 14);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 15);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 16);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 17);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 18);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 19);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 20);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 21);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 22);
            Console.Write("║                                           ║");
            Console.SetCursorPosition(40, 23);
            Console.Write("╚═══════════════════════════════════════════╝");

            //  CODE


            
            Console.SetCursorPosition(54,1);
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.Write("CONSOLE CALCULATOR");

            Console.ForegroundColor = ConsoleColor.White;

            Console.SetCursorPosition(48, 3);
            Console.ForegroundColor = ConsoleColor.DarkYellow;
            Console.Write("[            ] [            ]");



            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40, 8);
            Console.Write("╠═══════════════════════════════════════════╣");
            Console.SetCursorPosition(41, 9);
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("1.CALC A+B :");
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40,10);
            Console.Write("╠═══════════════════════════════════════════╣");


            Console.SetCursorPosition(40, 11);
            Console.Write("╠═══════════════════════════════════════════╣");
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.SetCursorPosition(41, 12);
            Console.WriteLine("2.CALC A*B :");
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40, 13);
            Console.Write("╠═══════════════════════════════════════════╣");

            Console.SetCursorPosition(40, 14);
            Console.Write("╠═══════════════════════════════════════════╣");
            Console.SetCursorPosition(41, 15);
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("3.CALC A/B :");
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40, 16);
            Console.Write("╠═══════════════════════════════════════════╣");

            Console.SetCursorPosition(40, 17);
            Console.Write("╠═══════════════════════════════════════════╣");
            Console.SetCursorPosition(41, 18);
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("4.CALC A-B :");
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.SetCursorPosition(40, 19);
            Console.Write("╠═══════════════════════════════════════════╣");


            Console.ForegroundColor = ConsoleColor.DarkYellow;
            Console.SetCursorPosition(47, 22);
            Console.WriteLine("5.EXIT ");
            Console.SetCursorPosition(66, 22);
            Console.WriteLine("6.CHANGE NUMBER ");

            Console.ForegroundColor = ConsoleColor.Blue;
            Console.SetCursorPosition(49, 3);
            int a = int.Parse(Console.ReadLine() + "          ");
            Console.SetCursorPosition(64, 3);
            int b = int.Parse(Console.ReadLine() + "          ");



            Console.SetCursorPosition(40, 5);
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.WriteLine("╠═══════════════════════════════════════════╣");
            Console.SetCursorPosition(50, 6);
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("NUMBER : {0}    NUMBER : {1}", a, b);
            Console.SetCursorPosition(40, 7);
            Console.ForegroundColor = ConsoleColor.Magenta;
            Console.WriteLine("╠═══════════════════════════════════════════╣");



            Console.ForegroundColor = ConsoleColor.Blue;
            Console.SetCursorPosition(41, 20);
            Console.Write("Enter Number(1 - 6) :");
            
            Console.SetCursorPosition(63, 20);
            Console.Write("[ ]");
            Console.SetCursorPosition(64, 20);
            int num = int.Parse(Console.ReadLine());

            while (num >= 1 & num <= 6)
            {
                if (num == 1)
                {
                    Console.SetCursorPosition(54, 9);
                    Console.WriteLine(a + b + "                ");
                }

                if (num == 2)
                {
                    Console.SetCursorPosition(54, 12);
                    Console.WriteLine(a * b + "                ");
                }

                if (num == 3)
                {
                    Console.SetCursorPosition(54, 15);
                    Console.WriteLine(a / b + "                ");
                }

                if (num == 4)
                {
                    Console.SetCursorPosition(54, 18);
                    Console.WriteLine(a - b + "                ");
                }
                if (num == 5)
                {
                    Console.Clear();
                    Console.SetCursorPosition(20, 13);
                    Console.ForegroundColor = ConsoleColor.Red;
                    Console.Write("{ THE PROGRAM DOES NOT WORK CUZ YOU PRESS 5 KEY PLEASE CLOSE THE APP AND RUN AGAIN}");
                    break;
                    
                }
                if (num == 6)
                {

                    Console.ForegroundColor = ConsoleColor.DarkYellow;
                    Console.SetCursorPosition(48, 3);
                    Console.Write("[            ] [            ]");
                    Console.ForegroundColor = ConsoleColor.Blue;
                    Console.SetCursorPosition(49, 3);
                    a = int.Parse(Console.ReadLine());
                    Console.SetCursorPosition(64, 3);
                    b = int.Parse(Console.ReadLine());

                    Console.SetCursorPosition(50, 6);
                    Console.WriteLine("NUMBER : {0}    NUMBER : {1}", a, b );

                }


                Console.SetCursorPosition(64, 20);

                num = int.Parse(Console.ReadLine());
                Console.SetCursorPosition(63, 20);
                Console.Write("[ ]");
            }



            Console.ReadKey();
        }
    }
}
