# skillrack_daily_challenge
problem winner of card Game



import java.util.*;
public class Hello {

    public static void main(String[] args) {
		//Your Code Here
		String[] s={"Arun","Balaji","Chandra"};
		int res=0;
		Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        
        if(a==b&&b==c){
            System.out.println("TIE");
        }
        else if(a==b){
            System.out.println("Arun Balaji");
        }
        else if(a==c){
            System.out.println("Arun Chandra");
        }
        else if(b==c){
            System.out.println("Balaji Chandra");
        }
        else{
            if(a>b&&a>c)
            res=0;
            if(b>a&&b>c)
            res=1;
            if(c>a&&c>b)
            res=2;
            System.out.println(s[res]);
        }
      
	}
}
