# Fectorial
find fectorial using this code
package mypackage;

import java.util.Scanner;

public class FindFectorial {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("Enter Number:");
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		//int i=1;
		int fect=1;
//		while(i<=n) {
//			fect=fect*i;
//		//}
//		System.out.println(fect);
	for(int i=1;i<=n;i++) {
			fect=fect*i;
	}
		System.out.println(fect);
		}
	}
	//}


