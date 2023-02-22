# Exrs1
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner num = new Scanner(System.in);
        while(true) {
            int subject;
            System.out.print("Введите число: ");
            subject = num.nextInt();

            if (subject >= 7)
                System.out.println("Привет");
            else
                System.out.println("Попробуй еще раз.");
        }


    }


}
