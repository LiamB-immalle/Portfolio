# CSharp
- Made a little exercise about mathematic formulas
``` CSharp
using System;
					
public class Program
{
	public static void Main()
	{
		double euro = DollarToEuro(37.50);
		Console.WriteLine("37.50 dollar is {0} euro", euro);
		
		double vol = KubusVolume(1.2);
		Console.WriteLine("kubus met ribbe 1.2 heeft een opp van {0}", vol);
	}
	
	private static double DollarToEuro(double dollar){
		
		double change = dollar * 0.91;
		return change;
	}
	
	private static double KubusVolume(double r){
		
		double vol = r*r*r;
		return vol;
	}
}
```

- Drew a pinguin and refactored the code: https://github.com/LiamB-immalle/pinguin
- Finished my clickergame: https://github.com/LiamB-immalle/Clicker

- Started a game to learn how timers work, it's not yet working though: https://github.com/LiamB-immalle/timergame

- Tried the FizzBuzzTest and came up with this solution:

``` CSharp
for (var i = 1; i <= 100; i++)
            {
                if (i % 3 == 0)
                {
                    if (i % 5 == 0)
                    {
                        Console.WriteLine("fizzbuzz");
                    }
                    else
                    {
                        Console.WriteLine("fizz");
                    }
                }
                else if (i % 5 == 0)
                {
                    Console.WriteLine("buzz");
                }
                else
                {
                    Console.WriteLine(i);
                }
            }
```
- Got a struggle in class: i made an exercise which worked with the wrong output although the guys with the right output had exactly the same code. I hope to be able to fix it next class.

# Javascript
