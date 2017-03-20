package kassd;

import java.util.Scanner;
import javax.swing.JOptionPane;

public class Week3 {
public static void main(String[] arg) {
	
		
		
/*Repeat
*	Prompt the user for numeric values.
*	Read in the Values from the string the user entered.
* 	Calculate the average value:
*		Initialize the total of all values to zero.
*		Initialize the count of values to zero.
*		While there are more values to process
*			Add the next value to the total
*			Increment the count of values
*		Set average value to the total divided by the count
* 	Display the average value. 
* 	Ask if the user wants to enter more data.
* As long as the answer is "yes"
*/	
	
		String answer;
		do {
			String userInput = JOptionPane.showInputDialog("Please enter some numbers");

			if (userInput != null) {
				
				Scanner  inScan = new Scanner(userInput);
				
				double total = 0;
				int countOfValues = 0;
				
				while (inScan.hasNextDouble()){
					total = total + inScan.nextDouble();
					countOfValues++;
				}
				
				double average = total / countOfValues;
				
				JOptionPane.showMessageDialog(null, "The average of '" + userInput + "' is " + average);
			}
			
			answer = JOptionPane.showInputDialog("Want to do more? ('yes' or 'no')");
		} while (answer.equals("yes"));
		
		
	}

}
		

