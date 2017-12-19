
[![Build Status](https://travis-ci.org/rodrigodosanjosoliveira/SftpWrapper.svg?branch=develop)](https://travis-ci.org/rodrigodosanjosoliveira/SftpWrapper)

# SftpWrapper #
Pacote NuGet responsável por realizar operações de download e upload de arquivos utilizando servidores SFTP

## Utilizando o nuget

Configurar o Visual Studio para adicionar a origem desse nuget:
```
Tools-> NuGet Package Manager -> Package Manager Settings -> Package Sources
```
## Executando os testes 

Dentro do diretório do projeto de testes, deve-se executar o comando abaixo para iniciar o servidor SFTP a partir da imagem Docker.

``` docker-compose up -d ```

Dados de autenticação para acesso ao Servidor
* User: foo
* Password: pass
* Host: 127.0.0.1
* Port: 2222

## Dependências

https://github.com/sshnet/SSH.NET

