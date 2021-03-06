# Clase String
Para crear una cadena tenemos dos opciones:
- Instanciamos la clase String. Que sería una creación explicita de la clase
```java
String miCadena = new String("texto");
```
- Crear implícitamente la cadena de texto. Es decir, simplemente le asignamos el valor al objeto.
```java
String miCadena = "texto";
```

## Métodos Básicos con Cadenas
- length(): Devuelve el tamaño que tiene la cadena.
- charAt(int index): Devuelve el carácter de un indice indicado.
- toUpperCase(): Convertir la cadena a mayúsculas.
- toLowerCase(): Convertir la cadena a minúsculas.
- equals(Objecto objecto): Permite comparar si dos cadenas de texto son iguales.
- equalsIgnoreCase(String otraCadena): Compara dos cadenas de caracteres omitiendo si los caracteres están en mayúsculas o en minúsculas.
- indexOf(String cadena): Devuelve el primera indice del carácter o cadena.
- lastIndexOf(String cadena): Devuelve el ultimo indice del carácter o cadena.
- startsWith(String prefijo): Compara si empieza con el prefijo.
- endsWith(String sufijo): Compara si termina con el sufijo.
- substring(int indice): Devuelve la cadena de caracteres después del indice indicado.
- trim(): Elimina los espacios en blanco en el inicio y al final de la cadena.
- replace(String cadenaAnterior, String cadenaNuevo): Este método lo utilizaremos cuando lo que quaremos hacer sea el reemplazo un carácter por otro. Se reemplazarán todos los caracteres encontrados.

## [Anterior](page5.md)  --  [Siguiente](page7.md)