# Git e GutHub

## git

git init .						-> Inicia projeto git\r
git add <nome_arquivo>			-> Adiciona arquivos na stage\r
git commit -m "Nome commit"		-> Commit a stage atual\r
git status						-> mostra o status da branch atual\r
git log							-> Exibe o histórico de commits\r
git reset						-> Retorna para unstage\r
git reset <id_commit>			-> Retorna para pós commit\r


git branch						-> Exibe a branch atual\r
git branch -D <nome_branch>		-> deleta a branch (fazer após o merge)\r
git checkout -b <nova_branch>	-> Cria uma nova branch e entra nela\r
git checkout <nome_branch>		-> Entra na branch\r
git switch <nome_branch>		-> Entra na branch\r


git merge <nome_branch>			-> Faz o merge com a branch informada na branch atual\r

## github 

git clone <link_repositorio_github>		-> Traz o repositório da nuvem para o git local. \r
git push origin <nome_branch>			-> Enviar alterações ao repositório\r
git pull								-> Traz a branch atual do repositório\r