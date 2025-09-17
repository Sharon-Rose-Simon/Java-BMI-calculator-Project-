# Java-BMI-Calculator-Project
This is my Java-based Project that demonstartes my understanding of developing a console-based Body Mass Index (BMI) Calculator application. The program takes user input for weight and height, calculates the BMI and provides feedback on the user's weight category of whether they are underweight, normal weight, overweight or obese. This project highlights my skills and understanding of Java Basics such as input handling with Scanner, arithmetic operations, conditional statements, and console output formatting. 

# What I have Learned: 
- How to take and validate user input in Java using Scanner
- Performing arithmetic operations and calculations in Java
- Using conditional statements such as if-else
- I have learned and deepened my knowledge and understanding in structuring a simple console application

# Skills Used:
- Java Programming Skills
- Input handling and Output formatting
- Control flow with conditional statements

# Tools Used: 
- IntelliJ IDEA
- Java Development Kit
- Console/Terminal = For running the program
- Git and GitHUB for version control and Management 

# Code Implementation: 

import java.util.Scanner;
public class BMI {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Welcome to the BMI Calculator!");

        System.out.println("Enter your weight in Kilograms ? ");
        double weight = scanner.nextDouble();

        System.out.println("Enter your height in Kilograms ?");
        double height = scanner.nextDouble();

        double BMI_sum = weight / (height * height);
        System.out.printf("Your BMI is:", BMI_sum);

        if(BMI_sum < 18.5) {
            System.out.println("You are Underweight");
        } else if (BMI_sum < 25){
            System.out.println("You are Normal Weight");
        } else if (BMI_sum < 30) {
            System.out.println("You are Overweight");
        } else{
            System.out.println("You are Obese");
        }
        scanner.close();
    }
}

# Project File Link: 
- I have attached the full source code below:  
[BMI.java](https://github.com/user-attachments/files/22369151/BMI.java)


