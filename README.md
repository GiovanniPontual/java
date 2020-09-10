# java
Calculadora de salários para profissionais liberais 

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
	Scanner sc= new Scanner(System.in);
	
	double salario;
	System.out.println("Qual Valor do salario pretendido :");
	salario=sc.nextDouble();
	
	double semana=salario/4;
	System.out.println("Você precisa ganhar por semana: "+semana);
	
	double dia=semana/5;
	System.out.println("Você precisa ganhar por dia: "+dia);
	
	double hora=dia/8;
	System.out.println("Você precisa ganhar por hora: "+hora);
	
	System.out.println("TRABALHANDO APENAS 8 HORAS AO DIA , DE SEGUNDA A SEXTA!");
	
	 
	 sc.close();
	 
	
	}

}
