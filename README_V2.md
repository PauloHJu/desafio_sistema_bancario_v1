# Sistema Bancário em Python

## Sobre o Projeto

Fomos contratados por um grande banco para desenvolver o seu novo sistema. O objetivo é modernizar as operações bancárias utilizando a linguagem Python. Esta é a versão 1.0 do sistema, focada nas operações bancárias básicas para um único usuário.

## Funcionalidades

A primeira versão do sistema possui três operações principais:

1. **Depósito**
   - Permite ao usuário depositar valores **positivos** em sua conta bancária.
   - Todos os depósitos são armazenados em uma variável e exibidos no extrato.

2. **Saque**
   - O usuário pode realizar **até 3 saques diários**.
   - Cada saque possui um **limite máximo de R$ 500,00**.
   - Caso o saldo em conta seja insuficiente, o sistema exibe uma mensagem informando que não será possível realizar o saque.
   - Todos os saques são registrados e exibidos no extrato.

3. **Extrato**
   - Lista todos os depósitos e saques realizados.
   - No final da listagem, exibe o **saldo atual da conta**.

## Regras do Sistema

- O sistema trabalha com **apenas 1 usuário**, então não há necessidade de identificar número da agência ou conta bancária.
- Os valores são exibidos no seguinte formato monetário: **R$ xxx.xx**.
- Exemplo: um saldo de **1500.45** será exibido como **R$ 1500.45**.

## Como Executar o Projeto

1. Certifique-se de ter o Python instalado na sua máquina (versão 3.x).
2. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

3. Acesse o diretório do projeto:

```bash
cd nome-do-repositorio
```

4. Execute o programa:

```bash
python nome_do_arquivo.py
```

## Exemplo de Uso

Menu exibido ao rodar o sistema:

```
Menu:
1 - Depositar
2 - Sacar
3 - Extrato
4 - Sair
```

## Contribuição

Esta é a versão inicial do projeto. Futuras melhorias podem incluir suporte a múltiplos usuários, integração com bancos de dados e autenticação segura.

Sinta-se à vontade para sugerir alterações ou colaborar diretamente!

---

Projeto desenvolvido para estudo e prática da linguagem Python.


