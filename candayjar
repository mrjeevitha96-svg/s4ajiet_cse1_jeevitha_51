
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int N = 10;   
        int K = 5;  
        int jar = N;  
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter number of candies to buy: ");
        int buy = sc.nextInt();

          if (buy > jar) {
            System.out.println("INVALID INPUT");
        } else {
            jar = jar - buy; 
            System.out.println("Number of Candies Sold: " + buy);
            System.out.println("Number of Candies available: " + jar);

                if (jar <= K) {
                jar = N;
                System.out.println("Jar refilled to full: " + jar);
            }
        }
    }
}
output:
Enter number of candies to buy: 3
Number of Candies Sold: 3
Number of Candies available: 7
