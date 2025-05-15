# te-amokyu
da nota 10
SEQUENCIA DE COMANDOS PARA CONECTAR O REPOSITÓRIO REMOTO PELA PRIMEIRA VEZ
git init => iniciar o git

git add . => adicionar os arquivos ou alterações no repositório local

git commit -m "sua_descrição-aqui" => descrição do que foi feito: ex: "atualização do script"

git log => mostrar a lista sequencial de commits feito por quem, quando e onde ou git log --oneline => mesma função do git log, mas reduzido somente a uma linha

git remote add origin  => conectar o repositório remoto ao local

git pull => puxa tudo do repositório remoto pro local

git branch --set-upstream-to=origin/master master => conecta ambas as branchs: local e remoto

git pull --allow-unrelated-histories => puxa tudo do repositório remoto pro local

git status => verificar o status

git commit -m "sua_descrição_aqui" => descrição do que foi feito: ex: "atualização do script"

git log ou git log --oneline

git push => envia tudo do repositório local pro remoto

git checkout -b Minha_laele => cria e entra na branch nova

git branch -d Minha-laele => apaga a branch
