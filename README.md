# welcome 
welcome.java
 import java.util.scanner;


public class Welcome {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the user
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter their first name
        System.out.print("Enter your First Name: ");
        String firstName = scanner.nextLine();

        // Prompt the user to enter their last name
        System.out.print("Enter your Last Name: ");
        String lastName = scanner.nextLine();

        // Display the welcome message
        System.out.println("Welcome to the Second Year " + firstName + " " + lastName);

        // Close the scanner to avoid resource leak
        scanner.close();
    }
}