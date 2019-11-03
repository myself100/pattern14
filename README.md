# pattern14

import java.util.Scanner;
public class Pattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		for(int i=1;i<=n;i++) {
			  int k=2,u=1;
			for(int j=1;j<=i;j++) {
                if(i%2==0) {
                	System.out.print(k + " ");
                	k=k+2;
                }
                else {
                	System.out.print(u + " ");
                	u=u+2;
                }
				
			}
			System.out.println();

		}
	}
}

output ::                      ////when n is  5
5
1 
2 4 
1 3 5 
2 4 6 8 
1 3 5 7 9 
