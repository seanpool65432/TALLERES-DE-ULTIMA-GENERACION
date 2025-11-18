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
//octavo codigo
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
     int myInt = 10;
     double myDouble = 5.25;
     bool myBool = true;
     
     Console.WriteLine(Convert.ToString(myInt));
     Console.WriteLine(Convert.ToDouble(myInt));
     Console.WriteLine(Convert.ToInt32(myDouble));
     Console.WriteLine(Convert.ToString(myBool));
    }
  }
}
// noveno codigo 
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Ingresa el nombre");
      string userName = Console.ReadLine();

      Console.WriteLine("Ingresa el apellido ");
      string Apellido = Console.ReadLine();

      Console.WriteLine("Ingresa la edad ");
      int Edad = int.Parse(Console.ReadLine());

      Console.WriteLine("El usuario es: " + userName + ", Apellido: " + Apellido + ", Edad: " + Edad);
    }
  }
}
// decimo code
Nombre Sean Pool Sierra Ortega

 
using System;
class Program
{
    static void Main(string[] args)
    {
        Console.Write("Ingresa el valor de x: ");
        int x = int.Parse(Console.ReadLine());

        Console.Write("Ingresa el valor de y: ");
        int y = int.Parse(Console.ReadLine());

        int suma = x + y;
        Console.WriteLine("La suma es: " + suma);

        int multiplicacion = x * y;
        Console.WriteLine("La multiplicación es: " + multiplicacion);

        int resta = x - y;
        Console.WriteLine("La resta es: " + resta);
        int modulo = x % y;
        Console.WriteLine("El módulo es: " + modulo);
    }
}

// once codigo
using System;
class Program
{
  { Console.WriteLine("ingrese la edad ");
  int edad = int.Parse(Console.ReadLine());
  Console.WriteLine("su edad es " + edad);
   
   }
}
