# Arithmatic_operator
using java language.


import java.util.Scanner;
class Arithmatic
{
   public static void main(String args[])
   {
      int a,b;
      System.out.print("Enter the two numbers..... ");
      Scanner obj=new Scanner(System.in);
      a=obj.nextInt();
      b=obj.nextInt();
      System.out.println("Addition "+(a+b));
      System.out.println("Substraction "+(a-b));
      System.out.println("Multiplication "+(a*b));
      System.out.println("Division "+(a/b));
      System.out.println("Reminder "+(a%b));
   }
 }  
      
