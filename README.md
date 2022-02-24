--Anotações das aulas da B7Web de GIT---

Git/GitHub
O que é, pra que serve, como funciona?
Versionamento
-para voltar se o programa der problema;
-Trabalho em equipe

--------------------------------------------------------------------------------
Configurações iniciais
C:\WINDOWS\system32>git config --global user.name "Afranio Cruz"

C:\WINDOWS\system32>git config --global user.email "afranio.af1.web@gmail.com"

C:\WINDOWS\system32>git config --global core.editor "Vs code"

----------------------------------------------------------------------------------
Verificar qual usuário:
>git config user.name
----------------------------------------------------------------------------------
Comandos básicos CMD
dentro da pasta modulogit (pasta do projeto) digitar 
>git init
para ver as mudanças
 >git status
adicionar monitoramento 
>git -A
criar um commit 
>git commit -am "nomeDoComnit"
----------------------------------------------------------------------------------
Mostrar os commits criados
>git log
----------------------------------------------------------------------------------
Para saber em qual commit estamos
>git branch
----------------------------------------------------------------------------------
Voltando para um commit 
> git reset --hard/soft numero do commit
*hard: apaga todos os arquivos
*soft: mantem os arquivos preparado para um novo commit
----------------------------------------------------------------------------------
Criar um novo branch
>git branch nomeBranch
----------------------------------------------------------------------------------
Mudando de branch
>git checkout nomeBranch
----------------------------------------------------------------------------------
Para saber o que foi alterado exatamente
>git diff
----------------------------------------------------------------------------------
Para saber qual arquivo foi modificado
>git diff --name-only
---------------------------------------------------------------------------------
Para saber apenas o que foi alterado em determinado arquivo
>git diff nomeDoArquivo.xxx
---------------------------------------------------------------------------------
Para desfazer/retornar as alterações de determinado arquivo
>git checkout HEAD -- nomeDoArquivo.xxx
*HEAD - pega dentro do branch atual.
----------------------------------------------------------------------------------
Criação do usuário e senha
----------------------------------------------------------------------------------
Enviado os arquivos para o git remoto
Gereando as chaves
>ssh-keygen -t rsa -b 4096 -c "afranio.af1@gmail.com"
-copiar a chave publica e colar no github
-comando para enviar os arquivos: 
>git push -u origin master
------------------------------------------------------------------------------------
Fazendo alterações no repositório remoto
1. Fazer commit dos arquivos alterados no repositorio local
2. Fazer o Push -> git push origin master  





