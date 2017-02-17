1)	Write a program to accepts two numbers from “stdin” and find all the odd as well as even numbers present in between them.

import java.util.ArrayList;
import java.util.Scanner;

public class acad 
{ 
	public static void main(String[] args)
	{ 

	Scanner s=new Scanner(System.in); 
	int a=s.nextInt(); 
	int b=s.nextInt(); 
    ArrayList <Integer>odd=new ArrayList(); 
    ArrayList <Integer>even=new ArrayList(); 
    for(int i=a;i<=b;i++)
    { 
    	if(i%2==0) even.add(i);
    	else odd.add(i);
    }
     System.out.println("Odd numbers are:");
    for(int i:odd) 
    	{
    	System.out.print(i+" "); 
    	}
    System.out.println("\nEven numbers are:"); 
    for(int i:even) 
    	System.out.print(i+" "); 
    } 
	}


















2)	Joe is scared to go to school. When her dad asked the reason, joe said she is unable to complete the task given by her teacher. The task was to find the “first 10 multiples” of the number entered from stdin.

import java.util.Scanner;

public class acad 
{ 
	public static void main(String[] args)
	{ 
		Scanner s=new Scanner(System.in); 
		int n=s.nextInt(); 
	System.out.println("Input: "+n); 
	System.out.println("O/p:"); 
	for(int i=1;i<=10;i++)
	{ 
		System.out.println(n+" * "+i+" = "+(n*i));
	}
	}
}

3)	Write a program consisting method sum() and demonstrate the concept of method overloading using this method.

import java.util.Scanner;

public class acad
{
public static void main(String[] args)
{
Scanner s=new Scanner(System.in);
int a=s.nextInt();
int b=s.nextInt();
int c=s.nextInt();
sum(a,b);
sum(a,b,c); 
}
public static void sum(int a,int b)
{
 System.out.println("Sum of first 2 numbers is: "+(a+b));
}
public static void sum(int a,int b,int c)
{
System.out.println("Sum of all 3 numbers is: "+(a+b+c));
}
}

