# if-else
This is basic of java 
import java.util.Scanner;

public class ifelse {
    public ifelse() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a no.:");
        int n = sc.nextInt();
        if (n % 2 == 0) {
            System.out.println("The no. is even");
        } else {
            System.out.println("The no. is odd");
        }

    }
}
