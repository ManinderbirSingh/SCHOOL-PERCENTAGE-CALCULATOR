# SCHOOL-PERCENTAGE-CALCULATOR
SCHOOL MARKS PERCENTAGE CALCULATOR 
This is Java Programming Code for Calculating Percentage for Exams :

// hello,this is my cbse board percentage calculator for Exams

import java.util.Scanner;

class Main {

 public static void main(String[] args) {

Scanner sc = new Scanner(System.in);

System.out.println("Marks of English ");

float a = sc.nextFloat();

System.out.println("Marks of Maths");

float b = sc.nextFloat();

System.out.println("Marks of Science");

float c = sc.nextFloat();

System.out.println("Marks of Social Studies");

float d = sc.nextFloat();

System.out.println("Marks of Hindi");

float e = sc.nextFloat();

 

float Percentage = ((a+b+c+d+e)/500)*100;

System.out.println("Your Percentage is:" + Percentage);

 

 

 }

}
