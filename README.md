# TALLERES-DE-ULTIMA-GENERACION
Taller de ultima generacion
//primer código 

using System;
namespace trabajo1
{ 
public class program
{
        public static void Main(string[] args)
        {
            Console.Write("ingresa el nombre porfavor");

    string nombre = Console.ReadLine();

    Console.WriteLine("Hola, " + nombre );
        }

 }
// segundo codigo
using System;
namespace trabajo1
{
    public class program
    {
        public static void Main(string[] args)
        {
            Console.Write("ingresa el nombre porfavor");

            
            string nombre = Console.ReadLine();

            Console ForegroundColor= ConsoleColor.Red;
            
            Console.WriteLine("Hola, " + nombre + "❤️ ");
            
        }

    }
}



// tercer codigo
using System;
namespace trabajo1
{
    public class program
    {
        public static void Main(string[] args)
        {
            string nombre = "sean sierra ";
            int edad = 18;
            Console.WriteLine("nombre:"+nombre + "edad" +edad);
            
        }

    }
}


// cuarto codigo
using System;
namespace trabajo1
{
    public class program
    {
        public static void Main(string[] args)
        {
            string nombre = "sean sierra ";
            int edad = 18;
            Console.WriteLine(string.Format("nombre: {0}, edad {1}",nombre,edad));
            
        }

    }
}
