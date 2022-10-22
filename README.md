# java-5
package com;

import java.util.Scanner;

class Problem2 {
	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
		int a=scan.nextInt();
		for(int i=1;i<=a*2;i++){
			if(i%2==1){
				System.out.print(i+" ");
			}
		}
	}
}
