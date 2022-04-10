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

	public
		Qualquer classe de qualquer pacote poderá acessar o 
		atributo ou método.
	
	protected
		Qualquer classe definida no mesmo pacote ou subclasse.
	
	Sem modificador
		Apenas classes definidas no mesmo pacote.
		
	

Métodos
	São funções que definem o comportamento de uma classe.
	
	Tipos de métodos:
	
		Contrutores
			Definenm como uma classe será instanciada "construída".
			
		Comum
			Definem comportamentos que podem ou não estar atribuídas
			às regras de negócio.
			
			Exemplo: calcular taxas de um pedido, etc...
			
		
Estrutura de Condição
	Responsável por fazer o desvio do fluxo de execução do código
	de acordo com uma condição.
	
	Tipos de estruturas de condição:
	
	if - else
		// metodo
		public double calculateFee() {
		
			if(this.totalValue > 100) {
				return this.totalValue * 0.99;				
			} else {
				return this.totalValue;
			}
			
		}
		
	switch - case
	
		public double calculateFee() {
		
			switch (this.totalValue) {
				case 100:
					return totalValue * 0.99;
				case 200:
					return totalValue * 1.99;
				default:
					return totalValue;				
			}
		}
	
Estrutura de Repetição
	Responsável por executar repetidamente uma instrução ou um
	bloco de instruções, até uma condição estiver sendo satisfeita.
	
	Tipos de estruturas de repetição:

	while
	
		public void printItens() {
		
			int i = 0;
				
			while (i < itens.length) {
				
				System.out.println(itens[i]);
				i++;
				
			}
				
		}
	
	do - while

		public void printItens() {
		
			int i = 0;
				
			do {
				
				System.out.println(itens[i]);
				i++;
				
			} while (i < itens.length)
				
		}
	
	
	for
	
		public void printItens() {

			for (int i = 0; i < itens.length; i++) {

				System.out.println(itens[i]);

			}
		}
		
	enhanced for
	
		public void printItens() {
	
			for (String i : itens) {
			
				System.out.println(i);

			}
		}
		
		
		