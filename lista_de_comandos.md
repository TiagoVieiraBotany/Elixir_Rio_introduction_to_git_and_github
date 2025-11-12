# Lista de comandos

## Iniciando o git

`git init`

## Rotina básica para adicionar versão na linha do tempo

`git add <nome_do_arquivo>`

`git commit -m "mensagem significativa"`

`git status`

## Histórico de commits

`git log`

`git log -n`

`git log -abbrev-commit`

## Comparando commits

- git diff mostra as diferencas entre duas versoes (resumo)
`git diff <commit_ID1_old> <commit_ID2_new` 

- git show mostra modificacoes em ambas versoes de arquivo (completo)
`git show <commit_ID1_old> <commit_ID2_new`


## Estabelecendo uma conexão entre o Git (local) e GitHub (nuvem)

`git push --set-upstream origin main`


## Enviando ao github todas suas atualizacoes

`git push`