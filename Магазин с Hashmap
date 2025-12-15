import java.util.*;
public class Main {
    public static void main(String[] args) {
        Map<String, Double> magazin = new HashMap<>();
        magazin.put("хляб", 1.50);
        magazin.put("мляко", 2.30);
        magazin.put("сирене", 8.40);
        magazin.put("яйца", 4.20);
        magazin.put("вода", 1.00);
        Scanner scanner = new Scanner(System.in);
        double obshtaSuma = 0;
        System.out.print("Колко продукта искаш? ");
        int broi = scanner.nextInt();
        scanner.nextLine();
        for (int i = 0; i < broi; i++) {
            System.out.print("Продукт " + (i + 1) + ": ");
            String produkt = scanner.nextLine().toLowerCase();
            if (magazin.containsKey(produkt)) {
                double cena = magazin.get(produkt);
                System.out.println("Цена: " + cena + " лв.");
                obshtaSuma += cena;
            } else {
                System.out.println("Нямаме такъв продукт");
            }
        }
        System.out.println("Обща сума: " + obshtaSuma + " лв.");
    }
}