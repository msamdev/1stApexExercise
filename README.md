# 1stApexExercise
1.	Write a program to a specified number of generate fibonacci series. 
Note: Read the required count from the keyboard

package asignments;

public class Fibonacci {

	public static void main(String[] args) {
		
		int a=1, b=1;
		
		
		for (int i=1; i<=9; i++)
		{
			 System.out.print(a + " + ");
			int sum = a + b;
			a = b;  //cheated for this part but I do not know why a should be plus b
			b=sum;
				
		}

	}

}



/*
 * 3. Write a class BasicCalulator.java to provide basic mathematical operation like
 * additional, subtractions, multiplications, and division  
 * for two numbers. Write a client to use above class and call its operations.
 */

package asignments;

import java.util.Scanner;
public class Calculator {

	public static void main(String[] args) {
		
		Scanner mycalc = new Scanner (System.in);
		
		double num1, num2, result;
		
		//Addition Code
		
		System.out.println("Enter 1st Num for Addition ");
		num1 = mycalc.nextDouble();
		System.out.println("Enter 2nd Num for Addition ");
		num2 = mycalc.nextDouble();
		result = num1+num2;
		System.out.println(result);
		
				
		//Subtraction Code
		
		System.out.println("Enter 1st Num for Subtraction ");
		num1 = mycalc.nextDouble();
		System.out.println("Enter 2nd Num for Subtraction ");
		num2 = mycalc.nextDouble();
		result = num1-num2;
		System.out.println(result);
		
		//Multiplication Code
		
		System.out.println("Enter 1st Num for Multiplicaiton ");
		num1 = mycalc.nextDouble();
		System.out.println("Enter 2nd Num for Multiplication ");
		num2 = mycalc.nextDouble();
		result = num1*num2;
		System.out.println(result);
		
		//Division Code
		
		System.out.println("Enter 1st Num for Devision ");
		num1 = mycalc.nextDouble();
		System.out.println("Enter 2nd Num for Division ");
		num2 = mycalc.nextDouble();
		result = num1/num2;
		System.out.println(result);
		
		System.out.println("Congratulations You Are So Good In Math");
		
	}

}



/*
 * 5.	Generate following
 * •	Generate 1000 numbers
 * •	Generate multiple of 5 and less than 1000
 * •	Generate odd numbers up to 1000
 */


package asignments;

public class NumberGeneration {

	public static void main(String[] args) {

		System.out.println("1000 Numbers");
		//int n=1000;
		for (int i=0; i<=1000; i++)
		{
			System.out.println(i);
		}
		
		System.out.println("===========================");
		System.out.println("5 Step Numbers");
		//int n=1000;
		for (int i=0; i<=1000; i=i+5)
		{
			System.out.println(i);
		}
		
		
		System.out.println("Odd Numbers");
		//int n=1000;
		for (int i=0; i<=1000; i=i+3)
		{
			System.out.println(i);
		}
		
	}

}


/*
 * 6.	Define a arrary with 10 integers and print all the elements 
 * with its index number.
 */

package asignments;

public class ArrayIndexing {

	public static void main(String[] args) {
		
		int a[] = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
		
		for (int i=0; i<=a.length; i++){
		
		System.out.println(i + "  " + a[i]);
		}
		

	}

}
