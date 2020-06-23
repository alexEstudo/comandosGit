# COMANDOS GIT

## PRIMEIROS COMANDOS - CONFIGURAÇÃO INICIAL

#### Definindo o Usuário
`git config --global user.name "nome_desejado"`

#### Definindo o E-mail do Usuário
`git config --global user.email "email_valido" `

#### Definindo o Editor principal
`git config --global core.editor o_comando_editor` 
Por padrão o editor é o vim / vi .

#### Listar configurações
`git config --list`

#### Listar somente nome de usuário e/ou e-mail
`git config user.name`
`git config email.name`


### CRIAR e INICIALIZAR UM REPOSITÓRIO (LOCAL)

#### Criando Repositório
`mkdir nome_do_repositorio_desejado`

#### Entrando na pasta do Repositório / arquivo
`cd nome_do_repositorio_escolhido`

#### Saindo da pasta do Repositório / arquivo
`cd ..` 

#### Inicializando repositório
`git init`

#### Entrando no arquivo .git/
`cd .git/`

#### Listar todos os arquivos do repositório / arquivo
`dir nome_do_repositorio_escolhido`
ou
`ls` Porém para o ls funcionar, tem que estar dentro da pasta.