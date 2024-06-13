using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Sum
{
    class Sum
    {

        public void Add(int a, int b)
        { 
            int c=a+b;
            Console.WriteLine("Sum Is"+ " "+ c);
        }
        public void Sub(int a, int b)
        {
            int c = a - b;
            Console.WriteLine("Difference Is" + " " + c);
        }

    }

    
    internal class Program
    {
        static void Main(string[] args)
        {
            int a;
            int b;
            Console.WriteLine( "Enter A and B");
            a =Convert.ToInt32(Console.ReadLine());
            b = Convert.ToInt32(Console.ReadLine());
            Sum obj= new Sum();
            obj.Add(a, b);
            obj.Sub(a, b);
             
        }
    }
}
