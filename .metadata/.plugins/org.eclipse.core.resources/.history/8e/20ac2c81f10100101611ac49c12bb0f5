import java.util.HashSet;
import java.util.Scanner;
import java.util.Set;

public class Solution {
	public static int solution(int[] nums) {
		int answer = 0;
		
		Set<Integer> set1 = new HashSet<>();
		
		for(int i=0;i<nums.length;i++)
			set1.add(nums[i]);
		
		answer = set1.size();
		
		return answer;
	}
	
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		int n = scanner.nextInt();
		
		int[] nums = new int[n];
		for(int i = 0; i<n; i++) {
			nums[i] = scanner.nextInt();
		}
		
		System.out.println(solution(nums)); 
		scanner.close();
	}
}
