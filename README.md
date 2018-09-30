//number of basic input and output for integer character  string anf float
//package com.tcc.java.program;

import java.io.*;
import java.util.Scanner;
public class ionumber
{
	public static void main(String args[])
	{
		int a;
		char ch;
		String st; 
		float f;
		Scanner sc=new Scanner(System.in);
		System.out.println("enter Strng value::");
		st=sc.nextLine();
		System.out.println("enter Integer value::");
		a=sc.nextInt();
		System.out.println("enter character value::");
		ch=sc.next().charAt(0);
		System.out.println("enter float value::");
		f=sc.nextFloat();
		System.out.println("strng value of st %s is:\n"+st);
	    System.out.println("integer value of a %d is:\n"+a);
		System.out.println("character value of ch %c is::\n"+ch);
		System.out.println("float value of f is::%f is:\n"+f);
	}
}
