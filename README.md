# ICP-ASSIGNMENT-2
Check here the codes for our ICP Assg 2 questions. Note- Please comment out the questions before writing.

package com.icpasgtwo;
import java.util.Scanner;
import java.lang.Math;
import javax.swing.*;
public class Main {

   public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);

//    QUESTION 1
//        System.out.println("Enter the temperature in Celcius ");
//    double Celcius= sc.nextDouble();
//    double Farenheit = (9.0/5)*Celcius+32;
//        System.out.println("Your temperature in Farenheit is "+Farenheit);


//      QUESTION 2
//        System.out.println("Enter the radius ");
//        double radius= sc.nextDouble();
//        System.out.println("Enter the length ");
//        double length= sc.nextDouble();
//
//        double area = (radius*radius*Math.PI);
//        System.out.println("The Area is "+ area);
//        double volume = area*length;
//        System.out.println("The Volume is "+ volume);

//        QUESTION 3
//        System.out.println("Enter a value for feet: ");
//        double feet = sc.nextDouble();
//        double meter = feet*0.305d;
//        System.out.println(feet+" feet is "+ meter + " meters");


//        QUESTION 4
//        System.out.println("Enter a number between 0 and 1000: ");
//        int a = sc.nextInt();
//        if (a<=1000){
//            int b= a%10;
//            int c=a/10;
//            int d=c%10;
//            int e=c/10;
//            int f=d + b+ e;
//            System.out.println("The sum of the digits is "+ f);
//        }
//        else{
//            System.out.println("Invalid input, please enter a number between 0 to 1000 only");
//        }


//        QUESTION 5
//
//        System.out.println("Enter initial velocity Vo(in m/s):");
//        double Vo= sc.nextDouble();
//        System.out.println("Enter the final velocity V1(in m/s): ");
//        double V1= sc.nextDouble();
//        System.out.println("Enter time in seconds:");
//        double t= sc.nextDouble();
//        double avgA= (V1-Vo)/t;
//        System.out.println("The average acceleration is "+ avgA);

//        QUESTION 6
//        System.out.println("Enter weight in pounds");
//        double pound = sc.nextDouble();
//        double weight = pound*0.45359237d;
//        System.out.println("Enter height in inches");
//        double inch = sc.nextDouble();
//        double height = inch*0.0254d;
//
//        double BMI = weight/(height*height);
//        System.out.println("BMI is "+BMI);

//        QUESTION 7
//        System.out.println("Enter the side: ");
//        double side = sc.nextDouble();
//        double area = 3*Math.sqrt(3)/2*(side*side);
//        System.out.println("The are of the hexagon is " + area);

//        QUESTION 8
//        JFrame frame;
//        frame = new JFrame();
//        String data[][]={
//                {"1","2","1"},
//                {"2","3","8"},
//                {"3","4","81"},
//                {"4","5","1024"},
//                {"5","6","15625"}
//        };
//        String column[]={"a","b","pow(a.b)"};
//        JTable jt = new JTable(data,column);
//        jt.setBounds(50,80,300,600);
//        JScrollPane sp = new JScrollPane(jt);
//        frame.add(sp);
//        frame.setSize(600,700);
//        frame.setVisible(true);

//        QUESTION 9
//        System.out.println("Enter point x1: ");
//        double x1 = sc.nextDouble();
//        System.out.println("Enter point y1: ");
//        double y1 = sc.nextDouble();
//        System.out.println("Enter point x2: ");
//        double x2 = sc.nextDouble();
//        System.out.println("Enter point y2: ");
//        double y2 = sc.nextDouble();
//
//        double a = (x2-x1)*(x2-x1)+(y2-y1)*(y2-y1);
//        double distance = Math.pow(a,0.5);
//        System.out.println("The distance is " + distance);

//
//        QUESTION 10
//        System.out.println("Enter x1: ");
//        double x1 = sc.nextDouble();
//        System.out.println("Enter y1: ");
//        double y1 = sc.nextDouble();
//        System.out.println("Enter x2: ");
//        double x2 = sc.nextDouble();
//        System.out.println("Enter y2: ");
//        double y2 = sc.nextDouble();
//        System.out.println("Enter x3: ");
//        double x3 = sc.nextDouble();
//        System.out.println("Enter y3: ");
//        double y3 = sc.nextDouble();
//
//        double p = (x2-x1)*(x2-x1)+(y2-y1)*(y2-y1);
//        double q = (x3-x2)*(x3-x2)+(y3-y2)*(y3-y2);
//        double r = (x1-x3)*(x1-x3)+(y1-y3)*(y1-y3);
//        double a = Math.pow(p,0.5);
//        double b = Math.pow(q,0.5);
//        double c = Math.pow(r,0.5);
//
//        double s = (a+b+c)/2;
//        double formula = s*(s-a)*(s-b)*(s-c);
//        double area = Math.pow(formula,0.5);
//        System.out.println("Area of the triangle is " + area);

//        QUESTION 11
//
//        System.out.println("Enter investment amount: ");
//        double investmentAmount = sc.nextDouble();
//        System.out.println("Enter annual interest rate in percentage: ");
//        double annualInterestRate = sc.nextDouble();
//        System.out.println("Enter the number of years: ");
//        int numberOfYears = sc.nextInt();
//
//        double monthlyInterestRate = (annualInterestRate/1200);
//
//        double a = (1+monthlyInterestRate);
//        double b = (numberOfYears*12);
//        double c = Math.pow(a,b);
//
//
//        double futureInvestmentValue= investmentAmount*c;
//
//        System.out.println("The accumulated value is " + futureInvestmentValue);


QUESTION 12

//        System.out.println("Enter the number of eggs you have: ");
//        int Eggs = sc.nextInt();
//        if(Eggs>=12 && Eggs<=144){
//            int dozens = Eggs/12;
//            int leftOver = Eggs%12;
//            System.out.println("You have " + dozens + " dozens and " + leftOver + " Eggs");
//        }
//        if (Eggs<12){
//            int leftOver = Eggs;
//            System.out.println("You have " + leftOver + " Eggs");
//        }
//        if (Eggs>=144){
//            int gross = Eggs/144;
//            int afterGross = Eggs%144;
//            int dozens = afterGross/12;
//            int leftOver = afterGross%12;
//            System.out.println("You have " + gross + " Gross " +dozens+ " Dozens " + leftOver + " Eggs" );
//        }


QUESTION 13

//        System.out.println("Enter the number of minutes:");
//        int minutes = sc.nextInt();
//
//
//        int year = minutes / 525600;
//        int day = minutes / 1440;
//        int remainingMinutes = day % 525600;
//
//
//        System.out.println(minutes + " minutes is " + year + " years and "  +  remainingMinutes + " days ");


//        QUESTION 14
//
//                int a = Integer.parseInt(args[0]);
//                int b = Integer.parseInt(args[1]);
//                boolean res = (a%b==0 || b%a==0);
//                System.out.println("result=" + res);
//

//        QUESTION 15
//
//        int a = Integer.parseInt(args[0]);
//        int b = Integer.parseInt(args[1]);
//        int c = a + (int)((b-a)*Math.random());
//        System.out.println("Result=" + c);


//        QUESTION 16

//        int a = Integer.parseInt(args[0]);
//        int b = Integer.parseInt(args[1]);
//        int c = a + (int)((b-a)*Math.random());
//        int d = a + (int)((b-a)*Math.random());
//        System.out.println("Result= " + (c+d));


//        QUESTION 17

//        int a = Integer.parseInt(args[0]);
//        int b = Integer.parseInt(args[1]);
//        int c = Integer.parseInt(args[2]);
//        boolean res = (a<=(b+c) || b<=(c+a) || c<=(a+b));
//        System.out.println("result=" + res);


//        QUESTION 18

//        double x = Double.parseDouble(args[0]);
//        double y = Double.parseDouble(args[1]);
//        double z = Double.parseDouble(args[2]);
//        boolean result = (((x>y)&&(y>z))||((x < y)&&(y < z)));
//        System.out.println("Result = " + result);


//        QUESTION 19

//        Scanner sc = new Scanner(System.in);
//        System.out.println("Input basic salary:");
//        double bs = sc.nextDouble();
//        double da = 0.4*bs;
//        double hra = 0.2*bs;
//        double gross = bs + da + hra;
//        System.out.println("Gross salary of the employee is :"+ gross);


//        QUESTION 20

//        int m = Integer.parseInt(args[0]);
//        int d = Integer.parseInt(args[1]);
//        boolean res = (((m==3)&&(d>20&&d<=31))||((m==4)&&(d>=1&&d<=30))||((m==5)&&(d>=1&&d<=31))||((m==6)&&(d>=1&&d<20)));
//        System.out.println("Result=" + res);


//        QUESTION 21

//        double a = Double.parseDouble(args[0]);
//        double b = Math.toRadians(a);
//        double c = Math.sin(2*b) + Math.sin(3*b);
//        System.out.println("Result=" + c);


//        QUESTION 22

//        double P = Double.parseDouble(args[0]);
//        double r = Double.parseDouble(args[1]);
//        double t = Double.parseDouble(args[2]);
//        System.out.print(P*Math.pow(Math.E,(r*t)));


//        QUESTION 23

//        int a = Integer.parseInt( args[0] );
//        int b = Integer.parseInt( args[1] );
//        int c = Integer.parseInt( args[2] );
//        int x = Math.min(a, b);
//        int min = Math.min(x,c);
//        int z = Math.max(a, b);
//        int max = Math.max(z, c);
//        int mid = a+ b+ c- min - max;
//        System.out.println(min);
//        System.out.println(mid);
//        System.out.println(max);


//        QUESTION 24

       //        int a = Integer.parseInt(args[0]);
//        int b = Integer.parseInt(args[1]);
//        int c1 = a + (int)((b-a)*Math.random());
//        int c2 = a + (int)((b-a)*Math.random());
//        int c3 = a + (int)((b-a)*Math.random());
//        int c4 = a + (int)((b-a)*Math.random());
//        int c5 = a + (int)((b-a)*Math.random());
//        System.out.println(c1);
//        System.out.println(c2);
//        System.out.println(c3);
//        System.out.println(c4);
//        System.out.println(c5);
//        int min = Math.min(c1 , c2);
//        min = Math.min(min , c3);
//        min = Math.min(min , c4);
//        min = Math.min(min , c5);
//        int max = Math.max(c1 , c2);
//        max = Math.max(max , c3);
//        max = Math.max(max , c4);
//        max = Math.max(max , c5);
//        System.out.println("Minimum value is = " + min);
//        System.out.println("Maximum value is = " + max);



























   }
}




















