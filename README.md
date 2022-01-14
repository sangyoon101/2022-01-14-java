# 2022-01-14 java Scanner 구구단 홀수항만 출력
import java.util.Scanner;
public class D20220114 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("단을 입력하세요");
		Scanner sc = new Scanner(System.in);
		int i = sc.nextInt();
		for(int j = 1; j<=9; j ++) {
			if(j %2 ==0)
				continue;
			System.out.println(i + "*" + j + "=" + i*j);
		}
	}

}
