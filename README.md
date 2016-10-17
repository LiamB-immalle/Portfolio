# CSharp
'''CS
using System;
					
public class Program
{
	public static void Main()
	{
		double euro = Dollartoeuro(37.50);
		Console.WriteLine("37.50 dollar is {0} euro", euro);
		
		double vol = KubusVolume(1.2);
		Console.WriteLine("kubus met ribbe 1.2 heeft een opp van {0}", vol);
	}
	
	private static double Dollartoeuro(double dollar){
		
		double change = dollar * 0.91;
		return change;
	}
	
	private static double KubusVolume(double r){
		
		double vol = r*r*r;
		return vol;
	}
}
'''




# Javascript
