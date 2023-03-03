package Verifica;

import java.lang.reflect.Array;
import java.util.Scanner;

public class fileverifica {

	public static void main(String[] args) {
		
		//PRIMA RICHIESTA//
		
int x = 0 ;         //Questo è il primo intero
int y = 0 ;			//Questo è il secondo intero
	

System.out.println(x + y);  //Questo è il metodo per stampare il risultato "somma" con gli interi scritti prima.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

		//SECONDA RICHIESTA//

Scanner valore= new Scanner(System.in); //nomino uno scanner affinchè io possa in seguito inserire i valori nel terminale


System.out.print("Inserisci il primo valore:"); 		 //testo che viene stampato nel terminale per la comprensione
x=valore.nextInt();                 //Primo valore che inseriremo nel terminale
System.out.print("Inserisci il secondo valore:");		 //testo che viene stampato nel terminale per la comprensione
y=valore.nextInt();					//Secondo valore che inseriremo nel terminale

System.out.println("La somma è: " + x + y);

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


		//TERZA e QUARTA RICHIESTA//

{
int[] insieme={2,4,6,8,10}; // array di interi
double m=0;          //variabile double per non perdere una parte dei dati, m = media
for(int i=0;i<insieme.length;i++) //ho stanziato le condizioni all'interno di un ciclo for
m+=insieme[i];
m=m/insieme.length;
System.out.println("La media è="+m);   //testo che viene stampato nel terminale per la comprensione

	

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

		//QUINTA e SESTA RICHIESTA//



String stringa1 = "Ciao";      								//Stringa da invertire
System.out.println("Questa è la stringa base:");
System.out.println(stringa1);								//Stampa della scritta da invertire
StringBuilder stringBuilder = new StringBuilder(stringa1);  //metodo utilizzato per poter invertire la stringa
stringa1 = stringBuilder.reverse().toString(); 				//Stringa invertita
System.out.println("Questa è la stringa invertita");
System.out.println(stringa1); 								//stampa scritta invertita
}}}
