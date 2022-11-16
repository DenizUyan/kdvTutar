import java.util.Scanner;
public class kdvhesap {
    public static void main(String[] args) {
        double tutar, kdvOran = 0.18;
        Scanner input = new Scanner(System.in);
        System.out.print("Ucret Tutarini Girin :");
        tutar = input.nextDouble();
        double kdvTutar = tutar * kdvOran;
        double toplam = kdvTutar + tutar;
        System.out.println("KDV'li Tutar: " + toplam);
    }
}
