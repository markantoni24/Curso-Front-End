# Curso Front End
#### EBAC


#GIT
## Conceitos de versionamento
- historico
- controle de versão
- Quem alterou
- oque alterou
- Todos os arquivos 
- Evolução continua

Arquivo A | versão 1 | versão 2
Arquivo B | versão 1 | versão 2

## Instalação do GIT
https://git.scm.com/

Linux (apt-get) sudo apt-get install git
Mac (brew): brew install git

## Criar conta no GitHub

## Clonar o projeto
git clone https://github.com/markantoni24/Curso-FrontEnd.git

## commits
informação de açteração 
- apos testado todo seu codigo
- git status
- git add *
- git commit -m "mensagem"
- git push ( para enviar informações para o repositorio)
- git pull (puxar / trazer alterações do github para sua maquina)

## GitFlow
Fluxo do git


### Branchs
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto e publicado)
- develop 
- dd definition of done: criterios de aceite
- versionamento 1.0.0

- git checkout -b (cria uma branch)
- git checkout master (muda de branch)

### Merge
Mescla de Branchs
voce pode precisar resolver conflitos manualmente

git merge main 

### Pull Requests
Mescla de branchs no repositorio
permite code review 
o repositorio resolve os conflitos automaticamente

### configura o GitFlow
git flow init
git flow feature start (nome-da-feature)
git flow feature finish melhoria-html
