// Yug Purohit
import java.util.*;
public class Calculator_Ver1   // This program is made by using multiple methods
{
    static int Sum(int x,int y )
    {
        return x+y;
    }
    static int Subtract(int x,int y )
    {
        return x-y;
    }
    static int multiply(int x,int y )
    {
        return x*y;
    }
    static int divide(int x,int y )
    {
        return x/y;
    }
    static int remainder(int x,int y )
    {
        return x%y;
    }
    
    
    public static void main(String args[])
  {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the values...");
        int a=sc.nextInt();
        int b=sc.nextInt();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println("Entered values:");
        System.out.println(a);
        System.out.println(b);
        System.out.println("Enter 1 to Add two values:");
        System.out.println("Enter 2 to Subtract two values:");
        System.out.println("Enter 3 to Multiply two values:");
        System.out.println("Enter 4 to Divide two values:");
        System.out.println("Enter 5 to find  Remainder two values:");
        System.out.println();
        System.out.println("Enter your choice:");
        int choice=sc.nextInt();
        System.out.println("You've entered:"+choice);
      switch(choice)
    {
        case 1:
            {
                int c=Sum(a,b);
                System.out.println("Addition of two numbers="+c);
                break;
            }
        case 2:
                {
                  int c=Subtract(a,b);
                  System.out.println("Subtraction of two numbers="+c);
                  break;
               }
       case 3:
                   {
                      int c=multiply(a,b);
                      System.out.println("Product of two numbers="+c );
                      break;
                   }
       case 4:
                       {
                          int c=divide(a,b);
                          System.out.println("Quotient of two numbers="+c);
                          break;
                       }
       case 5:
                           {
                              int c=remainder(a,b);
                              System.out.println("Remainder of two numbers="+c);
                              break;
                           }
    default:
    System.out.println("Error");
    }
  }
}
