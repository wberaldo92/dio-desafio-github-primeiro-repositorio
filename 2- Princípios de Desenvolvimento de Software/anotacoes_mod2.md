
# Princípios de Desenvolvimento de Sotware :computer: <h1>

Olá! Bem vindo ao meu book de anotações :wave: :smile: :blue_book:
 
![Tuxy, GitHub mascot](/assets/images/GitHub.jpg)

## 1- Pensamento computacional 15/09/2022 :loudspeaker:
* Pilares: Decomposição
* Pilares: Padrões
* Pilares: Abstração
* Pilares: Algoritmos

* Estudo de caso conceitual: perdido

* Estudo de caso aplicado: Soma de um intervalo

* Estudo de caso aplicado: Adivinhe um número

## 2- Introdução a lógica de programação pg 210 :trident:
* O que é lógica?

### Técnicas de lógica de programação :slot_machine:
* Técnicas: Linear; estruturada e modular

* Tipologia e variáveis

* Instruções primitivas

* Estruturas de repetição

* Vetores e matrizes

* Algoritimos em portugol

## Introdução ao Git e ao GitHub :smile_cat:
### Entendendo o que é GIT e sua importância

### Navegação via command line interface e instalação
Comando basicos para um bom desempenho no terminal
* git não tem interface grafica
Comandos
* dir (windows) ls (linux) -> lista de diretorios de todas as pastas
* cd / -> vai para a raiz da pasta
* cd windows -> abre a pasta
* cd .. -> volta uma pasta
* cls (windows) clear (linux) -> limpa a pasta
* cd win aperta tab q preenche o resto
* mkdir workspace (cria a pasta workspace) se nao aparece msg é pq deu certo
* echo hello > hello.txt -> direciona o texto hello criando um arquivo hello.txt
	* >del
	* >rmdir workspace /S /Q -> remove o dispositorio
* rm -rf workspace (linux) -> remove o dispositorio

* cd mudar de diretorio
* dir ou ls
* mkdir - criar diretorios
* del / rmdir ou rm -rf - deletar os arquivos

## Realizando a instalação do GIT :mag:

## Tópicos fundamentais para entender o funcionamento do Git :loop:
* SHA1
	* Algoritimo de hash seguro
	* conj de caracteres de 40 digitos
* Objetos fundamentais
* Sistema distribuido
* Segurança

## Objetos internos do Git :cd:
* Blobs - guarda o sha dos arquivos
* trees - armazena os blob; aponta para um blob; guarda as estruturas; uma tree aponta p/ outra tree
* commits - obj que junta tudo; aponta para a tree, parente e o autor; ele da um significado para todos os dados; O SHA1 desse commil é o hash de toda a essa info
* Sistema distribuido seguro - 

## Chave SSH e Token :crystal_ball:
* Chave SSH - conexao segura e encriptada entre duas maquinas; duas chaves, publica e privada; 
* cat id_ed25516.pub -> Para visualizar o conteudo das chaves
* pwb -> Mostra o caminho completo de qual pasta vc ta no git bash
* eval $(ssh-agent -s) -> Cria um agente que fica responsável de cuidar das chave (o nº gerado varia, é como se estivesse startando um projeto pra rodar em um plano de fundo
* ssh-add id_ed25519 (como no exemplo do curso nos já estamos na pasta .ssh que contem o arquivo que vai receber a info, usa-se esse script)-> Entregar a chave privada para o agente add pq toda vez que chegar uma criptografia com essa chave ele vai usar essa chave privada para descriptografar essa mensagem
* Clonar um repositorio (git@github.com:wberaldo92/wberaldo.git
	* Não fiz pq ele disse que estava copiando um diretorio de site que ele ja tem e como ele nao ensinou a criar um diretorio do zero, nao fiz

## TOKEN DE ZCESSO PESSOAL - segunda forma de autenticação segura que o github fornece :minidisc:

### Iniciando o Git e criando um commit
### Primeiros comando com o GIT
### Iniciar o GIT
### Iniciar o versionamento
### Criar um commit

* git init - iniciar o repositorio do git
* git add - mover os arquivos
* git commit - criar o commit
* Quando estamos lidando com o terminal, colocamos sempre na frente o nome do programa, exemplo do git "alguma coisa"

## CRIANDO UM REPOSITORIO :bulb:
* ls -a -> Ver pastas ocultas
* Como é a primeira vez que vai mexer com o git, precisamos realizar algumas confirgurações iniciais com base em um autor para ficar atrelado (user name e email)
* git config --global user.email "wellington.beraldo92@gmail.com"
* git config --global user.name Wberaldo

## ADICIONANDO UM ARQUIVO :unlock:
* Markdown
* Navegador
* HTML
* Arquivos .md (Markdown)
* m é um flag git commit

* Local dos arquivos da aula: C:\workspace\livro-receitas

NOTA: USAR USER.NAME AO INVES DE USER.NICKNAME

## Passo a passo no ciclo de vida :floppy_disk: <h2>
* GIT INTI
* GIT STATUS
* MV - mover
* GIT ADD * -> Pega tudo que foi modificado, td que esta na workdirect, diretorio de trabalho e adiciona para o staged p/ comitar

* git add strogonoff2.md  receitas/
* git commit -m "cria pasta receitas, move arquivo para receitas"
* echo > README.md
* git commit -m "adiciona index"

## Trabalhando com o GitHub :mortar_board:
* git config --list -? -> verifica as config da pasta
* git config --global --unset user.name -> Remove o atributo unser.name
* git config --global user.name "wberaldo92" -> Adiciona o atributo

### Empurrar a versão do nosso repositorio local para o repositorio remoto (add primeiro a origem)
	* git remote add origin https://github.com/wberaldo92/livro-receitas.git

### Listar a lista de repositorios que temos cadastrados
	* git remote -v

### Enviar o código que alteramos no PC para o GitHub (empurrado por isso do push)
	* git push origin master

## Como os conflitos acontecem no GitHub e como resolvê-los :dart:

### Puxar as alterações que estao no github para o seu PC
	* git pull origin master
	* vc abre o arquivo, faz as alterações e salva
	* git status
	* git add *
	* git commit -m "resolve conflitos"
	* git push origin master

### Clonar um repositorio do GitHub
	* git clone cola_aqui_HRL

### Mostra repositórios ocultos
	* ls -a


 ## Links Úteis :link:
[Treinar Raciocínio Lógico](https://www.google.com/search?q=treinar+racioc%C3%ADnio+l%C3%B3gico&oq=treinar+rac&aqs=chrome.1.69i57j0i22i30l2j0i15i22i30j0i22i30l6.2671j0j7&sourceid=chrome&ie=UTF-8) <br>
[Algoritimos em portugol](https://portugol-webstudio.cubos.io/) <br>


