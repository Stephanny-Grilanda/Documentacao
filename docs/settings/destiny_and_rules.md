---
sidebar_position: 3
title: "Destinos de Testes e Regras de SKU"
---

## Destinos de Testes de Funcionalidade

O sistema permite ao usuário definir os destinos dos produtos que serão testados nos testes de funcionalidade. Veja abaixo como o processo é feito.

### Acessar a página de destino de testes

- Clique na aba **Config.**;
- Clique em **Destinos Teste de Funcionalidade**.

![Caminho destino teste de funcionalidade](/img/images/destino_teste.png)

:::info

### Pré-requisitos

- Ter acesso à página de destino de testes;
- Ter permissão de escrita à página de destino de testes.
  :::

### Passo a Passo

- Clique no botão **`Cadastrar Novo`**, localizado no canto superior direito da tela;
- Digite o nome do destino, o mesmo será apresentado nos relatórios;
- Digite a descrição referente ao destino do teste.
- Clique em **`Salvar`**.

![Tela cadastro de destino](/img/images/cadastrar_destino.png)

## Regras de SKU

As regras de SKU têm por objetivo definir a forma como as infomações de SKU irão aparecer nos relatórios.

### Acessar a página de Regras de SKU

- Clique na aba **Config.**;
- Clique em **Regras de Sku**.

![Caminho regras de SKU](/img/images/aba_regras_sku.png)

:::info

### Pré-requisitos

- Ter acesso à página de regras de SKU;
- Ter permissão de escrita à página de regras de SKU.
  :::

### Passo a Passo

- Clique no botão **`Cadastrar Nova`** localizado no canto superior direito da tela;
- Escolha a **área do SKU** na qual a regra deverá ser aplicada;
- Digite a informação de **entrada** a ser tratada;
- Escolha a **condicional**, ou seja, defina se a informação deverá ser maior, menor ou igual à quantidade;
- Escolha a **quantidade** de vezes que a informação aparecerá no SKU;
- Digite a **saída**, ou seja, como a informação ficará depois de tratada;
- Selecione o **peso** que esta regra terá, levando em consideração que o sistema sempre utilizará a informação que possui o maior peso.

Veja um exemplo de cadastro:

![Exemplo cadastro regra de SKU](/img/images/cadastro_regra_sku.png)

:::warning[Aviso!]

### Informações Importantes

- As regras de SKU dependem do que é selecionado nos testes de funcionalidade;
- A entrada refere-se à descrição da saída nas regras de campos de teste.
  :::

Após o cadastro, a regra será incluída em uma lista que contém todas as regras de SKU cadastradas, veja abaixo:

![Lista Regras de SKU](/img/images/lista_regra_sku.png)

## Regras de SKU Dispositivos de Armazenamento

As regras de SKU tem como objetivo definir como os dispositivos de armazenamento aparecerão nos relatórios de SKU.

### Acessar página de regras de SKU Disp. Armazenamento

- Clique na aba **Config.**;
- Clique em **Regras de SKU Disp. Armazenamento**.

![Caminho regras de SKU de Dispositivos de Armazenamento](/img/images/aba_regras_dispositivo.png)

:::info

### Pré-requisitos

- Ter acesso à página de regras de SKU de dispositivos de armazenamento;
- Ter permissão de escrita à página de regras de SKU dispositivos de armazenamento.
  :::

### Passo a Passo

- Clique no botão **`Cadastrar Nova`** localizado no canto superior direito da tela;
- Escolha o **Tipo de Hardware** para o qual deseja cadastrar uma regra;
- Selecione o **Campo de Especificação**;
- Selecione a **ordem** em que tipo de hardware aparecerá no SKU.

Veja abaixo um exemplo de como a regra é cadastrada.

![Tela Cadastrado Regras de SKU de Dispositivos de Armazenamento](/img/images/tela_sku_dispositivo.png)

Veja na próxima página como são realizadas as configurações de transferência de produtos!
