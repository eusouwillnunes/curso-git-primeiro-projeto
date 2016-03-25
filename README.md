# Code Education - Curso de Git
## Primeiro Projeto

Olá pessoal, este é o meu primeiro projeto desenvolvido utilizando o Git. Está sendo desenvolvido através do curso de Git da Code Education. Aqui vou listar os principais comandos para a criação e manutenção do repositório.

### Inicializando o Repositório
Navego até a pasta raiz do repositório e utilizao o comando:

    git init

    ### Criando Arquivos no Branch Master
    Criei aqui dois arquivos. O **OlaMundo.txt** e o **Teste.txt**

    ### Verifico estado dos arquivos.
    Aqui verificarei como estão os arquivos do projetos.

        git status
	    
	    Percebo que os dois arquivos criados anteriormente ainda não fazem parte do versionamento.

	    ### Adiciono os arquivos ao Controle de Versão

	    Utilizo o comando abaixo para adicionar todos os arquivos ao controle de versão.

	        git add .
		Agora os arquivos estão preparados para serem comitados.

		### Realizando commit de todos os arquivos.
		Utilizando o comando abaixo faço o commit de todos os arquivos preparados para serem comitados.

		    git commit
		    Uma tela de meu editor de texto é aberta para que eu digite as informações do commit.
		    Após ter digitado as informações e salvado o arquivo posso sair e o commit está pronto.

		    ### Criação do Repositório no GitHub
		    Agora preciso enviar o meu repositório local para o GitHub. Primeiramente, acesso minha conta no GitHub, procuro por **Repositories** e então clico em **New**. Crio então o repositório **curso-git-primeiro-projeto**

		    ### Adicionando Repositório Remoto ao Meu Projeto
		    Nesta etapa, preciso informar para o Git que eu vou sincronizar o projeto com o repositório criado no GitHun, para isso utilizo o comando: 

		        git remote add origin https://local_do_repositório
			    
			    ### Enviando Arquivos para Repositório Remoto
			    Agora preciso enviar meus arquivos para o repositório remoto. Utilizo para tanto o comando:

			        git push origin master

				### Adicionando o Arquivo README para que você veja este texto
				Criei um arquivo README.md com instruções escritas em Markdown, posteriormente adicionei o arquivo ao controle de versão, commitei e fiz um novo push.
