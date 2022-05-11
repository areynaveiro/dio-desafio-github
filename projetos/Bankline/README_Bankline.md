#Projeto Bankline
##Arquitetura
Desenvolvida na arquitetura do Spring Framework + Springboot estruturado no padrão MVC para prover uma API Rest para movimentações financeiras simples.

### Spring Framework
Estruturado em dois pilares:
* Inversion of Control ou IoC

	Trata-se do redirecionamento do fluxo de execuçãp de um código retirando parcialmente o controle sobre ele e delegando-o para um container. Principal propósito é minimizar o acoplamento do código.

* Injeção de Dependência

	Padrão de desenvolvimento com a finalidade de manter baixo o nível de acoplamento entre módulos de um sistema.

### Springboot
Enquanto que o Spring Framework é baseado no padrão de injeção de dependências, o Springboot foca na configuração automática, é a evolução do Spring Framework.

	Starters (spring-boot-starter-*)
    	data-jpa: Integração ao banco de dados via JPA-Hibernate.
        
        data-mongodb: Integração com o banco de dados MongoDB.
        
        web: Inclusão do container Tomcat para aplicações REST.
        
        web-services: Webservices baseados na arquitetura SOAP.
        
        batch: Implementação de JOBs de processos.
        
        test: Disponibilização de recursos para testes unitários como JUnit.
        
        openfeign: Client HTTP baseado em interfaces.
        
        actuator: Gerenciamento de monitoramento da aplicação.
    	

    
### JAVA EE x Spring

Possuem o mesmo propósito e hoje o Spring é mais utilizado, por questões de mais recursos, menos burocracia que o JAVA EE.


    

