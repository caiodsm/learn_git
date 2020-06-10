# learn_git
Aprendendo a mexer no git e podendo compartilhar figurinhas

git vs github
- um faz o versionamento de códigos o outro hospeda o código (basicamente)

.gitignore
- ignora os documentos que vao para o git

git init
- inicia o git na pasta, criando um repositorio vazio e um .git

git add <file> ou git add . (all)
- comando que adiciona arquivos alterados para comitar

git rm --cached <filed> 
- remove os arquivos que estão pra adicionados

git status
- visualiza os arquivos que estão apra comitar

git commit (abre um vim ) git commit -m "<titulo>"
- comita os arquivos que foram adicionados. Obs.: é muito importante criar um titulo que ilustre especificamente o que foi realizado,
existem algumas metodologias para colocar no titulo do commit como:
    - test:(adionar, alterar ou coisas do genero voltadas para test);
    - fix: (acabar com bugs ahahah);
    - feat: (criar algo novo);
    - chore: (alterar funcionaldiade, expandir elas ou simplesmente não conseguiu encaixar nos outros ahahah)

git log 
- visualiza os commmits

git remote add <nome>(padrao= origin) <url do repositorio>
- cria no caso a branch master sincronizando com o github

git push -u ( o -u é o primeiro push para deixar como branch DEFAULT) origin master (nome da branch de push)
- esse comando é o primeiro comando que vai setar sua branch como a padrão para o git, os proximos push podem ser so git push
a menos que voce queira mandar uma branch diferente, então é so colcoar git push <nome da branch>

git clone < url>
- clona o repositorio na sua maquina

git checkout -b <nome da nova branch> (esse b cria a nova branch)
- esse comando cria um branch que voce pode trabalhar para não ter que mexer diretamente na sua master,
se precisar trocar de branchs é só dar git checkout <nome da branch que deseja ir>

git pull
- puxa tudo que ta no repositorio do github

git merge <branch>
- sincroniza a master com os commits e alterações das branchs

git push origin <branch>
- esse comando cria uma PULL REQUEST que voce pode autorizar ou não, assim voce pode olhar o que foi alterado e pode pedir pra alguem
revisar no REVIWES. Se for dado um merge pull request ele sincroniza as alterações. Caso tenha dado RUIM é possivel reverter o merge,
lembrando que essa reverção é mais facil dentro do github. Observação: quando 2 ou mais epssoas estão fazendo alterações no mesmo 
codigo e acabam dando merge, pode ocorrer um conflito que pode tanto ser resolvido dentro do github ou no vscode

git rebase
- (ainda preciso estudar) mas ele pode dar um merge das branchs



