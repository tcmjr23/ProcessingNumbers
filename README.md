# ProcessingNumbers
This project prompts the user to enter numbers which it then uses to analyze the minimum, maximum, and sum. 
Here are some key code samples from the project:

# public static int sumEven(int runningSum, int newNum) {
			runningSum += newNum;
			return runningSum;
	}
 This method keeps a running sum of all the even numbers inputted. It stores this in a field called runningSum. 
  
# public static int maxEven(int currentMax, int compare) {	
		if (compare>currentMax) {
			currentMax = compare;
		}else {
			return currentMax;
		}
		return currentMax;
	 }
  Tests to see if the int compare parameter passed is greater than the currently stored currentMax value. If compare is greater than currentMax, currentMax is updated to hold the value of compare. 
   
# public static int Max(int currentMax, int compare) {
		if(compare>currentMax) {
			currentMax = compare;
		}else {
			return currentMax;
		}
		return currentMax;
	}
returns the max value out of all the nubers passed.
