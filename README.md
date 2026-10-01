# Sistema de Login e Cadastro de Usuários

Projeto desenvolvido em **Java** utilizando **NetBeans**, com integração ao banco de dados **MySQL**.

O sistema permite realizar o login de usuários e gerenciar os dados cadastrados através de operações de CRUD.

## Tecnologias utilizadas

* Java
* NetBeans
* MySQL
* XAMPP
* JDBC
* Git e GitHub

## Funcionalidades

O sistema possui funcionalidades para:

* Login de usuários
* Cadastro de usuários
* Consulta de usuários
* Alteração de dados
* Exclusão de usuários
* Conexão com banco de dados MySQL
* Interface gráfica desenvolvida em Java Swing

## Banco de dados

O projeto utiliza um banco de dados MySQL.

O arquivo:

```text
bancojava.sql
```

contém a estrutura necessária para criar o banco e suas tabelas.

### Como importar o banco

1. Inicie o **Apache** e o **MySQL** pelo XAMPP.
2. Acesse o **phpMyAdmin**.
3. Crie ou selecione o banco de dados utilizado pelo projeto.
4. Acesse a opção **Importar**.
5. Selecione o arquivo `bancojava.sql`.
6. Clique em **Importar**.

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Abrir no NetBeans

Abra o projeto pelo NetBeans e aguarde o carregamento das dependências.

### 3. Configurar o banco

Verifique na classe de conexão se os dados do MySQL estão corretos:

* Endereço do banco
* Porta
* Nome do banco
* Usuário
* Senha

### 4. Iniciar o MySQL

No XAMPP, deixe o **MySQL** iniciado.

### 5. Executar

Execute o projeto pelo NetBeans e utilize a tela de login para acessar o sistema.

## Estrutura do projeto

```text
LoginUsuario2/
├── src/
│   └── classes e telas do sistema
├── nbproject/
├── build.xml
├── bancojava.sql
└── README.md
```

## Objetivo

O objetivo do projeto é desenvolver um sistema simples de gerenciamento de usuários, colocando em prática conhecimentos de **Java, programação orientada a objetos, interfaces gráficas, banco de dados, JDBC e operações CRUD**.

## Autores

Projeto desenvolvido para fins acadêmicos.

**Curso Técnico em Informática**

**Colégio ULBRA São Lucas**
