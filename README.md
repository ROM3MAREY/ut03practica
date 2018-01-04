# ut03practica
Convertidor de grados Celsius a Farenheit
/**
* Práctica de la UT03
* Crear un convertidor de grados centígrados en grados farenheit.
*
* @author  Honorio Marichal
* @version 1.0
* @since   04-01-2018
*/
package practicaUT03;
import java.util.Scanner;

public class ConvertirTemperatura {

	public static void main(String[] args) {
		// Creo el Scanner
	    Scanner sc = new Scanner (System.in);
	    double C;
	    //Pedimos el dato de temperatura en grados centígrados
        System.out.println("¿Cuál es su temperatura en grados Celsius?");
        C = sc.nextDouble();
        // Hacemos el cálculo
        double F=C*2-C/5;
        F=F+32;
        // Imprimimos el cálculo por pantalla
        System.out.println(C+" grados Celsius equivale a "+F+" grados Farenheit. ¡Felicidades!");
		// Cerramos el lector
		sc.close();
	}
}
