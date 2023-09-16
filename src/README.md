# Guia de Comandos
Esse é um guia pra lembrar nós que estaremos desenvolvendo de manter o código atualizado antes de fazer modificações e evitar conflitos entre commits e merges.

## Ao clonar o repositório
Ao clonar esse repositório, os repositórios contidos nele não serão clonados junto. Para trazer os códigos dos submodules, utilize o comando abaixo:
* `git submodule init` - Esse comando vai trazer os códigos dos submodules (repositórios Back, Front e BD) para esse repositório.

## Antes de fazer qualquer alteração
Sempre faça o pull dos commits que estão em nuvem antes de fazer seus commits para evitar conflitos entre commits.
* `git pull` - Esse comando puxará os commits que estão em nuvem, mas somente desse repositório, ele não pega os commits dos submodules.
* `git submodule update --remote` - Esse comando vai fazer um "`git pull`" dos submodules, pois o `git pull` não puxa os commits dos submodules.
