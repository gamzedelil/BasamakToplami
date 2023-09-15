# BasamakToplami

package basamaktoplami;

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	
		
		Scanner input = new Scanner(System.in);
		
		System.out.println("Sayi girin:");
		int sayi = input.nextInt();

		int toplam = 0;
		int gerceksayi = sayi;
		
		while (sayi > 0){
		int basamak = sayi % 10;
		toplam += basamak;
		sayi /=10; 
		}
		
		System.out.println("Sayinin basamak toplami:" +toplam);

      }
}
