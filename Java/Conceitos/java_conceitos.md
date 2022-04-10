Introdução ao Ecossistema e Documentação Java

Características da linguagem JAVA:

- Compilada

	Diferença do JAVA para as outras linguagens:
	
		Nas outras linguagens deve se criar uma compilação para cada Sistema Operacional.
		
		No JAVA a compilação criará um executável .class e cada Sistema Operacional
		terá a sua JVM, responsável pela tradução do código.

- Interpretada

- Fortemente tipada

- Linguagem de alto nível

	Orientada a objetos

- Executada em uma máquina virtual - JVM (Java Virtual Machine)

	Máquina virtual responsável pela tradução do BytesCodes oriundos 
	do compilador JAVAC (JAVA Compiler) em código de máquina de cada sistema.




					Compilação							Interpreção
Source File (.java) 	--> 	Bytecodes (.class) 			--> 		JAVA (JVM)

	Características:
		
		Execução de pilhas
		Gerenciamento de memória
		Gerenciamento de threads
		Otimização de código (Compilação  JIT - Just in Time)
		Garbage Collector (GC)
			Responsável pela limpeza da memória suja.
		
		
Diferença entree JRE e JDK:

	JRE (JAVA Runtime Environment) 
		Responsável pela execução dos programas JAVA.
		
	JDK (JAVA Development Kit)
		Utilitário que permite o desenvolvimento de programas em JAVA e
		já possui o JVM para execução dos programas. 
		
Tipos de plataformas JAVA:

JAVA SE (JAVA Standard Edition)
	Contém as especificações do JAVA e pode ser
	implementado por diversas empresas.

	
JAVA EE (JAVA Enterprise Edition)
	Contém  todas as implementações do JAVA SE e 
	um número de programas úteis para que executam em
	servidores. (Renomeada para Jakarta EE)

JAVA ME (JAVA Micro Edition)
	Contém especificações para desenvolvimento de 
	programas para dispositivos pequenos como celulares,
	PDA's entre outros.
		
		
Palavras Reservadas
	Como todas as linguagens de programação exitem algumas palavras
	que são reservadas ao JAVA e não podem ser definidas para dar um
	nome a classe, método, variável, etc...

Declaração de Classes

	   
	public class Order {
		// public --> modificador de acesso
		// class --> palavra reservada para definição de classe
		// <Nome> --> nome da classe representa o objeto iniciando com letra maiúscula
	
		//atributos
		private final String code;
		private final BigDecimal totalValue;
		
		//metodo
		public BigDecimal calculateFee() {
		
		}
	}

Modificadores de Acesso


Métodos


Estrutura de Condição

Estrutura de Repetição

		