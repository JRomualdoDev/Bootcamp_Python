
# 💰 Sistema Bancário em Python

Este é um projeto simples de terminal feito em Python que simula um **sistema bancário** com funcionalidades de depósito, saque, extrato e limite de saques diários.

## 🚀 Funcionalidades

- [x] Depósito de valores
- [x] Saque com limite de valor por operação
- [x] Limite de até 3 saques por dia
- [x] Visualização do extrato das movimentações
- [x] Exibição do saldo atual
- [x] Sistema de menu interativo no terminal

## 🖥️ Como usar

1. Execute o arquivo Python:

```bash
python sistema_bancario.py
```

2. Utilize o menu para interagir:

```
[d] Depositar  
[s] Sacar  
[e] Extrato  
[q] Sair  
```

## 🔒 Regras do sistema

- O valor máximo de saque por operação é **R$ 500,00**.
- É permitido realizar até **3 saques por dia**.
- Depósitos e saques precisam ser maiores que **R$ 0,00**.
- O sistema exibe o extrato de todas as operações realizadas.

## 📌 Exemplo de uso

```
=> d
Informe o valor do depósito: 1000

=> s
Informe o valor do saque: 200

=> e
================ EXTRATO ================
Depósito: R$ 1000.00
Saque: R$ 200.00

Saldo: R$ 800.00
=========================================
```

## 📁 Arquivo

- `sistema_bancario.py`: contém o código-fonte principal.

## 🛠️ Requisitos

- Python 3.x instalado

## 📄 Licença

Este projeto é livre para uso educacional e pessoal. 🚀
