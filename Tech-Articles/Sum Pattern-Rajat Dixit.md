
=======================================================

Article Title: Sum Pattern
Author Name: Rajat Dixit
Author Profile: https://github.com/rajat7377
Date:18/10/2021

=======================================================

import java.util.Scanner;
public class Main {
public static void main(String[] args) {
 Scanner s = new Scanner (System.in);
 int n = s.nextInt();
 int ans=0;
 int i = 1;
 while(i<=n) 
  {
             int j=1;
            ans = ans+i;
            while(j<i){
                
            System.out.print(j+ "+" );
               
                j =j+1;
            }
               System.out.print(j );
               
                j =j+1;
             System.out.print( "=" + ans);
            System.out.println();
            i=i+1;
             }
	}
}



