# Go

## Tópicos

### Go

#### Linguagem

![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Go_Logo_Blue.svg/215px-Go_Logo_Blue.svg.png)

Citando trechos de [golang.org](https://golang.org/):

> _Go é uma linguagem de código aberto que facilita 0 desenvolvimento de
> software **simples**, **confiável** e **eficiente**._

**Go** é uma linguagem de código aberto mantida pelo Google e pela comunidade
desenvolvedora. É uma linguagem compilada, ou seja, seu produto final é um
arquivo obtido através de compilação (transformação de código escrito numa
linguagem em alto nível, voltada para humanos, em uma linguagem de baixo nível,
voltada para máquinas), mas que também pode ser executada em formato de script
(código de alto nível executado pela ferramenta CLI).

A linguagem tem as seguintes características:

- Sistema de tipos;
- Familliaridade de sintaxe com a linguagem C;
- Segurança de memória;
- Garbage collector;
- Sistema de concorrência;
- Sistema de pacotes e módulos.

Entre outras características descritas na [Wikipedia](https://en.wikipedia.org/wiki/Go_(programming_language)).

#### Comandos

A linguagem oferece um compilador por CLI, junto de  outras ferramentas. A lista
de comandos oferecida pode ser vista pelo comando `go help`:

```bash
~ go help

Go is a tool for managing Go source code.

Usage:

        go <command> [arguments]

The commands are:

        bug         start a bug report
        build       compile packages and dependencies
        clean       remove object files and cached files
        doc         show documentation for package or symbol
        env         print Go environment information
        fix         update packages to use new APIs
        fmt         gofmt (reformat) package sources
        generate    generate Go files by processing source
        get         download and install packages and dependencies
        install     compile and install packages and dependencies
        list        list packages or modules
        mod         module maintenance
        run         compile and run Go program
        test        test packages
        tool        run specified go tool
        version     print Go version
        vet         report likely mistakes in packages

Use "go help <command>" for more information about a command.

Additional help topics:

        buildconstraint build constraints
        buildmode       build modes
        c               calling between Go and C
        cache           build and test caching
        environment     environment variables
        filetype        file types
        go.mod          the go.mod file
        gopath          GOPATH environment variable
        gopath-get      legacy GOPATH go get
        goproxy         module proxy protocol
        importpath      import path syntax
        modules         modules, module versions, and more
        module-get      module-aware go get
        module-auth     module authentication using go.sum
        module-private  module configuration for non-public modules
        packages        package lists and patterns
        testflag        testing flags
        testfunc        testing functions

Use "go help <topic>" for more information about that topic.

```

Estes são os comandos principais:

|Comando|Descrição|Resumo|
|:---|:---|:---|
|`bug`|`start a bug report`|Instruções para abrir uma issue em `golang.org/issue/new`.|
|`build`|`compile packages and dependencies`|Cria binário.|
|`clean`|`remove object files and cached files`|Limpa arquivos desnecessários criados por packages.|
|`doc`|`show documentation for package or symbol`|Exibe documentação de um pacote.|
|`env`|`print Go environment information`|Exibe informações do ambiente atual.|
|`fix`|`update packages to use new APIs`|Atualiza o uso de APIs antigas no código.|
|`fmt`|`gofmt (reformat) package sources`|Aplica a formatação tradicional no código.|
|`generate`|`generate Go files by processing source`|Executa comandos descritos por diretivas no código.|
|`get`|`download and install packages and dependencies`|Baixa packages importados e suas dependências.|
|`install`|`compile and install packages and dependencies`|Compila e instala packages importados.|
|`list`|`list packages or modules`|Lista packages nomeados no projeto.|
|`mod`|`module maintenance`|Gerenciamento do uso de módulos no projeto.|
|`run`|`compile and run Go program`|Compila e executa código Go.|
|`test`|`test packages`|Executa testes dos packages importados.|
|`tool`|`run specified go tool`|Executa uma das ferramentas listadas por `go tool`.|
|`version`|`print Go version`|Exibe a versão de Go.|
|`vet`|`report likely mistakes in packages`|Examina código Go por erros não identificados por compiladores.|

E estes são tópicos adicionais:

|Tópico Adicional|Descrição|Resumo|
|:---|:---|:---|
|`buildconstraint`|`build constraints`|Tags consideradas na execução de `go build`.|
|`buildmode`|`build modes`|Argumento usado nos comandos `go install` e `go build` orientando qual o tipo de arquivo a ser gerado/instalado.|
|`c`|`calling between Go and C`|Sobre chamadas entre Go e C/C++.|
|`cache`|`build and test caching`|Sobre cache gerado e apagado nos comandos `go ...` e `go clean`.|
|`environment`|`environment variables`|Sobre variáveis de ambiente usadas nos comandos `go ...`.|
|`filetype`|`file types`|Sobre tipos de arquivo observados nos comandos `go ...`.|
|`go.mod`|`the go.mod file`|Sobre o uso e funcionamento de módulos.|
|`gopath`|`GOPATH environment variable`|Sobre resolução de imports.|
|`gopath-get`|`legacy GOPATH go get`|Antiga resolução de imports.|
|`goproxy`|`module proxy protocol`|Sobre servidor web que pode responder a requests GET definidas numa forma específica.|
|`importpath`|`import path syntax`|Sobre packages localizados no sistema de arquivos atual.|
|`modules`|`modules, module versions, and more`|Sobre módulos em geral.|
|`module-get`|`module-aware go get`|Sobre módulos no comando `go get`.|
|`module-auth`|`module authentication using go.sum`|Sobre autenticação de módulos no comando `go get`.|
|`module-private`|`module configuration for non-public modules`|Sobre módulos não públicos no comando `go get`.|
|`packages`|`package lists and patterns`|Sobre o uso de packages em cada comando `go ...`|
|`testflag`|`testing flags`|Sobre tags usadas no comando `go test`.|
|`testfunc`|`testing functions`|Sobre os tipos de funções esperadas nos arquivos de testes.|


####  Variáveis, Constantes, Tipos, Funções, Packages



####  Array e Slices



####  Ponteiros, Estruturas, Métodos



####  Interface



####  GoRotinas, Channel, Buffer, Select, Mutex



####  Defer, Error, Panic, Recover



