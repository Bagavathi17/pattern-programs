1.PYRAMID PATTERN

PATTERN :
    * 
   * * 
  * * * 
 * * * * 
* * * * *

CODE:
public class Bagavathi
{  
    public static void pyramidPattern(int n) 
    {  
        for (int i=0; i<n; i++)
        {
                System.out.print(" "); 
            }  
            for (int j=0; j<=i; j++ ) 
            { 
                System.out.print("* "); 
            } 
  
            System.out.println(); 
            }
    } 
  
    public static void main(String args[]) 
    { 
        int n = 5; 
        pyramidPattern(n); 
    } 
}
________________________________________________________________________________________________________________________________________________________________________________

2.SIMPLE NUMBER PROGRAM

CODE:
              1 
              1 2 
              1 2 3 
              1 2 3 4 
              1 2 3 4 5
 
PROGRAM:

public class Bagavathi
{
    public static void printNums(int n) 
    { 
        int i, j,num; 
    
        for(i=0; i<n; i++) 
        { 
            num=1; 
            for(j=0; j<=i; j++)
            { 
               System.out.print(num+ " ");
               num++; 
            } 
         System.out.println(); 
        } 
    } 
       public static void main(String args[]) 
    { 
        int n = 5; 
        printNums(n); 
    } 
}
______________________________________________________________________________________________________________________________________________________________________________

3.NUMBER PATTERN PROGRAM 
Enter the number of rows: 5

            1 
            2 2 
            3 3 3 
            4 4 4 4 
            5 5 5 5 5
 
CODE:
import java.util.Scanner;
  
public class Bagavathi
{            
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);  
        System.out.println("Enter the number of rows: ");    
        int rows = sc.nextInt();         
        for (int i = 1; i <= rows; i++) 
        {
            for (int j = 1; j <= i; j++)
            {
                System.out.print(i+" ");
            }
               
            System.out.println();
        }         
        sc.close();
    }
}
_____________________________________________________________________________________________________________________________________________________________________________
4. DESCENDING ORDER PATTERN

Enter the number of rows: 5

                                5 
                                5 4 
                                5 4 3 
                                5 4 3 2 
                                5 4 3 2 1
CODE:
import java.util.Scanner;
public class Bagavathi
{
public static void main(String[] args)
{
Scanner sc = new Scanner(System.in);
 System.out.println("Enter the number of rows: ");
 int rows = sc.nextInt();
for (int i = rows; i >= 1; i--)
{
for (int j = rows; j >= i; j--)
{
System.out.print(j+" ");
}
 
System.out.println();
}
sc.close();
}
}
_____________________________________________________________________________________________________________________________________________________________________
 
5.ZERO/ONES PATTERN
Enter the number of rows: 5

          1
          10
          101
          1010
          10101
 
CODE:
import java.util.Scanner;
 
public class Bagavathi
{            
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);
          
        System.out.println("Enter the number of rows: ");
          
        int rows = sc.nextInt();         
        for (int i = 1; i <= rows; i++) 
        {
            for (int j = 1; j <= i; j++)
            {
                if(j%2 == 0)
                {
                    System.out.print(0);
                }
                else
                {
                    System.out.print(1);
                }
            }
              
            System.out.println();
        }
          
        sc.close();
    }
}
 __________________________________________________________________________________________________________________________________________________________________________

















 
