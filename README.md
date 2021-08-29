## Sumário
* [Informação geral](#Informação-geral)
* [Tecnologias](#Tecnologias)
* [Configuração](#configuração)

## Informação geral
Esse projeto é um simples header feito em vtex io no qual o usuário consegue fazer buscas, se logar na plataforma, ir para o carrinho. O header é totalmente responsivo tanto para desktops, tablets e celulares.

## Tecnologias
Project is created with:
* vtex io
* vtex apps  
	
## Setup
Para rodar esse projeto: 

primeiro: clone o repository usando o git:

```
$ git clone https://github.com/Brian-Mello/shoes-on.git
```

Segundo: acesse o seu ambiente:

```
$ cd ../header-vtex-io
$ vtex login (nome da sua loja)
```

Terceiro: logue em um ambiente, desinstale o vtex.store-theme e link o ambiente:

```
$ vtex use (nome do seu workspace) - Caso não tenha, só criar um.
$ vtex uninstall vtex.store-theme
$ vtex link
```

As imagens de alguns icones podem não aparecer pois estão salvos em um ambiente privado.
