# Dik-gende-Hipoten-s-Bulan-Program
Java ile kullanıcıdan dik kenarlarının uzunluğunu alan ve hipotenüsü hesaplayan programı yazın.Üç kenar uzunluğunu kullanıcıdan aldığınız üçgenin alanını hesaplayan programı yazınız.


import  java.util.Scanner;

public class Main {
    public static void main(String[] args) {

          int a,b;
          double c;

          Scanner inpa = new Scanner(System.in);
          System.out.print("1. Kenarı Giriniz: ");
          a = inpa.nextInt();
          System.out.print("2. Kenarı Giriniz :");
          b = inpa.nextInt();

          c = Math.sqrt((a*a) + (b*b));
        System.out.println("Hipotenüs:" + c);
        }
      }
