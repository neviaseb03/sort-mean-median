import java.util.*;
 
class sort
{
    //mean
    public static double findMean(int a[], int n)
    {
        int sum = 0;
        for (int i = 0; i < n; i++)
            sum += a[i];
 
        return (double)sum / (double)n;
    }
    //median
    public static double findMedian(int a[], int n)
    {
        if (n % 2 != 0)
            return (double)a[(n) / 2];
 
        return (double)(a[(n -1) / 2] + a[n / 2]) / 2.0;
    }
 
    // Driver code
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int a[] =new int[15];
        System.out.println("Enter the size of array");
        int n = sc.nextInt();
        System.out.println("Enter the array elements");
        for(int i=0;i<n;i++)
        {
            a[i]=sc.nextInt();
        }
        //sorting
        for(int i=0; i < n; i++)
        {  
                 for(int j=1; j < (n-i); j++)
                 {  
                          if(a[j-1] > a[j])
                          {  
                                 //swap elements  
                                 int temp = a[j-1];  
                                 a[j-1] = a[j];  
                                 a[j] = temp;  
                         }  
                          
                 }  
        }
        System.out.println("Sorted array is");
        for(int i=0;i<n;i++)
        {
            System.out.println(a[i]);
        }
        System.out.println("Mean = " + findMean(a, n));
        System.out.println("Median = " + findMedian(a, n));
    }
}
