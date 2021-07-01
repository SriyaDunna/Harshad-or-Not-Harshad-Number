# Harshad-or-Not-Harshad-Number
import java.util.*;
class harshadnumber
{
 public static void main(String args[])
{
Scanner sc = new Scanner (System.in);

System.out.print("Enter a number");
 int num= sc.nextInt();
 int y = num, z, sum = 0;

 while (y>0)  {
z = y%10;
sum = sum + z;
 y = y/10;
 }
 if(num%sum == 0)
 {
     System.out.println(num+" is a harshad number"); 
 }
     else
     {
         System.out.println(num+" is not a a harshad number");
     }
}
}
