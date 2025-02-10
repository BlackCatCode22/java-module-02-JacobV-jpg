//1.Reverse_String

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        System.out.println("Type in a String");
        String input = sc.nextLine();
        String reverseString = new StringBuilder(input).reverse().toString();
        System.out.println("Done");
        System.out.println("The reversed string is: " + reverseString);
        
        }

    }


//2. Maddness_Method




