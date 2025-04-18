# evenodd
import java.util.Scanner;

class EvenOddChecker {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = scanner.nextInt();

        if (number % 2 == 0) {
            System.out.println("This is even");
        } else {
            System.out.println("This is odd");
        }

        scanner.close(); // Good practice to close Scanner
    }
}
