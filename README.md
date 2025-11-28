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
//codigo 12
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        Console.Write("Ingrese su nombre completo: ");
        string nombre = Console.ReadLine();
        Console.Write("Ingrese su edad: ");
        int edad = int.Parse(Console.ReadLine());
        Console.Write("ingrese su direccion");
        string direccion = Console.ReadLine();
        Console.Write("Ingrese su email");
        string email = Console.ReadLine();
        Console.WriteLine("------------------------");
        Console.WriteLine("Nombre: " + nombre);
        Console.WriteLine("Edad: " + edad);
        Console.WriteLine("Direccion: " + direccion);
        Console.WriteLine("Email: " + email);
    }
}

//codigo trece 
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        double x = Math.Pow((2 + 4), 2);
        double y = Math.Pow((4 * 8), 3);
        double resultado = x / y;
        Console.WriteLine("el resultado es" + resultado);
    }
}

//codigo catorce
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        int max = Math.Max(5, 10);
        Console.WriteLine("el valor maximo es: " + max);
    }
}

//codigo quince
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        int min = Math.Min(5, 10);
        Console.WriteLine("el valor minimo es: " + min);
    }
}

//codigo dieciseis
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        double raiz = Math.Sqrt(64);
        Console.WriteLine("La raiz de 64 es: " + raiz);
    }
}

//codigo dieciciete
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        double valorabs = Math.Abs(-4.7);
        Console.WriteLine("El valor absoluto es: " + valorabs);
    }
}

//codigodieciocho
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        double redondeado = Math.Round(9.99);
        Console.WriteLine("El valor redondeado de 9.99 es: " + redondeado);
    }
}

//codigo diescinueve
using System;
public class Proto1
{
    public static void Main(string[] args)
    {
        double x = Math.Pow((2 + 4), 2);
        double y = Math.Pow((4 * 8), 3);
        double resultado = x / y;
        Console.WriteLine("el resultado es: " + resultado);
        double redondeado = Math.Round(resultado);
        Console.WriteLine("El valor redondeado del resultado es: " + redondeado);
    }

//codigo veinte

using System;
class Proto1
{
    public static void Main(string[] args)
    {
        string txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        Console.WriteLine("La longitud del texto es de: " + txt.Length);
    }
}

//codigo21
using System;
class Proto1
{
    public static void Main(string[] args)
    {
        Console.Write("ingrese su direccion: ");
        string direccion = Console.ReadLine();
        Console.WriteLine("------------------------");
        Console.WriteLine("Direccion: " + direccion);
        Console.WriteLine("La longitud de la direccion es de: " + direccion.Length);
    }
}
//codigo23 para solicitar que el ingreso de datos no este vacio
using System;

public class Proto1
{
    public static void Main(string[] args)
    {

        string nombre = "";
        while (string.IsNullOrWhiteSpace(nombre))
        {
            Console.Write("Ingrese su nombre completo: ");
            nombre = Console.ReadLine();

            if (string.IsNullOrWhiteSpace(nombre))
            {
                Console.WriteLine(" Error debe ingresar su nombre.");
            }
        }
        string nombremayus = nombre.ToUpper();

        string edadTexto = "";
        while (string.IsNullOrWhiteSpace(edadTexto))
        {
            Console.Write("Ingrese su edad: ");
            edadTexto = Console.ReadLine();

            if (string.IsNullOrWhiteSpace(edadTexto))
            {
                Console.WriteLine(" Error la edad no puede estar vacía.");
            }
        }

        int edad = int.Parse(edadTexto);

        string direccion = "";
        while (string.IsNullOrWhiteSpace(direccion))
        {
            Console.Write("Ingrese su dirección: ");
            direccion = Console.ReadLine();

            if (string.IsNullOrWhiteSpace(direccion))
            {
                Console.WriteLine("Error debe ingresar una dirección.");
            }
        }

        string email = "";
        while (string.IsNullOrWhiteSpace(email))
        {
            Console.Write("Ingrese su email: ");
            email = Console.ReadLine();

            if (string.IsNullOrWhiteSpace(email))
            {
                Console.WriteLine("Error debe ingresar un email.");
            }
        }
        string emailminus = email.ToLower();

        Console.WriteLine("------------------------");
        Console.WriteLine("Nombre: " + nombremayus);
        Console.WriteLine("Edad: " + edad);
        Console.WriteLine("Dirección: " + direccion);
        Console.WriteLine("Email: " + emailminus);
    }
//codigo24
}
using System;
class Car
 
{
  private string model = "Mustang";

  static void Main(string[] args)
  {
    Car myObj = new Car();
    Console.WriteLine(myObj.model);
  }
}
//codigo25 
using System;

class Car
{
  public string model = "Mustang";
}

class Program
{
  static void Main(string[] args)
  {
    Car myObj = new Car();
    Console.WriteLine(myObj.model);
  }
}

