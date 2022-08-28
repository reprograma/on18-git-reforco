# O que aprendemos sobre Git e Github até o momento

Linha de comando, é uma aplicação de texto para ver e manipular arquivos em seu computador. É como o Windows Explorer ou o Finder no Mac, mas sem a interface gráfica.
O Git é um sistema de controle de versão distribuído e amplamente adotado.
GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle.

## _Configuração do git_

$ git config --global user.email "meuemail@gmail.com"

// Listar todas as configurações
$ git config --list

// Criar um repositório local
$ git init

// Verificar arquivos
$ git status

// Adicionar um arquivo
$ git add arquivo.txt


// variações do git add
$ git add  --all
$ git add  -a
$ git add  .


// Salvar e rastrear uma alteração
$ git commit -m "Frase curta explicando a modificação realizada"
 
// Verificar históricos de alterações
$ git log

// Clonar repositório 
$ git clone

// Verificar status dos arquivos 
$ git status

// Verificar modificações
$ git diff

// Adicionar arquivos
$ git add arquivo.txt

// Fazer commit
$ git commit -m "primeiro commit"

// Enviar para repositório remoto
$ git push
ou
$ git push origin main

// Enviar para repositório remoto

🚨 Atenção: se na seu repositório local a branch principal é master, atualize para main para que o push no repositório que você criou e clonou funcione  🤗
 git checkout -b main
$ git branch -M main
$ git push -u origin main


- ✨Magic ✨
