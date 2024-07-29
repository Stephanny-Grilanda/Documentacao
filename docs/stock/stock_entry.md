---
sidebar_position: 3
title: "Entrada no Estoque"
---

# Entrada no Estoque

Nesta página encontram-se os produtos cadastrados nos pedidos que estão aguardando entrada nos estoques.

## Acessar aba entrada no estoque

- Clique na aba **`Estoques`**
- Clique em **`Entrada no Estoque`**

![Aba Controle de Estoque](/img/images/entrada_estoque.png)

:::info

## Pré-requisitos

- Ter acesso à página de estoques
- Ter permissão de escrita à página de estoques
  :::

## Realizar Entrada no Estoque

A entrada no estoque acontece da seguinte forma:

1. O administrador configura os destinos no teste de funcionalidade;

2. Após a configuração, os destinos devem ser vinculados aos estoques e aos produtos que serão cadastrados;

3. Os produtos serão automaticamente incluídos nos estoques de acordo com os destinos definidos.

## Regras de Negócio

:::info
Para que o processo de entrada de estoque ocorra da maneira correta, é necessário que todas as regras abaixo sejam cumpridas:
:::

1. **Todos os produtos devem ter sido testados** para que possam ser incluídos no estoque.

:::warning[IMPORTANTE!]
Os produtos que forem testados, mas que não tiverem nenhum destino vinculado, **não entrarão no estoque.**
:::

2. Para pedidos que possuem eliminação de dados, **é obrigatório eliminar todos os dados da mídia do produto**. Ex: produtos com memória integrada.

3. **Os dispositivos de armazenamento devem ter seus dados eliminados**, exceto os que forem adquiridos pela empresa.

4. Só podem entrar no estoque produtos onde o status atual seja "no estoque, aguardando entrada", ou seja, aqueles tiveram a **transferência para o estoque aprovada!**

:::info
Se o estoque selecionado permitir entrada automática e a venda no ERP, o sistema irá cadastrá-lo e atualizar o ERP automaticamente.
:::

Veja na próxima página como é feito o controle de estoque de itens!
