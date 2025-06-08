# Projeto Banco Simples - Bootcamp DIO

Este projeto é um sistema bancário simples desenvolvido em Python, com funcionalidades para gerenciar contas, usuários, depósitos, saques e extratos, usando interface via terminal.

---

## Funcionalidades

- Criar usuário com CPF, nome, data de nascimento e endereço
- Criar contas vinculadas a usuários existentes
- Realizar depósitos e saques com limites definidos
- Consultar extrato de movimentações
- Listar todas as contas criadas
- Limite de saques diários para controle

---

## Como usar

1. Clone este repositório:

```bash
git clone <url-do-repositorio>

python nome_do_arquivo.py
Use o menu interativo para navegar entre as opções.

Estrutura do código
menu(): Exibe o menu principal

depositar(): Realiza depósitos validando valor

sacar(): Realiza saques considerando saldo, limite e número máximo de saques

exibir_extrato(): Mostra o extrato das operações e saldo atual

criar_usuario(): Cria novo usuário único por CPF

filtrar_usuario(): Busca usuário pelo CPF

criar_conta(): Cria conta vinculada a usuário existente

listar_contas(): Exibe todas as contas criadas

main(): Loop principal do programa, gerenciando as operações e armazenando dados em memória

Requisitos
Python 3.x

Observações
Os dados não são persistidos em banco de dados, ficam armazenados em memória durante a execução do programa.

Limite de saques diários: 3

Limite máximo por saque: R$ 500,00

Contato
Criado  Bootcamp DIO