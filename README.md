public class EnKucukBulucu {

    public static int enKucukBul(int a, int b, int c) {
        int enKucuk = a;

        if (b < enKucuk) {
            enKucuk = b;
        }

        if (c < enKucuk) {
            enKucuk = c;
        }

        return enKucuk;
    }

    public static void main(String[] args) {
        int sayi1 = 5;
        int sayi2 = 10;
        int sayi3 = 3;

        int enKucukSayi = enKucukBul(sayi1, sayi2, sayi3);

        System.out.println("En küçük sayı: " + enKucukSayi);
    }
}
