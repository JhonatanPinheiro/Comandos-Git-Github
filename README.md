# Comandos-Git-Github
Anotações de comandos usados na rotina de um desenvolvedor ! 

- <strong>git init <O nome do seu repositório></strong> (Se você já possui um repositório anterior ou deseja criar um repositório com um nome em específico) <br> <br>
- <strong>git clone <URL do seu projeto> <O nome do seu repositório></strong> (Esse comando Git cria uma cópia exata de um repositório já existente) <br> <br>   
- <strong> git add seu_arquivo </strong> (Esse comando irá adicionar o arquivo em específico ao repositório) <br> <br> <br>
- <strong> git add * </strong> (Esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório) <br>  <br> <br> 
- <strong> git commit -a -m “seu comentário” </strong> (O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.) <br> <br>
- <strong> git branch </strong> (Lista todas as ramificações) <br> <br>  <br>
- <strong> git branch <nome_do_branch> </strong> (Cria um branch com o nome especificado) <br> <br>
- <strong> git branch -d <nome_do_branch> </strong> (Deleta o branch com o nome especificado) <br> <br> <br> 
- <strong> git checkout <nome_do_branch> </strong> (Ainda sobre branches, esse comando Git pode ser utilizado para trocar de uma ramificação para outra.) <br> <br>
- <strong> git checkout -b <nome_do_branch_novo> </strong> (Também é possível combinar operações, criando e fazendo o checkout de um novo branch com um único comando) <br> <br>  <br>
- <strong> git remote add <nomecurto> <url></strong> (O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.)<br> <br>  <br>
- <strong> git push -u <nome_curto> <nome_do_branch> </strong> (Esse comando serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote. Esse comando serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote) <br> <br> 
- <strong> git push –set-upstream <nome_curto> <nome_do_branch> </strong> (É importante especificar a origem e o upstream antes de usar o git push) <br> <br>  <br>
- <strong> git fetch </strong> (Quando você precisa baixar as mudanças criadas por outros membros do seu projeto colaborativo, você precisa do comando Git fetch. A partir desse comando, você irá receber todas as informações de commits, para avaliar, antes de aplicar essas alterações na sua versão local do repositório.) <br>
- <strong>  git pull <URL> </strong> (O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.) <br> <br>
- <strong> git stash </strong> (Esse comando Git armazena temporariamente seus arquivos modificados em uma área chamada stash (“esconderijo”), sem interagir com os outros arquivos até ser necessário.) <br> <br>  <br>
- <strong> git stash list </strong> (Para listar todos os seus “esconderijos”) <br>  <br>
- <strong> git stash apply </strong> (Quando for o momento de aplicar o conteúdo do stash a um branch, usamos o parâmetro “apply) <br> <br> <br>
- <strong> git show <hash_do_commit> </strong> (Detalhes específicos sobre um commit que o log não mostra) <br>  <br>
- <strong> git rm <nome_do_arquivo> </strong> (Para remover arquivos da sua pasta, você pode utilizar o comando Git rm.) <br>  <br>
- <strong> git help <comando que se tem dúvida> </strong> (O próprio Git tem o comando help para trazer ajuda diretamente no terminal) <br>  <br>
- <strong> git merge <nome_do_branch> </strong> (Esse comando Git integra as mudanças de dois branches diferentes em um único branch. Ele precisa ser iniciado a partir de um branch já selecionado, que será mesclado com outro, com o nome passado por parâmetro.) <br>  <br>
- <strong> git rebase <base> </strong> (Git rebase a princípio parece fazer o mesmo que um comando git merge: ele integra dois branches em um branch único. Porém, esse comando refaz o histórico de commits, tornando-o linear. É o mais indicado para consolidar múltiplos branches) <br>  <br>
- <strong> git pull –rebase </strong> (Essa é uma variação do comando pull mostrado anteriormente. A partir dessa instrução, o Git irá fazer um rebase (não um merge) depois de se utilizar um comando pull.) <br>  <br> <br> 
- <strong> git cherry-pick <commit-hash> </strong> (Essa é uma variação do comando pull mostrado anteriormente. A partir dessa instrução, o Git irá fazer um rebase (não um merge) depois de se utilizar um comando pull.) <br>  <br>
- <strong> git cherry-pick <commit-hash> </strong> (Esse é um comando poderoso que permite selecionar qualquer commit específico de um brach e aplicá-lo a outro branch, sem precisar de uma mescla completa. A operação fica adicionada no histórico.) <br> <br> <br> 
- <strong> git archive –format zip HEAD > archive-HEAD.zip </strong> (Esse comando Git combina múltiplos arquivos em um único arquivo, como se fosse um arquivo zipado. Esse pacote pode ser aberto depois e os arquivos contidos podem ser extraídos individualmente) <br>  <br>
- <strong> git blame <nome_do_arquivo> </strong> (O comando “dedo-duro”, blame ajuda a determinar qual usuário realizou qual mudança em um determinado arquivo) <br>
- <strong> git tag -a v1.0.0 </strong> (Tags são uma boa opção para marcar uma branch e evitar alteração, principalmente em releases públicos.) 
- <strong> git citool </strong> (Esse comando Git oferece uma alternativa gráfica ao commi) <br>  <br>
- <strong> git whatchanged </strong> (Esse comando oferece informações de log, mas em formato raw) <br> <br> <br> <br>

 Para comparar dois arquivos gits ou dois branches antes de passarem por um commit ou um push, é importante executar esse comando Git.
1 - Comparando o repositório ativo com o repositório local: <strong>  git diff HEAD <nome_do_arquivo> </strong>  <br>
2 - comparando duas ramificações: <strong> git diff <branch de origem> <branch de destino> </strong>  <br>

 
 
 
