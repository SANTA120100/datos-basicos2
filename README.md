using System;

namespace ConsoleApp20
{
    class Program
    {
        static void Main(string[] args)
        {
            String Nombre;
            StringCons ApellidoPaterno;
            String ApellidoMaterno;
            int Edad;
            String Ocupacion;
            String Correo;
String Mes;

            Console.WriteLine("Ingresa Tu nombre");
            Nombre = Console.ReadLine();
            Console.WriteLine(Nombre);


Console.WriteLine("Ingresa tu Ocupacion:");
Ocupacion= Console.ReadLine();
Console.WriteLine(Ocupacion);

Console.WriteLine("Ingresa tu correo:");
Correo=Console.Readline();
Console.WriteLine(Correo);


Console.WriteLine("Ingresa tu edad: ");
            Edad = Convert.ToInt32(Console.ReadLine());
            if (Edad <= 18)
            {
                Console.WriteLine("El usuario es menor de edad, Registro Fallido");
            }
        }
    }
}
