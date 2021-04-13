package week3;
import java.util.Scanner;

public class Demo {
public static void main(String[] args){
Scanner scanner = new Scanner(System.in);

System.out.println("请输入第一个自然数");

int start = scanner.nextInt();

System.out.println("请输入第二个自然数");

int end = scanner.nextInt();


int evenSum = 0;

int currentNum = start;

do{
if(currentNum % 2 == 0){
evenSum+=currentNum;

}

else{
oddSum+=currentNum;

}

currentNum++;

}while(currentNum <= end);

System.out.println("奇数为:");

System.out.println("偶数之和为:"+evenSum);

}

}
