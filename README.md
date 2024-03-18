import java.util.Scanner;

public class SquareArea {

  public static double computeArea(double length, double second length) {
    // Calculate and return the area
    return 2*(length * second length);
  }

  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);

    // Get dimensions from the user
    System.out.print("Enter the length of the Square: ");
    double length = scanner.nextDouble();
    System.out.print("Enter the second length of the Square: ");
    double width = scanner.nextDouble();

    // Call the method to calculate the area
    double area = computeArea(length, second length);

    // Print the calculated area
    System.out.println("The area of the square is: " + area);
  }
}
