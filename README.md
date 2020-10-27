# Comandos de GIT

# Configuração de Utilizador
git config --global user.name "NOME"
git config --global user.email "EMAIL"
git init --> inicia o repositóriogit status --> verifica o estado do repositório
git status --> verifica o estado do repositório
git add NOMEFICHEIRO --> adiciona um ficheiro específico ao repositório

git commit -m "MENSAGEM" --> cria ponto no controlo de versões do repositório com os ficheiros adicionados
git commit -am "MENSAGEM" --> cria um commit e adiciona os ficheiros modificados já adicionados a um commit anterior do repositório 
git log --> mostra as informações de todos os commit feitosgit show  CODIGOCOMMIT--> apresenta  as alterações efetuadas no commit do código fornecido
git show --> apresenta as alterações efetuadas no último commit

git branch NOME --> cria uma nova branch
git branch --> mostra as branch existentes
gitcheckout NOME --> troca para a branch NOME
git  merge  NOME -->  estando  numa  branch  acrescenta  as  funcionalidades  da  branch NOME à atual
git branch -D NOME --> elimina a branch NOME

git remote add origin LINK --> liga o repositório atual local a um repositório online
git push -u origin master --> envia a branch master para o repositório online (necessário apenas no primeiro envio)
git push --> enviar o repositório atual local para o repositório online