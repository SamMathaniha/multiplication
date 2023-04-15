# multiplication

import java.util.Scanner;

public class Table {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        //User input
        System.out.print("Enter a number: ");
        int number = scanner.nextInt();

        System.out.println("Multiplication table for " + number + ":");
        
        //for loop to get until 10 times
        for (int i = 1; i <= 10; i++) {
            System.out.println(number + " x " + i + " = " + (number * i));
        }
    }
}






