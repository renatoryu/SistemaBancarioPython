# Sistema Bancário em Python

Este é um projeto de sistema bancário simples desenvolvido em Python com colaboração da [DIO](https://www.dio.me/). O sistema permite realizar operações bancárias básicas, como depositar, sacar e consultar extrato. Nesta versão, o sistema foi aprimorado para utilizar objetos ao invés de dicionários, e agora incorpora mais conceitos de Programação Orientada a Objetos como interfaces, métodos abstratos e herança.

## Funcionalidades

- **Depósitos**: Permite adicionar fundos com valores positivos.
- **Saques**: Permite retirar fundos, desde que haja saldo suficiente, com um limite de 3 saques por acesso de até R$500.
- **Consulta de Extrato**: Mostra o extrato realizado ao longo das operações.
- **Criação de Usuário**: Permite criar novos usuários.
- **Criação de Conta Corrente**: Cria contas correntes vinculadas a um usuário.
- **Listagem de Contas**: Lista todas as contas correntes.
- **Filtragem de Usuário**: Permite filtrar usuários existentes.

## Melhorias na v3

- **Uso de Objetos**: Dados dos clientes são agora armazenados em objetos ao invés de dicionários.
- **Interfaces e Métodos Abstratos**: Implementação de interfaces e métodos abstratos para melhor organização e reutilização de código.
- **Herança**: Utilização de herança para criar uma estrutura de classes mais eficiente e modular.

## Pré-requisitos

- Python 3.x instalado
- Nenhum pacote adicional é necessário.
