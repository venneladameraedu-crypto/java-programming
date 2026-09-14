import java.util.Scanner;

public class AIChatbot {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.println("================================");
        System.out.println("       JAVA AI CHATBOT");
        System.out.println("================================");
        System.out.println("Bot: Hello! I am your AI chatbot.");
        System.out.println("Bot: Type 'bye' to exit.");

        while (true) {

            System.out.print("You: ");
            String input = sc.nextLine().toLowerCase();

            if (input.equals("bye") || input.equals("exit")) {
                System.out.println("Bot: Goodbye!");
                break;
            }

            if (input.contains("hello") || input.contains("hi")) {
                System.out.println("Bot: Hello! How can I help you?");
            }
            else if (input.contains("name")) {
                System.out.println("Bot: My name is Java AI Chatbot.");
            }
            else if (input.contains("java")) {
                System.out.println("Bot: Java is an object-oriented programming language.");
            }
            else if (input.contains("internship")) {
                System.out.println("Bot: Internships help students gain practical experience.");
            }
            else if (input.contains("how are you")) {
                System.out.println("Bot: I am doing great!");
            }
            else if (input.contains("help")) {
                System.out.println("Bot: I can answer questions about Java, internships and college.");
            }
            else if (input.contains("thank")) {
                System.out.println("Bot: You're welcome!");
            }
            else {
                System.out.println("Bot: Sorry, I don't understand that.");
            }
        }

        sc.close();
    }
}
