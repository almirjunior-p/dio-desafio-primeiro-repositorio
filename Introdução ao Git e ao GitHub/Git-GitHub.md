# O que é o Git e o GitHub

### O que é o Git

Estes sistemas de controle possuem a função de registrar quaisquer alterações feitas em cima de um código, armazenando essas informações e permitindo que, caso seja necessário, um programador possa regredir a versões anteriores de uma aplicação de modo simples e rápido, basicamente um programa que possibilita o dimensionamento de códigos, seus principais benefícios são controle de versão, upload dos arquivos fonte em um servidor nuvem,  trabalho em equipe uma vez que um grupo determinado de pessoas vão ter acesso ao um arquivo simultaneamente, aprimoramento do código fonte e reconhecimento.

### O que é o GitHub

O GitHub sim muita relação com o Git. GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. Ele vai facilitar o uso do Git, escondendo alguns detalhes mais complicados de setup. É lá que você provavelmente vai ter seu repositório e usar no dia a dia.

### Instalação do Git

O passo a seguir para a instalação são como qualquer outro programa, sendo necessários somente algumas mudança no momento da instalação, algumas alterações devem ser feitas de acordo com o sistema operacional da maquina que esta sendo feita a instalação para melhor compatibilidade e evitar erros, segue o links uteis e as opções baseadas em um sistema operacional Windows 10 64bits.

##### Links

[Git Última Versão](https://git-scm.com/download/win) 

[Git versão 2.33.02 Usada no curso de "Introdução ao Git e ao GitHub"](https://www.npackd.org/p/git64/2.32.0.2)

A instalação segue padrão como qualquer outra, após o download do arquivo basta encontra-ló no diretório em que o arquivo foi salvo e iniciar a instalação, segue avançando deixando como padrão as opções já selecionadas, faça alterações somente nas opções em destaque a seguir.

##### Opções a serem marcadas para o sistema operacional Windows 

![](https://github.com/almirjunior-p/dio-desafio-primeiro-repositorio/blob/main/img/Screenshot_2.png)

"Git Credential Manager", refere-se a um gerenciador de credenciais que realizam a autorização da  comunicação entre o Git e o GitHub, evitando erro ao tentar o envio de alguma atualização do seu código fonte, essa opção estava disponível na versão 2.33.02, mas foi removida nas versões mais recentes.

### Comandos Básicos 

Como o Git é um ferramenta que opera em um Interface de Linha de Comando (CLI - *Command Line Interpreter*), nós não temos um interface tão intuitiva como um gráfica, sendo feito todo o trabalho em linhas de comandos, segue alguns comandos  básicos para seu funcionamento e utilização:

- **ls** - Lista pastas e arquivos no diretório atual
- **cd** - Função para ir até um diretório especificado
- **cd..** - Sobre um diretório, retornando uma pasta
- **Ctrl+l** - Conjunto de teclas que realiza a limpeza do painel
- **mkdir** - Cria uma pasta no diretório atual
- **echo** - Quando usado sozinho volta uma mensagem no terminal, também possibilita a criação de arquivos

##### Comando para iniciar um Commit

- **git commit** - Inicializa um repositório vazio no diretório atual
- **git config** - git config --global user.email "E-mail usado para identificar quem fez a alteração ao enviar o commit"
- **git config** - git config --global user.name "Nome usado para identificar quem fez a alteração ao enviar o commit"
- **git add*** - Adiciona todos os arquivos do diretorio que foram feito alterações para o Stageged aguardando o commit
- **git commit** - git commit -m "Mensagem para identificar qual foi a alteração realizada"
- **git config** - git config --global unser user.(dados a ser alterado) "Serve para dar um reset na informação, podendo mudar suas informações que serão enviadas"



### Trabalhando com o GitHub, Comandos para realizar o "Push" do código fonte

Push (Empurra o versão do repositório local para um repositório remoto)

Após criar um repositório no GitHub que ira hospedar seu arquivos fonte, deve-se pegar o link do repositório, e então adiciona-ló ao GitBash usando os comandos a baixo:

- **git remote add** - git remote add **origin**(Apelido, usado como padrão origin) "link do repositório do GitHub"
- **git push origin master** - Usado para empurrar o repositório local para o remoto



### Como Clonar um repositório no GitHub

Após encontrar o repositório que deseja estar realizando a clonagem, basta copiar o link do repositório, vá até pasta raiz que ira receber o repositório, abre o GitBash no diretório e use o comando "git clone (link do repositório que deseja fazer a clonagem)", ira automaticamente começar a fazer a clonagem, caso seja a primeira fez realizando uma clonagem, ira ser solicitado que você faça uma autentificarão através do navegador padrão, solicitando login e senha para vincular a credencial.



### **Onde encontrar o Link de um repositório**

![](https://github.com/almirjunior-p/dio-desafio-primeiro-repositorio/blob/main/img/link-repositorio.png)





