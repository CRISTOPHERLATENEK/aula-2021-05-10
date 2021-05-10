#projeto para entender como as branches funcionam

#gitbranche master ou main


É a branch principal do repositório, é a partir dela que
nosso sitema será entregue para os clientes.

o 'git' usa o nome da branch como master o 'github' como main.

para converter use ''git branch -M main'' depois que fizer o primeiro commit a partir do repositório criado com o ''git init''

#manipulação

Para Listar use :

$ git branch --list

Para Excluir uma branch 

$git branch -d nome_da_branch

Para Alterar o nome de uma branch

$git branch -m nome_da_branch
