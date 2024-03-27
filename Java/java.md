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


	3. Referencia a los Atributos del Objeto Actual en Métodos:

	```java

	public class Circulo {
	    private double radio;

	    public void setRadio(double radio) {
	        if (radio > 0) {
	            this.radio = radio;
	        } else {
	            System.out.println("Radio inválido");
	        }
	    }
	}

	```

	'this.radio' se refiere al atributo 'radio' del objeto actual en el método 'setRadio'.


	4. Retorno del Objeto Actual desde Métodos.

		Llama al metodo después de la creación de objetos (instancias).


	```java

	public class Empleado {
	    private String nombre;

	    public Empleado withNombre(String nombre) {
	        this.nombre = nombre;
	        return this;
	    }
	}

	```


	5. This a través de un método estático: 

		Referencia a la clase actual en métodos estático.

	```java

	public class MiClase {
	    private static int contador = 0;

	    public static int obtenerContador() {
	        return contador;
	    }

	    public void incrementarContador() {
	        contador++;
	    }
	}

	```


	this se utiliza para referenciar al objeto actual (instancia creada) en el que se está trabajando y se emplea en situaciones donde es necesario distinguir entre los atributos de la clase y los parámetros del método, así como en la llamada a otros constructores de la misma clase.



|| Métodos sobrecargados

	Es la capacidad de definir varios métodos en la misma clase con el mismo nombre pero con diferentes listas de parámetros. 

	La sobrecarga de métodos permite a una clase tener múltiples versiones de un método con la misma firma (nombre del método), pero con diferentes tipos o cantidades de parámetros. 

	Características: 

	1. Mismo Nombre:
        
        Los métodos sobrecargados tienen el mismo nombre.

    2. Diferentes Parámetros:

        Deben tener listas de parámetros diferentes, lo que puede incluir un número diferente de parámetros, tipos de parámetros diferentes o ambos.

    3. Diferentes Tipos de Retorno:
      
        El tipo de retorno no es considerado al determinar si dos métodos son sobrecargados.


    ```java

    public class Calculadora {
	    // Método para sumar dos enteros
	    public int sumar(int a, int b) {
	        return a + b;
	    }

	    // Método sobrecargado para sumar tres enteros
	    public int sumar(int a, int b, int c) {
	        return a + b + c;
	    }

	    // Método sobrecargado para sumar dos números de punto flotante
	    public double sumar(double a, double b) {
	        return a + b;
	    }

	    public static void main(String[] args) {
	        Calculadora calculadora = new Calculadora();

	        // Llamadas a los métodos sobrecargados
	        int resultado1 = calculadora.sumar(3, 4);
	        int resultado2 = calculadora.sumar(1, 2, 3);
	        double resultado3 = calculadora.sumar(2.5, 3.5);

	        System.out.println("Resultado 1: " + resultado1);
	        System.out.println("Resultado 2: " + resultado2);
	        System.out.println("Resultado 3: " + resultado3);
	    }
	}


    ```


    Reglas para los métodos sobrecargados: 

   	1. Número Diferente de Parámetros:

        Puedes sobrecargar un método cambiando el número de parámetros.

    2. Tipos Diferentes de Parámetros:
        
        Puedes sobrecargar un método cambiando los tipos de parámetros.

    3. Orden de los Parámetros no es Suficiente:

        Cambiar el orden de los parámetros sin cambiar su tipo no es suficiente para considerar que un método está sobrecargado.


    ```java

    // Esto no es una sobrecarga
	public void metodo(int a, double b) {}

	// Esto tampoco es una sobrecarga
	public void metodo(double a, int b) {}

    ```

	

|| Printf
	
	Es un método de la clase PrintStream (también utilizado en la clase System.out) que permite formatear y mostrar texto en la consola. 

	Este método sigue el estilo de formato del lenguaje de programación C.

	```java
	
	System.out.printf(formato, argumento1, argumento2, ...);

	```

	formato: 

		Una cadena que especifica el formato de salida.

    argumento1, argumento2, ...: 

    	Los valores que se insertarán en el formato.

	```java

	public class EjemploPrintf {
	    public static void main(String[] args) {
	        String nombre = "Juan";
	        int edad = 25;
	        double salario = 50000.75;

	        // Formateo de texto con printf
	        System.out.printf("Hola, %s. Tienes %d años y tu salario es %.2f\n", nombre, edad, salario);
	    }
	}

	```    

	'%s', '%d', y '%.2f' son especificadores de formato que se corresponden con el tipo de dato de los argumentos (String, int, y double, respectivamente). 

	Al usar '%s', se espera que el argumento sea una cadena. 

	'%d' espera un entero, y '%.2f' espera un número de punto flotante con dos decimales.


	Especificaciones de formato: 

	    %s: Formatea una cadena de caracteres.

	    %d: Formatea un número entero.

	    %f: Formatea un número de punto flotante.

	    %.2f: Formatea un número de punto flotante con dos decimales.

	    %c: Formatea un carácter.

	    %b: Formatea un valor booleano


	Escape de Caracteres: 

		caracteres de escape especiales:

    	\n: Nueva línea.
    	
    	\t: Tabulación.
    	
    	\\: Barra invertida.


    	```java

    	System.out.printf("Primera línea\nSegunda línea\n");
		System.out.printf("Nombre\tEdad\tSalario\n");
		System.out.printf("C:\\Directorio\\Archivo.txt");

    	```



|| Final

	Indica que una entidad, como una variable, método o clase, no puede ser modificada después de su declaración o definición. 

	Su significado y aplicación pueden variar dependiendo del contexto en el que se utiliza.


	1. Variables: 

		Cuando se aplica a una variable, 'final' indica que una vez que se le asigna un valor, ese valor no puede ser cambiado. 

		La variable debe ser inicializada y solo se le puede asignar un valor una vez.

		```java

		final int edad = 30;
		// Intentar reasignar causará un error de compilación
		// edad = 31;

		```


	2. Métodos: 

		Cuando se aplica a un método, 'final' indica que el método no puede ser sobrescrito por las subclases.	
		
		```java

		class ClasePadre {
		    // Método final que no puede ser sobrescrito
		    final void metodoFinal() {
		        // Código del método
		    }
		}

		class ClaseHija extends ClasePadre {
		    // Intentar sobrescribir causará un error de compilación
		    // @Override
		    // void metodoFinal() { /* ... */ }
		}

		```	


	3. Clase: 

		'final' indica que la clase no puede ser extendida, es decir, no puede tener subclases.

		```java

		final class ClaseFinal {
		    // Código de la clase
		}

		// Intentar extender una clase final causará un error de compilación
		// class ClaseHija extends ClaseFinal { /* ... */ }

		```


	Características: 

	Inmutabilidad:

	    En el caso de variables, final se utiliza para crear variables inmutables, lo que significa que su valor no puede cambiar después de la inicialización.


	Evitar Cambios Accidentales:

	    Al marcar un método como final, se evita que las clases hijas lo sobrescriban, lo que puede ser útil cuando queremos asegurarnos de que un método en una clase base no sea modificado por clases derivadas.


	Seguridad y Optimización:

	    final puede ayudar al compilador y al intérprete de Java a realizar optimizaciones y puede mejorar la seguridad del código al prevenir ciertos tipos de modificaciones no deseadas.


	Claridad en el Código:

	    Al utilizar final, puedes expresar tu intención de que una variable, método o clase no debe cambiar, lo que mejora la claridad y la comprensión del código.


	Si bien final proporciona inmutabilidad para variables, métodos y clases, no significa que los objetos a los que apuntan las variables final sean inmutables. 

	Puedes tener una variable final que apunte a un objeto mutable, pero la variable en sí no puede ser reasignada.



|| Objetos 

	Se refiere a instancias de clases. 

	Java es un lenguaje de programación orientado a objetos, lo que significa que todo en Java es un objeto (excepto los tipos primitivos). 

	Un objeto es una instancia única de una clase que tiene atributos y métodos asociados.


	1. Clases y objetos: 

		Clases: 

			Es una plantilla para crear objetos. 

			Define la estructura y el comportamiento que compartirán los objetos de esa clase. 

			Se definen con la palabra clave 'class'. 

		```java

		public class Persona {
		    // Atributos
		    String nombre;
		    int edad;

		    // Métodos
		    void saludar() {
		        System.out.println("Hola, soy " + nombre + " y tengo " + edad + " años.");
		    }
		}

		```


		Objetos: 

			Es una instancia particular de una clase.

			Se crea a partir de la plantilla proporcionada por la clase y tiene su propia existencia en la memoria.


		```java

		// Creación de un objeto de la clase Persona
		Persona persona1 = new Persona();
		persona1.nombre = "Juan";
		persona1.edad = 30;

		// Llamada al método de la clase
		persona1.saludar();

		```


	2. Características de los Objetos:

    	Atributos: 

    		Representan las propiedades o características del objeto. 

    		En el ejemplo anterior, 'nombre' y 'edad' son atributos de la clase Persona.


    	Métodos: 

    		Representan el comportamiento del objeto. 

    		El método 'saludar()' es un método de la clase Persona.


   	3. Instanciación de Objetos:

    	La palabra clave 'new' se utiliza para crear una instancia (un objeto) de una clase. 

    	La memoria se asigna para el objeto, y el constructor de la clase se llama para inicializar el objeto.

    	```java

    	Persona persona1 = new Persona();

    	```


	4. Referencias a Objetos:

    	Las variables que almacenan objetos no almacenan realmente el objeto en sí, sino una referencia al objeto en la memoria.    

    	```java

    	Persona persona1 = new Persona();
		Persona persona2 = persona1; // Ambas variables apuntan al mismo objeto

    	```


    5. Encapsulamiento: 


    	Las clases pueden utilizar el concepto de encapsulamiento para ocultar ciertos detalles internos y exponer solo lo necesario a través de métodos públicos.

    	```java

    	public class CuentaBancaria {
		    private double saldo; // Atributo privado

		    public void depositar(double cantidad) {
		        // Lógica para depositar
		        saldo += cantidad;
		    }

		    public double obtenerSaldo() {
		        return saldo;
		    }
		}

    	```


    6. Herencia y Polimorfismo:

    	Herencia. 

    		Una clase puede heredar atributos y métodos de otra clase.

    	```java

    	// Herencia
		public class Empleado extends Persona {
		    // Nuevos atributos y métodos específicos para Empleado
		}

    	``` 


    	Polimorfismo: 

    		Un objeto puede ser tratado como un objeto de su clase base.

    		Es la capacidad de un objeto de tomar muchas formas.

    	```java

    	// Clase base
		class Animal {
		    void hacerSonido() {
		        System.out.println("Haciendo un sonido genérico");
		    }
		}

		// Clases derivadas
		class Perro extends Animal {
		    @Override
		    void hacerSonido() {
		        System.out.println("El perro ladra");
		    }
		}

		class Gato extends Animal {
		    @Override
		    void hacerSonido() {
		        System.out.println("El gato maulla");
		    }
		}

		public class EjemploPolimorfismo {
		    public static void main(String[] args) {
		        // Creación de objetos
		        Animal miAnimal1 = new Perro();
		        Animal miAnimal2 = new Gato();

		        // Llamadas a los métodos
		        miAnimal1.hacerSonido();  // Salida esperada: El perro ladra
		        miAnimal2.hacerSonido();  // Salida esperada: El gato maulla
		    }
		}

    	```

    	'Animal' es la clase base que tiene un método llamado 'hacerSonido'. 

    	Luego, hay dos clases derivadas, 'Perro' y 'Gato', que sobrescriben el método 'hacerSonido' para proporcionar implementaciones específicas para cada tipo de animal.

		En el método 'main', creamos dos objetos de tipo 'Animal', pero asignamos instancias de las clases derivadas 'Perro' y 'Gato' a esas variables. 

		Esto se llama "polimorfismo de ejecución". 

		Cuando llamamos al método 'hacerSonido' en estos objetos, se ejecuta la versión específica del método según el tipo real del objeto en tiempo de ejecución.


    7. Recolector de Basura: 

    	Java cuenta con un recolector de basura (Garbage Collector) que se encarga de liberar la memoria utilizada por los objetos que ya no son referenciados.


   	8. Equals y HashCode:

    	Los métodos 'equals()' y 'hashCode()' se utilizan para comparar la igualdad de objetos y son parte de la implementación de la clase Object, la clase base para todas las clases en Java.



|| Constructor 

	Es un método especial utilizado para inicializar objetos de una clase. 

	Su nombre debe ser idéntico al nombre de la clase y no tiene tipo de retorno, ni siquiera void. 

	Los constructores se llaman automáticamente cuando se crea una instancia (objeto) de la clase.


	1. Sintaxis: 

		```java

		public class MiClase {
		    // Constructor por defecto (sin parámetros)
		    public MiClase() {
		        // Código de inicialización
		    }

		    // Constructor con parámetros
		    public MiClase(int parametro1, String parametro2) {
		        // Código de inicialización con parámetros
		    }
		}


		```


	2. Constructor por Defecto:

    	Si no defines ningún constructor en tu clase, Java proporciona un constructor por defecto automáticamente.

    	Este constructor no toma ningún parámetro y simplemente inicializa los valores predeterminados.


	3. Constructor con Parámetros:

    	Puedes definir constructores que acepten parámetros para inicializar los atributos de la clase según los valores proporcionados durante la creación del objeto.


	4. Llamada al Constructor de la Clase Base:

    	En una jerarquía de clases, el constructor de una clase puede llamar al constructor de su clase base usando 'super()'.

    	```java

    	public class ClaseBase {
		    public ClaseBase(int valor) {
		        // Código de inicialización para la clase base
		    }
		}

		public class ClaseDerivada extends ClaseBase {
		    public ClaseDerivada(int valor) {
		        super(valor); // Llamada al constructor de la clase base
		        // Código de inicialización para la clase derivada
		    }
		}

    	```


    5. Uso de Constructores:

	    Los constructores se utilizan para asignar valores iniciales a los atributos de un objeto y realizar otras operaciones de inicialización necesarias. 

	    Son esenciales para garantizar que un objeto sea válido y coherente en su estado inicial.


	6. Sobrecarga de Constructores:

	    Puedes tener múltiples constructores en una clase mediante la técnica de sobrecarga de métodos, donde cada constructor tiene una lista de parámetros diferente.

	    ```java

	    public class Persona {
		    private String nombre;
		    private int edad;

		    // Constructor por defecto
		    public Persona() {
		        // Inicialización predeterminada
		    }

		    // Constructor con parámetros
		    public Persona(String nombre, int edad) {
		        this.nombre = nombre;
		        this.edad = edad;
		    }
		}

	    ```


	7. Construcción de objetos. 

		Se usa el operador 'new' seguido por la llamada al constructor de la clase.

		```java

		Persona persona1 = new Persona(); // Constructor por defecto
		Persona persona2 = new Persona("Juan", 25); // Constructor con parámetros

		```


	Ejemplos de uso: 

	1. Inicializar de Atributos: 

		Asignar valores iniciales a los atributos de un objeto.

		Esto garantiza que el objeto tenga un estado coherente desde el principio.

	```java

	public class Persona {
	    String nombre;
	    int edad;

	    // Constructor con parámetros para inicializar atributos
	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }
	}

	// Uso del constructor
	Persona persona = new Persona("Juan", 25);

	```


	2. Asignación de Valores Predeterminados: 

		Un constructor puede establecer valores predeterminados para los atributos si no se proporcionan al crear el objeto.


	```java

	public class Coche {
	    String modelo;
	    int año;

	    // Constructor con valores predeterminados
	    public Coche() {
	        this.modelo = "Desconocido";
	        this.año = 0;
	    }
	}

	// Uso del constructor
	Coche miCoche = new Coche(); // Se asignan valores predeterminados

	```


	3. Acciones adicionales:	

		Los constructores también se utilizan para realizar operaciones de inicialización adicionales necesarias para que el objeto esté en un estado válido.

	```java

	public class ConectorBD {
	    // Constructor que abre la conexión a la base de datos
	    public ConectorBD() {
	        // Código para abrir la conexión
	    }
	}

	// Uso del constructor
	ConectorBD bd = new ConectorBD(); // Se abre la conexión automáticamente

	```


	4. Herencia:	 

		Los constructores se utilizan para inicializar tanto la parte de la clase base como la de las clases derivadas.	

	```java

	public class Vehiculo {
	    int velocidad;

	    public Vehiculo(int velocidad) {
	        this.velocidad = velocidad;
	    }
	}

	public class Coche extends Vehiculo {
	    String modelo;

	    public Coche(int velocidad, String modelo) {
	        super(velocidad); // Llamada al constructor de la clase base
	        this.modelo = modelo;
	    }
	}

	```	


	5. Sobrecarga de Constructores:

   		Puedes tener múltiples constructores en una clase mediante la sobrecarga, lo que significa tener diferentes versiones del constructor con diferentes parámetros.

	```java

	public class Libro {
	    String titulo;
	    String autor;

	    // Constructor por defecto
	    public Libro() {
	        // Código de inicialización por defecto
	    }

	    // Constructor con parámetros
	    public Libro(String titulo, String autor) {
	        this.titulo = titulo;
	        this.autor = autor;
	    }
	}

	```


	6. This, llamada al constructor (sobrecargado o por defecto):

		Asigna valores. 

	```java

	public class Persona {
	    private String nombre;
	    private int edad;

	    // Constructor principal
	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Constructor por defecto que llama al constructor principal
	    public Persona() {
	        this("Desconocido", 0);
	    }
	}

	```



|| Ámbito de variable

	Se refiere a la región del programa donde la variable es válida y accesible. 

	Determina en qué partes del código una variable puede ser utilizada y cuándo se destruye.


	Se puede clasificar en tres categorías principales:

	1. Alcance de Bloque (Block Scope):

	    Una variable declarada dentro de un bloque de código delimitado por llaves {} tiene un alcance de bloque.

	    La variable es válida solo dentro de ese bloque y no es accesible fuera de él.


	    ```java

	    public class AlcanceDeBloque {
		    public static void main(String[] args) {
		        // Alcance de bloque
		        int x = 10;
		        {
		            int y = 20;
		            System.out.println(x); // Válido: x está en el alcance
		            System.out.println(y); // Válido: y está en el alcance
		        }
		        System.out.println(x); // Válido: x sigue en el alcance
		        // System.out.println(y); // Inválido: y está fuera de alcance
		    }
		}

	    ```


	2. Alcance de Método (Method Scope):

    	Una variable declarada dentro de un método tiene un alcance de método.

    	Es válida solo dentro del cuerpo del método y no es accesible fuera de ese método

    	```java

    	public class AlcanceDeMetodo {
		    public static void main(String[] args) {
		        // Alcance de método
		        int x = 10;
		        System.out.println(x); // Válido: x está en el alcance
		        muestraMensaje();
		        // System.out.println(y); // Inválido: y está fuera de alcance
		    }

		    static void muestraMensaje() {
		        int y = 20;
		        System.out.println(y); // Válido: y está en el alcance del método
		    }
		}

    	```


	3. Alcance de Clase (Class Scope):

   		Las variables de instancia (miembros de la clase) tienen un alcance de clase.

    	Son accesibles en cualquier parte de la clase.

    	```java

    	public class AlcanceDeClase {
		    // Alcance de clase
		    int x = 10;

		    public static void main(String[] args) {
		        AlcanceDeClase objeto = new AlcanceDeClase();
		        System.out.println(objeto.x); // Válido: x es un miembro de la clase
		    }
		}

    	```

    El alcance de una variable también se aplica a los parámetros de un método. 

    Además, cuando se declara una variable local con el mismo nombre que una variable de instancia en una clase, el alcance de la variable local tiene prioridad dentro de ese bloque de código.

    Manejar adecuadamente el alcance de las variables es esencial para evitar errores y escribir código más limpio y mantenible.


    Buenas prácticas:  


		Mantén el Alcance Tan Reducido Como Sea Posible:

		    Limita el alcance de las variables tanto como sea posible. 

		    Esto mejora la legibilidad y mantenibilidad del código, ya que reduce la cantidad de variables que deben ser rastreadas en diferentes partes del programa.


		Evita el Alcance Excesivo de las Variables de Clase:

		    Evita declarar variables de instancia como públicas o protegidas a menos que sea necesario.

		    Opta por encapsular las variables y proporcionar métodos de acceso (getters y setters) según sea necesario.


		Preferir Variables Locales:

		    Dale preferencia a las variables locales sobre las variables de instancia siempre que sea posible. 

		    Las variables locales son más eficientes y están más cerca de donde se utilizan.


		Evita Variables Globales Innecesarias:

		    Minimiza el uso de variables globales. 

		    Las variables globales pueden hacer que el código sea más difícil de entender y depurar. 

		    Se prefieren las variables locales o parámetros de método siempre que sean suficientes para el propósito.


		Utiliza Variables Finales (final) Cuando Sea Apropiado:

		    Marca las variables que no deben cambiar de valor como final. 

		    Esto ayuda a prevenir errores y proporciona información adicional a los lectores del código sobre la intención del programador 

		    ```java

		    final int CONSTANTE = 42;

		    ```


		Evitar Nombres de Variables Redundantes:

		    Utiliza nombres de variables descriptivos pero evita redundancias.

		    Por ejemplo, si tienes un método que recibe un parámetro llamado numero, no es necesario nombrar la variable local como numeroLocal.


		Evitar Nombres de Variables Muy Cortos o Crípticos:

		    Aunque es importante mantener los nombres de variables concisos, evita nombres que sean demasiado cortos o crípticos. 

		    Utiliza nombres que indiquen claramente el propósito o contenido de la variable.


		Manejar Excepciones de Alcance:

		    Maneja adecuadamente las excepciones de alcance, como la sombra de variables (shadowing), que ocurre cuando una variable local tiene el mismo nombre que una variable de instancia. 

		    Si es necesario, utiliza this para hacer referencia explícita a la variable de instancia.

		    ```java

		    public class EjemploShadows {
			    private int x = 5;

			    public void muestraEjemplo(int x) {
			        this.x = x; // Usando 'this' para referirse a la variable de instancia
			    }
			}

		    ```



|| Variables de instancia: 

	Son variables que se declaran dentro de una clase pero fuera de cualquier método, constructor o bloque. 

	Pertenecen a la instancia de la clase y tienen un alcance que está vinculado a la instancia específica del objeto. 

	Tiene un alcance que se extiende a lo largo de toda la clase.

	Puede ser accedida y modificada por cualquier método de la misma clase utilizando la referencia a la instancia del objeto.

	Cada instancia (objeto) de la clase tiene su propia copia de las variables de instancia, y los valores de estas variables pueden variar de una instancia a otra.

	Existe durante toda la vida de la instancia del objeto a la que está asociada. 

	Se crea cuando se instancia el objeto y se destruye cuando el objeto es elegible para la recolección de basura.

	Para declarar una variable de instancia, se utiliza el modificador de acceso seguido del tipo de datos y el nombre de la variable.

	```java

	public class EjemploVariablesDeInstancia {
	    // Variable de instancia
	    private int numero;

	    // Otro ejemplo de variable de instancia
	    private String nombre;

	    // Constructor que inicializa las variables de instancia
	    public EjemploVariablesDeInstancia(int numero, String nombre) {
	        this.numero = numero;
	        this.nombre = nombre;
	    }

	    // Método que accede a las variables de instancia
	    public void mostrarInformacion() {
	        System.out.println("Número: " + numero);
	        System.out.println("Nombre: " + nombre);
	    }

	    public static void main(String[] args) {
	        // Crear instancias de la clase y acceder a las variables de instancia
	        EjemploVariablesDeInstancia objeto1 = new EjemploVariablesDeInstancia(42, "Objeto 1");
	        EjemploVariablesDeInstancia objeto2 = new EjemploVariablesDeInstancia(99, "Objeto 2");

	        // Mostrar información de cada objeto
	        objeto1.mostrarInformacion();
	        objeto2.mostrarInformacion();
	    }
	}

	```



|| Variables locales y de instancia

		
	Alcance (Scope):
        
        Variable Local: 

        	Tiene un alcance limitado a la parte del código en la que se declara (un método, un bloque, etc.). No es accesible fuera de ese ámbito.


        Variable de Instancia: 

        	Tiene un alcance que se extiende a lo largo de toda la clase. 

        	Puede ser accedida y modificada por cualquier método de la misma clase y está vinculada a una instancia específica del objeto.


    Duración:

        Variable Local: 

        	Existe solo durante la ejecución del bloque de código en el que se declara. 

        	Cuando el bloque de código termina, la variable local se destruye y su espacio en memoria se libera.


        Variable de Instancia: 

        	Existe durante toda la vida de la instancia del objeto a la que está asociada. 

        	Se crea cuando se instancia el objeto y se destruye cuando el objeto es elegible para la recolección de basura.


    Asociación con la Instancia:

        Variable Local: 

        	No está vinculada a ninguna instancia específica de la clase.

        	Su existencia y valor son locales al método o bloque en el que se declara.


        Variable de Instancia: 

        	Está asociada a una instancia específica de la clase. 

        	Cada instancia del objeto tiene su propia copia de las variables de instancia.


    Acceso y Modificación:
        
        Variable Local: 

        	Solo es accesible y modificable dentro del método o bloque en el que se declara.


        Variable de Instancia: 	

        	Puede ser accedida y modificada por cualquier método de la misma clase utilizando la referencia a la instancia del objeto.


    Encapsulamiento:

    	Las variables locales están más alineadas con el principio de encapsulamiento.

    	Al limitar el alcance de una variable a un método o bloque de código específico, se reduce la visibilidad y accesibilidad desde otros métodos o partes del código, lo que favorece la encapsulación y la modularidad.


	Prevención de Modificaciones Accidentales:

	    Las variables locales, al tener un alcance más limitado, son menos propensas a ser modificadas accidentalmente desde otros métodos o partes del código.

	    Esto ayuda a prevenir errores sutiles que pueden ocurrir cuando múltiples métodos intentan modificar el estado de una variable de instancia.


	Evita Efectos Secundarios Indeseados:

   		El uso extensivo de variables de instancia puede llevar a efectos secundarios indeseados. 

   		Si varios métodos modifican variables de instancia en un objeto compartido, puede ser difícil rastrear el origen de los cambios y comprender el estado del objeto en un momento dado.


	```java

	public class EjemploVariables {
	    // Variable de instancia
	    private int variableDeInstancia;

	    public void ejemploMetodo(int parametro) {
	        // Variable local
	        int variableLocal = parametro;

	        // Uso de variables
	        variableLocal = variableLocal + 10;
	        variableDeInstancia = variableDeInstancia + 5;
	    }
	}

	```



|| Estado de un objeto: 

	Son valores de sus campos (también conocidos como atributos o propiedades) en un momento dado. 

	Cada objeto en Java tiene un conjunto de campos que representan sus características y propiedades. 

	El estado de un objeto se determina por los valores actuales de estos campos en un momento específico durante la ejecución del programa.


	Características del Estado de un Objeto:

    1. Representación de Datos: 

    	Los campos de un objeto representan los datos asociados con ese objeto.

    	Estos campos pueden ser de diferentes tipos, como primitivos, objetos u otros tipos de datos.


    2. Cambios Dinámicos: 

    	El estado de un objeto puede cambiar durante la ejecución del programa a medida que se realizan operaciones en él.

    	Los métodos pueden modificar los valores de los campos, lo que altera el estado del objeto.


    3. Encapsulamiento: 

    	El estado de un objeto está encapsulado dentro de él, lo que significa que solo los métodos de la propia clase (o clases relacionadas) pueden acceder y modificar sus campos directamente. 

    	Esto promueve la ocultación de información y el principio de encapsulamiento en la programación orientada a objetos.


    Ejemplo: 

    	Una clase 'Persona' que representa a una persona con campos como nombre, edad y género. 

    ```java

    public class Persona {
	    // Campos (estado)
	    private String nombre;
	    private int edad;
	    private char genero;

	    // Constructor
	    public Persona(String nombre, int edad, char genero) {
	        this.nombre = nombre;
	        this.edad = edad;
	        this.genero = genero;
	    }

	    // Métodos para acceder y modificar el estado
	    public String getNombre() {
	        return nombre;
	    }

	    public void setNombre(String nombre) {
	        this.nombre = nombre;
	    }

	    public int getEdad() {
	        return edad;
	    }

	    public void setEdad(int edad) {
	        this.edad = edad;
	    }

	    public char getGenero() {
	        return genero;
	    }

	    public void setGenero(char genero) {
	        this.genero = genero;
	    }
	}

    ```

    La clase Persona tiene tres campos: nombre, edad y genero. 

    El estado de un objeto Persona se define por los valores actuales de estos campos. 

    Por ejemplo, si creamos una instancia de Persona con el nombre "Juan", edad 25 y género 'M', ese sería el estado inicial de ese objeto.

    ```java

    Persona persona = new Persona("Juan", 25, 'M');

    ```

    El estado de este objeto puede cambiar más tarde, por ejemplo, si llamamos a métodos para actualizar el nombre o la edad de la persona.

    ```java

    persona.setEdad(26);
	persona.setNombre("Juan Pérez");

    ```


|| Constructores sobrecargados
	
	Capacidad de una clase de tener múltiples constructores con la misma o diferente cantidad de parámetros. 

	Estos constructores comparten el mismo nombre pero difieren en la firma, es decir, en la cantidad, tipo o orden de los parámetros que aceptan.

	Cuando se crea una instancia de una clase utilizando un constructor, la JVM (Java Virtual Machine) determina cuál constructor utilizar según la cantidad y tipo de argumentos proporcionados. 

	Esto permite a la clase proporcionar diferentes maneras de inicializar sus objetos.

	```java

	public class Persona {
	    private String nombre;
	    private int edad;

	    // Constructor por defecto
	    public Persona() {
	        nombre = "Sin nombre";
	        edad = 0;
	    }

	    // Constructor con un parámetro
	    public Persona(String nombre) {
	        this.nombre = nombre;
	        edad = 0; // Edad por defecto
	    }

	    // Constructor con dos parámetros
	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Otros métodos de la clase...
	    
	    // Método para mostrar información de la persona
	    public void mostrarInformacion() {
	        System.out.println("Nombre: " + nombre);
	        System.out.println("Edad: " + edad);
	    }

	    public static void main(String[] args) {
	        // Crear instancias utilizando diferentes constructores
	        Persona persona1 = new Persona();
	        Persona persona2 = new Persona("Alice");
	        Persona persona3 = new Persona("Bob", 30);

	        // Mostrar información de las personas
	        persona1.mostrarInformacion();
	        persona2.mostrarInformacion();
	        persona3.mostrarInformacion();
	    }
	}

	```



|| toString
	
	Es un método de la clase 'Object' que se puede sobrescribir en cualquier clase para proporcionar una representación de cadena de texto de un objeto. 

	Cuando imprimes un objeto utilizando el método 'System.out.println' o al concatenar el objeto con una cadena, Java invoca implícitamente el método toString del objeto para obtener una representación de cadena legible.

	Al sobrescribir el método toString en una clase específica, puedes proporcionar tu propia lógica para generar una representación más significativa y descriptiva del objeto.

	```java

	public class Persona {
	    private String nombre;
	    private int edad;

	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Sobrescribir el método toString
	    @Override
	    public String toString() {
	        return "Persona [nombre=" + nombre + ", edad=" + edad + "]";
	    }

	    public static void main(String[] args) {
	        Persona persona = new Persona("Alice", 25);

	        // Al imprimir el objeto, se invoca implícitamente el método toString
	        System.out.println(persona); // Salida: Persona [nombre=Alice, edad=25]
	    }
	}

	```

	La clase 'Persona' sobrescribe el método toString para proporcionar una representación más significativa que incluye el nombre y la edad de la persona. 

	Cuando imprimes una instancia de Persona, se llama automáticamente al método 'toString', y la salida es más descriptiva.


	Sobrescribir el método 'toString' es útil al depurar o al imprimir información sobre objetos, y puede hacer que tu código sea más legible y fácil de entender. 

	Es una práctica común en Java proporcionar una implementación personalizada de 'toString' en clases específicas.



|| Array de Objetos

	Es un arreglo que contiene elementos que son objetos en lugar de tipos de datos primitivos. 

	Cada elemento en el arreglo es una referencia a un objeto, y esos objetos pueden ser instancias de cualquier clase.

	```java

	// Declaración de un array de objetos
	NombreDeClase[] nombreArreglo = new NombreDeClase[tamaño];

	```

	Ejemplo: 


	```java

	public class EjemploArrayOfObjects {
	    public static void main(String[] args) {
	        // Declarar un array de objetos de la clase Persona
	        Persona[] personas = new Persona[3];

	        // Crear instancias de Persona y asignarlas al array
	        personas[0] = new Persona("Alice", 25);
	        personas[1] = new Persona("Bob", 30);
	        personas[2] = new Persona("Charlie", 22);

	        // Acceder a los objetos del array y mostrar información
	        for (Persona persona : personas) {
	            System.out.println(persona);
	        }
	    }
	}

	class Persona {
	    private String nombre;
	    private int edad;

	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    @Override
	    public String toString() {
	        return "Persona [nombre=" + nombre + ", edad=" + edad + "]";
	    }
	}

	```
	
	El array 'personas' que puede contener instancias de la clase 'Persona'. 

	Se crean instancias de 'Persona' y se asignan a las posiciones del arreglo. 

	Luego, se utiliza un bucle 'for-each' para recorrer el arreglo y mostrar información sobre cada persona.

	Un arreglo almacena referencias a objetos, no los objetos en sí.

	Por lo tanto, al declarar un "array of objects", se están almacenando referencias a las instancias de las clases en lugar de los objetos directamente. 

	Esto implica que es necesario crear instancias de los objetos y asignarlas al arreglo antes de utilizarlo.



|| Referencias

	Son variables que almacenan direcciones de memoria, específicamente direcciones de objetos en el 'heap'. 

	Aunque en Java no puedes manipular directamente direcciones de memoria como lo harías en lenguajes de bajo nivel, las referencias te permiten acceder y manipular objetos de forma indirecta.

	1. Declaracion de Referencias:

		Se declaran con el tipo de objeto al que apuntarán, seguido del nombre de la variable. 

		```java

		// Declaración de referencia a un objeto de tipo String
		String miString;

		```

	2. Asignación de Referencias: 

		Las referencias se pueden asignar a objetos existentes utilizando el operador de asignación (=).

		```java

		// Asignación de referencia a un nuevo objeto String
		miString = new String("Hola, mundo");

		```


	3. Operaciones con Referencias: 

		Como pasarlas como argumentos a métodos, retornarlas desde métodos o asignarles nuevos valores.

		```java

		String otroString = miString;  // Asignación de una referencia a otra

		```


	4. Referencias y Objetos:

		La referencia apunta al objeto en el heap, pero no es el objeto en sí. 

		Varias referencias pueden apuntar al mismo objeto.

		```java

		String referencia1 = new String("Java");
		String referencia2 = referencia1;  // Ambas referencias apuntan al mismo objeto

		```


	5. Null: 	

		Una referencia puede tener el valor especial null, que indica que no apunta a ningún objeto.


	6. Operaciones de Dereferenciación:

    	Para acceder a los métodos y campos de un objeto, se utiliza la dereferenciación a través de la referencia.

    	```java

    	int longitud = miString.length();  // Dereferenciación para acceder al método 'length'

    	```


    7. Garbage Collection:

    	El recolector de basura liberar la memoria de objetos no utilizados. 

    	Cuando no hay referencias que apunten a un objeto, se convierte en candidato para ser recolectado.

    	```java

    	miString = null;  // La referencia a 'miString' ahora es null, el objeto puede ser recolectado

    	```


    8. Referencias a Objetos Anónimos:

    	Puedes crear referencias a objetos de manera anónima, especialmente al trabajar con interfaces o clases abstractas.

    
    9. Referencias a Objetos Genéricos:

    	Las referencias a objetos pueden ser utilizadas con tipos genéricos para hacer que el código sea más flexible y reutilizable

    	```java

    	List<String> lista = new ArrayList<>();

    	```



|| Objetos como argumentos
	
	De métodos o como valores de retorno desde métodos. 

	En Java, cuando pasas un objeto a un método, estás pasando la referencia al objeto, no el objeto en sí. 

	Esto significa que, dentro del método, puedes manipular el objeto referenciado, y cualquier cambio que realices afectará al objeto original fuera del método.

	```java

	public class ObjectPassingExample {
	    public static void main(String[] args) {
	        // Crear un objeto Persona
	        Persona persona = new Persona("Alice", 25);

	        // Llamar a un método y pasar el objeto como argumento
	        modificarPersona(persona);

	        // Imprimir la información después de llamar al método
	        System.out.println("Después de llamar al método:");
	        System.out.println(persona);
	    }

	    // Método que modifica el objeto Persona
	    public static void modificarPersona(Persona p) {
	        p.setEdad(30);
	        p.setNombre("Nuevo Nombre");
	    }
	}

	class Persona {
	    private String nombre;
	    private int edad;

	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    public void setNombre(String nombre) {
	        this.nombre = nombre;
	    }

	    public void setEdad(int edad) {
	        this.edad = edad;
	    }

	    @Override
	    public String toString() {
	        return "Persona [nombre=" + nombre + ", edad=" + edad + "]";
	    }
	}

	```

	Se crea un objeto 'Persona' llamado 'persona'. 

	Luego, se llama al método 'modificarPersona' y se le pasa el objeto 'persona' como argumento. 

	Dentro del método, se modifica la 'edad' y el 'nombre' de la persona.

	Después de llamar al método, se imprime la información de la persona y se observa que los cambios realizados dentro del método han afectado al objeto original.


	Estás pasando la referencia al objeto, no puedes cambiar la referencia en sí misma. 

	Es decir, no puedes hacer que la referencia apunte a un objeto completamente diferente dentro del método. 

	La referencia es pasada por valor, pero aún así te permite modificar el estado del objeto al que apunta.



|| Static

	'static' se utiliza para declarar miembros de clase que pertenecen a la propia clase en lugar de a las instancias individuales de esa clase.


	Contextos: 

	1. Métodos Estáticos:

    	Un método estático pertenece a la clase en lugar de a instancias específicas de esa clase. 

    	Se llama a través del nombre de la clase en lugar de a través de una instancia del objeto. 

    	Los métodos estáticos no pueden acceder a variables de instancia directamente y generalmente se utilizan para operaciones que no dependen del estado específico de un objeto.

    	```java

    	public class EjemploStaticMethod {
		    public static void metodoEstatico() {
		        System.out.println("Este es un método estático.");
		    }

		    public static void main(String[] args) {
		        // Llamada a un método estático
		        EjemploStaticMethod.metodoEstatico();
		    }
		}

    	```


    2. Variables Estáticas (Campos Estáticos):

    	Una variable estática es compartida por todas las instancias de una clase.

    	Existe una única copia de la variable, independientemente de cuántas instancias de la clase se hayan creado. 

    	Se accede a las variables estáticas a través del nombre de la clase, no a través de instancias individuales.

    	```java

    	public class EjemploStaticVariable {
		    // Variable estática
		    public static int contador = 0;

		    public static void main(String[] args) {
		        // Acceder y modificar una variable estática
		        EjemploStaticVariable.contador++;
		        System.out.println("Valor del contador: " + EjemploStaticVariable.contador);
		    }
		}

    	```


    3. Bloques de Inicialización Estáticos:

    	Los bloques de inicialización estáticos son bloques de código que se ejecutan una vez cuando la clase se carga en la memoria. 

    	Se utilizan para inicializar variables estáticas o realizar operaciones de inicialización específicas de la clase.

    	```java

    	public class EjemploStaticBlock {
		    // Variable estática
		    public static int valor;

		    // Bloque de inicialización estática
		    static {
		        valor = 42;
		        System.out.println("Inicialización estática completada.");
		    }

		    public static void main(String[] args) {
		        // Acceder a la variable estática después de la inicialización
		        System.out.println("Valor después de la inicialización: " + EjemploStaticBlock.valor);
		    }
		}

    	```


    4. Clases Anidadas Estáticas:

    	Una clase estática anidada es una clase que se declara dentro de otra clase y se modifica con la palabra clave static. 

    	Puede tener acceso a miembros estáticos de la clase externa.

    	```java

    	public class ClaseExterna {
		    // Miembro estático de la clase externa
		    public static int valorExterno = 10;

		    // Clase interna estática
		    public static class ClaseInterna {
		        public void mostrarValorExterno() {
		            // Acceder a un miembro estático de la clase externa
		            System.out.println("Valor externo desde la clase interna: " + valorExterno);
		        }
		    }
		}

    	```



|| Herencia 

	Permite la creación de nuevas clases basadas en clases existentes. 

	En Java, la herencia se implementa utilizando la palabra clave 'extends'. 

	Una clase que hereda de otra se denomina "subclase" o "clase hija", y la clase de la cual hereda se llama "superclase" o "clase padre". 

	Facilita la reutilización de código y la creación de una jerarquía de clases.

	```java

	// Superclase o clase padre
	class Animal {
	    String nombre;

	    public Animal(String nombre) {
	        this.nombre = nombre;
	    }

	    public void hacerSonido() {
	        System.out.println("Haciendo un sonido genérico");
	    }
	}

	// Subclase o clase hija que hereda de Animal
	class Perro extends Animal {
	    public Perro(String nombre) {
	        super(nombre);
	    }

	    // Sobrescribe el método hacerSonido de la superclase
	    @Override
	    public void hacerSonido() {
	        System.out.println("Guau, guau");
	    }

	    // Nuevo método específico de la clase Perro
	    public void perseguirCola() {
	        System.out.println("Persiguiendo la cola");
	    }
	}

	public class EjemploHerencia {
	    public static void main(String[] args) {
	        // Crear una instancia de la clase Perro
	        Perro miPerro = new Perro("Buddy");

	        // Acceder a los miembros de la superclase
	        System.out.println("Nombre del perro: " + miPerro.nombre);

	        // Llamar al método hacerSonido de la subclase
	        miPerro.hacerSonido();

	        // Llamar al método específico de la clase Perro
	        miPerro.perseguirCola();
	    }
	}

	```

	La clase 'Animal' es la superclase con un constructor y un método 'hacerSonido'.

    La clase 'Perro' es la subclase que hereda de Animal utilizando extends.

    La subclase 'Perro' sobrescribe el método 'hacerSonido' y agrega un nuevo método 'perseguirCola'.

    En el método 'main', se crea una instancia de 'Perro' y se accede tanto a los miembros heredados de 'Animal' como a los específicos de 'Perro'.



|| Métodos sobreescritos
	
	Una subclase proporciona una implementación específica de un método que ya está definido en su superclase. 

	Cuando una subclase tiene un método con la misma firma (nombre, tipo de retorno y parámetros) que un método en la superclase, se dice que la subclase está sobrescribiendo el método de la superclase.


	1. Firma Idéntica: 

		El método en la subclase debe tener la misma firma que el método en la superclase. Esto incluye el nombre del método, el tipo de retorno y la lista de parámetros.


    2. Visibilidad Compatible o Más Permisiva: 

    	La visibilidad del método en la subclase puede ser igual o más permisiva que la visibilidad del método en la superclase. 

    	Por ejemplo, si un método en la superclase es 'protected', en la subclase puede ser 'protected' o 'public', pero no puede ser private.

    
    3. Valor de Retorno Covariante:

    	El tipo de retorno del método en la subclase puede ser un subtipo del tipo de retorno del método en la superclase.

    	Esto significa que la subclase puede devolver un tipo más específico.



|| Super
	
	Se utiliza para referirse a la superclase de la clase actual.

	Puede ser utilizada de varias maneras, y su principal propósito es acceder a los miembros (campos o métodos) de la superclase.


	1. Acceder a los Campos de la Superclase:

		Puedes utilizar 'super' para acceder a los campos de la superclase cuando hay un campo en la subclase con el mismo nombre y deseas diferenciarlos.

		```java
		class Animal {
		    String nombre = "Animal";
		}

		class Perro extends Animal {
		    String nombre = "Perro";

		    void mostrarNombres() {
		        System.out.println("Nombre en la subclase: " + nombre);
		        System.out.println("Nombre en la superclase: " + super.nombre);
		    }
		}

		public class EjemploSuperKeyword {
		    public static void main(String[] args) {
		        Perro miPerro = new Perro();
		        miPerro.mostrarNombres();
		    }
		}

		```

		'super.nombre' se utiliza para acceder al campo 'nombre' de la superclase 'Animal', mientras que nombre se refiere al campo de la subclase 'Perro'.

	
	2. Invocar Métodos de la Superclase:

		Puedes utilizar 'super' para invocar métodos de la superclase cuando hay una sobrescritura de método en la subclase y deseas ejecutar la versión de la superclase.

		```java

		class Animal {
		    void hacerSonido() {
		        System.out.println("Sonido genérico de un animal");
		    }
		}

		class Perro extends Animal {
		    @Override
		    void hacerSonido() {
		        super.hacerSonido();  // Invoca el método de la superclase
		        System.out.println("Guau, guau");
		    }
		}

		public class EjemploSuperKeyword {
		    public static void main(String[] args) {
		        Perro miPerro = new Perro();
		        miPerro.hacerSonido();
		    }
		}

		```

		'super.hacerSonido()' se utiliza para invocar el método 'hacerSonido' de la superclase 'Animal' desde la subclase 'Perro'.		


	3. Llamar al Constructor de la Superclase:

		Puedes utilizar 'super' para llamar al constructor de la superclase desde el constructor de la subclase.

		```java

		class Animal {
		    String nombre;

		    Animal(String nombre) {
		        this.nombre = nombre;
		    }
		}

		class Perro extends Animal {
		    String raza;

		    Perro(String nombre, String raza) {
		        super(nombre);  // Llama al constructor de la superclase
		        this.raza = raza;
		    }
		}

		public class EjemploSuperKeyword {
		    public static void main(String[] args) {
		        Perro miPerro = new Perro("Buddy", "Labrador");
		        System.out.println("Nombre del perro: " + miPerro.nombre);
		        System.out.println("Raza del perro: " + miPerro.raza);
		    }
		}

		```

		'super(nombre)' se utiliza para llamar al constructor de la superclase 'Animal' desde el constructor de la subclase 'Perro' y heredar la característica. 



|| Abstracción
	
	Es la capacidad de representar las características esenciales de un objeto sin proporcionar detalles innecesarios o irrelevantes. 

	En otras palabras, la abstracción se trata de centrarse en los aspectos más importantes de un objeto y ocultar los detalles de implementación menos importantes.


	Principios: 

	1. Identificar Entidades Relevantes: 

		La abstracción comienza identificando las entidades relevantes en el problema que estás tratando de resolver.

		Estas entidades pueden ser objetos del mundo real o conceptos abstractos.


    2. Definir Clases y Objetos: 

    	Una vez identificadas las entidades, las representas en tu programa mediante clases y objetos en Java. 

    	Cada clase encapsula el comportamiento y el estado asociado con una entidad específica.


    3. Ocultar Detalles de Implementación: 

    	En la definición de una clase, te enfocas en los detalles esenciales y relevantes para la entidad que estás representando, mientras ocultas los detalles de implementación innecesarios. 

    	Esto se logra mediante la encapsulación, donde los detalles internos de la clase se mantienen privados y solo se exponen los aspectos relevantes a través de métodos públicos.


    Ejemplo: 

		Programa para gestionar una biblioteca, debemos tener una clase que represente sus entidades, como una clase 'Libro' que representa a los libros de la biblioteca. 


	```java

	public class Libro {
	    private String titulo;
	    private String autor;
	    private int añoPublicacion;

	    // Constructor y métodos getter y setter...

	    public void prestar() {
	        // Implementación para prestar un libro
	    }

	    public void devolver() {
	        // Implementación para devolver un libro
	    }

	    // Otros métodos relevantes...
	}

	```

	La clase 'Libro' encapsula el comportamiento y el estado asociado con un libro. 

	Los detalles de implementación, sobre cómo se almacena el título o el autor, se mantienen ocultos dentro de la clase y solo se exponen a través de métodos públicos como 'getTitulo()' y 'getAutor()'. 

	Esto permite que otros objetos interactúen con un libro de manera abstracta, sin necesidad de conocer los detalles internos de cómo se implementa la clase Libro.
	


|| Modificadores de Acceso

	Son palabras clave que se utilizan para controlar el nivel de acceso a clases, campos, métodos y constructores en un programa. 

	Estos modificadores determinan qué partes del código pueden acceder a los miembros de una clase y en qué medida.


	1. Public: 

		Los miembros declarados como 'public' son accesibles desde cualquier clase. 

		No hay restricciones de acceso.

		```java

		public class MiClase {
		    public int miCampo;
		    public void miMetodo() {
		        // Código del método
		    }
		}

		```


	2. Private:

    	Los miembros declarados como 'private' son accesibles solo dentro de la misma clase. 

    	No son accesibles desde clases externas.

    	```java

    	public class MiClase {
		    private int miCampo;
		    private void miMetodo() {
		        // Código del método
		    }
		}

    	```


    3. Protected (protected):

    	Los miembros declarados como 'protected' son accesibles dentro de la misma clase, dentro de las clases del mismo paquete y en las subclases (incluso si están en paquetes diferentes).

    	```java

    	public class MiClase {
		    protected int miCampo;
		    protected void miMetodo() {
		        // Código del método
		    }
		}

    	```


    4. Default (sin modificador):

    	Si no se especifica ningún modificador de acceso (es decir, no se usa 'public', 'private' o 'protected'), se aplica el acceso predeterminado. 

    	Los miembros con acceso predeterminado son accesibles solo dentro del mismo paquete.

    	```java

    	class MiClase {
		    int miCampo;  // Acceso predeterminado
		    void miMetodo() {
		        // Código del método
		    }
		}

    	```


    Uso de Modificadores de Acceso:

	    Clases:

	        Las clases pueden ser 'public' o tener acceso predeterminado. 

	        No pueden ser 'private' ni 'protected'.


	    Campos (Variables de Instancia o de Clase):

	        Pueden ser 'public', 'private', 'protected' o tener acceso predeterminado.


	    Métodos:

	        Pueden ser 'public', 'private', 'protected' o tener acceso predeterminado.

	    
	    Constructores:

	        Pueden ser 'public', 'private', 'protected' o tener acceso predeterminado.


	Contribución: 

		Encapsulamiento:

	        Los modificadores de acceso son esenciales para el principio de encapsulamiento, que sugiere ocultar los detalles internos de implementación y proporcionar una interfaz pública para interactuar con el objeto.


	    Seguridad:

	        Los modificadores de acceso también contribuyen a la seguridad y la integridad del código, ya que limitan el acceso a ciertos miembros solo a las partes del código que realmente necesitan utilizarlos.       




|| Encapsulación
		
	Es la idea de agrupar datos y los métodos que operan sobre esos datos en una única unidad llamada clase. 

	Además, la encapsulación implica ocultar los detalles internos de implementación de una clase y proporcionar una interfaz pública consistente para interactuar con la misma.

	
	Principios: 

	1. Ocultar Detalles Internos:

        Los detalles internos de implementación, como la representación interna de los datos y la lógica de implementación de los métodos, se ocultan fuera de la clase. 

        Esto se conoce como ocultamiento de información.


    2. Proteger Datos:

        Los datos internos de una clase se protegen al proporcionar acceso controlado a través de métodos de la clase. 

        Esto evita que los datos sean modificados de manera inapropiada desde fuera de la clase.


    3. Proporcionar Interfaz Pública:

        Se define una interfaz pública consistente que especifica cómo interactuar con la clase. 

        Esta interfaz se compone de métodos públicos y actúa como un contrato entre la clase y el mundo exterior.


    4. Facilitar Mantenimiento:

        La encapsulación facilita el mantenimiento del código, ya que los cambios internos en la implementación de una clase no afectarán a las partes del programa que utilizan la clase, siempre y cuando la interfaz pública permanezca inalterada.


	```java

	public class Persona {
	    private String nombre;  // Campo encapsulado
	    private int edad;       // Campo encapsulado

	    // Constructor
	    public Persona(String nombre, int edad) {
	        this.nombre = nombre;
	        this.edad = edad;
	    }

	    // Métodos públicos para acceder a los campos encapsulados
	    public String getNombre() {
	        return nombre;
	    }

	    public void setNombre(String nombre) {
	        this.nombre = nombre;
	    }

	    public int getEdad() {
	        return edad;
	    }

	    public void setEdad(int edad) {
	        if (edad > 0) {
	            this.edad = edad;
	        }
	    }
	}

	```

	La clase 'Persona' encapsula los campos 'nombre' y 'edad'. 

	Los métodos 'get' y 'set' proporcionan una interfaz para acceder y modificar estos campos.

	La palabra clave 'private' asegura que los campos solo sean accesibles y modificables desde dentro de la propia clase. 

	Este enfoque permite un control más preciso sobre cómo se accede y se modifica la información interna de la clase.	

	```java

	public class EjemploEncapsulacion {
	    public static void main(String[] args) {
	        Persona persona = new Persona("Alice", 25);

	        // Acceder a los campos encapsulados mediante métodos públicos
	        System.out.println("Nombre: " + persona.getNombre());
	        System.out.println("Edad: " + persona.getEdad());

	        // Modificar los campos encapsulados mediante métodos públicos
	        persona.setNombre("Bob");
	        persona.setEdad(30);

	        System.out.println("Nuevo Nombre: " + persona.getNombre());
	        System.out.println("Nueva Edad: " + persona.getEdad());
	    }
	}

	```



|| Copia de Objetos
	
	Es la creación de un nuevo objeto que tiene los mismos valores que otro objeto existente. 

	Es importante comprender que en Java, cuando copias un objeto, en realidad estás creando una nueva referencia al mismo objeto o, en el caso de la copia profunda, una nueva instancia con valores idénticos pero independiente del objeto original.


	1. Copia Superficial (Shallow Copy):

		Una copia superficial crea un nuevo objeto, pero si el objeto original contiene referencias a otros objetos, la copia solo copia esas referencias, no los objetos a los que apuntan. 

		Ambas referencias (original y copia) apuntarán a los mismos objetos internos.

		```java

		class Persona {
		    String nombre;

		    Persona(String nombre) {
		        this.nombre = nombre;
		    }
		}

		public class EjemploCopiaSuperficial {
		    public static void main(String[] args) {
		        Persona personaOriginal = new Persona("Alice");

		        // Copia superficial
		        Persona personaCopia = personaOriginal;

		        // Ambas referencias apuntan al mismo objeto
		        System.out.println("Original: " + personaOriginal.nombre);
		        System.out.println("Copia: " + personaCopia.nombre);

		        // Modificar el objeto a través de una de las referencias
		        personaOriginal.nombre = "Bob";

		        // Ambas referencias reflejan el cambio
		        System.out.println("Original después de modificar: " + personaOriginal.nombre);
		        System.out.println("Copia después de modificar: " + personaCopia.nombre);
		    }
		}


		```


	2. Copia Profunda (Deep Copy):

		Una copia profunda crea un nuevo objeto y también copia los objetos internos a los que hace referencia, de modo que ambos objetos (original y copia) son independientes y no comparten referencias a los mismos objetos internos.

		```java

		class Persona {
		    String nombre;

		    Persona(String nombre) {
		        this.nombre = nombre;
		    }
		}

		public class EjemploCopiaProfunda {
		    public static void main(String[] args) {
		        Persona personaOriginal = new Persona("Alice");

		        // Copia profunda
		        Persona personaCopia = new Persona(personaOriginal.nombre);

		        // Ambas referencias apuntan a objetos independientes
		        System.out.println("Original: " + personaOriginal.nombre);
		        System.out.println("Copia: " + personaCopia.nombre);

		        // Modificar el objeto a través de una de las referencias
		        personaOriginal.nombre = "Bob";

		        // Los objetos internos no se ven afectados por el cambio
		        System.out.println("Original después de modificar: " + personaOriginal.nombre);
		        System.out.println("Copia después de modificar: " + personaCopia.nombre);
		    }
		}

		```

		Si los objetos internos son mutables (por ejemplo, listas o mapas), una copia superficial solo duplicará las referencias a esos objetos mutables, mientras que una copia profunda también duplicará el contenido mutable. 

		En algunos casos, puede ser necesario implementar la lógica de copia profunda manualmente o utilizar bibliotecas externas como 'Object.clone()' o bibliotecas de serialización/deserialización para realizar copias profundas automáticamente.


	Casos de uso: 

	1. Inmutabilidad:

    	Si un objeto es inmutable (sus estados no cambian después de la creación), generalmente no necesitas realizar copias, ya que los objetos inmutables son inherentemente seguros para compartir entre múltiples partes de un programa.


	2. Evitar Efectos Secundarios:

    	Al realizar copias, puedes evitar efectos secundarios no deseados cuando compartes objetos entre diferentes partes del código. 

    	Una copia crea una instancia independiente, lo que significa que las modificaciones en una instancia no afectarán a la otra.


	3. Cambios Locales:

    	Cuando necesitas realizar cambios locales en un objeto sin afectar el objeto original. 

    	Esto es especialmente útil cuando trabajas con colecciones, como listas o mapas, y deseas realizar modificaciones sin afectar la versión original


	4. Seguridad:

    	En algunos casos, puede ser necesario utilizar copias para garantizar la seguridad de los datos. 

    	Por ejemplo, cuando pasas objetos a través de interfaces públicas, puedes proporcionar copias para evitar que el código cliente realice modificaciones no autorizadas.


    5. Evitar Referencias Compartidas:

    	Algunas estructuras de datos pueden compartir referencias a objetos internos. 

    	En tales casos, realizar una copia asegura que las instancias originales y copiadas no compartan referencias internas


    6. Snapshot de Datos:

    	Cuando necesitas tomar un "snapshot" (instantánea) de los datos en un momento específico para trabajar con ellos independientemente de los cambios futuros.



|| Interface 
	
	Colección de métodos abstractos (sin implementación) y, a partir de Java 8, puede contener métodos con implementación (conocidos como métodos por defecto o default methods) y constantes (variables que no pueden ser modificadas). 

	Una interfaz define un contrato que las clases pueden implementar, especificando los métodos que deben proporcionar. Las interfaces permiten la creación de código más modular y facilitan la implementación de múltiples herencias


	Características: 

	1 .Métodos Abstractos:

    	Una interfaz puede contener métodos abstractos, que son declaraciones de métodos sin implementación.

    	```java

    	interface Forma {
		    void dibujar();  // Método abstracto
		}

    	```


    2. Métodos por Defecto (Default Methods):

    	A partir de Java 8, las interfaces pueden tener métodos con implementación proporcionando una implementación predeterminada para el método. 

    	Las clases que implementan la interfaz pueden optar por utilizar la implementación predeterminada o proporcionar su propia implementación

    	```java

    	interface Saludable {
		    default void saludar() {
		        System.out.println("¡Hola!");
		    }
		}

    	```


    3. Constantes:

   		Las interfaces pueden contener constantes, que son variables con valores que no pueden ser modificados. 

   		Estas constantes son implícitamente public, static y final.

   		```java

   		interface Colores {
		    int ROJO = 1;     // Constante
		    int VERDE = 2;    // Constante
		    int AZUL = 3;     // Constante
		}

   		```


   	4. Múltiple Herencia:

    	A diferencia de las clases, una clase puede implementar múltiples interfaces. 

    	Esto permite la implementación de múltiple herencia en Java.

    	```java

    	class Circulo implements Forma, Saludable {
		    @Override
		    public void dibujar() {
		        System.out.println("Dibujando un círculo");
		    }
		}

    	```


    Ejemplo: 

    ```java

    // Definir una interfaz
		interface Animal {
		    void hacerSonido();  // Método abstracto
		}

		// Implementar la interfaz en una clase
		class Perro implements Animal {
		    @Override
		    public void hacerSonido() {
		        System.out.println("Guau, guau");
		    }
		}

		// Otra implementación de la interfaz
		class Gato implements Animal {
		    @Override
		    public void hacerSonido() {
		        System.out.println("Miau, miau");
		    }
		}

		// Ejemplo de uso
		public class EjemploInterfaz {
		    public static void main(String[] args) {
		        Animal perro = new Perro();
		        perro.hacerSonido();  // Resultado: Guau, guau

		        Animal gato = new Gato();
		        gato.hacerSonido();   // Resultado: Miau, miau
		    }
		}


    ```



|| Contrato: 

	Conjunto de reglas y expectativas que establece cómo se deben utilizar y comportar las clases que implementan una interfaz o heredan de una clase base. 

	Un contrato establece las responsabilidades y garantías que deben cumplir las clases que participan en él.	

	
	1. Interfaz como contrato: 

		Se establece mediante los métodos declarados en la interfaz. 

		Cada clase que implementa la interfaz está obligada a proporcionar implementaciones concretas para todos los métodos declarados en esa interfaz. 

		Cada método en la interfaz representa una expectativa que se debe cumplir. 

		```java

		interface Forma {
		    void dibujar();
		    double calcularArea();
		}

		```

		Cualquier clase que implemente la interfaz Forma debe proporcionar una implementación para los métodos dibujar y calcularArea. 

		Este conjunto de métodos forma el contrato que las clases deben seguir.


	2. Herencia como Contrato:

    	En el caso de la herencia, una clase base define un conjunto de métodos y propiedades que las clases derivadas deben heredar. 

    	La clase base establece un contrato que las clases derivadas deben cumplir, lo que significa que deben proporcionar implementaciones concretas para todos los métodos definidos en la clase base.

    	```java

    	class Animal {
		    void hacerSonido() {
		        System.out.println("Sonido genérico de un animal");
		    }
		}

		class Perro extends Animal {
		    // Implementación específica para hacerSonido en la clase Perro
		    @Override
		    void hacerSonido() {
		        System.out.println("Guau, guau");
		    }
		}

    	```

    	En este ejemplo, la clase 'Animal' establece un contrato al definir el método 'hacerSonido'. 

    	La clase 'Perro', que hereda de 'Animal', debe proporcionar su propia implementación del método 'hacerSonido' para cumplir con el contrato.


    Características: 

    1. Interoperabilidad:

	    El contrato facilita la interoperabilidad entre clases y componentes. 

	    Las clases que cumplen con el mismo contrato pueden interactuar de manera eficiente y predecible, lo que facilita la construcción de sistemas complejos.


	2. Extensibilidad:

	    El contrato permite la extensibilidad del código.

	    Puedes introducir nuevas clases que implementen el mismo contrato sin afectar las partes existentes del sistema.


	3. Mantenimiento:

	    El contrato facilita el mantenimiento del código. 

	    Si una clase cumple con un contrato, se puede confiar en que cumplirá con las expectativas definidas por ese contrato, incluso si la implementación interna de la clase cambia.




|| Polimorfismo 
	
	Es la capacidad de un objeto de tomar muchas formas diferentes.

	El polimorfismo permite que un mismo nombre (como un método o una propiedad) se utilice de manera diferente en diferentes contextos. 

	Hay dos tipos principales de polimorfismo en POO: 

	1. Polimorfismo de tiempo de compilación (compile-time polymorphism o polimorfismo estático): 

		También conocido como sobrecarga de métodos o "overloading", este tipo de polimorfismo ocurre en tiempo de compilación. 

		En la sobrecarga de métodos, múltiples métodos en una clase tienen el mismo nombre pero diferentes listas de parámetros. 

		El compilador determina qué método llamar en función de la cantidad y tipos de argumentos proporcionados.

		```java

		public class EjemploPolimorfismoCompileTime {
		    // Sobrecarga de métodos
		    static int sumar(int a, int b) {
		        return a + b;
		    }

		    static double sumar(double a, double b) {
		        return a + b;
		    }

		    public static void main(String[] args) {
		        System.out.println(sumar(5, 10));       // Llama al primer método
		        System.out.println(sumar(3.5, 7.2));    // Llama al segundo método
		    }
		}

		```


	2. Polimorfismo de tiempo de ejecución (runtime polymorphism o polimorfismo dinámico): 

		También conocido como sobrescritura de métodos o "overriding", este tipo de polimorfismo ocurre en tiempo de ejecución. 

		En la sobrescritura de métodos, una clase hija proporciona una implementación específica para un método que ya está definido en su clase base. 

		La elección de qué método llamar se realiza en tiempo de ejecución, basándose en el tipo real del objeto.

		```java

		// Clase base
		class Animal {
		    void hacerSonido() {
		        System.out.println("Sonido genérico de un animal");
		    }
		}

		// Clase derivada que sobrescribe el método hacerSonido
		class Perro extends Animal {
		    @Override
		    void hacerSonido() {
		        System.out.println("Guau, guau");
		    }
		}

		public class EjemploPolimorfismoRunTime {
		    public static void main(String[] args) {
		        Animal miAnimal = new Perro();  // Crear una instancia de la clase derivada

		        miAnimal.hacerSonido();  // Llama al método sobrescrito en tiempo de ejecución
		    }
		}

		```



|| Manejo de excepciones

	Permite a los programadores controlar y responder a situaciones excepcionales o errores que pueden ocurrir durante la ejecución de un programa. 

	Las excepciones son eventos imprevistos que interrumpen el flujo normal de ejecución. 

	Al utilizar el manejo de excepciones, puedes escribir código que detecte, maneje y recupere de manera controlada de estos errores.

	Se manejan mediante el uso de bloques 'try', 'catch', 'finally' y, opcionalmente, la cláusula 'throws' en la firma de los métodos.


	1. Bloque try y catch:

		El bloque 'try' se utiliza para contener el código que podría generar una excepción.

		Dentro del bloque 'try', puedes tener uno o varios bloques 'catch' que capturan y manejan excepciones específicas.

	```java

	try {
	    // Código que podría generar una excepción
	    // Por ejemplo, división entre cero
	    int resultado = 10 / 0;
	} catch (ArithmeticException e) {
	    // Manejar la excepción específica
	    System.out.println("Error de división por cero: " + e.getMessage());
	} catch (Exception e) {
	    // Manejar excepciones generales
	    System.out.println("Ocurrió una excepción: " + e.getMessage());
	} finally {
	    // Bloque opcional que siempre se ejecutará, ocurra o no una excepción
	    System.out.println("Este bloque siempre se ejecuta.");
	}

	```

	Si ocurre una excepción durante la división entre cero, el control se transfiere al bloque 'catch' correspondiente (ArithmeticException). 

	Si no coincide con el tipo de excepción esperado, se intentará con el siguiente bloque 'catch'. 

	El bloque 'finally' se ejecutará siempre, independientemente de si se produjo una excepción o no.


	2. Cláusula throws:

		La cláusula 'throws' se utiliza en la firma de un método para indicar que el método puede lanzar ciertos tipos de excepciones. 

		Los métodos que lanzan excepciones deben declarar las excepciones usando throws o manejarlas internamente con bloques try-catch.

	```java

	public void miMetodo() throws MiExcepcion {
	    // Código que podría lanzar la excepción MiExcepcion
	    if (condicion) {
	        throw new MiExcepcion("Ocurrió un error");
	    }
	}

	```

	'miMetodo' puede lanzar una excepción de tipo 'MiExcepcion'.
	
	Quien llame a este método deberá manejar esta excepción o declararla en su propia firma usando 'throws'	


	3. Excepciones Personalizadas

		Puedes crear tus propias excepciones personalizadas extendiendo la clase Exception o alguna de sus subclases. 

		Esto te permite definir excepciones específicas para tu aplicación.

		```java

		class MiExcepcion extends Exception {
		    public MiExcepcion(String mensaje) {
		        super(mensaje);
		    }
		}

		```

		Luego, puedes lanzar y manejar instancias de esta excepción en tu código.

		```java

		try {
		    throw new MiExcepcion("Ocurrió un error personalizado");
		} catch (MiExcepcion e) {
		    System.out.println("Manejando MiExcepcion: " + e.getMessage());
		}

		```


	El manejo de excepciones permiten escribir código que pueda anticipar y gestionar situaciones excepcionales, mejorando la robustez y la fiabilidad de tus programas. 

	Es crucial para desarrollar software que pueda responder adecuadamente a condiciones imprevistas durante la ejecución.



|| Buenas prácticas para Objetos






|| File class





