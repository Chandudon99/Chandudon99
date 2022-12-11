import java.util.*;

public class App {
    public static void main(String[] args) {
        // Create a new Scanner object to read input from the user
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter a name
        System.out.print("Enter your name: ");

        // Read the user's name and store it in a variable
        String name = scanner.nextLine();

        // Greet the user by name
        System.out.println("Hello, " + name + "!");
    }
}
