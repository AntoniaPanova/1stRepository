# 1stRepository
MixCodes

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ComparingStrings
{
    class Program
    {
        static void Main(string[] args)
        {
            string s = "Antonia";
            string s1 = "Antonia";
            string s2 = "Pesho";
            if (s == s1)
            {
                Console.WriteLine("True");  //dava otgovor true
            }
            else
            {
                Console.WriteLine("Niama suvpadenie ");
            }
            if (s == s2)
            {
                Console.WriteLine("True"); 
            }
            else
            {
                Console.WriteLine("Niama suvpadenie "); //dava otgovo"niama suvpadenie pri tova uslovie
            }

            if (s.Equals(s1))
            {
                Console.WriteLine("true"); //tuk otnovo dava otgovor true,so == e ednakvo na Equals
            } 
        }
    }
}
