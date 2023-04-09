import java.util.Scanner;
public class Mainn {

    public static void main(String[] args) {
        // Değişkenleri oluştur
        int mat, fizik, kimya, turkce, tarih, muzik;

        //Scanner sınıfımızı tanımladık
        Scanner inp = new Scanner(System.in);

        //Kullanıcıdan değerleri al
        System.out.print("Matematik Notunuz :");
        mat = inp.nextInt();

        //Kullanıcıdan değerleri al
        System.out.print("fizik Notunuz :");
        fizik = inp.nextInt();

        //Kullanıcıdan değerleri al
        System.out.print("kimya Notunuz :");
        kimya = inp.nextInt();

        //Kullanıcıdan değerleri al
        System.out.print("turkce Notunuz :");
        turkce = inp.nextInt();

        //Kullanıcıdan değerleri al
        System.out.print("tarih Notunuz :");
        tarih = inp.nextInt();

        //Kullanıcıdan değerleri al
        System.out.print("muzik Notunuz :");
        muzik = inp.nextInt();

        double sonuc = (mat + fizik + kimya + turkce + tarih + muzik) / 6;
        System.out.print("Ortalamanız : " + sonuc);
        System.out.println(ort >= 60 ? "Sınıfı Geçtiniz" : "Sınıfta Kaldınız");
