package Ultimate;
import java.util.Scanner;
import Ultimate.Calculator;
import Ultimate.TextAnalyzer;

public class Menu {
	static Scanner userinput = new Scanner(System.in);
	public static void main (String[] args)
	{
		
		Calculator task=new Calculator();
		TextAnalyzer task1= new TextAnalyzer();
		
		int i =0;
		String answer; 
		System.out.println();
		System.out.println("Would you to enroll your information ?");
		answer=userinput.nextLine();
		while((answer.charAt(0)=='y')&(i<=3)) {
		System.out.println();
		System.out.println("Hi, what can l do for you ?");
		System.out.println();
		System.out.println("1: Display Favorite Saying  2: Give Encouragement  3: Draw Text art "
				+ "  4: Opening  5: String Processor ");
		System.out.println("6: Standard Calculator   7: Binary  Calculator  8: Number Converter   9: Double Factorial  ");
		System.out.print("please type number 1 or 9: " + " (0 for ending program) " );
	
		int choice = userinput.nextInt();
		if (choice == 0) {
			System.out.print(" Thank you ! :) ");
			
		}else if(choice ==1) {
			System.out.println();
			task1.saying();
		}else if(choice == 2) {
			System.out.println();
			task1.encouragement();
		}else if(choice == 3) {
			System.out.println();
			task1.textart();	
		}else if(choice == 4 ) {
			System.out.println();
			task1.open();}
		else if(choice == 5 ) {
			System.out.println();
				task1.stringprocessor();
		}else if(choice == 6 ) {
			System.out.println();
			task.standardcal();
		}else if(choice == 7 ) {
			System.out.println();
			task.binarycal();
		}else if(choice == 8 ) {
			System.out.println();
			task.numberconv();
		}else if(choice == 9 ) {
			System.out.println();
			task.doublefactor();
		}
		}
	}
}
