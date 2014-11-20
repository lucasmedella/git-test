1 - Criar pasta do projeto
2 - git init criar o repositorio
3 - Adicionar os arquivos
4 - git add . = adiciona todos os arquivos
	  git status = mostra o que ta pendente
   - git add *.php
   - git add nome.txt
5 - git commit -m "Comentario" = Commita somente
   - git commit - a -m "comentario" = Commita e adiciona os arquivos
   - git commit --amend -m "comentario (edicao)" = pega o ultimo commit e adiciona os arquivos que faltaram
6 - git diff = Ve modificações realizadas no diretorio de trabalho
   - git diff --staged = Ve modificações realizadas que já foram adicionadas na stage area
7 - git log = ver os comits que foram feitos
   - git log -p = log em ordem decrescente com paginacao
   - git log -p -1 = por quantidade de comit
   - git log --pretty=online
8 - gitk - abre programa para ver os commit de forma visual
9 - git reset HEAD nome.html = leva o arquivo da stage area para work area.
10 - git rm nome.txt = remove arquivo 
11 - git tag = exibe as tags crias
     - git tag -a codigodocommit -m "Descricao" = definindo uma tag para commit ja realizado
	 - git tag -a v1.0 -m "comentario" = criando uma tag sem vinculacao
	 - git show v.1.0 = ve os dados e o commit vinculado a tag
	 - git tag -d v.0.1 = delete tag
12 - git branch teste = criar branch
	 - git checkout teste = ir para branch teste
	 - git checkout -b teste = cria e ja vai para brach criado
	 - git checkout master = volta para branch master
	 - git branch = lista os branches criados
	 - git -d teste = deleta o brach
13 - git merge teste = junta os branches - estar no branch destino

criar arquivo
.gitignore 
nomes dos arquivos ignorados
index.html

Web starter kit

Atualizar npm
npm install -g npm
 
 ----------------
 
Using Chocolatey:

cinst nodejs
# or for full install with npm
cinst nodejs.install
