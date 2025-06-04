import java.util.Scanner;
class Utility {
 public static int max(int a, int b) {
 return (a > b) ? a : b;
 }
}
public class Main {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);


 int num1 = scanner.nextInt();
 int num2 = scanner.nextInt();

 int result = Utility.max(num1, num2);
 System.out.println(result);
 }
 }
