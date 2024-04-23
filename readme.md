<div align='center'><h1>Manual de Produção MVC em Gin/Go</h1></div>
<hr>

<br>

## 1 - QuickStart

**1.1 - criar a pasta do projeto**
```sh
$ mkdir app
$ cd app/
```
**1.2 - iniciar um go.mod**
```sh
$ go mod init github.com/user/app
```
**1.3 - verificar o arquivo go.mod**
```sh
$ cat go.mod
module github.com/user/app

go 1.21.6
```
**1.4 - Instalando Modulos**
*Ex: gin*
```sh
$ go get -u github.com/gin-gonic/gin
```
**1.5 - Instalando Modulos do go.mod**
```sh
$ go get
```
**1.7 - Escrevendo o Código main**
```sh
$ nano main.go
```
Deve ficar assim depois disso:
```sh
$ ls
main.go         go.sum          go.mod
```
**1.6 - Rodando o Sistema**
**1.6.1 - Run -> Rodando o Código Apenas**
```sh
$ go run main.go
```
**1.6.2 - Build -> Compilando o Arquivo Binário do Sistema**
```sh
$ go build
$./app
running..
```