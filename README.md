Git/GitHub
O que é, pra que serve, como funciona?
Versionamento
-para voltar se o programa der problema;
-Trabalho em equipe

--------------------------------------------------------------------------------
Configurações iniciais
>git config --global user.name "Afranio Cruz"

>git config --global user.email "afranio.af1.web@gmail.com"

>git config --global core.editor "Vs code"

----------------------------------------------------------------------------------
Verificar o usuário atual:

>git config user.name
Afranio Cruz
----------------------------------------------------------------------------------
Comandos básicos CMD
dentro da pasta modulogit (pasta do projeto) digitar >git init
--para ver as mudanças >git status
--adicionar monitoramento >git -A
--criar um commit >git commit -am "Primeiro Commit"
----------------------------------------------------------------------------------
Mostrar os commits criados
c:\Projetos\modulogit>git log
commit a03b10db6c179cfdb956b296359b36ae4206e9b7 (HEAD -> master)
Author: Afranio Cruz <afranio.af1.web@gmail.com>
Date:   Thu Feb 24 15:09:17 2022 -0300

    Primeiro Commit
---------------------------------------------------------------------------------
Para saber em qual commit estamos
c:\Projetos\modulogit>git branch
* master
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

