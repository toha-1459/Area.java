# Area.java
package AreaCalculator;
import java.util.Scanner;
public class Area {
    public static void main (String[] arges){
        Scanner out =new Scanner(System.in);
        System.out.print("Squre Area.\ngive  lenth s= " );
        int k = out.nextInt();
        k*=k;
        System.out.println("A= " + k);
        System.out.print("Rectangle give l valu: ");
        int k1=out.nextInt();
        System.out.print("Rectangle give w valu: ");
        int k2=out.nextInt();
        k1*=k2;
        System.out.print("A= "+k1);
        System.out.print("\nTriangle.valu of b= " );
        double b=out.nextDouble();
        System.out.print("valu of h=");
        double h=out.nextDouble();
        h*=(b*0.5);
        System.out.printf("A = %.4f",h);
        System.out.print("\nfor circle valu r= " );
        double kop=out.nextDouble();
         kop*=Math.PI;
        System.out.printf("A=%.2f",kop);

       /* System.out.println();
        Java Bangla Tutorials 18  Area of triangle and circle and others 
           */
    }
}
