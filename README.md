# Taxperson
Interview question #3
import java.util.Scanner;

public class TaxPerson
 {
    public static void main(String[] args)
    {
        Scanner user_input = new Scanner(System.in);
        Double taxrate;
        String item_type;
        Double tax_amount;
        Double item_price;
        Double price;

        // Enter item type, necessity, or luxery:
        System.out.println("Enter Item Type");
        item_type = scanner.nextString();

        // Enter initial item price:
        System.out.println("Enter Item Price");
        initial_item_price = scanner.nextDouble();

        // Determine tax rate based on item type:
        if (item_type = "necessity" )
          taxrate = 0.01;
        else if (item_type = "luxury")
          taxrate = 0.09;
        else {
          System.out.println("Error in Item Type");
          exit(0); }

    // Calculate tax amount and total price:
    tax_amount = initial_item_price * taxrate;
    price = tax_amount + initial_item_price;

    // Print out results:
    System.out.println("The item type is: " + item_type);
    System.out.println("The taxrate is: " + taxrate);
    System.out.println("The initial item price is: " + initial_item_price);
    System.out.println("The total price is: " + price);

 }
}
