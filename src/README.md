# Guia de Comandos
Este é um guia pra lembrar nós que estaremos desenvolvendo de manter o código atualizado antes de fazer modificações e evitar conflitos entre commits e merges.

## Ao clonar o repositório
Ao clonar esse repositório, é importante que se use o comando abaixo para inicializar o submodule:
* `git submodule init` - Esse comando vai inicializar os submodules (repositórios Back, Front e BD) nesse repositório.

## Antes de fazer qualquer alteração
Sempre faça o pull dos commits que estão em nuvem antes de fazer seus commits para evitar conflitos entre commits.
* `git pull` - Esse comando puxará os commits que estão em nuvem, mas somente desse repositório, ele não pega os commits dos submodules.
* `git submodule update --remote` - Esse comando vai fazer um "`git pull`" dos submodules e trazer seus códigos para dentro desse repositório, pois o `git pull` não puxa os commits dos submodules.
