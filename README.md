package product.of.array;
import java.util.Scanner;

public class ProductOfArray 
{

    
    public static void main(String[] args) 
    {
        int[] arr=new int[] {1,2,3,4,5,};
        int product=1;
            for(int i=0;i<arr.length;i++)
            {
          product=product*arr[i];
    }
       System.out.println("product of all the elements of appaaa an array:"+product);
          
       }
}   
