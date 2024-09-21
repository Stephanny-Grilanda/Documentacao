---
sidebar_position: 4
title: "Controle de Estoque de Itens"
---

# Controle de Estoque de Item

Diferentemente da entrada, o controle de estoque de itens é feita de forma manual, tendo como base a localização do item no estoque físico da empresa.

:::info

## Pré-requisitos

- Ter acesso à página de estoque;
- Ter permissão de escrita;
- Ter um item cadastrado;
- Selecionar um **pedido** para movimentações de **entrada**;
- Selecionar um **motivo** para movimentações de **saída**.
  :::

## Acessar Página Controle de Estoque de Itens

- Clique na guia **Estoque**;
- Clique em **Controle de Estoque de Itens**.

![Caminho estoque de itens](/img/images/aba_estoque_item.png)

- O sistema irá apresentar a tela abaixo:

![Cadastrar estoque de item](/img/images/cadastrar_estoque_item.png)

## Entrada de Item no Estoque

- Clique no botão **`Cadastrar Novo`**
- Selecione o item que deseja.
- Selecione o estoque no qual o item se encontra.
- Digite a localização do item correspondente à etiqueta da prateleira.
- Digite a quantidade que deseja incluir, excluir ou realizar o balanço.
- Escolha o tipo que deseja incluir:
  - **Balanço:** a quantidade total do item será atualizada para o montante que foi digitado.
  - **Entrada:** a quantidade digitada será adicionada à quantidade atual do item.
  - **Saída:** a quantidade digitada será subtraída da quantidade atual do item.
- Após preencher todos os campos clique em **`Salvar`**

:::warning[IMPORTANTE!]

- Se o estoque selecionado permitir entrada automática e a venda no ERP, o sistema irá cadastrá-lo e atualizar o ERP automaticamente.
  :::

![ajuste de itens](/img/images/ajuste_itens.png)

### Visualizar Histórico

Para visualizar o histórico de movimentações de um item, clique no botão **`Visualizar Histórico`** localizado em frente ao cadastro do mesmo.

![Visualizar histórico](/img/images/visualizar_estoque.png)

O sistema irá exibir uma tela onde constam o código do produto, quantidade, tipo de entrada, estoque de destino e data de movimentação.

![Painel histórico de estoque](/img/images/historico.png)

Veja na próxima página como é realizado o controle de pacotes!
