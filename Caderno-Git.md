<h1>Caderno Git</h1>
<h2>TERMOS</h2>

Termos que são usados muito frequentemente neste assunto.
>**_Master_** - versão principal, é um _branch_ tambem;

>**_Branch_** - versões do projeto;

>**_Commit_** - enviar alterações para o sistema. Acompanhado de um comentario explicando a alteração;


<h2>COMANDOS:</h2>

<h3>COMANDOS DO GIT</h3>

`git init` - prepara a pasta para ser um repositorio
`git --version` - ver a versão
`git config --global user.nome "Seu nome"` - definir seu nome.
`git config --global user.email "Seu email"` - definir seu email.
`git config --global core.editor seuEditor` - definir seu editor.
`git init` - criar a pasta .git.
``git status` - saber os status dos arquivos dentro da pasta que não foram commitados.
`git add "nome do arquivo"` ou `-A` - adicionar arquivos não reconhecidos pelo git em reconhecidos.
`git restore --staged "nome do arquivo"` ou `-A` - Reverte o git add.
`git commit -m "mensagem"` - fazer o commit com sua mensagem.
`git log` - ver os commities ja feitos.
`git branch` - mostra todas as _branch_ do projeto.
`git branch "nome da versão"` - cria uma nova _branch_, com base na versão que está selecionada.
`git checkout "nome da versão"` - seleciona a versão _branch_ que você quiser.
`git reset --soft "id do commit"` - voltar para o commit que escolher, e anulando os commities posteriores, mas ainda continuaram exisitindo, retornando eles como um git add e um git commit.
`git reset --mixed "id do commit"` - mesma coisa do soft, porem será necessario usar o add para comitar.
`git reset --hard "id do commit"` - excluir todos os commities anteriores.


<h3>COMANDOS DO PROMPT</h3>

`cd 'nome da pasta'` - entra na pasta com esse nome.
`cd ../` - volta uma pasta.
`dir` ou `tree /f` - mostra o que tem dentro da pasta.
`mkdir 'nome da pasta'` - cria uma pasta com esse nome.
`cls` - dar um clear no cmd.
