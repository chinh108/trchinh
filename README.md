import java.util.Scanner;

public class Baitap {

public static void main (String args[]){
	int a,b;
	int tong = 0;
	Scanner sc = new Scanner(System.in);
	a = sc.nextInt();
	b = sc.nextInt();
	System.out.println("nhap so a: ");
	System.out.println("nhap so b: ");
	if (a<b) {
		for(int n = a; n <= b; n++){
			tong = tong+n;
		}
	}
	if (a>b) {
		for(int n = b; n <=a; n++){
			tong = tong+n;
		}
	}
	System.out.println("Tong la:" +tong);
		
}
}
