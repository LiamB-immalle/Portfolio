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

- Drew a pinguin and refactored the code: [pinguin](https://github.com/LiamB-immalle/pinguin)
- Finished my clickergame: [Clicker](https://github.com/LiamB-immalle/Clicker)

- Started a game to learn how timers work, it's not yet working though: [timergame](https://github.com/LiamB-immalle/timergame) -> never finished

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

- Learned how to make classes yesterday by [Bloons](https://github.com/LiamB-immalle/bloons)
- Followed by [Balloons](https://github.com/LiamB-immalle/Balloons)

# Javascript

- started learning javascript, seems to be really similar to C# which i am already used to.
