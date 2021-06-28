import java .util.*;
class Even
{ 
public static void main(String args[])
{ Scanner sc=new Scanner (System.in);
System.out.println("Enter m value");
System.out.println("Enter n value");
int m=sc.nextInt();
int n=sc.nextInt();
while(m>=n)
{if (m%2==0)
	System.out.println(m+" ");
m--;
	 }
	  }}
