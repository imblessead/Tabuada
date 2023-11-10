# Tabuada
Tabuada


//Apresentar os resultado de uma tabuada de multiplicar 1 ate 10 de um numero qualquer.
import java.util.Scanner;

public class Tabuada {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);

		System.out.println("Digite um numero que seja saber a sua tabuada : ");
		int numero = sc.nextInt();

		int tabuada = 1;
		while (tabuada < 11) {
			System.out.println(numero + "x" + tabuada + "=" + numero * tabuada);
			tabuada++;
			sc.close();
		}

	}

}
