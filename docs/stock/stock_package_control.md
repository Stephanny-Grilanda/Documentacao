---
sidebar_position: 5
title: "Controle de Pacotes"
---

# Controle de Pacotes

Os pacotes são conjuntos de produtos selecionados que serão vendidos como um produto.

:::warning[Aviso!]
**Os pacotes substituem os antigos kits.**
:::

O controle de pacotes serve para criar, gerenciar e precificar os pacotes de produtos.

## Acesar aba de pacotes

Para acessar a aba de controle de pacotes, clique na guia **`Estoque`** e então clique em **`Controle de Pacotes`**

![Aba Controle de Pacotes](/img/images/pacotes.png)

## Cadastro Manual de Pacote

Para cadastrar um pacote, siga os passos abaixo:

- clique no botão **`Cadastrar Novo`** localizado no canto direito da tela.
- Nomeie o pacote
- Clique em **`Salvar`**

:::info[NOTAS]

### Prefixos

- A letra P seguida de um número é referente ao prefixo de SKU de produto e o número refere-se ao SKU em si.
- As letras SD seguidas de um número são referentes ao prefixo de SKU de dispositivos de armazenamento e o número refere-se ao SKU em si.
- As letras PC seguidas de um número são referentes ao prefixo do código do item, os itens por sua vez não possuem SKU, pois possuem um código próprio.
- A letra K seguida de um número é referente ao prefixo de um pacote, o número por sua vez refere-se ao código do pacote.
  :::

![Tela cadastrar pacote](/img/images/cadastrar_pacote.png)

:::warning[Aviso!]
O título dos pacotes que são gerados automaticamente à partir das regras de criação de pacotes é gerado pelo próprio sistema, seguindo o seguinte padrão:

1. Título do produto (SKU)
2. Quantidade de memória ram
3. Quantidade de armazenamento
4. Estado da bateria externa

Prioritariamente o sistema segue esta sequência, com exceção dos produtos que não possuem algum destes itens em sua regra de criação de pacotes
:::

:::danger[ATENÇÃO!]
A plataforma Tiny ERP não aceita nomenclaturas repetidas de produtos e nem códigos SKU repetidos, atente-se à criação manual de pacotes.
:::

:::info
Após o cadastro do pacote, o mesmo será incluído em uma lista onde será possível gerenciar seus produtos, registrar o pacote na Tiny e precificar o pacote, veja abaixo:
:::

![Tela gerenciar produtos](/img/images/cadastro_pacote_manual.png)

### Adicionar Produtos ao Pacote

Para adicionar um produto ao pacote siga os passos abaixo:

- Clique em **`Gerenciar Produtos`**
- Selecione o item ou SKU que deseja incluir no pacote
- Selecione a quantidade a ser adicionada
- Clique em **`Adicionar`**

Veja um exemplo de inclusão de produtos:

![Tela incluir produto no pacote](/img/images/cadastro_manual_produtos.png)

:::info
Após adicionar os produtos é necessário registrar o pacote na Tiny para gerar o Tiny ID, para isto basta clicar em **`Registrar Tiny`**
:::

## Precificar Pacote

Para precificar um pacote clique em **`$ Precificar`**, defina o preço e clique em **`Salvar`**

![Tela precificação](/img/images/preco_pct_manual.png)

:::info
Após a finalização do cadastro, o preço do pacote e seu ID na Tiny serão incluídos
:::

![Tela precificação](/img/images/lista_preco_manual.png)

## Cadastro Automático de Pacote
