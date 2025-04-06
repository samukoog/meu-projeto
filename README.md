# meu-projeto

git init 
-- iniciar novo projeto com git

git add<nome-arquivo>/.
-- add os arquivos que estao prontos para serem commitados

git commit -m "mensagem commit"
-- commit os arquivos no historico

git  log 
-- mostra os ultimos commits, log de alteracoes

git status
-- como esta o estado da nossa ramificação

git diff
-- que mostra o que foi alterado

git merge
-- merge de ramificações, mescla ramificações

git branch
-- mostra a branch atual

git branch -b <nome-da-branch>
-- cria uma nova branch a partir do historico da branch atual que estamos

git checkout <nome-da-branch>
-- muda pra essa branch

git checkout -b <nome-da-branch>
-- criar uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
-- add um novo repositorio remoto

git push <nome> <nome-da-branch>
-- manda nossas alterações locais para o repositório remoto, pra cada branch

git pull <nome> <nome-da-branch>
-- pega as alterações do repositório remoto, e joga pra nossa máquina

git fetch
-- atualiza o nosso historico local de acordo com o historico salvo la no repositorio remoto
-- sincronização do local com o remoto