//otavio
import java.util.Scanner;
import java.io.*;

class Main {
  public static void main(String[] args) {
     double num1 , num2, num3, total;    
		Scanner ler = new 
    Scanner(System.in);
        System.out.println("Vamos calcular média aritimética");
    
		System.out.println("Digite o 1º número:");
		num1 = ler.nextDouble();

		System.out.println("Digite o 2º número:");
		num2 = ler.nextDouble();

		System.out.println("Digite o 3º número:");
		num3 = ler.nextDouble();
    
		total = num1+num2+num3+num3/3;
		System.out.print("A média aritimética é de: " + total);
  }
}

