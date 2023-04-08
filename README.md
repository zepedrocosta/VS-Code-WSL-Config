# WSL-Config

Configurações para várias linguagens de programação usando WSL

> Contém dicas para usar as mesmas linguas no VS Code

## WSL Installation
Estes comandos irão instalar o WSL (Subsistema Windows para Linux) e a distro default (Ubuntu)

```sh
wsl --install

```

## Notas
Para escolher outra distro usar:

```sh
wsl --install [Distribuição]
```

## Ocaml setup

Comandos para instalar o Ocaml e o Opam (package manager for OCaml)

```sh
sudo apt install rlwrap ocaml-interp
sudo apt-get install opam
```
Após instalar o Ocaml e o Opam 



## C/C++ setup

Comandos para instalar o C/C++ e o respetivo debugger;

```sh
sudo apt install gcc
sudo apt-get install build-essential gdb
```

Para verificar se o compilador e o debbugger de C/C++ foram instalados corretamente usar:

```sh
whereis gcc
whereis g++
whereis gdb
```
Caso os comandos devolvam diretorias significa que foram bem instalados

Exemplo:

<img width="542" alt="image" src="https://user-images.githubusercontent.com/101460654/230719918-74ac632d-1fe9-4984-a9e7-da111f31be99.png">


## Release History

* 0.0.1
    * Work in progress
    * Start 08/04/2023

## Meta

José Costa - josepirescosta2003@gmail.com

[Twitter](https://twitter.com/Jos3Costa)

[GitHub](https://github.com/zepedrocosta)


<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
