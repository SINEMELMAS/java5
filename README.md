# java5
package lab1;
import java.util.Scanner;
public class Q5 {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);

        System.out.print("Please enter the first integer: ");
        int firstNum = scanner.nextInt();

        System.out.print("Enter the second integer: ");
        int secondNum = scanner.nextInt();

        int tripledFirstNum = firstNum * 3;
        int doubledSecondNum = secondNum * 2;

        if (tripledFirstNum % doubledSecondNum == 0) {
            System.out.println("Tripled first number is a multiple of doubled second number.");
        } else {
            System.out.println("Tripled first number is not a multiple of doubled second number.");
        }

        scanner.close();

	}
