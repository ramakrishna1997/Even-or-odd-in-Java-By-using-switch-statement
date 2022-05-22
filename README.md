# Even-or-odd-in-Java-By-using-switch-statement
import java.util.Scanner;

public class EvenorOddByUsingSwitch {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		int number = input.nextInt();
		int Remainder = number%2;
		switch(Remainder) {
		case 0 :
			System.out.println("Even");
			break;
		case 1 :
			System.out.println("odd");
		}
		input.close();

	}

}
