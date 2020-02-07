
## Treinamento para projetos GPDS

Este repositório oferece um treinamento básico das principais ferramentas que são utilizadas nas pesquisa realizadas no Grupo de Processamento Digital de Sinais (GPDS). O conteúdo pode (DEVE), ser usado para consulta e sempre melhorado, fique à vontade para fazer seu **pull request** com alterações, sugestões e etc.

### Linux

Lista de comandos para usar no terminal linux. Para abrir o terminal **tecle** `ctrl + alt + t` e use os seguintes comandos.   

Listando conteúdo de uma pasta:
	
	ls

Comandos para entrar e sair de uma pasta, respectivamente:

	cd nome_da_pasta
	cd ..

Criando uma nova pasta:

	mkdir nome_da_nova_pasta

Criando um novo arquivo:

	touch nome_do_novo_arquivo

Deletando arquivo:

	rm -rf nome_do_arquivo

Renomeando arquivo:

	mv arquivo_antigo artigo_novo

Copiando arquivos:

	cp arquivo outra_pasta/arquivo_copia	

Ver o path em que você está:

	pwd

### Github

O Github é uma poderosa ferramenta para quem vai trabalhar com códigos e em equipe, pois permite controle eficiente de versões do código além de possibilitar um fluxo de trabalho distribuído e fluído entre integrantes da equipe de desenvolvimento.

#### Instalando Github

No Linux (Ubuntu), basta digitar a seguinte linha no terminal:

	sudo apt-get install git

No Windows , baixe o arquivo disponível no site [gitforwindows.org](https://gitforwindows.org/), e siga o passo a passo. [Neste link](https://woliveiras.com.br/posts/instalando-o-git-windows/), há um tutorial explicando cada passo.

#### Criando conta

Crie uma conta no [site github](https://github.com/), é fácil e só precisa de um email e senha. Você também já pode configurar sua máquina, no terminal digite os seguintes comandos:

	git config --global user.name "Seu nome aqui"
	git config --global user.email "seu_email_aqui@email.com"

#### Criando repositório

Um repositório é como uma pasta no Github, no qual você colocará todos os arquivos da sua aplicação, explicações, licença, documentação e etc. Você pode criar pelo termina, porém é mais prático utilizar o site. Após logar no site do Github, no canto superior direito, há um sinal de **+** (próxima imagem), basta selecionar a opção **Novo repositório**, o restante é intuitivo.



> Tente evitar espaços, utilize underline (**_**) para separar as palavras, ex: meu_repositorio, ou letras maiúsculas para começar uma nova palavra, ex: meuRepositorio

![criando repositório](https://raw.githubusercontent.com/JoseRaimundo/treinamento_projeto_ecg_gpds/master/img/novo_repositorio.png)


##### Branchs

#### Clonando repositório

#### Subindo alterações


#### Sincronizando alterações

#### Documentando no README

### Python

!IMPORTANTE: Esse é apenas um tutorial básico, com as ferramentas mais usadas, para mais aprofundamentos acesse as documentações de referência no final de cada explicação.

#### Instalação

Apesar de haver versões mais recentes, é recomendado que instale uma das versões 3.5 - 3.7 do Phyton, pois são mais estáveis e com maior compatibilidade com aplicações e bibliotecas.

Para instalar no Ubuntu, use os comandos:

	sudo apt-get install python3.6
	sudo apt-get install python3-pip

O **pip** é uma ferramenta do python que ajuda na instalação de bibliotecas. 
 
#### Estrutura de Pastas de Projetos

Antes de começar a "codar", é bom organizar bem suas pastas e arquivos, uma alternativa para estrutura de projeto pode ser da seguinte forma:

	PastaDoProjeto
	--- main.py
	--> src
		 |--- funcao1.py
		 |--- funcao2.py	
	--> dataset
		 |--- dados.csv
	--> output
		 |--- graficos.png
		 |--- log.txt
	--- README.md

Explicando: 

 - A **PastaDoProjeto** é onde ficará tudo, também é a pasta que representará seu repositório no **github**.
 - **main.py** é o arquivo principal, que é executado antes de qualquer coisa.
 - Na pasta **src** fica o restante dos seus códigos: funções, classes, outras pastas.
 - Na pasta **dataset** fica seu banco de dados, arquivos do tipo xls, csv e etc. São os dados que sua aplicação irá usar.
 - Na pasta **output** fica as saídas do seu programa, gráficos, anotações de resultados, arquivos de relatórios (log) e etc.
 - Ainda dentro da pasta principal, temos o arquivo **README.md** que contém as instruções que irão aparecer no github. 

Esta estrutura de pastas não é uma regra geral, porém ela é simples e bem clara, o que ajudará para que outros pesquisadores entendam melhor o seu código/programa.

Exemplo: 

Crie uma estrutura de arquivos conforme explicado anteriormente

#### Numpy


#### Pandas
#### Plotagem

### Machine Learning
#### Sklearn
#### Tensorflow

### Desafios
