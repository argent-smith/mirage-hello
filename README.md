# mirage-hello

MirageOS/HelloWorld modelled after https://mirage.io/wiki/hello-world

## Installation && test run

Important: you should install && use [opam 2](https).

``` shell
$ opam switch create mirage ocaml-system.4.07.0
$ opam install mirage
$ mirage configure -t macosx
$ make depend
$ make
```
