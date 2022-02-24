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

C:\WINDOWS\system32>git config user.name
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
*HEAD - pega dentro dod branch atual.
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





