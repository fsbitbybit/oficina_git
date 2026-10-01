# Exercícios - Git & Github - Aula 2
## Parte 1 — Marque a alternativa correta
1. Qual comando exibe o histórico completo dos commits?
a) git status
b) git show
**c) git log**
d) git history
2. Qual comando exibe o histórico de forma resumida?
**a) git log --oneline**
b) git log --short
c) git history --oneline
d) git commit --oneline
3. O histórico do Git permite saber:
a) Apenas o tamanho do repositório
b) Quais pessoas têm acesso ao GitHub
**c) Quem fez cada alteração, quando e qual foi a mudança**
d) Somente o nome da branch principal
4. Uma branch é:
a) Uma cópia do projeto em outro computador
b) Um tipo especial de commit
c) Uma pasta oculta do Git
**d) Uma linha de desenvolvimento independente dentro do repositório**
5. Qual comando cria a branch login sem trocar para ela?
a) git switch login
b) git switch -c login
c) git merge login
**d) git branch login**
6. Qual comando cria a branch login e já troca para ela?
a) git branch login
b) git switch -c login
**c) git switch login**
d) git merge login
7. Para integrar a branch login na main, você deve:
**a) Estar na main e rodar git merge login**
b) Estar na login e rodar git merge main
c) Estar na main e rodar git branch login
d) Estar na login e rodar git tag main
8. Qual é o principal objetivo do rebase?
a) Apagar todos os commits antigos
b) Criar uma nova tag de versão
**c) Deixar o histórico mais linear e organizado**
d) Baixar o projeto do GitHub
9. Qual comando envia pela primeira vez os commits da branch main para o GitHub?
a) git pull -u origin main
**b) git push -u origin main**
c) git commit -u origin main
d) git add -u origin main
10. Depois do primeiro push, qual sequência envia novas alterações para o GitHub?
a) git push → git add . → git commit -m "mensagem"
**b) git add . → git commit -m "mensagem" → git push**
c) git init → git push → git commit -m "mensagem"
d) git pull → git remote add origin → git commit -m "mensagem"
11. Qual comando traz para o seu repositório local arquivos que existem apenas no GitHub?
a) git pull
**b) git push**
c) git remote add origin
d) git commit
12. Qual comando cria a tag v0.9.0 em um commit específico, de hash a1b2c3d?
a) git tag a1b2c3d
b) git show v0.9.0 a1b2c3d
c) git branch v0.9.0 a1b2c3d
**d) git tag v0.9.0 a1b2c3d**
## Marque C (certo) ou E (errado).
Criar uma branch nova altera imediatamente o conteúdo da main. (**F**)
O comando git branch, sem nenhum nome, lista as branches existentes. (**V**)
O comando git switch nova-branch cria a branch nova-branch e já troca para ela. (**V**)
O merge junta as alterações de uma branch em outra. (**V**)
Merge e rebase sempre geram exatamente o mesmo histórico de commits. (**F**)
O rebase é usado para deixar o histórico de commits mais linear e organizado. (**V**)
O comando git branch -M main renomeia a branch atual para main. (**V**)
O comando git init conecta a pasta local ao repositório do GitHub. (**F**)
O comando git pull envia suas alterações locais para o repositório no GitHub. (**F**)
Para adicionar apenas um arquivo específico ao commit, usa-se git add <nome-do-arquivo>. (**V**)
## Parte 3 — Perguntas discursivas
### O que é uma branch e por que ela é útil?
Uma linha de desenvolvimento independente dentro do repositório. Branches são úteis para facilitar o trabalho paralelo de uma equipe, em que cada pode estar trabalhando numa feature diferente para a versão atual de um app e as branches facilitam esse trabalho por evitar conflitos de versionamento. Por outro lado, em projetos open source podem gerar-se os famoso forks, branches do projeto principal que alteram o projeto original.
### Qual a diferença entre merge e rebase? 
O merge normal junta as alterações de uma branch em outra. Já o rebase faz o pruning, ou seja corta as branches, mas diferentemente da jardinagem que os galhos são descartados ou queimado as branches, nesse caso, são colocada nocaminho principal, ou seja main. O merge normal mantém o histórico do repositório, já o rebase apaga todas elas e elas são adicionadas ao caminho principal.
## Qual a diferença entre git push e git pull?
O git push deseja fazer mudanças ao estado atual do repositório e o git pull deseja trazer tudo aquilo que está norepositório para o destino desejado.

