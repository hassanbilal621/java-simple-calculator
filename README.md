# java-simple-calculator

package calculator;

import java.util.Scanner;

public class Calculator {
    
    public static void main(String[] args) {

        Scanner ob=new Scanner(System.in);
        System.out.println("Enter the First value ? ");
        int value1=ob.nextInt();
        System.out.println("Enter the Secound Value ? ");
        int value2=ob.nextInt();
        System.out.println("Type Method | add = 1 | subtract = 2 | multiply = 3 | Devide = 4");
        int method=ob.nextInt();
        int a = 1;
        int b = 2;
        int c = 3;
        int d = 4;
        if(method==a){
            int finalresult = value1 + value2;
            System.out.println("Your addition of " + value1 + " + " + value2 + " = " + finalresult );
        }
        else if(method==b){
            int finalresult = value1 - value2;
            System.out.println("Your Subtraction of " + value1 + " - " + value2 + " = " + finalresult );
        }
        else if(method==c){
            int finalresult = value1 * value2;
            System.out.println("Your multiplication of " + value1 + " x " + value2 + " = " + finalresult );
        }
        else if(method==d){
            int finalresult = value1 / value2;
            System.out.println("Your division of " + value1 + " / " + value2 + " = " + finalresult );
        }
        else {
            System.out.println("Please type Correct Method");
        }
  
    }
    
}
