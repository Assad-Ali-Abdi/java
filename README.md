import java.util.Scanner;

public class Assignment1 {
    public static void main (String[] args) {
        Scanner input = new Scanner(System.in);
        int totalEven = 0;
        int totalOdd = 0;
        System.out.println("ENter numbers : ");
        int times = input.nextInt();
        int i=0;
        while (i<times){
            System.out.println("Enter another number : ");
            int number = input.nextInt();
            if (number % 2 == 0)
                totalEven += number;
            else {
                totalOdd += number;
            }
            i++;
        }
        double averageOdd = (totalOdd + totalEven );
        double averageEven = (totalOdd + totalEven );
        double average = (totalOdd + totalEven );
        System.out.println("total even numbers : " + totalEven);
        System.out.println("total odd numbers : " + totalOdd);

        System.out.println("Average is : " + average);
    }
}va
