using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace RecuperaciónProgramaciónComputacionalI
{
    class MainClass
    {
        public static void Main(string[] args)
        {
            int RandomNumberEasy = new Random().Next(1, 50);
            int RandomNumberIntermediate = new Random().Next(1, 100);
            int RandomNumberHard = new Random().Next(1, 500);

            Console.WriteLine("=============================================");
            Console.WriteLine("Hola! Bienvenid@ al juego |Adivina el número|");
            Console.WriteLine("=============================================");
            Console.WriteLine("-----------------------------");
            Console.WriteLine("Que dificultad deseas probar?");
            Console.WriteLine("-----------------------------");

            var levels = new string[] { "Fácil", "Intermedia", "Difícil" };
            for (int i = 0; i < levels.Length; i++)
            {
                Console.WriteLine("------------------------");
                Console.WriteLine(levels[i]);
                Console.WriteLine("------------------------");
            }

            string level = Console.ReadLine();

            if (level == "facil")
            {
                int Tries = 0;

                while (Tries <= 3)
                {

                    Console.WriteLine("Que número piensas que es?");

                    Int32 number = Convert.ToInt32(Console.ReadLine());

                    if (number == RandomNumberEasy)
                    {
                        Console.WriteLine("---------");
                        Console.WriteLine("Correcto!");
                        Console.WriteLine("---------");
                        Console.WriteLine("Me leiste la mente! Gracias por jugar, hasta pronto!");
                    }
                    if (number > RandomNumberEasy)
                    {
                        Console.WriteLine("Eso es un numero alto al que pienso, prueba otra vez!");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (3 - Tries));
                        Console.WriteLine("----------------------------------");
                    }
                    if (number < RandomNumberEasy)
                    {
                        Console.WriteLine("No es tan bajo como yo lo imagino...");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (3 - Tries));
                        Console.WriteLine("----------------------------------");
                    }

                    if (Tries == 3)
                    {
                        Console.WriteLine("Tus intentos maximos acabaron...");
                        Console.WriteLine("Suerte a la próxima");
                        Console.ReadKey();
                    }
                }
            }

            if (level == "intermedio")
            {
                int Tries = 0;

                while (Tries <= 4)
                {

                    Console.WriteLine("Que número piensas que es?");

                    Int32 number = Convert.ToInt32(Console.ReadLine());

                    if (number == RandomNumberIntermediate)
                    {
                        Console.WriteLine("---------");
                        Console.WriteLine("Correcto!");
                        Console.WriteLine("---------");
                        Console.WriteLine("Me leiste la mente! Gracias por jugar, hasta pronto!");
                    }
                    if (number > RandomNumberIntermediate)
                    {
                        Console.WriteLine("Eso es un numero alto al que pienso, prueba otra vez!");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (4 - Tries));
                        Console.WriteLine("----------------------------------");
                    }
                    if (number < RandomNumberIntermediate)
                    {
                        Console.WriteLine("No es tan bajo como yo lo imagino...");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (4 - Tries));
                        Console.WriteLine("----------------------------------");
                    }

                    if (Tries == 4)
                    {
                        Console.WriteLine("Tus intentos maximos acabaron...");
                        Console.WriteLine("Suerte a la próxima");
                        Console.ReadKey();
                    }
                }
            }

            if (level == "dificil")
            {
                int Tries = 0;

                while (Tries <= 5)
                {

                    Console.WriteLine("Que número piensas que es?");

                    Int32 number = Convert.ToInt32(Console.ReadLine());

                    if (number == RandomNumberHard)
                    {
                        Console.WriteLine("---------");
                        Console.WriteLine("Correcto!");
                        Console.WriteLine("---------");
                        Console.WriteLine("Me leiste la mente! Gracias por jugar, hasta pronto!");
                    }
                    if (number > RandomNumberHard)
                    {
                        Console.WriteLine("Eso es un numero alto al que pienso, prueba otra vez!");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (5 - Tries));
                        Console.WriteLine("----------------------------------");
                    }
                    if (number < RandomNumberHard)
                    {
                        Console.WriteLine("No es tan bajo como yo lo imagino...");
                        Tries++;
                        Console.WriteLine("----------------------------------");
                        Console.WriteLine("Intentos restantes: " + (5 - Tries));
                        Console.WriteLine("----------------------------------");
                    }

                    if (Tries == 5) 
                    {
                        Console.WriteLine("Tus intentos maximos acabaron...");
                        Console.WriteLine("Suerte a la próxima");
                        Console.ReadKey();
                    }
                }
            }

            Console.ReadKey();
        }
    }
}
