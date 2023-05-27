# Tax
Finds the sale amount of an item after tax

    import java.util.Scanner;

    public class Tax
    {
      private static Scanner myScanner = new Scanner(System.in); 

      public static void main(String[] args)
      {
        System.out.println("Enter a sale amount.");
        double saleAmount = myScanner.nextDouble(); 
        System.out.println(saleAmount);

        saleAmount = saleAmount * 1.0625;
        System.out.println("The sale amount after tax is:" + saleAmount);

      }

    }
