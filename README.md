# Sistema Bancário em Python

Este é um projeto de sistema bancário simples desenvolvido em Python com a colaboração da DIO. O sistema permite realizar operações bancárias básicas, como depositar, sacar e consultar extrato. O projeto evoluiu ao longo de várias versões, cada uma adicionando novas funcionalidades e melhorias.

## Versões

### [v1.0](https://github.com/renatoryu/SistemaBancarioPython/tree/v1.0)

A versão inicial do sistema bancário com as seguintes funcionalidades:
- **Depósitos:** Permite adicionar fundos com valores positivos.
- **Saques:** Permite retirar fundos, desde que haja saldo suficiente, com um limite de 3 saques por acesso de até R$500.
- **Consulta de Extrato:** Mostra o extrato realizado ao longo das operações.

### [v2.0](https://github.com/renatoryu/SistemaBancarioPython/tree/v2.0)

Versão mais modularizada com novas funcionalidades:
- **Depósitos, Saques e Extrato:** Mantém as funcionalidades da v1.
- **Criação de Usuário:** Permite criar novos usuários.
- **Criação de Conta Corrente:** Permite criar contas correntes vinculadas a um usuário.
- **Listagem de Contas:** Lista todas as contas correntes.
- **Filtragem de Usuário:** Permite filtrar usuários existentes.

### [v3.0](https://github.com/renatoryu/SistemaBancarioPython/tree/v3.0)

- **Uso de Objetos**: Dados dos clientes são agora armazenados em objetos ao invés de dicionários.
- **Interfaces e Métodos Abstratos**: Implementação de interfaces e métodos abstratos para melhor organização e reutilização de código.
- **Herança**: Utilização de herança para criar uma estrutura de classes mais eficiente e modular.

## Pré-requisitos

- Python 3.x instalado
- Nenhum pacote adicional é necessário.

## Como Usar

1. Clone o repositório para o seu ambiente local:
    ```bash
    git clone https://github.com/seu-usuario/SistemaBancarioPython.git
    ```

2. Navegue até a branch desejada (v1.0, v2.0 ou v3.0):
    ```bash
    git checkout v2.0  # Exemplo para a versão 2.0
    ```

3. Navegue até o diretório do projeto:
    ```bash
    cd SistemaBancarioPython
    ```

4. Execute o programa principal:
    ```bash
    python SistemaBancario.py
    ```

5. Siga as instruções apresentadas no terminal para interagir com o sistema.

## Contribuições

Contribuições são bem-vindas! Se você deseja melhorar este projeto, por favor:

1. Fork o projeto.
2. Crie uma branch para sua nova funcionalidade:
    ```bash
    git checkout -b feature/nova-funcionalidade
    ```
3. Faça commit de suas alterações:
    ```bash
    git commit -am 'Adiciona nova funcionalidade'
    ```
4. Push para a branch:
    ```bash
    git push origin feature/nova-funcionalidade
    ```
5. Crie um novo Pull Request.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
