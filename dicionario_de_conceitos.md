# Dicionário de Conceitos

- Git: Software de versionamento que cria uma linha do tempo. Anota as alterações nos documentos e scripts em uma "linha do tempo":

- Github: Software que executa o backup dessa "linha do tempo"

- Workflow básico do git: 1) "$ git add <file>"; 2) "$git commit -m "mensagem relevante"

### Nota sobre o Commit: 

- **Por quê** houve uma mudança?
- **Como** o problema foi resolvido?
- **Efeitos** causados pela alteração
- **Limitações** das atualizações

## Áreas conceituais do Git

- Área de desenvolvimento (development area): o diretório em seu computador, onde o projeto está sendo desenvolvido e os arquivos associados sao armzenados

- Staging area: local onde organizo os arquivos antes do commit

- Repositório local (local repository): arquivo "hidden" que armazena toda linha do tempo de seu projeto git. É a minha linha do tempo, tambem representada pelo arquivo '.git'

### Sobre o git status

`git status`

- Indica qual o status de meus arquivos no meu diretorio git. No caso, indica os arquivos que nao foram 'add' ou 'commmit'

### Obs sobre o Staging area

- é onde eu vou acumulando meus arquivos, antes de dar o commit. Dessa forma posso dar commit em "blocos" de modificacao. Staging: acumular modificacoes em arquivos que, de alguma maneira, sao relacionados e que podem ter um 'commit' comum

### Obs sobre git push

<<<<<<< HEAD
- o `git push` lança para o GitHub suas atualizacoes feitas no Git. Antes de dar o comando, voce precisa estabelecer a conexao entre sua pasta do projeto e seu projeto no gitHub através de: `git push --set-upstream origin main`

### Obs sobre git pull

- assim como o push, trata de sincronizacao (tipo um rsync), mas agora no sentido contrario: da nuvem para o computador remoto/local

me lasqui, fiz merda e nao sei ainda como resolver aaaaaaaaaaaaaaaaaaaaaa desespero
=======
- o `git push` lança para o GitHub suas atualizacoes feitas no Git. Antes de dar o comando, voce precisa estabelecer a conexao entre sua pasta do projeto e seu projeto no gitHub através de: `git push --set-upstream origin main`
>>>>>>> parent of 896b293 (Adicionando informacoes sobre git pull no dicionario de conceitos e lista de comandos)
