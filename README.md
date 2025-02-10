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

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int first = getAnIntFromTheUser("Type the first integer: ");
        int second = getAnIntFromTheUser("Type the second integer: ");

        int comparisonResult = compareTwoInts(first, second);

        if (comparisonResult == 1) {
            System.out.println(first + " is equal to " + second);
        } else if (comparisonResult > 1) {
            System.out.println(first + " is greater than " + second);
        } else {
            System.out.println(first + " is less than " + second);
        }

        int sum = sumTwoInts(first, second);
        System.out.println("The sum of the two numbers is: " + sum);
    }
    public static int getAnIntFromTheUser(String prompt) {
        Scanner sc = new Scanner(System.in);
        System.out.print(prompt);
        int Inte = sc.nextInt();
        return Inte;
    }
    public static int compareTwoInts(int a, int b) {
        if (a == b) {
            return 1;
        } else if (a > b) {
            return 2;
        } else {
            return 0;
        }
    }
    public static int sumTwoInts(int a, int b) {
        return a + b;
    }
}


//3.LargestOfThree.java





