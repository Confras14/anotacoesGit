<h1>Caderno Git</h1>
<h2>TERMOS</h2>

Termos que são usados muito frequentemente neste assunto.
>**_.gitignore_** - um arquivo _git_, onde os arquivos que forem colocados dentro dele (apenas usando o nome.formato) vão ser ignorados pelo _git_;

>**_Branch_** - versões do projeto;

>**_Commit_** - enviar alterações para o sistema. Acompanhado de um comentario explicando a alteração;

>**_fetch_** - receber alterações de outra pessoa;

>**_Master_** - versão principal, é um _branch_ tambem;

>**_pull_** - receber informações _repositório remoto_;

>**_push_** - enviar alterações;

>**_push_** - enviar informações ao _repositório remoto_;

>**_Repositório local_** - repositório que está _localizado na maquina_, apenas ela tendo acesso (ou caso esteja em um servidor de computadores);

>**_Repositório remoto_** - repositório _online_ que pode ser acessado e alterado de qualquer máquina.


<h2>COMANDOS:</h2>

<h3>COMANDOS DO GIT</h3>

`git init` - prepara a pasta para ser um repositorio

`git --version` - ver a versão

`git config --global user.nome "Seu nome"` - definir seu nome.

`git config --global user.email "Seu email"` - definir seu email.

`git config --global core.editor seuEditor` - definir seu editor.

`git init` - criar a pasta .git.

`git status` - saber os status dos arquivos dentro da pasta que não foram commitados.

`git add "nome do arquivo"` ou `-A` - adicionar arquivos não reconhecidos pelo git em reconhecidos.

`git reset` - Reverte o git add.

`git commit -m "mensagem"` - fazer o commit com sua mensagem.

`git log` - ver os commities ja feitos.

`git branch` - mostra todas as _branch_ do projeto.

`git branch "nome da versão"` - cria uma nova _branch_, com base na versão que está selecionada.

`git checkout "nome da versão"` - seleciona a versão _branch_ que você quiser.

`git reset --soft "id do commit"` - voltar para o commit que escolher, e anulando os commities posteriores, mas ainda continuaram exisitindo, retornando eles como um git add e um git commit.

`git reset --mixed "id do commit"` - mesma coisa do soft, porem será necessario usar o add para comitar.

`git reset --hard "id do commit"` - excluir todos os commities anteriores.

`git diff` - mostra a diferança do arquivos entre um commit e o atual

`git diff --name-only` - mostra apenas os nomes do arquivos alterados

`git diff "nome arquivo.formato"` - mostra alterações do arquivo escolhido

`git checkout HEAD` ou `"nome do branch"` -- "nome dos arquivos" - retorna as alterações feitas nos arquivos selecionados

`git commit -am "MENSAGEM"` - Junção do `git add -A` com o `git commit -m "MENSAGEM"`

`git clone https://github.com/git/git` - Atualizar a versão do git

`git remote add origin "link do repositório remoto"` - adicionar o repositório remoto

`git remote` - nome dado ao repositório remoto

`git remote -v` - infos sobre push e fecth

`git branch -M "novo nome"` - mudara o nome do branch q estiver selecionado

`git push -u origin main` - enviar o primeiro commit ao github origin = nome dado ao repositório, main = nome do branch

`git push origin main` - enviar os outros commities ao github. origin = nome dado ao repositório, main = nome do branch

`git revert --no-edit "id commit"` reverte o commit escolhido

`git push origin :"nome do branch` - deletar o branch remoto

`git branch -D "nome do branch"` - deletar o branch local

`git pull origin "nome do branch"` - traz commit do remoto e leva para o local

`git clone "link do repositório remoto"` - clona o repositório

`git pull origin master --allow-unrelated-histories` - para mesclar branch's


<h3>COMANDOS DO GIT BASH</h3>

`cd 'nome da pasta'` - entra na pasta com esse nome.

`cd ../` - volta uma pasta.

`list` - mostra o que tem dentro da pasta.

`mkdir 'nome da pasta'` - cria uma pasta com esse nome.

`clear` - dar um clear no cmd.
