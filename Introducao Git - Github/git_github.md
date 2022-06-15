 GIT	(https://git-scm.com/)
 ------------------------------

Versionador de programas

## Instalação do GIT
	Para verificar se o GIT está instalado no equipamento:
    
    	git --version
        
        Efetuar o download do GIT
        
        Instalar o GIT
        
        git --version, mostrará a versão do GIT instalado no equipamento
        
   

##CICLOS GIT

Untracked			Unmodified			Modified			Staged

adiciona arquivo -------->
					Edita arquivo --------->
										git add * -------------->

							<-----------------------------git commit -m "<texto versao>"
							
git init		--> inicia um repositorio vazio /.git (diretório oculto - Pasta gerencial do GIT)

	
git config --global user.email "reynaveiro@gmail.com"
git config --global user.name SBIGNIFF

	Para utilizar o git é necessário um usuário e senha
	
git config --global --unset user.email
git config --global --unset user.nickname
git config --global --unset user.name
	
	Reset nestas variáveis no GIT, interessante ficar com os mesma configuração do GITHUB

git remote add origin https://github.com/areynaveiro/livro-receitas.git	
	
	Configurando o repositorio remoto para o projeto

	"origin" --> alias, poderia ser qualquer outro nome
	
git remote -v

	Mostrara todos os repositorios remotos cadastrados

git pull --rebase

	Atualizará os programas alterados por outros desenvs no repositório remoto para o seu repositório local.
    
git push origin master

	Enviar os arquivos do repositorio local para o remoto
	
	Sera solicitado a senha no GITHUB

	Caso esteja tudo bem configurado, basta executar o comando git push

git clone <link_repositorio>

	Baixara o projeto no repositorio local
	
	
git add *

	Adicionar as alterações para o Commit geralmente em vermelho, após o add, as alterações ficarão em verde, possibilitando a execução do git commit.
    
	
git commit -m "<texto versao>"

	Commit das alterações, neste momento é informado o sha1	(secure hash algorithm em inglês)
	
git status
		
	Traz informacoes da Branch atual e se ha arquivos para commit
	
git restore <nome arquivo>

	Voltara o arquivo para a versao anterior de acordo com o controle GIT

git config --list

	Mostrara as configuracoes atuais
	
git checkout <branch> 
	
	Mudará o ponteiro para a branch mencionada
	
###Para voltar uma determinada versão
	git log --> pegar o hash
	git checkout <hash>

###Para descartar as alterações

	git restore <file>... to discard changes in working directory

###Faça com que o Git armazene o nome de usuário e a senha e ele jamais pedirá por eles novamente

	git config --global credential.helper store

###Salvar o nome de usuário e a senha por uma sessão (colocá-los em cache)

	git config --global credential.helper cache

###Também é possível definir um tempo de expiração (timeout)

	git config --global credential.helper 'cache --timeout=600'


###Remover configuração Inicial

	git config <escopo> --unset credential.helper

	Onde o <escopo> pode ser --local, --global ou --system.

###Deletar Branch

	git checkout feature... (muda de branch)
	git push origin --delete <nome do branch> (deletar a branch) 

	
GIT Bash
--------
Terminal extendido para otimizar o uso do GIT.

		
Comandos Unix utilizados no GIT:	
	
	
pwd				--> diretorio que se encontra
ls				--> mostra conteudo do diretorio	
ls -a 			--> mostra diretórios ocultos
mv 				--> mover arquivos
echo > <arquivo>--> cria arquivo
 


GITHUB (https://github.com/)
-----------------------------------------------------------------------------------------------------------------
areynaveiro@gmail.com
SBIGNIFF1a
areynaveiro

Repositório remoto dos programas

Se cadastrar como estudante

criar um novo repositorio para o projeto

No box push, copiar o endereco html para configurar no GIT


