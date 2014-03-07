A2
==

A2 pascal
package ce1002.a2.s991002050;
import java.util.Scanner;
public class A2 {

	private static Scanner Scanner;

	public static void main(String[] args) 
	    {
		// TODO Auto-generated method stub
		int N;
		Scanner = new Scanner(System.in);
		System.out.print("Please input a number (1~10): ");
	int array[][];
		{
			N = Scanner.nextInt();
			if (N < 1 || N > 10)
				System.out.print("Out of range!\nPlease input again (1~10): ");
		} while (N < 1 || N > 10);	
		}
}



