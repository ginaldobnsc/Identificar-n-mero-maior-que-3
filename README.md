# Identificar-n-mero-maior-que-3
Programa em Java para exibir o maior número dentre três números inteiros digitados pelo usuário

import java.util.Scanner;


public class Main
{
    
	public static void main(String[] args) {
	Scanner input = new Scanner(System.in);
	    int num1;
	    int num2;
	    int num3;
	    System.out.print("Digite o primeiro número: ");
	    num1 = input.nextInt();
	    System.out.print("Digite o segundo número: ");
	    num2 = input.nextInt();
	    System.out.print("Digite o terceiro número: ");
	    num3 = input.nextInt();
	//    System.out.printf("%d %d %d",num1,num2,num3);

	    if(num1>num2 && num1>num3){ System.out.printf("%d",num1);}
	    if(num2>num1 && num2>num3){ System.out.printf("%d",num2);}   
	    if(num3>num1 && num3>num2){ System.out.printf("%d",num3);}
	   	    
	    }
}
