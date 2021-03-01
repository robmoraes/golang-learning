# Instalação de multiplas versões do Golang no Ubuntu

Passos para instalação e configuração do gerenciador de multiplas versões do golang.

## Instalar o golang

Primeiro instalar o golang para que o gvm funcione

```console
$ sudo apt-get install golang
```

## Instalar GVM para gerenciar multiplas versões

[Instruções de instalação e uso](https://github.com/moovweb/gvm)

GVM Install

```console
bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
```
Instalação de versão do Go pelo GVM

```console
gvm install go1.4
gvm use go1.4 [--default]
```

Listando versões instaladas

```console
gvm list
```
