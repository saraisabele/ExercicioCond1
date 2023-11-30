# ExercicioCond1
Resolução do exercicio 1 sobre estruturas condicionais (if/else) 

package exercicioCondicional1;
import java.util.Scanner;
public class ExercicioCond1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc = new Scanner(System.in);
		
		int numero; 
		System.out.println("Escreva um numero: ");
		numero = sc.nextInt();
		
		if (numero < 0) {
			System.out.println("NEGATIVO");
		}
		else {
			System.out.println("POSITIVO");
		}
		
		
		sc.close();
	}

}
