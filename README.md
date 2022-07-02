# previred
respuestas del cuestionario 


public class IteracionCaracteres {

    public static void main(String[] args) {
        
        String frase = "¡hola mundo!";
        
        for(int i = 0; i < frase.length(); ++i) {
            System.out.print(frase.charAt(i));
        }
        
        System.out.println();
        System.out.println();
        
        for(int i = frase.length() - 1; i >= 0; --i) {
            System.out.print(frase.charAt(i));
        }
    }
}

en este ejercicio podemos ver como recorrer una cadena de caracteres de una dirección a otra
1. se define la variable tipo string "frase" la cual recorrerá los caracteres que están dentro 
2. luego utilizamos el ciclo for la cual empieza desde el primer carácter hasta el ultimo, he usamos la función print para poder visualizar la frase
3. ahora nuevamente usamos el ciclo for el cual estará recorriendo la variable i y le estaremos usando un decremento unitario para poder leer la primera variable hasta la ultima pero esta vez estará al revés
