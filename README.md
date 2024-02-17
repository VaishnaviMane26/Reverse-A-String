# Reverse-A-String
public class ReverseString {

	public static void main(String[] args) {
    String str="SOFTWARE ENGINEER";
    System.out.println("THE  REVERSE  OF THE  STRING IS: ");
    /*           APPROACH I ->>>>>    StringBuffer sb=new StringBuffer(str);
    System.out.println(sb.reverse());*/
     	
    for(int i=str.length()-1;i>=0;i--)
    {
    	System.out.print(str.charAt(i));
    }
    }

	}
