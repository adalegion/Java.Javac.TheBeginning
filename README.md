# Instalación de Java

### Verifica que tienes Java instalado usando:
- `which java`
- `which javac`

### Verifica tu versión de Java:
- `java -version`
- `javac -version`


### Links para instalar Java:
- [Descarga Java SE](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Para la versión 8 de Java](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)


# Escribiendo y ejecutando "Hola Adalegion" en Java

1. Crea un archivo con extensión `.java`, como por ejemplo:
```
touch Hola.java
```
 
2. Escribe el siguiente código dentro del archivo anterior:
  ```java
  public class Hola {
        public static void main(String[] args) {
                System.out.println("¡Hola Adalegion!");
        }
}
  ```

3. Compila tú programa en ByteCode con
```
javac Hola.java
```

4. Finalmente, ejecútalo con
```
java Hola
```
