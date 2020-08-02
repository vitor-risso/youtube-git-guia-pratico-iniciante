# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

* `git init` // inicia a linha do tempo 
* `git remote add origin {url_do_repositorio}` // adiciona o repositório local a um repositório remoto
* `git add {nome_da_branch}` // adiciona ou atualiza mudanças para irem para a linha do tempoo
* `git commit -m '{commita aqui}'` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // lista as branches
* `git checkout {nome_da_branch}` // alterna entre as linhas do tempo
* `git checkout -b {noma_da_branch}` // cria uma nova branch
* `git checkout -d {nome_da_branch}` // deleta a banch
* `git checkout -D (nome_da_branch}` //força a branch a ser deletada (o -D significa --delete -- force)
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone {url_do_repositório}` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto
