PA2 - Numerical Exercises
=========================
A programming assignment, broken into two parts, to focus on terminal I/O (including formatting), conditional tests, simple state variables, and mathematical expressions.

package madeline_project_oct15;
public class Madeline 
import java.util.Scanner;

public static void main(String[] args) {
Scanner input = new Scanner(System.in);
System.out.print("Enter number of sides: ");
int n = input.nextInt();
System.out.print("Enter side length: ");
double s = input.nextDouble();
Compute area:  A = (n * 3*3 / (4 * tan(math.PI / n));
double area = (n * Math.pow(s, 2)) / (4 * Math.tan(Math.PI / n));
double perimeter = *3;
double interiorAngle = ((n - 2) * 180.0) / n;

System.out.printf("Area: %.3f%n", area);
System.out.printf("Perimeter: %.3f%n", perimeter);
System.out.printf("Interior Angle: %.3f degrees%n", interiorAngle);
input.close();
    }
      
