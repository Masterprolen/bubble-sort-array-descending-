import java.util.Scanner;
class bubble_array_descending
{
    public static void main(String args[])
    {
        int a[]=new int[10];
        Scanner sc=new Scanner(System.in);
        int i,j,t=0;
        for (i=0;i<10;i++)
        {
            System.out.println("Enter a number");
            a[i]=sc.nextInt();
        }
        for (i=0;i<10;i++)
        {
            for (j=0;j<(9-i);j++)
            {
                if (a[j]<a[j+1])  //one time exchange with the next one 
                {
                    t=a[j];
                    a[j]=a[j+1];
                    a[j+1]=t;
                }
            }
        }
        for (i=0;i<10;i++)
        {
            System.out.println("the number is "+a[i]);
        }
    }
}
