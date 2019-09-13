# Questao4

package exercicio.luana;

public class questao4 {

public static void main(String[] args) {
	int horaMensal = 180;
	int horaExtra= ((180-160)*50)/100;
	double salarioHora = 8.00;
	double salario= (salarioHora*horaMensal) + horaExtra;
	
      if(horaMensal>160) {
	      System.out.printf(" O salário de Felipe este mês foi de %.2f",salario);
    }
  }
}

Atividade 2

package poo;

public class PooTeste2 {

public static void main(String[] args) {
	double p1 = 8.5/2;
	double p2 = 5.0/3;
	double p3 = 9.2/5;
	double mediaFinal = p1 + p2 + p3;
	
	if (mediaFinal>=7) {
		
		System.out.printf("Parabéns! Você está aprovado! Sua média final foi: %.1f", mediaFinal);
		
	}else if(mediaFinal<=7) {
		
		System.out.printf("Você está de recuperação. Sua média final foi: %.1f", mediaFinal);
		
	}
}
}

© 2019 GitHub, Inc.
