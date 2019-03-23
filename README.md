# From100to200

import java.util.Scanner;

public class P17_From100to200 {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int number = Integer.parseInt(scanner.nextLine());

        int bottom = 100;
        int top = 200;

        if(number < bottom){
            System.out.printf("Less than %d%n",bottom);
        }
        else if (number <= top){
            System.out.printf("Between %d and %d%n",bottom, top);
        }
        else {
            System.out.printf("Greater than %d%n",top);
        }
    }
}
