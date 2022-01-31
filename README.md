import java.util.*;

public class vbn{

    public static void main(String args[]) {

        Scanner sc=new Scanner(System.in);

        int a;

         int b;

        int c;

        int d=0;

        System.out.println("Enter the value the variable:");

        a=sc.nextInt();

        System.out.println("Enter the value the another variable:");

        b=sc.nextInt();

        System.out.println("Enter the operation which you want to do:");

        c=sc.nextInt();

        switch(c){

        case 1:

            

        d=a+b;

        System.out.println("Sum="+d);

        break;

        case 2:

        d=a-b;

        System.out.println("difference="+d);

        break;

        case 3:

        d=a*b;

        System.out.println("product="+d);

        break;

        case 4:

        d=a/b;

        System.out.println("Quotient="+d);

        break;

        case 5:

        d=a%b;

        System.out.println("remainder="+d);

        break;

        default:

        System.out.println("ERROR");

        }

    }

}
