//This is the main branch
//I'm writing this line from TestBranch, you're not supposed to see this from the main branch

// Here is the code in one file, the code have errors that we need to adress. I haven't started debugging yet. 


import java.util.Scanner;


public class Item {
    static void itemOption() {
        Scanner itemMenu = new Scanner(System.in);
        System.out.println("Item options menu: \n" +
                "0. Return to Main Menu.\n" +
                "1. Create an Item.\n" +
                "2. Remove an Item.\n" +
                "3. Print all registered Items.\n" +
                "4. Buy an Item.\n" +
                "5. Update an item’s name.\n" +
                "6. Update an item’s price.\n" +
                "Type a option");

        int counter = 0;
        do {
            int option = itemMenu.nextInt();

            switch (option) {
                case 0 : System.out.println("1");// all println below are temporary.
                case 1 : System.out.println("2");
                case 2 : System.out.println("3");
                case 3 : System.out.println("4");
                case 4 : System.out.println("5");
                case 5 : System.out.println("6");
                case 6 : System.out.println("7");
                default : System.out.println("Please enter a valid option");
            }
        } while (counter >= 5) ;
        itemMenu.close();
    }

}

public class Review {
    static void ReviewMenu() {
        Scanner ReviewMenu = new Scanner(System.in);
        System.out.println("Reviews options menu:\n" +
                "0. Return to Main Menu.\n" +
                "1. Create a review for an Item.\n" +
                "2. Print a specific review of an Item.\n" +
                "3. Print all reviews of an Item.\n" +
                "4. Print mean grade of an Item\n" +
                "5. Print all comments of an Item.\n" +
                "6. Print all registered reviews.\n" +
                "7. Print item(s) with most reviews.\n" +
                "8. Print item(s) with least reviews.\n" +
                "9. Print item(s) with best mean review grade.\n" +
                "10. Print item(s) with worst mean review grade.\n" +
                "\n" +
                "Type an option number:\n");


        int counter = 0;
        do {
            int option = ReviewMenu.nextInt();

            switch (option) {
                case 0 : System.out.println("Option 1");
                case 1 : System.out.println("Option 2");
                case 2 : System.out.println("Option 3");
                case 3 : System.out.println("Option 4");
                case 4 : System.out.println("Option 5");
                case 5 : System.out.println("Option 6");
                case 6 : System.out.println("Option 7");
                case 7 : System.out.println("Option 8");
                case 8 : System.out.println("Option 9");
                case 9 : System.out.println("Option 10");
                default : System.out.println("Please enter a valid option");
            }
        } while (counter >= 5) ;
        ReviewMenu.close();
    }


}

public class MainMenu {
    public static void main (String[] args){

        Scanner OptionScan = new Scanner(System.in);
        System.out.println(
                "Main Menu: Please chose among the options below \n" +
                        "0. Close System.\n" +
                        "1. Open Item Options.\n" +
                        "2. Open Review options.\n" +
                        "3. Open Transaction History Options.\n" +
                        "Type any Option Number:");

        int counter = 0;
        do {
            int option = OptionScan.nextInt();

            switch (option) {
                case 0 : System.out.println("Closed"); // create method
                case 1 : Item.itemOption();
                case 2 : Review.ReviewMenu();
                case 3 : System.out.println("Transaction History");
                default : System.out.println("Please enter a valid option");
            }
        } while (counter >= 5) ;
        OptionScan.close();
    }
}
