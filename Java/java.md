|| Java

	Desarrollado por James Gosling y su equipo en Sun Microsystems a principios de la década de 1990. 

	La primera versión oficial, Java 1.0, fue lanzada en 1996. 

	El objetivo principal de Java en ese momento era proporcionar una plataforma de desarrollo que fuera independiente de la arquitectura de hardware y del sistema operativo, lo que significa que el código Java podría ejecutarse en cualquier dispositivo que tuviera una máquina virtual Java (JVM) instalada.

	El propósito inicial de Java era abordar los desafíos de la programación en un entorno de red. 

	Java fue diseñado para ser un lenguaje de programación seguro, portátil y de alto rendimiento. 

	Algunas de las características clave que contribuyeron a estos objetivos incluyen la portabilidad a través de la máquina virtual Java (JVM), la gestión automática de memoria (recolección de basura), y la seguridad incorporada.

	Desarrollo de aplicaciones empresariales y de servidor debido a su capacidad para ejecutarse en cualquier plataforma y su sólido soporte para la programación orientada a objetos.

	Java se utiliza en una variedad de aplicaciones, desde desarrollo de software empresarial y aplicaciones web hasta dispositivos móviles (a través de Android) y sistemas embebidos.

	Ha mantenido su posición en el desarrollo de grandes sistemas y aplicaciones empresariales gracias a su fiabilidad, escalabilidad y rendimiento.



|| Características 

	
	Portabilidad: 

		Java es conocido por su capacidad de ser "write once, run anywhere" (escribir una vez, ejecutar en cualquier lugar). 

		Esto se logra a través de la máquina virtual Java (JVM), que permite que el código Java sea ejecutado en cualquier dispositivo que tenga una JVM instalada, independientemente de la plataforma subyacente.


	Orientación a Objetos:

		Java es un lenguaje de programación orientado a objetos, lo que significa que sigue los principios de la programación orientada a objetos como encapsulamiento, herencia y polimorfismo. 

		Esto facilita la creación de software modular y reutilizable.


	Seguridad: 

		Java ha integrado características de seguridad desde sus primeras versiones. 

		La máquina virtual Java (JVM) ejecuta el código de manera segura, utilizando un modelo de seguridad basado en la ejecución de código en un entorno controlado llamado "sandbox". Además, Java incluye herramientas y tecnologías para la gestión de seguridad, como la firma digital y la gestión de claves.


	Manejo Automático de Memoria: 

		Java utiliza un recolector de basura (garbage collector) para gestionar automáticamente la liberación de memoria no utilizada. 

		Esto simplifica el desarrollo al evitar la necesidad de que los programadores gestionen manualmente la asignación y liberación de memoria.


	Rendimiento: 

		A lo largo de las versiones, Java ha mejorado constantemente su rendimiento. 

		La introducción de la máquina virtual Java HotSpot y otras optimizaciones ha permitido que las aplicaciones Java sean rápidas y eficientes.


	Multi-Hilo y Concurrencia:

		Java ofrece soporte nativo para programación multihilo, lo que permite la creación de aplicaciones concurrentes y paralelas. 

		Las clases y bibliotecas en Java proporcionan facilidades para la concurrencia de manera segura.


	APIs: 

		Java incluye una amplia gama de bibliotecas y APIs estándar que abarcan desde operaciones de entrada/salida hasta manipulación de datos, redes, GUI (interfaz gráfica de usuario), criptografía, y mucho más. 

		Esto acelera el desarrollo de aplicaciones al proporcionar componentes predefinidos y funcionalidades listas para usar.


	Desarrollo de Aplicaciones Empresariales: 

		Java es muy utilizado en el desarrollo de aplicaciones empresariales debido a su robustez y escalabilidad.

		Frameworks como Spring facilitan la creación de aplicaciones empresariales complejas y modulares.


	Comunidad Activa y Ecosistema: 

		Java cuenta con una amplia comunidad de desarrolladores y un ecosistema vibrante.

		Hay numerosos frameworks y herramientas de desarrollo disponibles que facilitan la creación de diversos tipos de aplicaciones.


	Actualizaciones y Mejoras Continuas: 

		Java ha experimentado actualizaciones y mejoras constantes a lo largo del tiempo, introduciendo nuevas características y tecnologías para mantenerse relevante y a la vanguardia de las tendencias en desarrollo de software.



|| Instalación 

	Java JDK: 

		Usado para desarrollar Apps Java. 


	Java JRE: 

		Usado para ejecutar Apps Java. 


	Verificar instalación: 

		```
		java -version

		```



|| Versiones


    JDK 1.0 (enero de 1996):

    	La primera versión oficial de Java, que incluía las bibliotecas básicas y la máquina virtual Java (JVM).


    JDK 1.1 (febrero de 1997): 

    	Introdujo nuevas características, como las clases internas anidadas y las interfaces.


    J2SE 1.2 (diciembre de 1998): 

    	Marcó el inicio de la plataforma Java 2, Standard Edition. Introdujo las colecciones, eventos de manejo, Swing y mejoras en la máquina virtual.


    J2SE 1.3 (mayo de 2000):

    	Incluyó mejoras de rendimiento, el manejo de excepciones y la introducción de Java Naming and Directory Interface (JNDI).


    J2SE 1.4 (febrero de 2002): 

    	Introdujo las afirmaciones (assertions), la API de Logging, la API de la máquina virtual y mejoras en la seguridad.


    J2SE 5.0 (también conocido como Java 5 o J2SE 1.5) (septiembre de 2004): 

    	Introdujo importantes características como generics, enumeraciones, autoboxing, y anotaciones.


    Java SE 6 (diciembre de 2006): 

    	Incluyó mejoras en el rendimiento, la introducción de Java Compiler API, y la inclusión de la máquina virtual Java HotSpot.


    Java SE 7 (julio de 2011): 	

    	Introdujo las expresiones lambda, el manejo multicatch, el soporte para la concurrencia y la introducción de la clase Fork/Join para la programación concurrente.


    Java SE 8 (marzo de 2014): 

    	La versión más destacada, que introdujo las expresiones lambda, Streams API, la interfaz funcional java.util.function, y la introducción de la plataforma JavaFX.


    Java SE 9 (septiembre de 2017): 

    	Marcó un cambio importante con la introducción de Jigsaw, que permite la modularización del JDK, y la inclusión de un nuevo sistema de módulos.


    Java SE 10 (marzo de 2018): 

    	Introdujo mejoras en el sistema de inferencia de tipos, la eliminación de herramientas obsoletas, y mejoras en la JVM.


    Java SE 11 (septiembre de 2018): 

    	Fue una versión de soporte a largo plazo (LTS) y marcó la transición de Oracle a un nuevo modelo de licencia.


    Java SE 12 a Java SE 16 (marzo de 2019 - marzo de 2021): 

    	Incluyeron mejoras incrementales y nuevas características, como el patrón switch expresión en Java SE 12 y la introducción del proyecto Panama para mejorar la interoperabilidad entre Java y código nativo en Java SE 16.


    Java SE 17 (septiembre de 2021): 

    	Introdujo mejoras en la seguridad, rendimiento y nuevas características	





|| JAVA_HOME

	Variable de entorno que se utiliza comúnmente en sistemas Unix y Windows para apuntar al directorio de instalación principal de Java (JDK o JRE). 

	Esta variable es especialmente útil en entornos de desarrollo, ya que muchas aplicaciones y herramientas dependen de saber dónde está instalado Java en el sistema.

	Proporciona a otras aplicaciones y herramientas un punto de referencia consistente para localizar la instalación de Java en tu sistema. 

	Algunas herramientas y scripts de compilación, como Maven o Gradle, pueden requerir esta variable para funcionar correctamente.


	Ubicación de Java: 

		```
		which java
		
		```

		```
		echo $PATH

		```

	Config JAVA_HOME: 

		```	
		export JAVA_HOME=/ruta/a/tu/instalacion/java
		
		export PATH=$JAVA_HOME/bin:$PATH

		```		

	Inicio automático:

		Agregar estos comandos a tu archivo de perfil (como .bashrc o .bash_profile) para que se configuren automáticamente cada vez que inicies sesión. 



|| Ejecución 

	Implica usar la máquina virtual Java (JVM) para interpretar y ejecutar el código Java.


	Compilar: 

		Un archivo '.java' debe compilarse.

		La instrucción 'javac' viene con JDK.

		```
		javac TuPrograma.java

		```	

		Generará un archivo '.class' que contiene el bytecode ejecutable.


		Usamos la instrucción 'java' sin la extensión '.class'

		```
		java TuPrograma

		```


	Ejecutar Clase principal 'main': 


		Es una clase especifica, debes proporcionar el nombre completo de la clase principal después de java.

		```
		java paquete.TuClasePrincipal

		```

		'paquete' es el nombre del paquete (si lo hay) y 'TuClasePrincipal' es el nombre de la clase con el método main.


	Si encuentras problemas, asegúrate de que Java esté en tu PATH y que las variables de entorno estén configuradas correctamente.



|| JAVA PATH

	Variable que especifica una lista de directorios en los cuales el sistema operativo debe buscar ejecutables cuando se emite un comando desde la línea de comandos o la terminal.

	Es relevante para ejecutar programas Java desde la línea de comandos sin tener que especificar la ruta completa al ejecutable de Java.	 



|| Bibliotecas Estándar

	Java tiene una amplia biblioteca estándar que cubre diversas áreas del desarrollo de aplicaciones. 


	java.lang: 

		Proporciona clases fundamentales, como Object (la raíz de la jerarquía de clases en Java), String (para manipulación de cadenas), Math (operaciones matemáticas básicas), System (interacción con el entorno del sistema), entre otras.


    java.util: 

    	Incluye clases y interfaces para estructuras de datos como listas, conjuntos, mapas, colas, así como clases para manejar fechas, temporizadores y otras utilidades.


    java.io: 

    	Ofrece clases para operaciones de entrada/salida, como lectura y escritura de archivos y flujos de datos.


    java.net: 

    	Proporciona clases para la programación de red, incluyendo sockets, URLs y protocolos como HTTP.


    java.awt y javax.swing:

    	Son bibliotecas para la creación de interfaces gráficas de usuario (GUI). 

    	AWT (Abstract Window Toolkit) es la biblioteca original, mientras que Swing proporciona componentes de GUI más avanzados y flexibles.


    java.nio: 

    	Ofrece soporte para operaciones de entrada/salida no bloqueantes y otras mejoras relacionadas con la manipulación de archivos.


    java.security: 

    	Contiene clases relacionadas con la seguridad, como cifrado, firmas digitales y generación de números aleatorios seguros.


    java.sql: 

    	Proporciona API para acceder y manipular bases de datos utilizando el lenguaje SQL.


    java.util.concurrent:

    	Ofrece clases para programación concurrente, incluyendo ejecutores, colecciones concurrentes y barreras.


    java.rmi: 

    	Implementa la infraestructura para la invocación remota de métodos, lo que permite la comunicación entre objetos distribuidos en una red.


    java.text: 

    	Contiene clases para manipular y formatear texto, incluyendo manipulación de fechas y números.


    java.xml y javax.xml:

    	Proporcionan soporte para el procesamiento de XML, incluyendo análisis y generación de documentos XML.


    java.util.regex: 

    	Incluye clases para el manejo de expresiones regulares.



|| Métodos en Java

	Java es un lenguaje orientado a objetos, fuertemente tipado. 

	Funciona a traves de métodos, clases e instancias. 


	Operaciones Básicas:

    	Clase Math:

    	 	Proporciona métodos matemáticos básicos como sqrt, pow, abs, etc.


    	```java

    	double raizCuadrada = Math.sqrt(25.0);

    	```


    Cadenas y Caracteres: 

	    Clase String: 

	    	Ofrece numerosos métodos para manipulación de cadenas, como length(), charAt(), substring(), etc.

	    
	    ```java

	    String mensaje = "Hola, mundo!";
		
		int longitud = mensaje.length();
	    
	    ```


	Entrada/Salida (I/O):

    	Clase System:

    		Proporciona métodos para entrada/salida estándar, como out.println.

    	```java

		System.out.println("Hola, mundo!");    	

    	```


	Colecciones:

   		Paquete java.util:

    		Contiene clases como ArrayList, HashMap, LinkedList para manipular colecciones de datos.    


    	```java
		
		List<String> lista = new ArrayList<>();
		
		lista.add("Elemento 1");

    	```


	Fecha y Hora:

    	Paquete java.time:

    		Introducido en Java 8, ofrece clases como LocalDate, LocalTime, DateTimeFormatter	    

    	```java

    	LocalDate fechaActual = LocalDate.now();

    	```


    Manejo de Archivos:

    	Clase java.nio.file.Files:

    		Proporciona métodos para leer, escribir y manipular archivos.


    	```java

    	Path ruta = Paths.get("archivo.txt");

		List<String> lineas = Files.readAllLines(ruta);

    	```


    Expresiones Regulares:

    	Paquete java.util.regex:

    		Permite el uso de expresiones regulares para búsqueda y manipulación de texto.


    	```java

		Pattern patron = Pattern.compile("\\d+");
		
		Matcher matcher = patron.matcher("123abc");    	
		```


	Redes:

    	Paquete java.net:

    		Contiene clases para trabajar con operaciones de red, como Socket y URL.


    	```java

    	URL url = new URL("https://www.ejemplo.com");

    	```


    Multihilo y Concurrencia:

    	Paquete java.util.concurrent:

    		Ofrece clases y utilidades para programación concurrente.


    	```java

    	ExecutorService executor = Executors.newFixedThreadPool(5);

    	```


    Interfaz Gráfica de Usuario (GUI):

    	Paquetes java.awt y javax.swing:

    		Proporcionan clases y componentes para desarrollar interfaces gráficas de usuario.


    	```java

    	JFrame ventana = new JFrame("Mi Aplicación");

    	```



|| Tipos de datos

	Se clasifican en tipos de datos primitivos y tipos de datos de referencia (u objetos).


	1. Primitivos:

    Enteros/int(-+):

        byte: 

        	8 bits, rango de -128 a 127.

        short: 

        	16 bits, rango de -32,768 a 32,767.

        int: 

        	32 bits, rango de -2,147,483,648 a 2,147,483,647.

        long: 

        	64 bits, rango de -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807.

        ```java

        int numeroEntero = 42;
		long numeroLargo = 123456789L;

        ```


    Flotante:

		float: 

			32 bits, precisión de 7 dígitos decimales.

		double: 

			64 bits, precisión de 15 dígitos decimales.

		```java

		float numeroFlotante = 3.14f;
		double numeroDoble = 2.71828;

		```


	Caracteres:

    	char: 

    		16 bits, representa un carácter Unicode.

    	```java

    	char letra = 'A';

    	```


    Booleanos:

    	boolean: 

    		Representa valores booleanos true o false.

    	```java

    	boolean esVerdadero = true;

    	```


    2. Referencia:


    Cadenas:

    	String: 

    		Secuencia de caracteres Unicode.

    	```java

    	String mensaje = "Hola, mundo!";

    	```


	Arreglos:

    	Representan colecciones de elementos del mismo tipo.   

    	```java

    	int[] arregloEnteros = {1, 2, 3, 4, 5};

    	```


    Clases y Objetos:

    	Los tipos de datos creados por el usuario, definidos mediante clases y objetos.

    	```java

    	class Persona {
		    String nombre;
		    int edad;
		}

		Persona persona = new Persona();

    	```


	Tipos Especiales:

    	null: 

    		Representa la ausencia de un valor o un objeto nulo.    

    	```java

    	String cadenaNula = null;

    	```



|| Operadores 

	
	1. Aritméticos: 

	Suma: 

		```
		int resultado = a + b;

		```

	Resta: 

		```
		int resultado = a - b;
			
		```

	Multiplicación: 

		```
		int resultado = a * b;
			
		```

	División: 

		```
		int resultado = a / b;
			
		```

	Módulo (Residuo):

		```
		int resultado = a % b;
			
		```

	Incremento: 

		```
		a++;
			
		```

	Decremento: 

		```
		b--;
			
		```


	2. Asignación: 


	Simple: 

		```
		int x = 10;
			
		```

	Asignación con Suma, resta, etc: 

		```
		a += 5 // Equivalente a: a = a + 5;
			
		```


	3. Relacionales: 


	Igual a: 

		```java

		if (a == b) {
		    // ...
		}

		```

	No igual: 

		```java

		if (a != b) {
		    // ...
		}

		```

	Mayor que, Menor que, Mayor o Igual, Menor o Igual: 

		```java

		if (a > b) {
		    // ...
		}

		if (a < b) {
		    // ...
		}

		if (a >= b) {
		    // ...
		}

		if (a <= b) {
		    // ...
		}

		```


	4. Lógicos: 


	AND: 

		```java

		if (condicion1 && condicion2) {
		    // ...
		}

		```

	Or: 

		```java

		if (condicion1 || condicion2) {
		    // ...
		}

		```

	Not: 

		```java

		if (!condicion) {
		    // ...
		}

		```


	5. Bitwise: 


	And Bitwise: 

		```java

		int resultado = a & b;

		```

	OR Bitwise:

		```java

		int resultado = a | b;

		```

	XOR Bitwise: 

		```java

		int resultado = a ^ b;

		```

	Desplazamiento a la Izquierda, Desplazamiento a la Derecha: 	

		```java

		int resultado = a << 2;  // Desplazamiento a la izquierda
		
		int resultado2 = a >> 1; // Desplazamiento a la derecha

		```		


	6. Ternario y Nulo: 


	Ternario: 

		```java

		int maximo = (a > b) ? a : b;			

		```

	Nulo (null): 

		```java

		String nombre = (nombreUsuario != null) ? nombreUsuario : "Invitado";

		```



|| Estructuras de Control

	Permiten a los programadores controlar el flujo de ejecución de un programa.


	Control de Selección:


	If-Else:

		Se utiliza para tomar decisiones basadas en condiciones.

		```
		if (condicion) {
		    // Bloque de código si la condición es verdadera
		} else {
		    // Bloque de código si la condición es falsa
		}

		```


	Switch-Case:

		Se utiliza para seleccionar una opción entre varias opciones.

		```java

		int opcion = 2;
		switch (opcion) {
		    case 1:
		        // Código para la opción 1
		        break;
		    case 2:
		        // Código para la opción 2
		        break;
		    default:
		        // Código para el caso por defecto (si ninguna opción coincide)
		}

		```


	Control de Iteración (Bucles):

	For:

		Se utiliza para repetir un bloque de código un número específico de veces.

		```
		for (int i = 0; i < 5; i++) {
		    // Bloque de código a repetir
		}

		```


	While:

		Se utiliza para repetir un bloque de código mientras una condición sea verdadera.

		```
		while (condicion) {
		    // Bloque de código a repetir
		}

		```


	Do-While:

		Similar a while, pero garantiza que el bloque de código se ejecute al menos una vez, ya que la condición se verifica después de la ejecución del bloque.

		```	
		do {
		    // Bloque de código a repetir
		} while (condicion);

		```


	Control de Salida:


	Break:

		Se utiliza para salir de un bucle o un bloque switch antes de que se complete normalmente.

		```
		for (int i = 0; i < 10; i++) {
		    if (i == 5) {
		        break; // Sale del bucle cuando i es igual a 5
		    }
		}

		```


	Continue:
		
		Se utiliza para pasar a la siguiente iteración de un bucle sin ejecutar el resto del código dentro del bucle para la iteración actual.

		```
		for (int i = 0; i < 10; i++) {
		    if (i == 5) {
		        continue; // Salta a la siguiente iteración cuando i es igual a 5
		    }
		    // Código aquí que no se ejecutará cuando i sea igual a 5
		}

		```



|| Estructuras de Datos

	Se utilizan para almacenar y organizar información de manera eficiente.


	Listas: 


	ArrayList:

		Implementa la interfaz List y proporciona una lista dinámica que puede crecer o reducir su tamaño según sea necesario.

		```java

		List<String> lista = new ArrayList<>();
		lista.add("Elemento 1");
		lista.add("Elemento 2");

		```


	LinkedList:

		Es una lista doblemente enlazada que permite un rápido acceso y modificación en ambos extremos de la lista.

		```java

		LinkedList<Integer> listaEnlazada = new LinkedList<>();
		listaEnlazada.add(1);
		listaEnlazada.add(2);

		```


	Conjuntos:
	

	HashSet:

		Implementa la interfaz Set y utiliza una tabla hash para almacenar elementos. 

		No permite elementos duplicados.

		```java

		Set<String> conjunto = new HashSet<>();
		conjunto.add("Elemento 1");
		conjunto.add("Elemento 2");

		```


	TreeSet:

		Implementa la interfaz SortedSet y mantiene los elementos ordenados en orden natural o mediante un comparador.	

		```java

		SortedSet<Integer> conjuntoOrdenado = new TreeSet<>();
		conjuntoOrdenado.add(3);
		conjuntoOrdenado.add(1);

		```


	Mapas: 


	HashMap:

		Implementa la interfaz Map y utiliza una tabla hash para almacenar pares clave-valor.

		```java

		Map<String, Integer> mapa = new HashMap<>();
		mapa.put("clave1", 1);
		mapa.put("clave2", 2);

		```


	Pilas:


	Stack:

		Representa una pila (stack) y sigue el principio de Last-In, First-Out (LIFO). 

		```
		Stack<String> pila = new Stack<>();
		pila.push("Elemento 1");
		pila.push("Elemento 2");

		```


	Colas: 


	Queue:

		Interfaz que representa una cola y sigue el principio de First-In, First-Out (FIFO).

		```
		Queue<String> cola = new LinkedList<>();
		cola.offer("Elemento 1");
		cola.offer("Elemento 2");

		```


	Arrays:
	

	Arrays:

		Estructuras de datos estáticas que pueden almacenar elementos del mismo tipo.

		```
		int[] arreglo = {1, 2, 3, 4, 5};

		```


	Vectores


	Vector: 

		Es una versión sincronizada de un array dinámico y es parte de las colecciones legadas de Java.

		```
		Vector<String> vector = new Vector<>();
		vector.add("Elemento 1");
		vector.add("Elemento 2");

		```



|| Sintaxis Java 

	Sintaxis básica para la declaración de variables, objetos, clases, estructuras, métodos, etc. 

	Todo gira entorno a las clases, dada las características de la programación orientada a objetos del lenguaje Java .


	Clases: 

		Necesitamos clases para definir variables. 

		```java

		public class MiClase {
		    public static void main(String[] args) {
		        // Declaración de variables
		        int edad = 25;
		        double altura = 1.75;
		        String nombre = "Juan";

		        // Imprimir variables
		        System.out.println("Nombre: " + nombre);
		        System.out.println("Edad: " + edad);
		        System.out.println("Altura: " + altura);
		    }
		}

		```


	Estructuras de Control:

		If-Else: 

			```java

			public class MiClase {
			    public static void main(String[] args) {
			        int edad = 18;

			        // Estructura de control If-Else
			        if (edad >= 18) {
			            System.out.println("Eres mayor de edad");
			        } else {
			            System.out.println("Eres menor de edad");
			        }
			    }
			}

			```


	Bucle for: 

		```java

		public class MiClase {
		    public static void main(String[] args) {
		        // Bucle For para imprimir números del 1 al 5
		        for (int i = 1; i <= 5; i++) {
		            System.out.println(i);
		        }
		    }
		}


		```


	Métodos: 

		```java

		public class MiClase {
		    public static void main(String[] args) {
		        // Llamada a un método
		        saludar("Juan");
		    }

		    // Definición de un método
		    static void saludar(String nombre) {
		        System.out.println("¡Hola, " + nombre + "!");
		    }
		}

		```


	Excepciones: 
		
		```java

		public class MiClase {
		    public static void main(String[] args) {
		        // Manejo de excepciones
		        try {
		            int resultado = dividir(10, 0);
		            System.out.println("Resultado: " + resultado);
		        } catch (ArithmeticException e) {
		            System.err.println("Error: División por cero");
		        }
		    }

		    // Método que puede lanzar una excepción
		    static int dividir(int numerador, int denominador) {
		        return numerador / denominador;
		    }
		}

		```


|| Proyecto básico 

	Estructura del proyecto, código, compilación y ejecución: 

	Estructura:

		Carpetas que contienen los módulos de la app. 


	Código: 

		Archivos para desarrollar. 

		```java

		public class HolaMundo {
		    public static void main(String[] args) {
		        System.out.println("¡Hola, mundo!");
		    }
		}

		```


	Compilación: 

		Transformar el archivo de código en un programa que la computadora pueda leer y entender. 

		```
		javac HolaMundo.java

		```

		Generará un archivo llamado 'HolaMundo.class'.


	Ejecución: 	

		Usar el programa. 

		```
		java HolaMundo

		```



|| Buenas prácticas


	1. Convenciones de Nombres:

    	Clases y Métodos: 

    		Usa nombres de clases y métodos significativos y en camelCase (ej. 'MiClase', 'miMetodo()').

    	Variables: 

    		Usa nombres de variables en camelCase y evita nombres de una sola letra (excepto para contadores en bucles).


	2. Comentarios Significativos:

	    Usa comentarios para explicar el propósito y la lógica detrás del código.

	    Evita comentarios innecesarios que simplemente repitan lo que hace el código.


	3. Organización del Código:

	    Paquetes: 

	    	Organiza tus clases en paquetes lógicos y sigue la convención de nombres de paquetes invertidos (ej. 'com.ejemplo.miproyecto').

	    Importaciones: 

	    	Limita las importaciones a lo esencial y evita importar clases enteras cuando solo necesitas unas pocas.


	4. Manejo de Excepciones:

	    No ignores las excepciones. Trata las excepciones o lánzalas si no puedes manejarlas adecuadamente.

	    Usa excepciones específicas en lugar de excepciones genéricas.


	5. Uso de Constantes:

	    Usa constantes para valores que no cambian ('final static').

	    Usa nombres en mayúsculas con subrayados para constantes (ej. 'MAXIMO_VALOR').


	6. Programación Defensiva:

	    Valida las entradas de los usuarios y las entradas externas para evitar errores.

	    Usa assertions ('assert') para verificar condiciones que siempre deben ser verdaderas.


	7. Evitar el Uso Excesivo de Estática:

	    Evita clases y métodos estáticos si no son realmente necesarios.

	    Prefiere la inyección de dependencias en lugar de métodos y variables estáticas.


	8. Programación Orientada a Objetos (OOP):

	    Aplica los principios 'SOLID'.
	    Evita el acoplamiento excesivo entre clases.


	9. Uso Efectivo de Colecciones:

	    Elije la implementación de colecciones adecuada para tu caso de uso.

	    Utiliza generics para hacer que tus colecciones sean más seguras y legibles.


	10. Testing:

	    Escribe pruebas unitarias para tus clases y métodos.
	    Usa frameworks de pruebas como 'JUnit'.


	11. Mantén un Estilo Consistente:

	    Adopta un estilo de codificación consistente en todo el proyecto.

	    Usa sangrías y espacios de manera coherente.


	12. Versionado y Control de Código:

	    Utiliza un sistema de control de versiones como 'Git'.

	    Etiqueta las versiones de tu software.



|| Buenas prácticas Tipado


	Genéricos:

	    Utiliza Genéricos para Hacer Código Reutilizable y Seguro. 

	    Donde sea posible, utiliza genéricos para crear clases y métodos que sean más flexibles y seguros en términos de tipos.


	    Evita el uso de raw types (tipos sin parámetros) en favor de tipos genéricos.

	    Proporciona parámetros de tipo siempre que sea posible.

	    ```java

	    // Evita esto:
		List lista = new ArrayList();

		// Prefiere esto:
		List<String> lista = new ArrayList<>();

	    ```


	Casting: 

		Utiliza Castings con Cuidado.

		Limita el uso de castings y utilízalos solo cuando sea necesario. 

		Si encuentras la necesidad frecuente de realizar castings, revisa la estructura de tu código.

		```java

		// Evita esto:
		double resultado = (double) numerador / denominador;

		// Mejor así:
		double resultado = (double) numerador / (double) denominador;

		```


	Enums:

    	Usa enums para representar conjuntos de constantes relacionadas. 

    	Esto mejora la legibilidad del código y evita errores tipográficos.

    	```java

    	// Evita esto:
		public static final int LUNES = 1;
		public static final int MARTES = 2;

		// Mejor así:
		public enum Dia {
		    LUNES, MARTES
		}

    	```


    Valores Nulos:
    	
    	Intenta evitar el uso excesivo de null en tus programas. 

    	Utiliza objetos nulos con moderación y considera otras estrategias, como Optional (introducido en Java 8), para representar la ausencia de valor de manera más explícita.

    	```java

    	// Evita esto:
		String nombre = null;

		// Mejor así:
		Optional<String> nombreOptional = Optional.ofNullable(nombre);

    	```


    Immutabilidad:

    	Prefiere Objetos Inmutables.

    	Donde sea posible, utiliza objetos inmutables para mejorar la seguridad y la predictibilidad del código.


    	```java

    	// Evita esto:
		public class MutablePersona {
		    private String nombre;

		    public void setNombre(String nombre) {
		        this.nombre = nombre;
		    }
		}

		// Mejor así:
		public final class PersonaInmutable {
		    private final String nombre;

		    public PersonaInmutable(String nombre) {
		        this.nombre = nombre;
		    }

		    public String getNombre() {
		        return nombre;
		    }
		}

    	```



|| Buenas prácticas Variables
	

	Nombres Descriptivos:
		
		Usa nombres descriptivos y significativos para tus variables globales para mejorar la legibilidad del código.

		```java

		// Evita esto:
		int x;

		// Mejor así:
		int contadorDeUsuarios;

		```


	Inicialización Antes de Uso:

		Asegúrate de inicializar tus variables locales antes de usarlas para evitar errores.

		```java

		// Evita esto:
		int y;
		// ... código ...
		System.out.println(y);  // Error: variable y podría no haber sido inicializada

		// Mejor así:
		int y = 5;
		// ... código ...
		System.out.println(y);

		```


	Minimiza el Uso de Variables Globales:

		Evita el uso excesivo de variables globales (atributos de clase) y utiliza la encapsulación adecuada. 

		Prefiere pasar datos entre métodos o clases mediante parámetros y retorno de valores.



	Minimiza el Ámbito de las Variables:
		
		Limita el ámbito de tus variables locales tanto como sea posible.

		Decláralas donde las necesitas y no antes.

		```java

		// Evita esto:
		int x;
		// ... código ...
		x = 10;

		// Mejor así:
		// ... código ...
		int x = 10;

		```


	Evita el Uso de Variables Globales Mutables:

		Si debes usar variables globales, intenta que sean inmutables siempre que sea posible. 

		Las variables globales mutables pueden ser fuente de problemas de concurrencia y dificultar el rastreo de errores.


	Usa Modificadores de Acceso Apropiados:

		Usa modificadores de acceso como 'private', 'protected' y 'public' para controlar la visibilidad de tus variables globales y proporcionar la encapsulación adecuada.

		```java

		// Evita esto:
		public class Ejemplo {
		    int variableGlobal;  // Debería ser private o protected
		}

		// Mejor así:
		public class Ejemplo {
		    private int variableGlobal;
		}

		```




|| Buenas prácticas Memoria

	La administración de memoria es manejada por el recolector de basura (garbage collector), lo que facilita en gran medida la tarea de los programadores al liberarlos de la responsabilidad directa de asignar y liberar memoria. 


	Referencias Nulas:

    	Evita Referencias Nulas Innecesarias.

    	Intenta mantener las referencias nulas al mínimo. Cuando una variable ya no se necesita, asignarle null puede ayudar al recolector de basura a liberar la memoria.


    	```java

    	// Evita esto:
		MiObjeto objeto = new MiObjeto();
		// ... código ...
		objeto = null;  // Esto puede ser innecesario

		// Mejor así:
		MiObjeto objeto = new MiObjeto();
		// ... código ...
		// No asigna null si la variable está fuera de alcance y no se necesita más

    	```


    Objetos Inútiles:

    	Evita Crear Objetos Inútiles.
    	
    	Minimiza la creación de objetos temporales que podrían generarse durante la ejecución de tu programa.

    	Puedes reutilizar objetos o utilizar tipos primitivos cuando sea posible.

    	```java

    	// Evita esto:
		String resultado = "Hola" + " " + "Mundo";

		// Mejor así:
		String saludo = "Hola";
		String mundo = "Mundo";
		String resultado = saludo + " " + mundo;

    	```


    Ciclo de Vida de los Objetos:

    	Comprende el Ciclo de Vida de los Objetos.
    	
    	Entiende cómo funciona el recolector de basura y cuándo se ejecuta. 

    	Aprende sobre las fases del ciclo de vida de los objetos (creación, uso, obsolescencia, recolección) y cómo pueden afectar el rendimiento.


    Manejo de Recursos Externos:

    	Cierra Recursos Externos.
    	
    	Si estás trabajando con recursos externos como archivos, bases de datos o conexiones de red, asegúrate de cerrar esos recursos cuando ya no sean necesarios para liberar cualquier recurso asociado.

    	```java

    	// Ejemplo con archivos
		try (FileInputStream fis = new FileInputStream("archivo.txt")) {
		    // ... código ...
		} catch (IOException e) {
		    e.printStackTrace();
		}

    	```


    Uso Cauteloso de finalize():

    	Evita Dependencias en 'finalize()'.
    
    	Evita depender en exceso del método 'finalize()' para liberar recursos. 

    	Este método no garantiza la liberación inmediata y no debería ser utilizado como principal mecanismo de liberación de recursos.


	Perfil de Memoria:

    	Utiliza Herramientas de Perfil de Memoria.

    	Usa herramientas de perfil de memoria para identificar posibles fugas de memoria y optimizar el uso de la memoria en tu aplicación.    


    Optimización Prematura:

    	Evita la Optimización Prematura.

    	No te obsesiones con la optimización antes de que sea necesario. 

    	Escribir código claro y mantenible es prioritario.

    	La optimización prematura a menudo conduce a complicaciones innecesarias.


    El recolector de basura es una parte fundamental de Java que simplifica en gran medida la administración de la memoria. 

    En la mayoría de los casos, confiar en él es suficiente, y las prácticas anteriores están más orientadas a situaciones específicas y a mejorar la eficiencia en casos particulares.



|| Variables

	Contenedor que almacena datos que pueden ser modificados durante la ejecución de un programa.

	Tienen un nombre, un tipo de datos y un valor.

	```java

	// Sintaxis básica de declaración de variable
	tipoDato nombreVariable;

	// Ejemplos
	int edad;
	double salario;
	String nombre;

	// Inicialización de variables
	edad = 25;
	salario = 50000.0;
	nombre = "Juan";

	```


	Tipos de datos: 

		Java es un lenguaje fuertemente tipado, lo que significa que cada variable debe tener un tipo de datos específico.

		Primitivos: 

			int, double, float, char, boolean, etc.
    	
    	Objetos: 

    		String, ArrayList, HashMap, etc.
    	
    	Tipos Personalizados: 

    		Clases que defines en tu código.


   	Convención de Nombres de Variables:

		Los nombres de variables en Java deben comenzar con una letra, un guion bajo (_) o el símbolo del dólar ($).

		Los nombres de variables distinguen entre mayúsculas y minúsculas (son sensibles a mayúsculas y minúsculas).

		Es una buena práctica seguir la convención de nomenclatura camelCase para nombres de variables (miVariable, nombrePersona, etc.).


	Ámbito de Variables:

		El ámbito de una variable define la parte del programa donde la variable puede ser utilizada. 

		En Java, el ámbito de una variable está determinado por el bloque de código en el que se declara.


	```java	

	public class EjemploVariables {
	    public static void main(String[] args) {
	        // Declaración e inicialización de variables
	        int edad = 25;
	        double salario = 50000.0;
	        String nombre = "Juan";

	        // Mostrar valores de variables
	        System.out.println("Nombre: " + nombre);
	        System.out.println("Edad: " + edad);
	        System.out.println("Salario: " + salario);
	    }
	}

	```
	
	Se declaran valores y se imprimen en la consola. 



|| Swap variables
	
	Intercambio de valores entre dos variables. 

	Es una operación común y útil, y en Java, se puede realizar de varias maneras. 

	La idea principal es intercambiar los valores almacenados en dos variables sin la necesidad de una variable temporal adicional.


	1. Usando una Variable Temporal: 

	```java

	public class SwapEjemplo {

	    public static void main(String[] args) {
	        // Declaración e inicialización de variables
	        int a = 5;
	        int b = 10;

	        // Mostrar valores originales
	        System.out.println("Antes del swap: a = " + a + ", b = " + b);

	        // Swap usando una variable temporal
	        int temp = a;
	        a = b;
	        b = temp;

	        // Mostrar valores después del swap
	        System.out.println("Después del swap: a = " + a + ", b = " + b);
	    }
	}

	```


	2. Sin Usar Variable Temporal (Usando Operadores Aritméticos):

	```java

	public class SwapEjemplo {

	    public static void main(String[] args) {
	        // Declaración e inicialización de variables
	        int a = 5;
	        int b = 10;

	        // Mostrar valores originales
	        System.out.println("Antes del swap: a = " + a + ", b = " + b);

	        // Swap sin usar variable temporal
	        a = a + b;
	        b = a - b;
	        a = a - b;

	        // Mostrar valores después del swap
	        System.out.println("Después del swap: a = " + a + ", b = " + b);
	    }
	}

	```


	3. Sin Usar Variable Temporal (Usando XOR):

	```java

	public class SwapEjemplo {

	    public static void main(String[] args) {
	        // Declaración e inicialización de variables
	        int a = 5;
	        int b = 10;

	        // Mostrar valores originales
	        System.out.println("Antes del swap: a = " + a + ", b = " + b);

	        // Swap sin usar variable temporal usando XOR
	        a = a ^ b;
	        b = a ^ b;
	        a = a ^ b;

	        // Mostrar valores después del swap
	        System.out.println("Después del swap: a = " + a + ", b = " + b);
	    }
	}

	```

	Operador XOR: 

		El operador XOR (Exclusivo o) es un operador lógico que se utiliza para determinar si solo una de las dos expresiones es verdadera. 

		Si una de las expresiones es verdadera y la otra es falsa, el resultado es verdadero. 

		Si ambas expresiones son verdaderas o ambas son falsas, el resultado es falso.



|| Public, Private, Protected Default, Static, Void

	Los modificadores de acceso permiten dar un nivel de seguridad mayor a nuestras aplicaciones restringiendo el acceso a diferentes atributos, métodos, constructores asegurándonos que el usuario deba seguir una "ruta" especificada por nosotros para acceder a la información.

	El encapsulamiento busca de alguna forma controlar el acceso a los datos que conforman un objeto o instancia, de este modo podríamos decir que una clase y por ende sus objetos que hacen uso de modificadores de acceso (especialmente privados) son objetos encapsulados.

	Siempre que se use una clase de otro paquete, se debe importar usando import. 

	Cuando dos clases se encuentran en el mismo paquete ('package') no es necesario hacer el import pero esto no significa que se pueda acceder a sus componentes directamente. 


	public:

		Es un modificador de acceso que indica que el método es accesible desde cualquier otra clase. 

		En otras palabras, el método puede ser llamado desde cualquier parte del código, ya sea dentro de la misma clase, desde otras clases en el mismo paquete o desde clases en otros paquetes.


	private:

		Es el más restrictivo de todos, cualquier elemento de una clase que sea privado puede ser accedido únicamente por la misma clase y nada más. 

		Es decir, si por ejemplo, un atributo es privado solo puede ser accedido por lo métodos o constructores de la misma clase. 

		Ninguna otra clase sin importar la relación que tengan podrá tener acceso a ellos.

		Generalmente el acceso a los atributos se consigue por medio de los métodos 'get()' y 'set()', pues es estrictamente necesario que los atributos de una clase sean privados.

		Siempre se recomienda que los atributos de una clase sean privados y por tanto cada atributo debe tener sus propios métodos get y set para obtener y establecer respectivamente el valor del atributo.


	protected: 

		Nos permite acceso a los componentes con 'protected' desde la misma clase, clases del mismo paquete y clases que hereden de ella (incluso en diferentes paquetes).

		Un error común pensar que se puede crear un objeto (instancia) de la clase madre y luego acceder al atributo con acceso protected sin problemas, sin embargo esto no es cierto, puesto que el modificador 'protected' lo que nos permite es acceder al atributo heredado desde el ámbito de la clase hija y no directamente.


	default: 

		Java nos da la opción de no usar un modificador de acceso y al no hacerlo, el elemento tendrá un acceso conocido como defaulto acceso por defecto que permite que tanto la propia clase como las clases del mismo paquete accedan a dichos componentes (de aquí la importancia de declararle siempre un 'paquete' a nuestras clases).


	static: 

		Indica que el método pertenece a la clase en lugar de una instancia específica de la clase. 

		Esto significa que el método puede ser llamado sin necesidad de crear una instancia de la clase. 

		Los métodos estáticos se asocian directamente con la clase y no con objetos individuales de esa clase.


	void: 

		Es el tipo de dato de retorno del método. 

		En Java, void significa que el método no devuelve ningún valor. 

		Es decir, el método realiza ciertas operaciones, pero no produce un resultado que pueda ser utilizado por el código que lo llamó.

		El resultado no se utilizará más adelante. 



|| Parámetros
	
	Son valores que se pasan a un método durante su invocación.

	Permiten que un método acepte datos desde el exterior, lo que le proporciona la flexibilidad de trabajar con diferentes valores en cada llamadas.
	
	```java

	// Declaración de un método con parámetros
	public void miMetodo(int parametro1, String parametro2) {
	    // Cuerpo del método que utiliza los parámetros
	    // ...
	}

	```

	Cuando este método es llamado, se espera que se le proporcionen un valor 'int' y una cadena ('String') como argumentos.


	```java

	// Llamada al método con argumentos
	miObjeto.miMetodo(10, "Hola");

	```


	1. Parámetro de valor: 

		En Java, los parámetros se pasan por valor, lo que significa que se pasa una copia del valor real al método.
    	
    	Si se modifica el valor del parámetro dentro del método, no afectará al valor original fuera del método.

    	```java

    	public void duplicar(int x) {
		    x = x * 2;
		}

		int numero = 5; 
		duplicar(numero);
		System.out.println(numero); // Imprimirá 5, no 10

    	```


    2. Parámetros de Referencia:

    	Cuando se pasa un objeto como parámetro, se está pasando una referencia al objeto, no una copia de los datos.

    	Si se modifica el contenido del objeto dentro del método, los cambios se reflejarán fuera del método.
		

    	```java

    	public void modificarLista(List<String> lista) {
		    lista.add("Nuevo elemento");
		}

		List<String> miLista = new ArrayList<>();
		modificarLista(miLista);
		System.out.println(miLista); // Imprimirá [Nuevo elemento]

    	```

    	Creamos el objeto 'miLista' de tipo 'List<String>' para usar el método 'modificarLista' que acepta como argumento un objeto 'List<String>'.


    3. Número y Tipo de Parámetros:

    	Un método puede tener cero o más parámetros.
    
    	El tipo y el orden de los parámetros deben coincidir entre la declaración del método y su llamada.


    4. Parámetros de Varargs:

    	Java también admite parámetros de longitud variable (varargs) que permiten pasar un número variable de argumentos del mismo tipo al método.

    	```java

		public void imprimirValores(int... valores) {
		    for (int valor : valores) {
		        System.out.println(valor);
		    }
		}

		imprimirValores(1, 2, 3, 4);

    	```


	5. Expresión 'main(String[] args){}': 

		Se refiere al método principal (main method) que sirve como punto de entrada para la ejecución de un programa Java.

		main: 

			Este es el nombre del método principal en Java. 

			Es el método que se ejecuta primero cuando se inicia un programa Java.


		String[] args: 

			Este es el parámetro del método main. 

			'String[]' indica que es un array (arreglo) de objetos de tipo String. 

			El parámetro 'args' es un nombre comúnmente utilizado, pero podría ser cualquier otro nombre válido. 

			Este parámetro se utiliza para pasar argumentos desde la línea de comandos al programa Java cuando se ejecuta.

			String es el tipo de datos que admite todos los tipos de datos primitivos como int, long, float, double, byte, shot, char.

			String es el único tipo (inmutable) que puede representar todos los valores posibles que puede proporcionar el usuario en la línea de comando.

			De lo contrario, la JVM no reconocerá el método principal como un método de punto de partida o entrada.



		```java

		public class MiPrograma {
		    public static void main(String[] args) {
		        System.out.println("¡Hola, mundo!");
		        
		        // Imprimir los argumentos pasados al programa
		        for (String arg : args) {
		            System.out.println("Argumento: " + arg);
		        }
		    }
		}

		```

		El programa simplemente imprime "¡Hola, mundo!" en la consola y luego imprime cualquier argumento que se haya pasado al programa en la línea de comandos.

		Cuando ejecutas un programa Java desde la línea de comandos, puedes proporcionar argumentos adicionales después del nombre del programa.

		```bash

		java MiPrograma arg1 arg2 arg3

		```

		'arg1', 'arg2' y 'arg3' serían elementos del array args que se pasan al método main.

		Estos argumentos pueden ser utilizados por el programa para personalizar su comportamiento según sea necesario.


		Mostrar argumentos de la terminal: 

			En Java, args contiene los argumentos de la línea de comandos proporcionados como una matriz de objetos String.

			Si ejecutamos en la terminal: 

			```
			java MiPrograma uno dos

			```

			entonces los argumentos contendrán ["uno", "dos"].

			Si desea generar el contenido de los argumentos, puede recorrerlos:

			```java

			public class mostrarArgs {
			    
			    public static void main (String [] args) {
			        
			        for(int i = 0; i < args.length; i++) {
			             
			            System.out.println(args[i]);
			        }
			    }
			}

			```

			El programa imprimirá en la terminal:

			```
			java MiPrograma uno dos
			
			```
			>>uno
			>>dos
			    
			

	6. Parámetro 'List<String>':

		Es un tipo de parámetro genérico que se utiliza para indicar que el parámetro esperado es una lista que contiene elementos de tipo 'String'.	

		List: 

			Es una interfaz en Java que representa una colección ordenada. 

			Las implementaciones comunes de List incluyen 'ArrayList', 'LinkedList', y 'Vector'. 

			Una lista permite almacenar elementos en un orden específico y proporciona métodos para acceder, agregar, eliminar y modificar elementos.


		String: 

			Es el tipo de elemento que se espera en la lista. 

			En este caso, se espera que la lista contenga elementos de tipo 'String'


		```java

    	public void procesarLista(List<String> lista) {
		    // Código para procesar la lista de Strings
		    for (String elemento : lista) {
		        System.out.println(elemento);
		    }
		}

		// Llamada al método con una lista de Strings
		List<String> miLista = Arrays.asList("Uno", "Dos", "Tres");
		procesarLista(miLista);

    	```

		'procesarLista' es un método que toma una lista de Strings como parámetro ('List<String>'), y se llama al método con una lista específica ('miLista'), que contiene los elementos "Uno", "Dos" y "Tres".

		El uso de tipos genéricos, como 'List<String>', proporciona flexibilidad y seguridad de tipos al trabajar con colecciones, ya que permite especificar el tipo de elementos que se espera dentro de la colección.    	


	7. Expresión readList'(List<String> list)':

		Se refiere a la declaración de un método llamado 'readList' que toma un parámetro de tipo 'List<String>'.    	

		readList: 

			Este es el nombre del método. 

			En este caso, se llama readList.


    	(List<String> list): 

    		Esto define los parámetros del método.

    		En este caso, hay un único parámetro llamado list, que es de tipo 'List<String>'. 

    		Esto significa que 'list' es una lista que contiene elementos de tipo String.		

		```java

		import java.util.List;

		public class EjemploMetodo {
		    public static void main(String[] args) {
		        // Crear una lista de cadenas
		        List<String> listaCadenas = List.of("Hola", "Mundo", "!");

		        // Llamar al método readList pasando la lista como argumento
		        readList(listaCadenas);
		    }

		    // Definición del método readList
		    public static void readList(List<String> list) {
		        // Iterar sobre la lista e imprimir cada elemento
		        for (String elemento : list) {
		            System.out.println(elemento);
		        }
		    }
		}

		```    		

		'readList' es un método que imprime cada elemento de una lista de cadenas que recibe como argumento. 

		Cuando se llama al método 'readList' desde el método 'main', se pasa la lista 'listaCadenas' como argumento.

		Luego, el método 'readList' itera sobre esta lista e imprime cada elemento en la consola.



|| User Input

	Se refiere a la información que un programa recibe del usuario durante su ejecución.

	
	Clase Scanner: 	

		Desde la biblioteca estándar 'java.util'


	```java

	import java.util.Scanner;

	public class UserInputExample {
	    public static void main(String[] args) {
	        // Crear un objeto Scanner para leer la entrada del usuario
	        Scanner scanner = new Scanner(System.in);

	        // Solicitar al usuario que ingrese un valor
	        System.out.print("Ingrese un número: ");

	        // Leer la entrada del usuario y almacenarla en una variable
	        int numeroIngresado = scanner.nextInt();

	        // Mostrar el valor ingresado por el usuario
	        System.out.println("Número ingresado: " + numeroIngresado);

	        // Cerrar el objeto Scanner para liberar recursos
	        scanner.close();
	    }
	}

	```

	1. Importamos la clase 'Scanner' desde el paquete java.util.

    2. Creamos un objeto Scanner llamado 'scanner' que está asociado a la entrada estándar ('System.in'), que generalmente corresponde al teclado.

    3. Usamos el método 'nextInt()'' para leer un entero que el usuario ingrese.

    4. Mostramos el número ingresado por el usuario en la consola.

	5. Cerramos el objeto 'Scanner' para liberar recursos.    
    

	Ten en cuenta que el manejo de excepciones, como 'InputMismatchException', puede ser necesario para manejar casos en los que el usuario ingrese datos que no coincidan con el tipo esperado.



|| Expressions
	
	Combinación de variables, operadores y valores que produce un resultado.

	Operadores: 

		Símbolos que indican la operación a realizar entre operandos.

	Operandos: 

		Son las variables o valores con los que se realiza la operación. 

	```java

	int resultado = 5 + 3;  // En esta expresión, 5 y 3 son operandos;  "+" es el operador de suma.

	```

	Variables: 

		Son nombres que representan valores almacenados en la memoria.

	```java

	int x = 10;
	int y = 20;
	int suma = x + y;  // x + y es una expresión que utiliza las variables x e y.

	```

	1. Expresiones Aritméticas:

		Realizan operaciones matemáticas.

	```java

	int resultado = 10 * (3 + 5);  // Expresión aritmética que utiliza paréntesis.
	
	```


	2. Expresiones Relacionales: 

		Evalúan condiciones y producen resultados booleanos.

	```java

	boolean esMayor = (x > y);  // Expresión relacional que evalúa si x es mayor que y.

	```


	3. Expresiones Lógicas: 

		Realizan operaciones lógicas y producen resultados booleanos.

	```java

	boolean andLogico = (x > 0) && (y > 0);  // Expresión lógica con operador AND.

	```


	4. Expresiones Condicionales (Ternarias): 

		Son expresiones compactas para tomar decisiones basadas en una condición.

	```java

	int maximo = (x > y) ? x : y;  // Expresión condicional que asigna el máximo de x e y.

	```		


	Evaluación de Expresiones: 

		Las expresiones se evalúan y producen un resultado. 

		Este resultado puede ser almacenado en una variable, utilizado en una instrucción, o pasado como argumento a otro método.		


|| GUI

	La Interfaz Gráfica de Usuario se refiere a la parte visual de una aplicación que permite a los usuarios interactuar con el programa mediante elementos gráficos como ventanas, botones, menús, campos de texto, etc. 

	En Java, se utiliza el paquete javax.swing y otros componentes para construir interfaces gráficas.


	Swing: 

	1. JFrame: 

		Es una ventana de nivel superior que sirve como contenedor principal para otros componentes de la interfaz gráfica.

		```java

		import javax.swing.JFrame;

		public class MiVentana extends JFrame {
		    // Constructor y otros métodos para configurar la ventana
		}

		```


	2. JPanel: 

		Es un contenedor ligero que se utiliza para organizar otros componentes dentro de un contenedor más grande, como un JFrame.

		```java

		import javax.swing.JPanel;

		public class MiPanel extends JPanel {
		    // Constructor y otros métodos para configurar el panel
		}

		```


	3. Componentes Swing: 

		Incluyen botones (JButton), etiquetas (JLabel), campos de texto (JTextField), áreas de texto (JTextArea), listas (JList), y muchos más. 

		Estos componentes se utilizan para construir la interfaz gráfica.

		```java

		import javax.swing.JButton;
		import javax.swing.JLabel;
		import javax.swing.JTextField;

		```


	Ejemplo: 


	```java

	import javax.swing.JButton;
	import javax.swing.JFrame;
	import javax.swing.JPanel;

	public class MiVentana extends JFrame {

	    public MiVentana() {
	        // Configurar la ventana
	        setTitle("Mi Aplicación");
	        setSize(400, 300);
	        setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

	        // Crear un panel
	        JPanel panel = new JPanel();

	        // Crear un botón
	        JButton boton = new JButton("Haz clic");

	        // Agregar el botón al panel
	        panel.add(boton);

	        // Agregar el panel a la ventana
	        add(panel);
	    }

	    public static void main(String[] args) {
	        // Crear una instancia de la ventana y hacerla visible
	        MiVentana ventana = new MiVentana();
	        ventana.setVisible(true);
	    }
	}

	```

	JFrame se utiliza como la ventana principal.

    JPanel se utiliza como un contenedor para organizar componentes.

    JButton se utiliza para crear un botón.


    Event Listener: 

    	Para que la interfaz gráfica sea interactiva, se utilizan escuchadores de eventos para responder a las acciones del usuario, como hacer clic en un botón. 

    	Los escuchadores se implementan mediante interfaces como 'ActionListener'.

    ```java

    import javax.swing.JButton;
	import javax.swing.JFrame;
	import java.awt.event.ActionEvent;
	import java.awt.event.ActionListener;

	public class MiVentana extends JFrame implements ActionListener {

	    public MiVentana() {
	        // ...

	        // Crear un botón
	        JButton boton = new JButton("Haz clic");

	        // Agregar un escuchador de eventos al botón
	        boton.addActionListener(this);

	        // ...
	    }

	    // Implementar el método actionPerformed para responder a eventos
	    @Override
	    public void actionPerformed(ActionEvent e) {
	        System.out.println("Botón clicado");
	    }
	}


    ```



|| Math Class

	Es parte del paquete 'java.lang' y proporciona un conjunto de métodos estáticos que realizan operaciones matemáticas comunes.

	Estos métodos permiten realizar cálculos como funciones trigonométricas, exponenciación, logaritmos, redondeo, y otras operaciones matemáticas. 

	Dado que los métodos de la clase Math son estáticos, puedes llamarlos directamente sin necesidad de crear una instancia de la clase.


	Operaciones básicas: 

		1. Math.abs(double a): 	

			Devuelve el valor absoluto de un número	

		```java

		double valorAbsoluto = Math.abs(-5.5); // Devuelve 5.5

		```


		2. Math.max(double a, double b): 	

			Devuelve el valor máximo entre dos números.

		```java

		double maximo = Math.max(10.5, 8.3); // Devuelve 10.5

		```

		3. Math.min(double a, double b): 

			Devuelve el valor mínimo entre dos números.


	Funciones Trigonométricas: 	

		Math.sin(double a), Math.cos(double a), Math.tan(double a):


	```java

	double seno = Math.sin(Math.toRadians(30)); // Seno de 30 grados

	```


	Funciones Exponenciales y Logaritmos: 

		1. Math.exp(double a):

			Devuelve e elevado a la potencia de un número.

		```java

		double exponencial = Math.exp(2); // Devuelve e^2

		```


		2. Math.log(double a): 

			Devuelve el logaritmo natural de un número.

		```java

		double logNatural = Math.log(10); // Devuelve el logaritmo natural de 10

		```


	Redondeo y Truncado:

    	1. Math.round(double a):

    		Redondea un número al entero más cercano.

    	```java

    	long redondeado = Math.round(3.8); // Devuelve 4

    	```


		2. Math.floor(double a), Math.ceil(double a):

			Devuelve el número entero más grande menor o igual a 'a', o el número entero más pequeño mayor o igual a 'a', respectivamente.

		```java

		double haciaAbajo = Math.floor(5.7); // Devuelve 5.0
		
		double haciaArriba = Math.ceil(5.7);  // Devuelve 6.0

		```


|| Random numbers

	Generación de números aleatorios se realiza a través de la clase 'java.util.Random'. 

	Esta clase proporciona métodos para generar valores aleatorios de diferentes tipos de datos, como enteros, decimales y booleanos.


	1. Creación de una Instancia de Random:
		
		Para utilizar la clase Random, primero necesitas crear una instancia de la misma.

		```java

		import java.util.Random;

		// Crear una instancia de Random
		Random random = new Random();

		```


	2. Generación de Enteros Aleatorios:

		Puedes utilizar el método 'nextInt()' para generar un entero aleatorio.

		```java

		int numeroAleatorio = random.nextInt();

		```


		Puedes especificar un límite para el rango de números generados.

		```java

		// Generar un entero aleatorio entre 0 (inclusive) y 100 (exclusive)
		
		int numeroEnRango = random.nextInt(100);

		```


	3. Generación de Decimales Aleatorios:
		
		Para generar números decimales aleatorios, puedes utilizar 'nextDouble()'.

		```java

		double decimalAleatorio = random.nextDouble();

		```


	4. Generación de Booleanos Aleatorios:
		
		'nextBoolean()' genera un valor booleano aleatorio.

		```java

		boolean valorBooleano = random.nextBoolean();

		```

	Ejemplo completo: 

	```java

	import java.util.Random;

	public class RandomExample {
	    public static void main(String[] args) {
	        // Crear una instancia de Random
	        Random random = new Random();

	        // Generar un entero aleatorio entre 1 y 10 (ambos inclusive)
	        int numeroAleatorio = random.nextInt(10) + 1;

	        // Generar un decimal aleatorio entre 0.0 (inclusive) y 1.0 (exclusive)
	        double decimalAleatorio = random.nextDouble();

	        // Generar un valor booleano aleatorio
	        boolean valorBooleano = random.nextBoolean();

	        // Imprimir los valores generados
	        System.out.println("Número Aleatorio: " + numeroAleatorio);
	        System.out.println("Decimal Aleatorio: " + decimalAleatorio);
	        System.out.println("Valor Booleano Aleatorio: " + valorBooleano);
	    }
	}

	```


	Semilla (seed): 

		La secuencia de números generada por la clase Random se basa en un algoritmo y, por lo tanto, si proporcionas la misma semilla, obtendrás la misma secuencia de números. 

		En aplicaciones donde se requiere reproducibilidad, puedes establecer una semilla utilizando el método 'setSeed(long seed)'.		

		```java

		// Establecer una semilla para reproducibilidad
		
		random.setSeed(123);

		```



|| If

	Se utilizan para tomar decisiones basadas en una condición.

	```java

	if (condición) {
    	// Código a ejecutar si la condición es verdadera
	}	

	```

	Condición: 

		Es una expresión booleana que se evalúa como verdadera (true) o falsa (false). 

		Si la condición es verdadera, el bloque de código dentro del if se ejecuta; de lo contrario, se salta.


    Bloque de Código: 

    	Es un conjunto de instrucciones encerradas entre llaves {}. 

    	Este bloque de código se ejecuta solo si la condición especificada es verdadera.



    Ejemplo:

    ```java

    int numero = 7;

	if (numero > 5) {
	    System.out.println("El número es mayor que 5");
	}

    ```

    El código dentro del bloque if se ejecutará porque la condición numero > 5 es verdadera.


    If-else: 

		Especificar un bloque de código que se ejecutará si la condición en el if es falsa.

	```java

	if (condición) {
	    // Código a ejecutar si la condición es verdadera
	} else {
	    // Código a ejecutar si la condición es falsa
	}

	```


	Ejemplo: 

	```java

	int numero = 3;

	if (numero > 5) {
	    System.out.println("El número es mayor que 5");
	} else {
	    System.out.println("El número no es mayor que 5");
	}

	```

	'numero' es 3, la condición del if es falsa, y se ejecutará el bloque de código dentro del else.


	if-else if-else:

		Encadenar múltiples condiciones utilizando else if para manejar varias opciones.

	```java

	if (condición1) {
	    // Código a ejecutar si la condición1 es verdadera
	} else if (condición2) {
	    // Código a ejecutar si la condición1 es falsa y la condición2 es verdadera
	} else {
	    // Código a ejecutar si todas las condiciones anteriores son falsas
	}

	```

	Ejemplo: 

	```java

	int numero = 0;

	if (numero > 0) {
	    System.out.println("El número es positivo");
	} else if (numero < 0) {
	    System.out.println("El número es negativo");
	} else {
	    System.out.println("El número es cero");
	}

	```



|| Switch

	Se utiliza para tomar decisiones basadas en el valor de una expresión.

	Proporciona una manera más limpia y eficiente de manejar múltiples casos en comparación con una serie de declaraciones if-else.

	```java

	switch (expresion) {
	    case valor1:
	        // Código a ejecutar si la expresión es igual a valor1
	        break;
	    case valor2:
	        // Código a ejecutar si la expresión es igual a valor2
	        break;
	    // Otros casos...
	    default:
	        // Código a ejecutar si ninguno de los casos anteriores coincide
	}

	```

	Expresión: 

	    Es una expresión cuyo valor se compara con los diferentes casos. 

	    Puede ser de tipo byte, short, char o int, o sus clases envolventes.


    Caso (case): 

    	Cada case especifica un valor posible de la expresión. 

    	Si la expresión coincide con un case, el bloque de código asociado se ejecutará.


    Break: 

    	Es una palabra clave que se utiliza para salir de la estructura switch después de que se ha ejecutado un bloque de código asociado a un case. 

    	Si se omite, la ejecución continuará en los casos siguientes, lo cual puede no ser el comportamiento deseado.


    Default: 

    	Es opcional y se ejecuta si ninguno de los casos anteriores coincide con la expresión. 

    	Puedes pensar en default como el equivalente de else en una estructura if-else.


    Ejemplo: 

    ```java

    int diaDeLaSemana = 3;
	String nombreDia;

	switch (diaDeLaSemana) {
	    case 1:
	        nombreDia = "Lunes";
	        break;
	    case 2:
	        nombreDia = "Martes";
	        break;
	    case 3:
	        nombreDia = "Miércoles";
	        break;
	    case 4:
	        nombreDia = "Jueves";
	        break;
	    case 5:
	        nombreDia = "Viernes";
	        break;
	    default:
	        nombreDia = "Fin de semana";
	}
	System.out.println("Hoy es " + nombreDia);

    ```

    'diaDeLaSemana' tiene un valor de 3, por lo que se ejecutará el bloque de código asociado al case 3, y se imprimirá "Hoy es Miércoles".


    La expresión en un switch solo puede ser de tipos primitivos o de la clase String a partir de Java 7. 

    Además, ten en cuenta que, a partir de Java 12, la estructura switch se ha mejorado con la expresión de switch (Switch Expressions), lo que proporciona una forma más concisa y expresiva de manejar casos.



|| Switch Expressions

	Mejora de la expresión de switch se introdujo en Java 12 para proporcionar una forma más concisa y expresiva de manejar casos en comparación con la versión anterior de switch.

	```java

	public class SwitchExpressionsExample {
	    public static void main(String[] args) {
	        int diaDeLaSemana = 3;

	        String nombreDia = switch (diaDeLaSemana) {
	            case 1 -> "Lunes";
	            case 2 -> "Martes";
	            case 3 -> "Miércoles";
	            case 4 -> "Jueves";
	            case 5 -> "Viernes";
	            default -> "Fin de semana";
	        };

	        System.out.println("Hoy es " + nombreDia);
	    }
	}

	```

	'switch' ahora se evalúa a un valor y ese valor se puede asignar directamente a una variable (nombreDia en este caso).
	
	La nueva sintaxis utiliza -> para asignar el resultado del case a la variable.


	No hay necesidad de usar 'break' ni 'default'.

	Además, puedes manejar múltiples valores en un solo case utilizando comas.

	Ejemplo: 

	```java

	public class SwitchExpressionsExample2 {
	    public static void main(String[] args) {
	        String diaDeLaSemana = "Lunes";

	        String tipoDia = switch (diaDeLaSemana) {
	            case "Lunes", "Martes", "Miércoles", "Jueves", "Viernes" -> "Día laboral";
	            case "Sábado", "Domingo" -> "Fin de semana";
	            default -> throw new IllegalStateException("Valor inesperado: " + diaDeLaSemana);
	        };

	        System.out.println("Tipo de día: " + tipoDia);
	    }
	}

	```


|| Operadores lógicos

	Permiten realizar operaciones lógicas entre valores booleanos o expresiones condicionales.

	AND Lógico (&&):

    	Sintaxis: 

    		expresion1 && expresion2
    	
    	Devuelve true si ambas expresion1 y expresion2 son true; de lo contrario, devuelve false.
				
	    ```java

	    boolean a = true;
		boolean b = false;
		boolean resultado = a && b; // resultado es false

	    ```	


	OR Lógico (||):

	    Sintaxis: 

	    	expresion1 || expresion2
	    
	    Devuelve true si al menos una de expresion1 o expresion2 es true; devuelve false si ambas son false.

		```java

		boolean a = true;
		boolean b = false;
		boolean resultado = a || b; // resultado es true

		```


	NOT Lógico (!):

		Sintaxis: 

			!expresion

		Devuelve true si expresion es false, y viceversa.

		```java

		boolean a = true;
		boolean resultado = !a; // resultado es false

		```


	Tabla de verdad: 

		A 	B 	A&&B 	A||B 	!A
		t 	t 	t 		t  	 	f
		t 	f 	f 		t 		f
		f 	t 	f 		t 		t
		f 	f 	f 		f  		t



|| While

	Se utiliza para repetir un bloque de código mientras una condición dada sea verdadera.	

	```java

	while (condición) {
	    // Código a repetir mientras la condición sea verdadera
	}

	```

	La 'condición' se evalúa antes de que se ejecute el bloque de código. 

	Si la condición es 'true', el bloque de código se ejecuta.
	
	Después de la ejecución del bloque, la condición se vuelve a evaluar.

	Si la condición sigue siendo 'true', el bloque se ejecutará nuevamente. 

	Este proceso se repetirá hasta que la condición se evalúe como 'false', momento en el que el bucle 'while' se detendrá y la ejecución del programa continuará con la siguiente instrucción después del bucle.


	```java

	int contador = 1;

	while (contador <= 5) {
	    System.out.println("Número: " + contador);
	    contador++;
	}

	```

	'contador' se inicializa en 1.
	La condición 'contador <= 5' se evalúa. 

	Como es verdadera, se ejecuta el bloque de código dentro del bucle while.

	El número se imprime en la consola, y luego contador se incrementa en 1.

	La condición se vuelve a evaluar. 

	Este proceso se repite hasta que contador alcanza el valor de 6, momento en el cual la condición se evalúa como false y el bucle while se detiene.

	Asegúrate de que la condición eventualmente se vuelva false para que el bucle se detenga.


	Es posible un while sin un bloque de código y usarlo para ejecutar múltiples instrucciones dentro del bucle:

	```java

	int contador = 1;

	while (contador <= 5) {
	    System.out.println("Número: " + contador);
	    System.out.println("¡Hola!");
	    contador++;
	}

	```

	Las dos instrucciones dentro del bucle se ejecutarán repetidamente mientras la condición sea verdadera.



|| For

	Es una estructura de control de flujo que se utiliza para repetir un bloque de código un número específico de veces.

	```java

	for (inicialización; condición; expresión de iteración) {
	    // Código a repetir en cada iteración
	}

	```

	Inicialización: 

		Se realiza una vez al inicio del bucle y generalmente se utiliza para inicializar la variable de control del bucle.


    Condición: 

    	Se evalúa antes de cada iteración. 

    	Si es true, el bucle continúa; si es false, el bucle se detiene.


    Expresión de Iteración: 

    	Se ejecuta después de cada iteración. 

    	Generalmente se utiliza para modificar la variable de control del bucle.

    ```java

    for (int i = 1; i <= 5; i++) {
	    System.out.println("Número: " + i);
	}

	```

	int i = 1: 

		La variable i se inicializa en 1.

    i <= 5: 

    	La condición es true mientras i sea menor o igual a 5.

    i++: 

    	Después de cada iteración, i se incrementa en 1.

	El bucle se ejecutará cinco veces, imprimiendo los números del 1 al 5 en la consola.


	Se puede utilizar para recorrer arreglos o collecciones de datos. 

	```java

	int[] numeros = {1, 2, 3, 4, 5};

	for (int i = 0; i < numeros.length; i++) {
	    System.out.println("Número: " + numeros[i]);
	}

	```

	'i' se utiliza como el índice para acceder a cada elemento del arreglo numeros.



|| Nested Loop

	Es un bucle contenido dentro de otro bucle.

	Esto significa que hay un bucle dentro del cuerpo de otro bucle.

	Puedes tener bucles anidados dentro de bucles anidados, creando así múltiples niveles de repetición.

	```java

	for (inicialización1; condición1; expresión de iteración1) {
	    // Código del primer bucle

	    for (inicialización2; condición2; expresión de iteración2) {
	        // Código del segundo bucle (anidado)
	    }

	    // Más código del primer bucle (se ejecuta después del segundo bucle)
	}

	```


	Ejemplo: 

		Imprimir una tabla de multiplicar.


	```java

	for (int i = 1; i <= 5; i++) {
	    for (int j = 1; j <= 5; j++) {
	        System.out.print(i * j + "\t");
	    }
	    System.out.println(); // Salto de línea después de cada fila
	}

	```

	El primer bucle for (bucle externo) itera sobre las filas de la tabla de multiplicar (números del 1 al 5).

    El segundo bucle for (bucle interno) itera sobre las columnas de la tabla de multiplicar (también números del 1 al 5).

    Dentro del bucle interno, se imprime el resultado de la multiplicación de i * j.


    Salida: 

    ```
    1   2   3   4   5   
	2   4   6   8   10  
	3   6   9   12  15  
	4   8   12  16  20  
	5   10  15  20  25  

    ```


    Son útiles para tareas donde se requiere repetición en múltiples dimensiones, como matrices bidimensionales o para recorrer elementos de una colección anidada.



|| Array
	
	Permite almacenar múltiples valores del mismo tipo bajo un mismo nombre. 

	Los elementos de un array son accesibles a través de un índice, que comienza en cero. 


	1. Definición: 

	```java

	tipo[] nombreArray = new tipo[tamaño];

	```	
	
	Tamaño:

		El número de elementos que puede almacenar el array.


	Ejemplo: 

	```java

	int[] numeros = new int[5];

	```


	2. Inicialización:

		Inicializar array al mismo tiempo que lo declaras.

	```java

	int[] numeros = {1, 2, 3, 4, 5};

	```


	3. Acceso a Elementos: 

		Mediante un índice que comienza con 0. 

	```java

	int primerNumero = numeros[0]; // Accede al primer elemento (índice 0)
	
	int segundoNumero = numeros[1]; // Accede al segundo elemento (índice 1)

	```


	4. Longitud:

		La propiedad length se utiliza para obtener la longitud (número de elementos).

	```java

	int longitud = numeros.length;

	```


	5. Bucles y Arrays:

		for y while, son comúnmente utilizados para recorrer los elementos de un array.

	```java

	int[] numeros = {1, 2, 3, 4, 5};

	for (int i = 0; i < numeros.length; i++) {
	    System.out.println(numeros[i]);
	}

	```		



|| 2D Array
	
	Array o matriz bidimensional, es un array cuyos elementos también son arrays. 

	Es una estructura de datos que organiza datos en filas y columnas como una tabla. 


	Sintaxis: 

	```java

	tipo[][] nombreArray = new tipo[filas][columnas];

	```


	Definición:

	```java

	int[][] matriz = new int[3][4];

	```
	Después agregamos elemenos al objeto 'matriz'. 


	Definición e inicialización: 

	```java

	int[][] matriz = {
	    {1, 2, 3},
	    {4, 5, 6},
	    {7, 8, 9}
	};

	```
	crea una matriz de 3x3 e se inicializa con los valores proporcionados.


	Acceso a elementos: 

		Mediante dos índices, uno para la fila y otro para la columna. 
		
		Los índices comienzan en cero.	

	```java

	int elemento = matriz[1][2]; // Accede al elemento en la segunda fila y tercera columna.

	```


	Recorrer 2D Array: 


	```java

	int[][] matriz = {
    	{1, 2, 3},
    	{4, 5, 6},
    	{7, 8, 9}
	};

	for (int i = 0; i < matriz.length; i++) {
	    for (int j = 0; j < matriz[i].length; j++) {
	        System.out.print(matriz[i][j] + " ");
	    }
	    System.out.println(); // Salto de línea después de cada fila
	}

	```

	Salida: 

	```
	1 2 3 
	4 5 6 	
	7 8 9 
	
	```


	2D Array irregular: 

		No necesariamente tienen que tener el mismo número de elementos en cada fila.


	```java

	int[][] irregular = {
    	{1, 2},
    	{3, 4, 5},
    	{6}
	};

	```		

	La primera fila tiene 2 elementos, la segunda tiene 3, y la tercera tiene 1.	




|| Usos Array


	1. Colección y clasificación de la información: 

		Almacenar un conjunto de datos relacionados, como una lista de nombres, edades, puntajes, etc.
		
		Ejemplo: String[] nombres = {"Alice", "Bob", "Charlie"};


	2. Matrices y Tablas:

    	Para representar matrices o tablas bidimensionales.
    	
    	Ejemplo: int[][] matriz = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};


    3. Operaciones Matemáticas:

    	Cuando estás realizando operaciones matemáticas o estadísticas en un conjunto de valores.
    	
    	Ejemplo: double[] precios = {10.99, 5.49, 8.75};


    4. Iteración:

    	Para simplificar la iteración sobre un conjunto de elementos.

    	```java

    	for (int i = 0; i < array.length; i++) {
		    // Procesar cada elemento del array
		    System.out.println(array[i]);
		}

    	```

    5. Almacenamiento de Datos en Estructuras de Algoritmos:

    	En algoritmos y estructuras de datos, los arrays son fundamentales para implementar estructuras más complejas como listas, colas, pilas, etc.


	6. Entrada y Salida:

	    Al manejar datos de entrada y salida, especialmente cuando se lee o se escribe en archivos o se interactúa con bases de datos.


	7. Imágenes y Matrices Tridimensionales:

	    En el procesamiento de imágenes y gráficos, donde las matrices bidimensionales o tridimensionales son comunes para representar píxeles.


	8. Búsqueda y Ordenación:

	    Cuando necesitas realizar operaciones de búsqueda y ordenación en conjuntos de datos.

	    Ejemplo: Arrays.sort(array);


	9. Representación de Elementos en Juegos:

	    En el desarrollo de juegos, los arrays pueden usarse para representar elementos como personajes, objetos, niveles, etc.


	10. Manipulación de Cadenas:

	    Al trabajar con cadenas de texto, un array de caracteres (char[]) se utiliza para representar y manipular palabras o frases.



|| String

	Representa una secuencia de caracteres. 

	Es una de las clases más utilizadas y es parte del paquete 'java.lang', lo que significa que no es necesario importarla explícitamente en tus programas de Java, ya que se importa automáticamente.

	```java

	String mensaje = "Hola, mundo!";  // Declaración e inicialización en una línea
	String saludo;                      // Declaración
	saludo = "¡Hola, Java!";            // Inicialización posterior

	```


	Operaciones:

		Las cadenas en Java son inmutables, lo que significa que una vez que se crea una cadena, no se puede modificar. 

		Sin embargo, puedes realizar muchas operaciones.


		1. Concatenación:

			```java

			String primerNombre = "John";
			String apellido = "Doe";
			String nombreCompleto = primerNombre + " " + apellido;  // Concatenación

			```

		2. Longitud:

			```java

			String mensaje = "¡Hola, mundo!";
			int longitud = mensaje.length();  // Devuelve la longitud de la cadena

			```

		3. Comparación:

			```java

			String cadena1 = "Java";
			String cadena2 = "java";
			boolean sonIguales = cadena1.equals(cadena2);  // Comparación sensible a mayúsculas y minúsculas

			```


	Métodos más comunes: 

		length(): 

			Devuelve la longitud de la cadena.


		charAt(int index): 

			Devuelve el carácter en la posición especificada.


		concat(String str):

			Concatena la cadena especificada al final de esta cadena.


		equals(Object obj): 

			Compara esta cadena con el objeto dado.


		equalsIgnoreCase(String anotherString): 

			Compara esta cadena con otra cadena, sin distinguir mayúsculas y minúsculas.


		indexOf(String str):

			Devuelve la posición de la primera ocurrencia de la cadena especificada.


		substring(int beginIndex):

			Devuelve una subcadena que comienza con el carácter en la posición especificada.


		toUpperCase(): 

			Convierte toda la cadena a mayúsculas.


		toLowerCase(): 

			Convierte toda la cadena a minúsculas.


		trim(): 

			Elimina los espacios en blanco iniciales y finales de la cadena.


		```java

		String mensaje = "¡Hola, Java!";
		int longitud = mensaje.length();  // Longitud
		char primerCaracter = mensaje.charAt(0);  // Primer carácter
		String subcadena = mensaje.substring(5);  // Subcadena desde la posición 5 en adelante

		System.out.println("Longitud: " + longitud);
		System.out.println("Primer Carácter: " + primerCaracter);
		System.out.println("Subcadena: " + subcadena);

		```



|| Char

	Es un tipo de dato primitivo que se utiliza para representar caracteres Unicode de 16 bits.

	Cada variable de tipo char almacena un solo carácter y se declara usando la palabra clave char. 

	Los caracteres en Java se pueden representar mediante un valor literal entre comillas simples, como 'a', '1', o '$'.

	```java

	char miCaracter = 'A';

	```


	Caracteres Especiales:

		Además de los caracteres alfanuméricos comunes, Java permite el uso de caracteres especiales precedidos por una barra invertida (\).	

		\n: Salto de línea.
    	
    	\t: Tabulación.
    	
    	\': Comilla simple.
    	
    	\": Comilla doble.
    	
    	\\: Barra invertida.


    Operaciones: 

    	1. Comparación: 

    		```java

    		char letra1 = 'a';
			char letra2 = 'b';

			boolean sonIguales = (letra1 == letra2);  // Comparación de caracteres

    		```


    	2. Conversión: 

    		Convertir un 'char' a su valor numérico (código Unicode) y viceversa.

    		```java

    		char miCaracter = 'A';
			int valorNumerico = (int) miCaracter;  // Convierte char a int
			char nuevoCaracter = (char) (valorNumerico + 1);  // Convierte int a char

    		```


    ```java

    char letra = 'Z';
	int codigoUnicode = letra;  // El valor Unicode de 'Z'

	System.out.println("Letra: " + letra);
	System.out.println("Código Unicode: " + codigoUnicode);

    ```
   


|| Wrapper Classes

	
	Wrapper (envolorio): 

		Se refiere a las clases que encapsulan tipos de datos primitivos en objetos. 

		Estos envoltorios proporcionan una interfaz para interactuar con tipos de datos primitivos de manera similar a como se interactúa con objetos.

		Estas clases permiten tratar los tipos de datos primitivos como objetos, ya que a veces es necesario trabajar con objetos en lugar de primitivos, por ejemplo, al utilizar colecciones o al interactuar con bibliotecas que requieren objetos.


	Integer: 

		Envuelve el tipo de dato primitivo 'int'.
	
	Long: 

		Envuelve el tipo de dato primitivo 'long'.
	
	Short: 

		Envuelve el tipo de dato primitivo 'short'.
	
	Byte: 

		Envuelve el tipo de dato primitivo 'byte'.
	
	Float: 

		Envuelve el tipo de dato primitivo 'float'.
	
	Double: 

		Envuelve el tipo de dato primitivo 'double'.
	
	Character: 

		Envuelve el tipo de dato primitivo 'char'.
	
	Boolean: 

		Envuelve el tipo de dato primitivo 'boolean'.	


	1. Creación del objeto: 

		```java

		Integer enteroObjeto = new Integer(42);  // A través del constructor
		Double dobleObjeto = Double.valueOf(3.14);  // A través de un método estático

		```


	2. Conversión entre Primitivos y Wrappers:

		Es especialmente útil al trabajar con colecciones y clases que solo aceptan objetos

		```java

		int numeroPrimitivo = enteroObjeto.intValue();  // Convierte Integer a int

		```


	3. Autoboxing y Unboxing automático:

		Significa que el lenguaje puede convertir automáticamente entre tipos primitivos y sus wrappers según sea necesario.

		```java

		// Autoboxing (int a Integer)
		Integer enteroObjeto = 42;

		// Unboxing (Integer a int)
		int numeroPrimitivo = enteroObjeto;

		```


	Ejemplo: 

		```java

		// Autoboxing
		Integer enteroObjeto = 100;

		// Unboxing
		int numeroPrimitivo = enteroObjeto;

		// Utilizando métodos de la clase wrapper
		double resultado = Math.sqrt(enteroObjeto.doubleValue());

		```

		'enteroObjeto' es un 'Integer' que se crea mediante autoboxing. 

		Luego, se realiza un unboxing para convertirlo de nuevo a un int. 

		Además, se utiliza el método 'doubleValue()' proporcionado por la clase Integer para obtener su valor como un double.


	Los wrappers son útiles cuando necesitas tratar tipos primitivos como objetos, por ejemplo, al trabajar con colecciones, APIs que requieren objetos en lugar de primitivos, o cuando necesitas realizar operaciones más complejas con tipos primitivos. 

	Sin embargo, en la mayoría de los casos, puedes trabajar directamente con tipos primitivos sin necesidad de usar wrappers.



|| ArrayList
	
	Es una clase que implementa la interfaz List y proporciona una implementación dinámica de arrays. 

	Esto significa que puedes almacenar y manipular un conjunto de elementos de manera flexible, y el tamaño del ArrayList puede cambiar dinámicamente durante la ejecución del programa.
	

	Tamaño Dinámico:

	    A diferencia de los arrays estáticos, un ArrayList puede cambiar de tamaño durante la ejecución del programa.

	Elementos Ordenados:

	    Están ordenados según el orden en el que se agregaron.

	Acceso Rápido:

	    Puedes acceder rápidamente a cualquier elemento en un ArrayList utilizando su índice.

	Manipulación Sencilla:

	    Proporciona métodos convenientes para agregar, eliminar, buscar y modificar elementos.


	1. Importamos la clase: 

		Para utilizar ArrayList, primero necesitas importar la clase. 

	```java

	import java.util.ArrayList;

	```


	2. Crear instacia y agregar elementos: 

	```java

	import java.util.ArrayList;

	public class EjemploArrayList {
	    public static void main(String[] args) {
	        // Crear un ArrayList de cadenas
	        ArrayList<String> listaDeNombres = new ArrayList<>();

	        // Agregar elementos
	        listaDeNombres.add("Alice");
	        listaDeNombres.add("Bob");
	        listaDeNombres.add("Charlie");

	        // Acceder a elementos por índice
	        String segundoNombre = listaDeNombres.get(1);
	        System.out.println("Segundo Nombre: " + segundoNombre);

	        // Modificar un elemento
	        listaDeNombres.set(0, "Alicia");

	        // Imprimir todos los elementos
	        System.out.println("Lista de Nombres:");
	        for (String nombre : listaDeNombres) {
	            System.out.println(nombre);
	        }

	        // Obtener el tamaño del ArrayList
	        int tamaño = listaDeNombres.size();
	        System.out.println("Tamaño de la Lista: " + tamaño);

	        // Verificar si la lista contiene un elemento
	        boolean contieneBob = listaDeNombres.contains("Bob");
	        System.out.println("¿Contiene a Bob? " + contieneBob);

	        // Eliminar un elemento por índice
	        listaDeNombres.remove(1);

	        // Imprimir la lista después de la eliminación
	        System.out.println("Lista después de la eliminación:");
	        for (String nombre : listaDeNombres) {
	            System.out.println(nombre);
	        }
	    }
	}

	```


	Métodos para ArrayList: 

		add(E elemento): 

			Agrega un elemento al final de la lista.

		
		get(int índice): 

			Obtiene el elemento en la posición especificada.
		

		set(int índice, E elemento):

			Reemplaza el elemento en la posición especificada con el nuevo elemento.
		

		remove(int índice): 

			Elimina el elemento en la posición especificada.
		

		size(): 

			Devuelve el número de elementos en la lista.
		

		contains(Object objeto):

			Devuelve true si la lista contiene el objeto especificado.
		

		isEmpty():
			
			Devuelve true si la lista está vacía.


	Uso con datos primitivos. 

		Para almacenar tipos de datos primitivos como int, char, etc., necesitas utilizar las clases envoltorio (Integer, Character, etc.) junto con ArrayList.

		```java

		ArrayList<Integer> numeros = new ArrayList<>();
		
		```


	Almacenar Elementos de Diferentes Tipos:

    	Si necesitas almacenar elementos de diferentes tipos, ya que ArrayList puede contener elementos de cualquier tipo (aunque es más comúnmente usado para almacenar elementos de un solo tipo).

    	```java

    	ArrayList<Object> elementosMixtos = new ArrayList<>();
		elementosMixtos.add("Hola");
		elementosMixtos.add(42);

    	```


    Uso con Java Collections: 

    	Si necesitas las funcionalidades de la interfaz 'List' y Java Collections para enar, buscar, iterar y etc. 

    	```java

    	Collections.sort(listaDeNombres);
    	
    	```



|| 2D ArrayList

	Se trata de lograr un array bidimensional (datos en filas y columnas) usando 'ArrayList'. 

	Se conoce como una "lista de listas" y puede ser utilizada para representar una matriz bidimensional o una tabla.

	```java

	import java.util.ArrayList;

	public class Ejemplo2DArrayList {
	    public static void main(String[] args) {
	        // Declaración de un ArrayList bidimensional de enteros
	        ArrayList<ArrayList<Integer>> matrizBidimensional = new ArrayList<>();

	        // Inicialización de la matriz bidimensional
	        for (int i = 0; i < 3; i++) {
	            matrizBidimensional.add(new ArrayList<>());
	        }

	        // Agregar elementos a la matriz bidimensional
	        matrizBidimensional.get(0).add(1);
	        matrizBidimensional.get(0).add(2);
	        matrizBidimensional.get(0).add(3);

	        matrizBidimensional.get(1).add(4);
	        matrizBidimensional.get(1).add(5);
	        matrizBidimensional.get(1).add(6);

	        matrizBidimensional.get(2).add(7);
	        matrizBidimensional.get(2).add(8);
	        matrizBidimensional.get(2).add(9);

	        // Imprimir la matriz bidimensional
	        for (ArrayList<Integer> fila : matrizBidimensional) {
	            for (int elemento : fila) {
	                System.out.print(elemento + " ");
	            }
	            System.out.println();
	        }
	    }
	}

	```


	Acceder a los elementos: 

		Utilizando índices dobles. 


		```java

		int elemento = matrizBidimensional.get(1).get(2);
		System.out.println("Elemento en la fila 1, columna 2: " + elemento);
		
		```


	Ventajas: 

		Tamaño Dinámico:

	        Puedes cambiar dinámicamente el tamaño de cada fila y columna según sea necesario.


	    Facilidad de Manipulación:
	        
	        Facilita la manipulación de datos bidimensionales sin preocuparte por los tamaños fijos.


	    Tipos de Datos Flexibles:
	        
	        Puedes usar diferentes tipos de datos en cada fila si es necesario.


	Desventajas: 

		Consumo de Memoria:

    		Puede consumir más memoria que una matriz bidimensional estática si las listas internas tienen tamaños variables.


		Acceso Menos Eficiente:

			El acceso a elementos puede ser menos eficiente que en una matriz bidimensional tradicional



|| For each
	
	Conocido como bucle mejorado, es una forma simplificada de iterar sobre elementos en una colección o en un array.

	Es útil cuando necesitas recorrer todos los elementos de una colección sin preocuparte por los índices o la longitud.

	```java

	for (Tipo elemento : colección) {
	    // Cuerpo del bucle
	}

	```

	Tipo:  

		es el tipo de datos de los elementos en la colección.

    elemento: 

    	es la variable que toma el valor de cada elemento en cada iteración.

    colección: 

    	es la colección o array sobre la cual estás iterando.


    Ejemplo: 

    	```java

    	int[] numeros = {1, 2, 3, 4, 5};

		for (int numero : numeros) {
		    System.out.println(numero);
		}

    	```

    	"for-each" itera sobre el array 'numeros', asignando cada elemento a la variable 'numero' y luego imprimiendo ese número.



    Ejemplo con ArrayList: 

    ```java

    import java.util.ArrayList;

	public class EjemploForEach {
	    public static void main(String[] args) {
	        ArrayList<String> nombres = new ArrayList<>();
	        nombres.add("Alice");
	        nombres.add("Bob");
	        nombres.add("Charlie");

	        for (String nombre : nombres) {
	            System.out.println(nombre);
	        }
	    }
	}

    ```

    itera sobre la colección nombres, asignando cada elemento a la variable nombre y luego imprimiendo ese nombre.


    Uso con Colecciones:

    	Puede ser utilizado con cualquier objeto iterable, como arrays, listas, conjuntos, mapas, etc.


    Limitaciones: 

        No se puede modificar la colección durante la iteración. 

        Intentar hacerlo lanzará una excepción 'ConcurrentModificationException'.

       	```java

       	// Esto lanzará ConcurrentModificationException
		for (String nombre : nombres) {
		    if (nombre.equals("Bob")) {
		        nombres.remove(nombre);
		    }
		}

       	```


    Es útil en situaciones donde solo necesitas acceder a los elementos y no necesitas realizar operaciones que modifiquen la estructura de la colección.




|| Métodos
	
	Los métodos pertenecen a una clase y deben ser invocados a través de una instancia de la clase o, en el caso de métodos estáticos, directamente desde la clase. 

	Llamar o invocar a una clase en sí misma (como si fuera un método) no tiene sentido en el contexto de Java y resultará en un error de compilación.	


	```java

	public class MiClase {
	    public void miMetodo() {
	        System.out.println("¡Hola desde miMetodo!");
	    }

	    public static void main(String[] args) {
	        // Creación de una instancia de la clase
	        MiClase instancia = new MiClase();

	        // Llamada al método desde la instancia
	        instancia.miMetodo();

	        // Intento incorrecto de llamar a la clase (lo siguiente causará un error de compilación)
	        // MiClase.miClase();  // Esto no es válido en Java
	    }
	}

	```

	'miMetodo' es un método de instancia, lo que significa que debe ser llamado a través de una instancia de la clase 'MiClase'. 

	En el método 'main', se crea una instancia de la clase y se llama al método 'miMetodo' en esa instancia.


	El intento de llamar directamente a la clase (MiClase.miClase()) resultará en un error de compilación porque 'miClase' no es un método definido en la clase.

	La llamada a un método estático debería ser algo como 'MiClase.metodoEstatico()'.

	Si estás intentando acceder a un método estático, asegúrate de usar el nombre correcto del método y de tener la sintaxis adecuada para llamar a un método estático. 

	La forma correcta sería 'MiClase.metodoEstatico()'.	


|| Método de instancia: 

	Cuando creas una clase en Java y luego creas objetos (instancias) de esa clase, puedes llamar a los métodos definidos en esa clase desde esas instancias. 

	Estos métodos pueden acceder a los datos específicos de esa instancia (también conocidos como campos o variables de instancia) utilizando la palabra clave 'this' que hace referencia al objeto o instancia actual de la clase.


	Usos: 

		1. No pueden acceder directamente a variables estáticas: 

			A diferencia de los métodos estáticos, los métodos de instancia no pueden acceder directamente a variables estáticas (variables de clase). 

			Sin embargo, pueden acceder a ellas a través del nombre de la clase.


		2. Pueden ser sobrescritos:

			Los métodos de instancia pueden ser sobrescritos en las subclases si están marcados como 'public' o 'protected' en la clase base.

			Esto permite que las subclases proporcionen una implementación específica para ese método.


	Ejemplo: 

	```java

	public class Persona {
	    private String nombre;
	    private int edad;

	    // Constructor
	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Método de instancia para imprimir información de la persona
	    public void imprimirInformacion() {
	        System.out.println("Nombre: " + this.nombre);
	        System.out.println("Edad: " + this.edad);
	    }

	    // Método de instancia para incrementar la edad
	    public void cumplirAnios() {
	        this.edad++;
	    }

	    public static void main(String[] args) {
	        // Crear una instancia de Persona
	        Persona persona1 = new Persona("Juan", 30);

	        // Llamar a métodos de instancia desde la instancia persona1
	        persona1.imprimirInformacion(); // Imprime Nombre: Juan, Edad: 30
	        persona1.cumplirAnios();
	        persona1.imprimirInformacion(); // Imprime Nombre: Juan, Edad: 31
	    }
	}

	```

 	'imprimirInformacion()' y 'cumplirAnios()'' son métodos de instancia de la clase 'Persona'.

 	Pueden ser llamados directamente desde una instancia específica de Persona, como 'persona1'. 

 	Estos métodos acceden a los campos 'nombre' y 'edad' utilizando la palabra clave 'this', que hace referencia a la instancia actual de la clase Persona.

 	Los métodos de instancia pueden acceder y modificar los datos de esas instancias.



|| Método estático: 

	Es un método asociado a la clase en lugar de a instancias específicas de esa clase. 

	Esto significa que puedes llamar a un método estático directamente desde la clase, sin necesidad de crear un objeto de esa clase primero


	Usos: 

		1. Se usan para operaciones que no dependen del estado del objeto: 

			Los métodos estáticos son útiles para operaciones que no dependen del estado de una instancia específica de la clase.

			Por ejemplo, métodos utilitarios, métodos de fábrica, métodos de inicialización estática, etc.


		2. No pueden ser sobrescritos: 

			A diferencia de los métodos de instancia, los métodos estáticos no pueden ser sobrescritos en las subclases. 

			Sin embargo, pueden ser ocultos si se define un método con el mismo nombre en una subclase.


	Ejemplo: 

		Se utiliza el nombre de la clase, seguido por un punto y el nombre del método estático. 

	```java

	public class EjemploMetodoEstatico {
	    private static int contador = 0;

	    public static void main(String[] args) {
	        // Llamada a un método estático sin instancia
	        int resultado = suma(5, 3);
	        System.out.println("Resultado de la suma: " + resultado);

	        // Acceso a una variable estática
	        System.out.println("Contador: " + contador);
	    }

	    // Definición de un método estático
	    public static int suma(int a, int b) {
	        return a + b;
	    }
	}

	```

	'suma' es estático, lo que significa que se puede llamar directamente desde la clase 'EjemploMetodoEstatico' sin necesidad de crear un objeto de esa clase. 

	Además, la variable 'contador' es estática, lo que significa que es compartida entre todas las instancias de la clase y también se puede acceder directamente desde la clase.



|| This

	Instancia actual de una clase. 

	Se utiliza principalmente en dos contextos:

	1. Referencia a variables de instancia: 

		'this' se utiliza dentro de un método o constructor para hacer referencia a las variables de instancia de la clase actual. 

		Esto es útil cuando el nombre de un parámetro o variable local en un método coincide con el nombre de una variable de instancia.

	```java

	public class Persona {
	    private String nombre;

	    // Constructor
	    public Persona(String nombre) {
	        // Usando 'this' para distinguir entre el parámetro 'nombre' y la variable de instancia 'nombre'
	        this.nombre = nombre;
	    }

	    // Método para imprimir el nombre de la persona
	    public void imprimirNombre() {
	        // Usando 'this' para hacer referencia a la variable de instancia 'nombre'
	        System.out.println("Nombre: " + this.nombre);
	    }

	    public static void main(String[] args) {
	        // Crear una instancia de Persona y llamar al método imprimirNombre
	        Persona persona = new Persona("Juan");
	        persona.imprimirNombre(); // Imprime "Nombre: Juan"
	    }
	}

	```

	'this.nombre' hace referencia a la variable de instancia 'nombre' de la clase 'Persona', mientras que 'nombre' en el constructor hace referencia al parámetro del mismo nombre


	2. Llamada a constructores: 

		'this' se puede utilizar para llamar a otro constructor de la misma clase dentro de un constructor. 

		Esta llamada a constructor se realiza en la primera línea del constructor y solo puede ser la primera instrucción en el constructor.

	```java

	public class Empleado {
	    private String nombre;
	    private int edad;

	    // Constructor que llama a otro constructor de la misma clase
	    public Empleado(String nombre) {
	        this(nombre, 0); // Llamar al otro constructor de la clase
	    }

	    // Constructor principal
	    public Empleado(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Método para imprimir información del empleado
	    public void imprimirInformacion() {
	        System.out.println("Nombre: " + this.nombre);
	        System.out.println("Edad: " + this.edad);
	    }

	    public static void main(String[] args) {
	        // Crear una instancia de Empleado y llamar al método imprimirInformacion
	        Empleado empleado = new Empleado("Ana");
	        empleado.imprimirInformacion();
	    }
	}

	```

	El constructor 'Empleado(String nombre)' llama al otro constructor de la misma clase utilizando 'this(nombre, 0)'.

	Esto permite la reutilización de código y evita la duplicación de inicialización de variables.



|| Métodos sobrecargados




|| Printf




|| Final



|| Objetos 



|| Constructor 




|| Ámbito de variable





|| toString




|| Array de Objetos



||

