## Projeto introdutório trilha (K1-T1): Versionamento de Código

Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

### Principais comandos:

Inicializar repositório git:
```
git init
```
Adicionar/remover repositório remoto
```
git remote [add / rm] [origin / name] <URL>
```
Verificar modificações feitas em arquivos/commits
```
git diff [<HEAD1> <HEAD2>] [file]
```
Confirmar modificações arquivos para serem commitados
```
git add <path / file>
```
Criar commit
```
git commit [-m "name"] [--amend]
```
Verificar histórico de commits
```
git log [--oneline]
```
Enviar commits para o GitHub (ou outro repositório remoto)
```
git push <remote> <branch / HEAD:branch / tag> [-f]
```
Mesclar repositório local com repositório remoto
```
git pull [remote / <ULR>] [branch]
```
Clonar repositório remoto
```
git clone <URL> -b <branch> <directory>
```
Alternar entre branchs ou resetar modificações em arquivos
```
git checkout [branch] <HEAD> [-file]
```
Reverter commits
```
git revert <HEAD>
```
Resetar modificações em arquivos
```
git reset <HEAD> [--hard]
```
Criar branch
```
git branch <name> [-d name]
```
Criar tag
```
git tag <name>
```
Mesclar repositório local com repositório remoto 
```
git merge <URL / remote> <branch>
```
Realizar rebase no repositório
```
git rebase <branch> [-i HEAD]
```
Baixar as alterações de um repositório remoto, sem aplicá-las localmente.
```
git fetch <URL / remote> <branch> <pull/ID/head:BRANCH>
```
Gudardar mudanças para serem feitas posteriomente
```
git stash [pop]
```
Mostrar a revisão e o último autor que modificou cada linha de um arquivo
```
git blame <file>
```
Mostrar diversas coisas no repositório local
```
git show <HEAD>
```
