# Deploy com Tags no GIT

## Baixar as tags do repositório

* `git fetch --tags`

## Lista as tags

* `git tag -l`

## Criar uma nova branch com o numero da versão da tag

* `git checkout -b v0.0.1`

## Compila o projeto 

* `npm run build` ou `npm run start` ou `npm run prod`

## Remover os assets do gitignore 

## Adicionar os arquivos ignorados nesse novo branch

* `git add .`

## Conferir arquivos adicionados

* `git status -u`

## Commitar arquivos estavam ignoarados

* `git commit -m "Add assets compilados"`

## Cria uma nova tag

* `git tag -a v0.0.1 -m ""`

## Enviar a tag ao repositório 

* `git push --tags`

## Voltar a branch original 

* `git checkout master`

## Conferir sua branch atual 

* `git branch`

## Deletar branch criada 

*  `git branch -D v0.0.1`

## Conferir as tags 

* `git fetch --tags`

* `git tag -l`

## Criar um novo branch versionado na tag

* `git checkout tags/v0.0.1 -b tags/v0.0.1`