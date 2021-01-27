# Comandos GIT

## Configurando Break no Log 

* `git config core.pager cat`
* `git config --global core.pager cat`

## Listar logs

* `git log`

## Listar determinado log 

* `git log -1`
* `git log -3`

## Listar logs em uma linha 

* `git log --oneline`

## Listar determinado log em uma linha

* `git log --oneline -1`
* `git log --oneline -2`

## Listar log por determinada data

* `git log --before="2020-12-29"`
* `git log --after="2020-12-29"`

## Listar log por determinada data e por determinado log 

* `git log --after="2020-12-29"`


## Listar logs por dias atras

* `git log --since="2 days ago" `

## Listar logs por semanas atras/a frente 

* `git log --after="2 week ago"`
* `git log --before="2 week ago"`

## Listar logs por meses atras/a frente 

* `git log --after="2 mouth ago"`
* `git log --before="2 mouth ago"`

## Listar logs por autor 

* `git log --author="pedro"`

## Voltar no tempo pelo id do commit 

* `git checkout <id commit>`

## Voltar para o commit original 

* `git checkout master`

## Renomear nome do arquivo

* `git mv <arquivo1> <arquivo2>`

## Deltar arquivo 

* `git rm <arquivo>`

## Comparar versão master com o ultimo commit 

* `git diff --staged`

## Comparar versão master com determinado commit 

* `git diff <id commit>`

## Ver diferença entre commits

* `git diff <id commit>..<id commit>`

## Renomear texto de um commit

* `git commit --amend -m "nova mensagem"`

## Mover arquivo para staged

* `git restore --staged <arquivo>`

## Voltar arquivo como estava no ultimo commit

* `git checkout <arquivo>`

## Voltar varios arquivos como estavam no ultimo commit

* `git reset HEAD --hard`

## Deltar branch sem ter feito o marge 

* `git branch -D <nome branch>`

## Deltar branch apos ter feito o marge 

* `git branch -d <nome branch>`

## Criar um branch e entrar nele

* `git checkout -b nome branch>`

## Criar uma tag no repositorio

* `git tag <nome da tag>`

## Listar tegs criadas 

* `git tag`

## Enviar tag para o repositorio remoto 

* `git push origin <nome da tag>`

## Baixar uma tag do repositorio remoto 

* `git pull `

## Acessar uma tag remotamente

* `git checkout <nome da tag>`

## Criar um branch de uma tag 

* `git switch -c <nome da nova branch referente a tag>`

## Desfazer todos arquivos modificados

* `git checkout -- .`

## Voltar apenas a modificação de um arquivo

* `git checkout -- <nome arquivo>`

* `## Retirar arquivos do git add `

* `git checkout  HEAD -- .`

* `## Retirar apenas um arquivo do git add `

* `git checkout  HEAD -- <nome arquivo>`

## Desfazer um commit

* `git revert <id commit>`

## Remover um commit 

* `git reset HEAD~1`

## Baixar pull request enviado 

* `git fetch origin pull/3/head:<nome do branch criando>`

## Seter autenticação de usuario 

* `git remote seturl origin <link do usuario>`


