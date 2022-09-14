# Factorial


// Print factorial of Number n 


public class Recursions{
	public static int printFactorial(int n ) {
		
		if(n == 1 || n == 0) {   // Base case if n== 1 or n== 0 it returns 1
			return 1;
		}
		
		int factorial_of_n_minus_1 = printFactorial(n-1);  //here first we calculate n-1
		int factorial_0f_n = n * factorial_of_n_1;   // here we will calculate n * n-1 
		return factorial_0f_n;
		
	}
	public static void main(String[] args) {
	Scanner sc = new Scanner(System.in)
  int n = sc.nextInt();
	int ans =	printFactorial(n);
	System.out.println(ans);
	}
}
