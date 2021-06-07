# Amstrong
/* Lab 2.3Write a program to verify whether the number is Armstrong or not.*/

import java.util.Scanner;

class ArmstrongNumber

{

	public static void main(String args[])	{

		int n,a,r,sum=0;

		Scanner s=new Scanner(System.in);

		System.out.print("Enter a number: ");

		n=s.nextInt();

		a=n;

		while(n!=0)

		{

			r=n%10;

			sum=sum+(r*r*r);

			n=n/10;

		}

		if(sum==a)

		{

			System.out.format("%d is a armstrong number",n);

		}

		else

		{

			System.out.format("%d is not a armstrong number",n);

		}

	}

}
