# Reverse-a-string-assignment
Reverse a string assignment
public class ReverseString {
    public static void main(String[] args) {
        if (args.length > 0) {
            String input = args[0];
            String reversed = reverseString(input);
            System.out.println("Reversed string: " + reversed);
        } else {
            System.out.println("Please provide a string as a parameter.");
        }
    }
    
    public static String reverseString(String str) {
        return new StringBuilder(str).reverse().toString();
    }
}
