import java.util.*;
class FinalIndex {
   public static void main(String[] args) {
	   Scanner a = new Scanner(System.in);
	   System.out.println("How many numbers is your array?");
	   int b = a.nextInt();
	   int nums[] = new int[b];
	   for (int i = 0; i < b; i++) {
			int c = 0;
			System.out.println("Enter index" + i);
			c = a.nextInt();
			nums[i] = c;
		}
		System.out.println("What number do you want to parse for?");
		int parse = a.nextInt();
		lastIndexOf(nums, parse);
  }
  public static void lastIndexOf(int[] numbahs, int parsing) {
	//	Tells you which index your string variable is located at last
		int counter = 0;
		for (int d = numbahs.length-1; d >= 0 ; d++) {
			if (numbahs[d] == parsing) {
				System.out.println("Your index is " + d);
			} else {
				counter++;
			}
		}
		if (counter == numbahs.length) {
			System.out.println("-1");
		}
	}
}