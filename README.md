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

