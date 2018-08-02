*/
Write a program that prompts the user
to enter the month and year and displays the number of days in the month. For
example, if the user entered month 2 and year 2012, the program should display
that February 2012 had 29 days. If the user entered month 3 and year 2015, the
program should display that March 2015 had 31 days. */

# Extra_Ex3_11

package com.personal.Exra3_11;

import java.util.Scanner;

public class Extra3_11 {

	public static void main(String[] args) {
	 Scanner sc = new Scanner(System.in);
		int year, month,heapMonth;
		System.out.print
	      ("Enter The number of a year :  ");
		year=sc.nextInt();
		
		System.out.print
	      ("Enter The number its month :  ");
	    month = sc.nextInt();
	    
	    if (heapyear(year) && month==2) {
	    	System.out.print
		      ("The time is February " + year + "(heap year) had 28 days " );
	    	System.exit(0);
	    }
		    	
	    
	    switch (month) {
		case 1:
			System.out.print
		      ("The time is January " + year );
		    
			break;
		case 2:
			System.out.print
		      ("The time is February " + year );
			break;

		case 3:
			System.out.print
		      ("The time is March " + year + " had 31 days" );
			break;

		case 4:
			System.out.print
		      ("The time is April " + year + " had 28 days");
			break;

		case 5:
			System.out.print
		      ("The time is May "+ year+ " had 31 days" );
			break;

		case 6:
			System.out.print
		      ("The time is June "+ year + " had 30 days" );
			break;

		case 7:
			System.out.print
		      ("The time is July " + year+ " had 31 days" );
			break;

		case 8:
			System.out.print
		      ("The time is August " + year+" had 31 days" );
			break;

		case 9:
			System.out.print
		      ("The time is Sebtember " + year +" had 30 days");
			break;
			
		case 10:
			System.out.print
		      ("The time is October " + year+" had 31 days" );
			break;

		case 11:
			System.out.print
		      ("The time is November " + year+ " had 30 days" );
			break;

		case 12:
			System.out.print
		      ("The time is December " + year+ " had 31 days" );
			break;

		default:
			break;
		}
	    
	}
	
	public static boolean heapyear(int heap) {
		
		if (heap%4 ==0)
			return true;
		else 
			return false;
			
		
	}

}
