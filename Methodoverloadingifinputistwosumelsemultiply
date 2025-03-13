import java.util.Scanner;
public class Methodoverloadingifinputistwosumelsemultiply {
    public static int calculate(int num1, int num2) {
        return num1 + num2;
    }
    public static int calculate(int num1, int num2, int num3) {
        return num1 * num2 * num3;
    }
    public static void calculate(int... numbers) {
        if (numbers.length > 3) {
            System.out.println("Wrong input");
        }
    }

    public static void main(String[] args) {
    	Scanner sc=new Scanner(System.in);
    	int n=sc.nextInt();
    	if(n==2) {
    		int num1=sc.nextInt();
    		int num2=sc.nextInt();
    		System.out.println(calculate(num1,num2));
    	}else if(n==3) {
    		int num3=sc.nextInt();
    		int num4=sc.nextInt();
    		int num5=sc.nextInt();
    		System.out.println(calculate(num3,num4,num5));
    	}
    	else {
    		System.out.println("Wrong input");
    	}
        
    }
}
