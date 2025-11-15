EX 1A Print All Numbers
DATE: 07/8/2025
AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

Algorithm
Start the program and import the Scanner class to take user input.
Create a Scanner object to read an integer input N from the user.
Check if N is greater than 0; if not, display "Invalid input. N must be greater than 0."
Use a for loop to iterate from 1 to N.
Print each number separated by a space on the same line.
Program:
/*
Program to implement Reverse a String
Developed by: Prakasam P
Register Number: 212222040118
*/

import java.util.*;
public class PrintNum{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
        }
    }
}
Output:
<img width="609" height="195" alt="image" src="https://github.com/user-attachments/assets/2a580e07-4c2b-4519-9f42-62afeaf380bf" />

Result:
The program successfully print all the numbers from 1 to N.
