# Comandos Basicos
## Inicio
- abrir terminal gitBash
- criar uma pasta
## Identicar usuario com git
- git config --global user.name "Seu nome  e sobre"
- git config --global user.email "Seu nome email"
- git config --global color.ui true
## Criar repositorio
## Tres estagios

### Criar pasta: 
-mkdir trinagit
### Entrar na pasta
-mkdir trinagit
#### Comandos:
- git init -> associação a pasta ao git repositorio
- usar editor, exemplo vscode
#### Entrar VsCode:
- code .
- criar arquivo com nome treinagit ou outro  nome

### Vamos ver os stagios

##### 1-Untracked files
- arquivos não versionados pelo git

###### git add
-  incluir arquivos para commit
- git add arquivo1, arquivo2,  ...
- git add . -> adiciona todos os arquivos

##### 2-Changes to be committed
- Após o comando Add os arquivos ficaram prontos para serem comitados pelo git.

- Gera um hash a uma identificação.

##### 3-Após o comando commit os arquivos são commitados

##### git commit -m "nome_arquivo"

- podemos ver como  estão os arquivos usando:

- git status
- git log

#### Alterar o aquivos, gravar

- der git status - o arquivo vai para fase staged, ou seja, foi, ele está no controle de versão, porém foi alterado, é preciso, usar add e commit

- der git add nome arquivo - volta para pronto para commit

- der git commit -m "alterado para teste e comitar"

