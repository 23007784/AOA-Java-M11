
# EX 1A Print All Numbers 
## DATE: 05.08.25
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line.

## Algorithm
1.Start the program.

2.Read an integer input N from the user.

3.Check if N is less than or equal to 0.

4.If yes, display the message: "Invalid input. N must be greater than 0."

5.If N is greater than 0, use a for loop to iterate from 1 to N.

6.Print each number separated by a space on the same line.  

## Program:
```
/*
Program to implement Reverse a String
Developed by: NIKSHITHA G
Register Number: 212223110031
*/

import java.util.*;
public class Sum
{
    public static void main(String a[])
    {
        int n;
        Scanner sc=new Scanner(System.in);
        n = sc.nextInt();
        if(n>0)
        {
            for(int i=1;i<=n;i++)
            {
                System.out.print(i+ " ");
            }
        }
        else
        {
            System.out.println("Invalid Input n mistake greater than 0.");
        }
        sc.close();
    }
}
```

## Output:

<img width="438" height="273" alt="image" src="https://github.com/user-attachments/assets/1f54b40d-e750-4100-af10-091d6e4a4d4f" />

## Result:
The program successfully print all the numbers from 1 to N. 
