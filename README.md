# ciftSayilariToplayipEkranaYazdiranProgram
import java.util.Scanner;

public class ciftSayilar {
    public static void main(String[] args) {

        int a, toplam = 0;

        Scanner inp = new Scanner(System.in);

        do{
            System.out.print("Lütfen Sayı Giriniz:");
            a = inp.nextInt();
            if (a%4 == 0 && a%2 == 0){
                toplam += a;
            }
        }while(a%2 != 1);

        System.out.print("toplam" +toplam);

        }
    }
