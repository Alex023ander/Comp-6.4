# Comp-6.4

import java.util.Scanner;

public static void main(String[] args) {
		//runs 100 times
	Scanner scan = new Scanner(System.in);
	System.out.println("How many bottle of beer are there?");
            int num = scan.nextInt();
            for (; num>0; num--)
            {
            printVerse.printVerse(num);
            }
    }
    
    public class printVerse {
	//prints verse
        public static void printVerse(int numberOfBottles)
        {
            System.out.println(numberOfBottles 
            + " bottles of beer on the wall\n" 
            + numberOfBottles 
            + " bottles of beer" 
            + "\nIf one of those bottles should happen to fall\n" 
            + (numberOfBottles - 1 )
            + " bottles of beer on the wall\n");
        }
    }
}
