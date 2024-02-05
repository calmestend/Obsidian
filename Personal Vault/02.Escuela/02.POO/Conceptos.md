Entidad independiente
- Atributos
- Comportamiento

**Abstracción funcional**: Función para realizar una tarea pero sin la necesidad de saber como se lleva a cabo.

**Abstracción de datos**: Define el tipo de dato que puede llevar el atributo.

## Ejemplo 1:

	> Objeto: Gorra
	> Abstraccion funcional (Metodos):
		- Proteger
		- Calentar
		- Vestimenta
	> Abstraccion de datos (Atributos):
		- Color -> String
		- Forma -> String
		- Diseno -> String
		- Logotipo -> String
		- Peso -> Float
		- Marca -> String

## Ejemplo 2:
		> Objeto: Computadora
		> Abstraccion funcional (Metodos):
			- Procesar
			- Guardar
			- Calcular
			- Comunicar
			- Visualizar
			- Compilar
		> Abstraccion de datos (Atributos):
			- Marca -> String
			- Diseno -> String
			- Peso -> Float
			- Tamano -> Float
			- OS -> String
			- Color -> String

# Clase

*Modelo o Prototipo*
- Variable
- Método 

```java
public class Computadora {
// Atributos
	String marca;
	String diseno;
	float peso;
	float tamano;
	String sistemaOperativo;
	String color;

// Metodos
/*
	Procesar, Guardar, Comunicar, Visualizar, Compilar.
*/
	public void procesar() {
		System.out.println("Estoy procesando");
	}
	public void guardar() {
		System.out.println("Estoy guardando");
	}
	public void calcular() {
		System.out.println("Estoy calculando");
	}
	public void comunicar() {
		System.out.println("Estoy comunicando");
	}
	public void visualizar() {
		System.out.println("Estoy visualizando");
	}
	public void compilar() {
		System.out.println("Estoy compilando");
	}

	public static void main(String[] args) {
		Computadora miComputadora = new Computadora();
		miComputadora.procesar();
		miComputadora.guardar();
		miComputadora.calcular();
		miComputadora.comunicar();
		miComputadora.visualizar();
		miComputadora.compilar();
		miComputadora.peso = 5.2f;
		System.out.println(miComputadora.peso);
	}
}

```
# Como es que compila?

| Lenguaje de programacion -> | Lenguaje maquina -> | Se crea un espacio en memoria-> | Se ejecuta |
|-----------------------------|---------------------|-----------------------|------------|
| Java | x86 / ARM | Memoria ROM o RAM | public static void main(String[] args) {} |

## Requerimientos funcionales.
Un requisito funcional define una función del sistema de software o sus componentes. Una función es descrita como un conjunto de entradas, comportamientos y salidas. 

