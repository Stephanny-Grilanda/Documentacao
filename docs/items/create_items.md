---
sidebar_position: 2
title: "Cadastrar Itens"
---

# Cadastrar Itens :computer:

O sistema permite que usuário cadastre itens para vendas posteriores, veja abaixo como acessar a página de cadastro de itens e como realizar os cadastros.

## Acessar página de itens

- Clique na guia **Produtos**
- Clique em **`Itens`**

![Caminho para acessar os itens](/img/images/caminho_itens.png)

A seguir confira os pré-requisitos para cadastrar os itens:

:::info

### Pré-requisitos

- Ter um perfil de acesso ao sistema
- Ter acesso à página de itens
- Ter permissão de escrita da página de itens
  :::

## Regras de Preenchimento

| Campo     | Tipo de dado     | Obrigatório | Descrição                     |
| --------- | ---------------- | ----------- | ----------------------------- |
| Modelos   | Entrada de texto | **Sim**     | Modelo do Equipamento         |
| Nome      | Entrada de texto | **Sim**     | Nome do Modelo do Equipamento |
| Código    | Entrada de texto | **Sim**     | Código do Equipamento         |
| Descrição | Entrada de texto | **Sim**     | Descrição do Equipamento      |

## Passo a Passo para Cadastro

- Clique no botão cadastrar novo, localizado no canto superior direito da tela
- Selecione o Modelo
- Digite o nome do item
- Digite o código do item
- Digite a descrição do item
- Clique em **`salvar`**

#### Tela de Cadastro

![Tela de Cadastro](/img/images/cadastro_item.png)

:::note

Após o cadastro, o item será incluído em uma lista que apresenta seu id, código, tipo de hardware, fabricante, modelo, nome, status e ações. Veja o exemplo abaixo:

:::

![Listagem de itens](/img/images/lista_itens.png)

:::info[NOTAS]

### Prefixos

- A letra P seguida de um número é referente ao prefixo de SKU de produto e o número refere-se ao SKU em si.
- As letras SD seguidas de um número são referentes ao prefixo de SKU de dispositivos de armazenamento e o número refere-se ao SKU em si.
- As letras PC seguidas de um número são referentes ao prefixo do código do item, os itens por sua vez não possuem SKU, pois possuem um código próprio.
- A letra K seguida de um número é referente ao prefixo de um pacote, o número por sua vez refere-se ao código do pacote.
  :::

Na próxima página veja as ações que estão disponíveis para os itens cadastrados!
