# Comandos do git

- 1. abrir o arquivo no terminal
- ir no arquivo, clicar com o botão direito e em seguida em "abir no terminal"
- Abrir terminal **(ctrl+ alt + T)** e aplicar os comandos :
**pwd** : acessa home/usuário 

    **ls:** mostra as pastas de home
**ls -a:** mostra as pastas ocultas de home e as visíveis.

    **cd pasta_do_projeto**: acessa a pasta que se quer usar

## 2. Git init
inicializa um repositório git vazio na pasta.
cria uma branch master/main.

## 3. git add + nome do arquivo 
manda o arquivo pra área de steyding - indica que o arquivo está próximo de receber commit
## 4. git status
mostra o estado do arquivo : quais estão na área de steyding em " changes to be mommitted"
## 5. git commit -m "mensagem/título do commit"
commita o arquivo da área de stayding.
## 6. git --version
mostra a versão atual do git instalada na máquina.

# github

## 1. git remote add origin/qualquer outro nome pra indicar o repositório do github <link.git>

faz o remote do projeto com o link do github

## git push-U origin main
faz o push do projetos commitados pro repositório do github
## git add.
manda todos os arquivos presentes na pasta pra área de stayding

## git checkout -b "nome branch"
Cria branch

## git push origin branch
faz o push da branch criada

## git checkout main
retorna pra branch principal

## git merge <nome_branch>
faz o marge da branch com o main 

## git clone <link,git>
clona um repositório pra máquina - deve criar um arquivo antes pra conter esse repositório e abrir o terminal nele.

## git pull
busca do repositório do github os commits atualizados com alguma alteração feita.