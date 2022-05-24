# Test
public class Calculator {
	/**
	 * will print the sums, differences, and products of 2 numbers using methods.
	 *
	 * @author (Kareem Mohsin)
	 * @version (oct 29 2021)
	 */
	    public static void main(String args[]){
	        int number1 = 8;
	        int number2 = 13;
	        computations calculate = new computations(number1, number2);//object
	        
	        calculate.add();//calling methods using the dot operator
	        calculate.subtract();
	        calculate.multiply();
	        calculate.evenOrOdd();
	        
	        System.out.println(calculate);
	    }
	
}
