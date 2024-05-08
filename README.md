# meu primeiro push do git 


git init
- iniciar novo projeto com git

gid add <nome-arquivo>/.file
- commit os arquivos no historico


git log 
- mostra os ultimos commit, log de alteracoes

git status
- como esta o estado da nossa ramificacoes

git diff
- que mostra o que foi alterado
- o que tem de alteracao na ramificacao

git merge 
- merge de ramificacoes, mescla ramificacoes

git branch
- mostrar a branch atual

git branch -b <nome-da-branch>
- cria uma nova branch a partir do historico da branch atual

git checkout <nome-da-branch>
- muda para essa branch

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alteracoes locais para o repositorio remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alteracoes do rep remoto, e joga pra nossa maquina


git fetch
- atualiza o novo historico local de acorde com o historico salvo la no rep remoto
- sincronizacao do local com o remoto
