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

// quinto codigo 
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      int myInt = 9;
      double myDouble = myInt; 
      Console.WriteLine(myInt);
      Console.WriteLine(myDouble);
    }
  }
}

//sexto codigo 
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      int myInt = 15;
      double myDouble = myInt; 
      Console.WriteLine(myInt);
      Console.WriteLine(myDouble);
    }
  }
}                

// septimo codigo 
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      double myDouble = 5.31;
      int myInt = (int) myDouble;  

      Console.WriteLine(myDouble);
      Console.WriteLine(myInt);
    }
  }
}
