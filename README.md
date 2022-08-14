# PATİKA ÖDEVLER
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
int mat,fizik,kimya,turkce,tarih,muzik;
double ortalama;

Scanner inp= new Scanner(System.in);

        System.out.print("Matematik Notunuz:");
  mat= inp.nextInt ();
System.out.println(mat);


System.out.print("Fizik Notunuz:");
fizik= inp.nextInt ();
System.out.println(fizik);

System.out.print("Kimya Notunuz");
kimya= inp.nextInt();
System.out.println(kimya);

System.out.print("Türkçe Notunuz:");
turkce= inp.nextInt ();
System.out.println(turkce);

System.out.print("Tarih Notunuz");
        (tarih) = inp.nextInt();
System.out.println(tarih);

System.out.print("Müzik Notunuz");
muzik= inp.nextInt();
System.out.println(muzik);


ortalama =(mat + fizik +kimya+turkce+tarih+muzik/6);
System.out.println("Not Ortalamanız"+ortalama);
String sonuc = (ortalama >= 60? "Sınıfı Geçti":"Sınıfta Kaldı");
        System.out.println(sonuc);







    }
}

