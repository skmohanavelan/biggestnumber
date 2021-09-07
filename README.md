import java.util.Scanner;
public class BiggestNumber
{
public static void main(String[] args)
{
int a, b, c;
Scanner s = new Scanner(System.in);
System.out.print(&quot;Enter the first number:&quot;);
a = s.nextInt();
System.out.print(&quot;Enter the second number:&quot;);
b = s.nextInt();
System.out.print(&quot;Enter the third number:&quot;);
c = s.nextInt();
if(a &gt; b &amp;&amp; c &gt; c)
{
System.out.println(&quot;Largest number is:&quot;+a);
}
else if(b &gt; a &amp;&amp; b&gt;c)
{
System.out.println(&quot;Largest number is:&quot;+b);
}
else
{
System.out.println(&quot;Largest number is:&quot;+c);
}
}
}
