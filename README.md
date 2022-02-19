# Dia_da_Semana
imprimir o dia da semana de acordo com o número


package cursoLogica;
import java.util.Scanner;

public class ImprimeDIaDaSemana {

	public static void main(String[] args) {
		Scanner scanner = new Scanner (System.in);
		
		System.out.println(" Digite um numero referente ao dia da semana : ");
		Integer  diaDaSemana = scanner.nextInt();
		
		String dia;
		
		switch (diaDaSemana) {
		case 1: dia = " Domingo";
			break;
		case 2: dia  = " Segunda-feira";
			break;
		case 3: dia = "terca-feira";
			break;
		case 4: dia = " Quarta-Feira";
			break;
		case 5: dia  = "Quinta-feira";
			break;
		case 6: dia = "Sexta-feira";
			break;
		case 7: dia = "sabado";
		    break;
		 default: dia = "Invalido";
		}
		 
		 System.out.println("O dia escolhido foi: " + dia );
		 
		 scanner.close();
			

	}

}
