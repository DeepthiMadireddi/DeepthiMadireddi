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

****************class  Num
{
public static void main(String args[])
{
Scanner sc=new Scanner(System.in);
System.out.println("Enter number");
int n=sc.nextInt();
String s=String.valueOf(n);
int even=0,odd=0;
for(int i=0;i<s.length();i++)
{
if(s.charAt(i)%2==0)
even+=1;
else
odd+=1;
}
System.out.println("odd digits ="+odd);
System.out.println("even digits ="+even);
}
}******************class Switch
{
public static void main(String args[])
{
Scanner sc=new Scanner(System.in);
System.out.println("Enter letter");
char letter=sc.next().charAt(0);
switch(letter)
{
case 'A':
case 'a':
case 'E':
case 'e':
case 'I':
case 'i':
case 'O':
case 'o':
case 'U':
case 'u':System.out.println("vowel");break;
default:System.out.println("consonant");
}
}
}
