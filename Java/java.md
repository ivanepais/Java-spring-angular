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




|| Void




|| Swap variables




