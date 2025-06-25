# GITHUB
Aqui eu estou estudando o github usando arquivos em python

## O que aprendi
No github antes de fazermos alterações podemos
criar branchs (ramificações) para futuramente 
colocarmos na main (branch principal)

### Criando uma branch
Como criar sua branch para alterações

´´´bash
git checkout -b "nome-branch"
´´´

### Salvando alterações
para salvar é a mesma sintaxe da main
mudando somente o nome da branch

´´´bash
git add .
git commit -m "sua mensagem"
git push origin nome-branch
´´´

### Mesclando branch
Por fim você pode finalmente adicionar os
conteúdos da sua branch para a branch principal
voltando para main e depois dando o merge

´´´bash
git checkout main
git merge nome-branch
git push origin main
´´´