# 3and4division
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int num, count = 0, total = 0;
        Scanner input = new Scanner(System.in);
        System.out.println("Bir sayi giriniz");
        num = input.nextInt();
        for (int i = 0; i <= num; i++) {

            if (i % 3 == 0 && i % 4 == 0) {
                total = total + i;
                count++;
            }
        }
        System.out.println("3 3 ve 4 e bölünen sayılarin ortalama degeri : "+ total/count);
    }
}


