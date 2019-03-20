# Tarefas de Git

As tarefas de GitHub serão duas: Uma que tem como ensinar a você como criar um novo arquivo e adicionar ele ao repositório e a outra tarefa tem como foco ensinar como modificar um arquivo e enviar estas mudanças para o repositório online.

Primeiramente você deve usar o link do GitHub Classroom enviado para você após a aula do dia 22/03 para criar um repositório só seu das tarefas. Feito o repositório, você então irá clonar ele para um diretório no seu computador. Recomendo colocar ele em um local que você irá se lembrar, seja nos seus documentos ou na área de trabalho. Com o repositório salvo no seu computador vce deve fazer um "branch" dele com o nome "tarefa_git". Para criar o novo branch, primeiro execute um `pull`, para garantir que os arquivos estão atualizados. Então, execute `git checkout -b [Nome do branch]`. O modificador `-b` serve para criar um novo branch. Assim que você terminar de usar esses comandos você está pronto para fazer as suas tarefas!

## Tarefa 1

A tarefa 1 consiste em você criar um arquivo chamado "Tarefa_1.md" e escrever nele a receita de uma sobremesa que você gosta.

Para isso é só criar o arquivo, seja pelo explorador de arquivos ou pelo prompt de comando, e escrever sua receita. Caso queiras, pesquise sobre formatação em Markdown para deixar seu arquivo ainda mais charmoso. Depois de concluido, navegue até o repositório e uso o comando 
`
git add Tarefa_1.md
`
para adicionar a tarefa ao seu commit. Após isso, use 
`
git commit -m "[sua mensagem de commit aqui]"
`
para realizar seu commit (a mensagem de commit deve estar entre aspas). Por fim, use o 
`
git push
`
para finalmente enviar seu novo arquivo para o repositório.


## Tarefa 2

As instruções da tarefa 2 se encontram no arquivo "Tarefa_2.md". Quando você concluir a tarefa deve usar o comando 
`
git commit -m "[sua mensagem de commit aqui]"
`
para realizar o seu commit e
`
git push
`
para enviar ele para o seu branch do repositório.

## Etapas finais

Quando voce terminar as duas tarefas o seu próximo passo é fazer um "merge request" de modo a enviar seu "branch" para a "master". Para isso, você tem que 