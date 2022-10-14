# Multiplicatin
import javax.swing.JOptionPane;
public class Multiplication {

	public static void main(String[] args) {
		String firstNumber = JOptionPane.showInputDialog("Enter first integer" );
		String secondNumber = JOptionPane.showInputDialog("Enter second integer" );
		
		int number1 = Integer.parseInt(firstNumber);
		int number2 = Integer.parseInt(secondNumber);
		
		int multiple = number1 * number2;
		
		JOptionPane.showMessageDialog(null, "The multiplication is " + multiple, "Multiplication of Two Integers", JOptionPane.PLAIN_MESSAGE);

	}

}
