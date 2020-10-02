// this program is used to print a star(*) pattern

package TypesOfPatterns;
import java.util.Scanner;
// public is a Java keyword which declares a member's access as public. Public members are visible to all other classes. This means that any other class can access a public field //or method. Further, other classes can modify public fields unless the field is declared as fina
public class box 

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		int n=sc.nextInt();
		for(int i=1;i<=n;i++)
		{
			for(int j=1;j<=n;j++)
			{
				System.out.print("* ");
				
				
			}
			System.out.println(" ");
		}

		sc.close();}

}
