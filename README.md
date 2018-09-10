import java.awt.*;
import java.util.Scanner;

public class firsttest {
public static void main(String args[]) {

    double x1 = 16;
    double x2 = 2.25;

    System.out.printf("sqrt(%.3f) = %.3f%n", x1, Math.sqrt(x1));
    System.out.printf("sqrt(%.3f) = %.3f%n", x2, Math.sqrt(x2));

    int a1 = 6;
    int b1 = 2;
    System.out.printf("Число 6 в квадрате равно %.2f \n", Math.pow(a1, b1));

    System.out.printf("Что сделаешь дальше? ");
    Scanner scan = new Scanner(System.in);
    System.out.println(" дальше будет массив ");

    double[] List = {1, 2, 5, 7, 9, 10};
    for (int i = 0; i < List.length; i++) ;
    {
        System.out.println(List + " ");

    }
    System.out.print(" Введите размер массива: ");
    Scanner scanner1 = new Scanner(System.in);
   double num1 = scanner1.nextInt();
    System.out.println("размер массива: " + num1);


    double[] List1 = {1, 2, 5, 7, 9, 10};
    if (List1[] < scanner1())
    System.out.println("размер массива не соответствует введенному значению");
}
}
