---
sidebar_position: 2
title: "Cadastrar Produtos"
---

# Cadastrar Produtos :computer:

Para cadastrar os produtos, é necessário seguir o caminho abaixo:

- Clique na guia Produtos;
- Clique em **Pedidos**.

![Caminho para acessar os pedidos](/img/images/aba_pedidos.png)

A seguir confira os pré-requisitos para cadastrar os produtos:

:::info

### Pré-requisitos

- Ter um perfil de acesso ao sistema;
- Ter acesso à página de pedidos;
- Ter permissão de escrita da página de pedidos;
- Ter permissão de leitura da página de pedidos;
- Ter um pedido cadastrado;
- Ter uma triagem cadastrada.
  :::

### Regras de Preenchimento

| Campo            | Tipo de dado     | Obrigatório | Descrição                                |
| ---------------- | ---------------- | ----------- | ---------------------------------------- |
| Triagens         | Entrada de texto | **Sim**     | Número da Triagem                        |
| Modelo           | Entrada de texto | **Sim**     | Nome do Modelo do Equipamento            |
| Código de Barras | Entrada de texto | **Sim**     | Código de Barras do Produto              |
| Part Number      | Entrada de texto | **Sim**     | Código do Fabricante                     |
| Serial Number    | Entrada de texto | **Sim**     | Identificação do equipamento             |
| Peso (KG)        | Entrada de texto | **Sim**     | Peso do Produto                          |
| Asset Tag        | Entrada de texto | **Sim**     | Código Antigo Proprietário               |
| Código do Vadis  | Entrada de texto | **Sim**     | Código utilizado no sistema Vadis        |
| Parent Id        | Entrada de texto | **Sim**     | Equipamento proprietário da mídia / item |

## Ações Disponíveis para Pedidos

Para manipulação de pedidos, o sistema disponibiliza as ações abaixo:

- **Abrir** - Abre um pedido novo para adicionar produtos;
- **Reabrir** - Reabre um pedido que já foi fechado para que possa ter seus produtos alterados;
- **Fechar** - Fecha um pedido que teve seu processo de cadastro concluído.

![Visualizar pedidos](/img/images/opcoes_pedidos.png)

## Passo a Passo para Cadastro

- Escolha o pedido em que deseja cadastrar um produto;
- Clique em **`Abrir`**;
- Clique no botão **`Visualizar`**.

![Visualizar pedidos](/img/images/visualizar_pedidos.png)

- Preencha todos os campos obrigatórios para o cadastro conforme as regras de preenchimento.
  - **Triagens:** Código gerado pelo setor de recebimento após a triagem dos materiais recebidos;
  - **Modelo:** Modelo do equipamento;
  - **Código de Barras:** Código fisicamente colado no equipamento;
  - **Part Number:** Código gerado pelo fabricante que indentifica o modelo do equipamento;
  - **Serial Number:** Código do fabricante que identifica exclusivamente o equipamento;
  - **Peso (KG):** Peso do equipamento em quilogramas;
  - **Asset Tag:** Código colado no equipamento que referencia a empresa anterior proprietária do equipamento;
  - **Código do Vadis:** Código colado no equipamento quando o pedido comercial exige inventário no sistema Vadis;
  - **Parent Id:** equipamento proprietário da mídia ou item a ser cadastrado;
- Confira as informações e clique em **`Salvar`**.

![Tela para cadastro de produtos](/img/images/tela_cadastrar_produtos.png)

:::info
Após o cadastro, o produto será incluído em uma lista e poderá ser localizado logo abaixo do campo **Cadastrar novo produto**.
:::

![Tela para cadastro de produtos](/img/images/lista_produtos.png)

Na próxima página veja as ações que estão disponíveis para os produtos cadastrados!
