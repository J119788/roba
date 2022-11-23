package it.corso.java;

public class calcolatore {

	public static void main(String[] args) {
	
		calcolatrice c = new calcolatrice();
		double a = 100;
		double b = 20;
		
 		System.out.println(c.somma(a, b));
		System.out.println(c.sottrazione(a, b));
		System.out.println(c.moltiplicazione(a, b));
		System.out.println(c.divisione(a, b));

	}

}






package it.corso.java;

/**
 * Classe che implementa le operazioni aritmetiche
 * 
 * I metodi implementati consentono di effettuare le seguenti operazioni:
 * <ul>
 * <li>somma</li>
 * <li>sottrazione</li>
 * <li>moltiplicazione</li>
 * <li>divisione</li>
 * </ul>
 * @author Roberto
 *
 */


public class calcolatrice {
/**
 * 
 * @param a
 * @param b
 * @return	il metodo ritorna la somma tra a e b
 */
	public double somma(double a, double b) {
		return a+b;
	}
	
	public double sottrazione(double a, double b) {
		return a-b;
	}
	
	public double moltiplicazione(double a, double b) {
		return a*b;
	}
	
	public double divisione(double a, double b) {
		if (b==0) {
			System.out.println("attenzione: ti puzza il culo");
		}
		return a/b;
	}
}
