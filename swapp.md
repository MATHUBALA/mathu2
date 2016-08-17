# mathu2
a.util.Scanner;


public class Swapp {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
       Scanner scanner=new Scanner(System.in);
       int a=scanner.nextInt();
       int b=scanner.nextInt();

       System.out.println("after the swapp"+a);
       System.out.println("after the swapp"+b);
       int temp;
       temp=a;
       a=b;
       b=temp;
       System.out.println("before the swapp"+a);
       System.out.println("before the swapp"+b);
	}
	

}
