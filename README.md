# 💳 Banco Digital em Java com Programação Orientada a Objetos (POO)

Este projeto prático tem como objetivo reforçar o conhecimento em **Programação Orientada a Objetos (POO)** com **Java**, por meio da implementação de um **Banco Digital**.

---

## 📚 Descrição do Projeto

Neste projeto, você irá implementar um sistema bancário básico, com funcionalidades como **depósito, saque, transferência e extrato**. Tudo isso utilizando os **4 pilares da POO**:

- **Abstração**
- **Encapsulamento**
- **Herança**
- **Polimorfismo**

As classes e interfaces estão organizadas para representar clientes, contas correntes, contas poupança e o banco em si.

---

## 🎯 Objetivo

Reforçar os conceitos de POO por meio de um desafio hands-on e prático.  
Você poderá reproduzir, testar, modificar e melhorar a aplicação com base no modelo proposto.

---

## ⚙️ Funcionalidades

- Criar contas correntes e poupança
- Depositar valores
- Realizar saques (com ou sem limite, dependendo do tipo de conta)
- Fazer transferências entre contas
- Gerar extrato com histórico de movimentações
- Listar todas as contas cadastradas no banco

---

## 🛠️ Tecnologias Utilizadas

- Java (versão 8 ou superior)
- Orientação a Objetos (POO)
- Nenhuma biblioteca externa (100% Java puro)
- IDE recomendada: IntelliJ, Eclipse ou VS Code com extensão Java

---

## 🧩 Estrutura do Projeto

src/
├── Banco.java # Gerencia todas as contas do banco
├── Cliente.java # Representa o cliente
├── Conta.java # Classe abstrata base para contas
├── ContaCorrente.java # Conta com limite
├── ContaPoupanca.java # Conta sem limite
├── IConta.java # Interface com as ações obrigatórias
└── Main.java # Classe principal para testes

---

## 🏁 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/banco-digital-poo-java.git
Abra a pasta do projeto em sua IDE Java favorita.

Compile e execute a classe Main.java.

✅ Exemplo de Saída

Depósito de R$ 1000.0 realizado com sucesso.
Depósito de R$ 500.0 realizado com sucesso.
Saque de R$ 1200.0 realizado com sucesso (usando limite).
Saque de R$ 100.0 realizado com sucesso.
Transferência de R$ 200.0 para a conta 2001 realizada.

=== Extrato da conta 1001 - Bianca Brito ===
Depósito: +R$ 1000.0
Saque: -R$ 1200.0 (usando limite)
Transferência enviada: -R$ 200.0 para conta 2001
Saldo atual: R$ -400.00

=== Extrato da conta 2001 - João Silva ===
Depósito: +R$ 500.0
Saque: -R$ 100.0
Transferência recebida: +R$ 200.0 da conta 1001
Saldo atual: R$ 600.00

=== Contas do Banco ===
Conta 1001 - Titular: Bianca 
Conta 2001 - Titular: João Silva

## 🔍 Conceitos Aplicados
✅ Abstração
Classe Conta define atributos e métodos comuns a todas as contas.

✅ Encapsulamento
Atributos como saldo são protected ou private, acessados via métodos públicos.

✅ Herança
ContaCorrente e ContaPoupanca herdam de Conta.

✅ Polimorfismo
Método sacar() é sobrescrito de forma diferente em cada tipo de conta.

## 🚀 Melhorias Futuras (Sugestões)
Implementar interface gráfica (Swing ou JavaFX)

Persistência de dados com arquivos ou banco de dados

Geração de extrato em PDF ou CSV

Autenticação de usuário

Testes unitários com JUnit

## 👨‍💻 Autor
Feito com 💻 por Seu Nome ou GitHub
Inspirado em projetos educacionais da DIO.me
