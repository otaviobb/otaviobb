import java.util.Scanner;
import java.io.*;

class Main {
  public static void main(String[] args) {
     double boleto1, boleto2, boleto3,boleto4, total,sobra,salariobruto,salarioliq;    
		Scanner ler = new 
    Scanner(System.in);
    
		System.out.println("Digite a fatura do Nubank:");
		boleto1 = ler.nextDouble();

		System.out.println("Digite a fatura do Inter:");
		boleto2 = ler.nextDouble();

		System.out.println("Digite a Fatura do Santander:");
		boleto3 = ler.nextDouble();
    
		System.out.println("Digite a fatura do financiamento Honda Civic G10:");
		boleto4 = ler.nextDouble();
		
		System.out.println("Digite seu salário bruto");
		salariobruto = ler.nextDouble();
    
        salarioliq = salariobruto-(salariobruto*0.14);
        System.out.println("Salario Liquido é" + salarioliq);
        
		total = boleto1+boleto2+boleto3+boleto4;
		System.out.println("O Total das contas : " + total);
		
		sobra= salarioliq-total;
		System.out.println("A sobra : " + sobra);
		
  }
}
