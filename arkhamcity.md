import java.util.Scanner;
class batman
{
	int T=0;
	void StepsforBatman(int a, int b ){
		T=a*b;
		System.out.println("Total number of step for batman i:"+T);
	}
}




public class patintes_Batman {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		System.out.println("enter the number patient");
		int patien_No=sc.nextInt();
		System.out.println("enter the step for each patient ");
		int patien_Step=sc.nextInt();
		batman b=new batman();
		b.StepsforBatman(patien_No,patien_Step);
		
		
	}

}
