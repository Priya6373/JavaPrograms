import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner in=new Scanner(System.in);
		String str=in.nextLine();
		String res="";
		int n=str.length();
		int i=0;
		while(i<n)
		{
		    if(Character.isLowerCase(str.charAt(i)))
		    {
		        res+=Character.toUpperCase(str.charAt(i));
		    }
		    else if(Character.isUpperCase(str.charAt(i)))
		    {
		        System.out.println(res);
		        res="";
		        res+=Character.toLowerCase(str.charAt(i));
		    }
		    i++;
		}
		System.out.println(res);
	}
}
