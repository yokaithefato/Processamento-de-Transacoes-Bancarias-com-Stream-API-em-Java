# Programa de Processamento de Transações Bancárias com Stream API

## Descrição

Você está aprimorando o programa anterior e agora deseja utilizar a Stream API do Java para processar as transações bancárias de forma mais eficiente.

## Entrada

O programa solicitará ao usuário que informe:
- O saldo inicial da conta.
- A quantidade total de transações que o cliente deseja realizar.

### Entrada de Transações

Para cada transação, o programa solicitará ao usuário:
- O tipo de transação: Digite 'D' para depósito ou 'S' para saque.
- O valor da transação.

## Saída

Utilizando a Stream API, o programa armazenará cada transação, que incluirá um tipo (Depósito ou Saque) e um valor. Ao final das transações, o programa exibirá o saldo final da conta e a lista de transações.

## Exemplos de Entrada e Saída

### Exemplo 1

| Entrada       | Saída                |
|---------------|----------------------|
| 100           | Saldo: 90.0          |
| 2             |                      |
| d             |                      |
| 10            |                      |
| s             |                      |
| 20            | Transações:          |
|               | d de 10.0            |
|               | s de 20.0            |

### Exemplo 2

| Entrada       | Saída                |
|---------------|----------------------|
| 5000          | Saldo: 5500.0        |
| 1             |                      |
| d             |                      |
| 500           |                      |
|               | Transações:          |
|               | d de 500.0           |
