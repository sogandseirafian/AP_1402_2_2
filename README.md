# AP_1402_2_2
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_10_CS
{
    internal class Program
    {
        static void Main(string[] args)
        { //برنامه ای بنویسید که نمره 20 دانشجو دریافت و معدل را چاپ کند 
            Console.WriteLine("Please enter a score of 20 student;");
            double score;
            double sum=0;
            for(int i=1;i<=20;i++)
            {

                score = Convert.ToDouble(Console.ReadLine());
                sum = score+sum;
            }
            sum = sum / 20;
            Console.WriteLine("avg is" + sum);




        }
    }
}
