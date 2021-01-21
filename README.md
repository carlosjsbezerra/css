# GIT E GITHUB

- `git init` // inicia a linha do tempo
- `git add .` // adiciona ou atualiza mudançãs para irem para a linha do tempo
- `git commit -m "mensage"` // adiciona um ponto na linha do tempo
- `git log` // visualiza os pontos da linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show ff07291c12108f98856e518bcb239c0e77742714` // apresenta determinado ponto na história

## Iniciar uma nova funcionalidade no projeto, sem estragar o que já foi feito.
`git branch nova_branch`
1. acessar a nova branch ou voltar para branch principal master
`git checkout nova_branch`
2. olhar todas as branchs
`git branch`
3. adicionando as novas funcionalidade da `nova_branch` para `master`
`git merge nova_branch`
4. deletar a `nova_branch`, depois de aplicar em seu projeto.
`git branch -D nova_branch`

## Colocar o projeto na nuvem.
