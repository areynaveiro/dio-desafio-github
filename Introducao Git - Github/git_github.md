 GIT	(https://git-scm.com/)
 ------------------------------

Versionador de programas


CICLOS GIT

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
	
git push origin master

	Enviar os arquivos do repositorio local para o remoto
	
	Sera solicitado a senha no GITHUB


git clone <link_repositorio>

	Baixara o projeto no repositorio local
	
	
git add *

	Adicionar as alterações para o Commit
	
git commit -m "<texto versao>"

	Commit das alterações, neste momento é informado o sha1	(secure hash algorithm em inglês)
	
git status
		
	Traz informacoes da Branch atual e se ha arquivos para commit
	
git restore <nome arquivo>

	Voltara o arquivo para a versao anterior de acordo com o controle GIT

git config --list

	Mostrara as configuracoes atuais
	
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

