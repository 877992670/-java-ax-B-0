# -java-ax-B-0
1，java 编写 ax+B=0(a不等于0)的根






import java.io.*;
public class Root
{
   public static void main (String args[])
  {
  float a,b,x;
  String str1="",str2="";
 System.out.println("请输入变量a和b的值:");
try{
   BufferedReader input1=new BufferedReader(new InputStreamReader( System.in));
   str1=input1.readLine();
   BufferedReader input2=new BufferedReader(new InputStreamReader( System.in));
   str2=input2.readLine();
 }
catch (IOException e ){System.out.println(e);}
a=Float.parseFloat(str1);
b=Float.parseFloat(str2);
if(Math.abs(a)>0.000001f)
{

x=-b/a;
System.out.println("x="+x);
}



}   


}
