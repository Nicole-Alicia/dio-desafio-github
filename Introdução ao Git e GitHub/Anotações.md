# Índice

[Comandos Básicos de Terminal](#Comandos-Básicos-de-Terminal)

[Comandos Diferentes de Cada OS](#Comandos-Diferentes-de-Cada-OS)

[Comandos do Git](#Comandos-do-Git)



# Comandos Básicos de Terminal

##### Esses comandos funcionam igualmente para todos os Sistemas Operacionais

Para entrar em uma pasta ----> **cd <nome pasta>**  

Para sair da pasta (voltar para a pasta anterior) -----> **cd ..**  

Para criar uma nova pasta ------> **mkdir <nome da nova pasta>**  

Para criar um novo arquivo ---------> **echo > <nome do novo arquivo.extencao>**



# Comandos Diferentes de Cada OS

##### Esses são comandos de terminal que variam de acordo com o Sistema Operacional de cada compuatador 

Comando para listar os arquivos dentro de uma pasta:

* Windows -----> **dir**
* Linux/Apple --------> **ls**  

Comando para limpar o terminal:

* Windows -------> **cls**
* Linux/Apple --------> **clear** ou **CTRL + L**  

Comando para apagar arquivos no *Windows* ------> **del <nome arquivo>**

Comando para apagar pastas com tudo o que tem dentro delas no *Windows* ---> **rmdir <nome pasta> /S /Q**   

No *Windows* podemos usar o atalho **TAB** para auto completar o que estamos escrevendo no terminal

Comando para apagar pastas e arquivos no *Linux* e *Apple* -----> **rm - rf <nome pasta>/**  



# Comandos do Git

Para inicializar o git no repositório ----> **git init**  

Para ver o status dos arquivos -------> **git status ** 

Para mudar os arquivos para staged ------> **git add <nome arquivo ou nome pasta>**  

Para mudar _todos_ os arquivos modificados para staged ----> **git add *** ou **git add .**   

Para tirar o arquivo da área de staged -------> **git restore --staged <nome arquivo>** 

Para fazer o commit ---------> **git commit -m "<mensagem>"**  

Para colocar os arquivos em um repositório remoto ----> **git remote add origin <link>**  

Para "empurrar" o repositório do computador local para o Git Hub ----> **git push origin master**  

Para "puxar" o repositório do Git Hub para o computador local -------> **git pull origin master**  





