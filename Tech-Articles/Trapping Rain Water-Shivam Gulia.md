
=======================================================

Article Title: Trapping Rainwater Problem
Author Name: Shivam Gulia
Author Profile: https://github.com/Shivamgulia
Date: 21-10-2021

=======================================================

//Here is the code for trapping rainwater problem

import java.io.*;
import java.util.*;
import java.lang.*;


class Array {

	public static void main (String[] args) throws IOException {
		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		int t = Integer.parseInt(br.readLine().trim()); //Inputting the testcases
		while(t-->0){
		  
		    //size of array
		    int n = Integer.parseInt(br.readLine().trim());
		    int arr[] = new int[n];
		    String inputLine[] = br.readLine().trim().split(" ");
		    
		    //adding elements to the array
		    for(int i=0; i<n; i++){
		        arr[i] = Integer.parseInt(inputLine[i]);
		    }
		    
		    Solution obj = new Solution();
		    
		    //calling trappingWater() function
		    System.out.println(obj.trappingWater(arr, n));
		}
	}
}

// } Driver Code Ends



class Solution{
    
    // arr: input array
    // n: size of array
    // Function to find the trapped water between the blocks.
    static int trappingWater(int arr[], int n) { 
        
        // Your code here
        int i=1,largest=0;
        int[] left=new int[n];
        int[] right=new int[n];
        for(i=1;i<n-1;i++) {
            if(arr[largest]>arr[i]) {
                left[i]=arr[largest]-arr[i];
            }
            else {
                left[i]=0;
                largest=i;
            }
        }
        largest=n-1;
        for(i=n-2;i>0;i--) {
            if(arr[largest]>arr[i]) {
                right[i]=arr[largest]-arr[i];
            }
            else {
                right[i]=0;
                largest=i;
            }
        }
        largest=0;
        for(i=1;i<n-1;i++) {
            largest+=Math.min(left[i],right[i]);
        }
        return largest;
    } 
}





