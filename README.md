# mathu2
import java.util.Scanner;


public class ReverseNum {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
    Scanner scanner=new Scanner(System.in);
    int a=scanner.nextInt();
    int n=0;
    while(a>0){
    	 n=a%10;
    	a=a/10;
    	 System.out.println(a);
    }
   
 
	}

}
