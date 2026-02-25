import java.util.Scanner;

public class KgAndLbs {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int option;
        double kg;
        double lbs;
        double weight;

        System.out.println("Weight Conversion Program");
        System.out.println("1: Convert lbs to kgs");
        System.out.println("2: Convert kgs to lbs");
        System.out.print("Choose an option: ");

        option = scanner.nextInt();

        if (option == 1) {
            System.out.print("Enter the weight in lbs: ");
            lbs = scanner.nextDouble();
            weight = lbs / 2.20462;
            System.out.printf("The new weight in kg is: %.2f", weight);

        } else if (option == 2) {
            System.out.print("Enter the weight in kgs: ");
            kg = scanner.nextDouble();
            weight = kg * 2.20462;
            System.out.printf("The new weight in lbs is: %.2f", weight);

        } else {
            System.out.println("You need to type either 1 or 2.");
        }

        scanner.close();
    }
}