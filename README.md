# 🏦 Sistema de Registro e Gestão de Contas Bancárias

Sistema de Registro e Gestão de Contas Bancárias desenvolvido em **C++** para a disciplina **INF101 - Programação de Computadores I**, do Centro Universitário de Viçosa – UNIVIÇOSA.

O projeto corresponde à **Etapa 1** do trabalho e tem como objetivo aplicar conceitos fundamentais de programação em C++, como variáveis, estruturas condicionais, estruturas de repetição, `switch`, vetores e validação de dados.

---

## 📚 Sobre o projeto

O sistema permite realizar o cadastro e o gerenciamento básico de contas bancárias.

Nesta etapa, o programa permite cadastrar **até 5 contas bancárias**, armazenando informações como:

* Número da conta;
* Nome do cliente;
* CPF;
* Tipo da conta;
* Saldo;
* Situação da conta.

O sistema funciona por meio de um menu interativo que permanece em execução até que o usuário escolha a opção de saída.

---

## ⚙️ Funcionalidades

O sistema possui as seguintes opções:

### 1 - Cadastrar conta

Permite cadastrar uma nova conta informando:

* Número da conta;
* Nome do cliente;
* CPF;
* Tipo da conta;
* Saldo inicial.

### 2 - Consultar conta

Permite consultar os dados cadastrados de uma conta através do número da conta.

São exibidas informações como:

* Número da conta;
* Nome do cliente;
* CPF;
* Tipo da conta;
* Saldo;
* Status da conta.

### 3 - Verificar saldo

Permite consultar o saldo atual de uma conta ativa.

Contas que estejam desativadas não podem realizar essa operação.

### 4 - Alterar tipo da conta

Permite alterar o tipo de uma conta ativa entre:

```text
1 - Conta Corrente
2 - Conta Poupança
```

### 5 - Ativar/Desativar conta

Permite alterar o status de uma conta entre:

* Ativa;
* Inativa.

### 6 - Sair

Encerra a execução do sistema.

---

## 🛡️ Validações

O sistema possui validações básicas para garantir que os dados informados sejam válidos.

### Número da conta

O número da conta deve ser maior que zero.

### Saldo inicial

O saldo inicial não pode ser negativo.

### Tipo da conta

O tipo da conta deve ser obrigatoriamente:

```text
1 - Conta Corrente
2 - Conta Poupança
```

### Status da conta

As operações que dependem de uma conta ativa verificam se a conta está ativa antes de serem executadas.

---

## 💾 Armazenamento das contas

Nesta primeira etapa, as contas são armazenadas utilizando **vetores**.

O sistema possui capacidade para:

```text
5 contas
```

Os dados permanecem armazenados somente enquanto o programa estiver em execução.

Ao encerrar o programa, os dados cadastrados são perdidos.

---

## 🧠 Conceitos de programação utilizados

O projeto utiliza conceitos fundamentais de C++:

* Variáveis;
* `int`;
* `string`;
* `double`;
* `bool`;
* Vetores;
* `if/else`;
* `switch`;
* `for`;
* `do while`;
* `cin`;
* `cout`;
* Validação de dados;
* Comentários no código.

---

## 🖥️ Menu do sistema

Ao iniciar o programa, o usuário encontrará um menu com as seguintes opções:

```text
========================================
       SISTEMA BANCÁRIO INF101
========================================
1 - Cadastrar conta
2 - Consultar conta
3 - Verificar saldo
4 - Alterar tipo da conta
5 - Ativar/Desativar conta
6 - Sair
========================================
Digite uma opcao:
```

---

## 🚀 Como executar

### Pré-requisitos

É necessário possuir um compilador C++ instalado.

Algumas opções são:

* Code::Blocks;
* Dev-C++;
* Visual Studio Code;
* Visual Studio;
* GCC/G++.

### Compilação

Utilizando o compilador G++, execute:

```bash
g++ main.cpp -o sistema_bancario
```

Depois, execute o programa.

### Windows

```bash
sistema_bancario.exe
```

### Linux/macOS

```bash
./sistema_bancario
```

---

## 📁 Estrutura do projeto

```text
Sistema-Bancario-INF101/
│
├── main.cpp
│
└── README.md
```

---

## 🎯 Objetivo acadêmico

O projeto foi desenvolvido para consolidar os conhecimentos iniciais da disciplina **INF101 - Programação de Computadores I**, colocando em prática os conceitos fundamentais de programação através de um sistema de gerenciamento de contas bancárias.

A implementação também atende ao desafio proposto no trabalho de possibilitar o cadastro de **até 5 contas**, utilizando vetores para armazenar os dados.

---

## 👨‍💻 Autor

**Leonardo Araújo**

### Disciplina

**INF101 - Programação de Computadores I**

### Instituição

**Centro Universitário de Viçosa – UNIVIÇOSA**

---

## 📌 Etapa

**Etapa 1 — Sistema de Registro e Gestão de Contas Bancárias**

**Data de entrega:** 30/09/2026

---

## 📄 Finalidade

Projeto desenvolvido exclusivamente para fins acadêmicos.
