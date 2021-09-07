# Biggest-Numbers
import java.util.Scanner;
public class BiggestNumber
{
  public static void main(String[] args)
{
  int x, y,z;
  Scanner S= new Scanner(System.in);
  System.out.println("Enter the first number:");
  x=S.nextInt();
   System.out.println("Enter the first number:");
  y=S.nextInt();
 System.out.println("Enter the first number:");
  z=S.nextInt();
if(x>y&&x>z)
 {
   System.out.println("largest number is:"+x);

  }

else if(y>x&&y>z)
  {
    System.out.println("largest number is :"+y);
  }
else
  {
     System.out.println("largest number is:"+z);
   }
  }
}
