---
sidebar_position: 2
title: "Cadastrar Produtos"
---

# Cadastrar Produtos :printer:

Para cadastrar os produtos, é necessário seguir o caminho abaixo:

- Guia produtos
- Pedidos
- Subtópico pedidos

![Caminho para acessar os pedidos](/img/images/aba_pedidos.png)

A seguir confira os pré-requisitos para cadastrar os modelos:

:::info

### Pré-requisitos

- Ter um perfil de acesso ao sistema
- Ter acesso à página de pedidos
- Ter permissão de escrita
- Ter uma versão de modelo cadastrada
  :::

### Regras de Preenchimento

| Campo            | Tipo de dado     | Obrigatório | Descrição                         |
| ---------------- | ---------------- | ----------- | --------------------------------- |
| Triagens         | Entrada de texto | **Sim**     | Número da Triagem                 |
| Modelo           | Entrada de texto | **Sim**     | Nome do Modelo do Equipamento     |
| Código de Barras | Entrada de texto | **Sim**     | Código de Barras do Produto       |
| Part Number      | Entrada de texto | **Sim**     | Código do Fabricante              |
| Serial Number    | Entrada de texto | **Sim**     | Identificação do equipamento      |
| Peso (KG)        | Entrada de texto | **Sim**     | Peso do Produto                   |
| Asset Tag        | Entrada de texto | **Sim**     | Código Antigo Proprietário        |
| Código do Vadis  | Entrada de texto | **Sim**     | Código utilizado no sistema Vadis |
| Parent Id        | Entrada de texto | **Sim**     |                                   |

## Passo a Passo para Cadastro

- Escolha o pedido em que deseja cadastrar um produto
- Clique no botão **`Visualizar`**
- Preencha todos os campos obrigatórios para o cadastro conforme as regras de preenchimento.
  - **Triagens:** Código gerado pelo setor de recebimento após a triagem dos materiais recebidos.
  - **Modelo:** Modelo do equipamento
  - **Código de Barras:** Código fisicamente colado no equipamento
  - **Part Number:** Código gerado pelo fabricante que indentifica o modelo do equipamento
  - **Serial Number:** Código do fabricante que identifica exclusivamente o equipamento
  - **Peso (KG):** Peso do equipamento em quilogramas
  - **Asset Tag:** Código colado no equipamento que referencia a empresa anterior proprietária do equipamento.
  - **Código do Vadis:** Código colado no equipamento quando o pedido comercial exige inventário no sistema Vadis.
  - **Parent Id:**
- Confira as informações e clique em **`Salvar`**

![Tela para cadastro de produtos](/img/images/tela_cadastrar_produtos.png)

:::info
Após o cadastro, o produto será incluído em uma lista e poderá ser localizado logo abaixo do campo **Cadastrar novo produto**
:::

![Tela para cadastro de produtos](/img/images/lista_produtos.png)

Na próxima página veja as ações que estão disponíveis para os produtos cadastrados
