---
sidebar_position: 5
title: "Configurações de Estoque"
---

# Configurações de Estoque

## Regras de Estoque de Dispositivos de Armazenamento

As regras de estoque de dispositivos de armazenamento servem para definir para qual estoque cada tipo de hardware será enviado.

Veja abaixo como cadastrar uma regra:

### Passo a Passo

- Acesse a página de Regras de Estoque de Dispositivos de Armazenamento através da guia de configurações

![caminho campos de teste](/img/images/aba_regras_estoque.png)

- Clique no botão **`Adicionar Regra`** localizado no canto superior direito da tela
- Selecione o tipo de hardware
- Selecione armazenamento, ou seja, o estoque para onde o tipo de hardware será enviado.
- Clique em **`Salvar`**

Veja abaixo um exemplo de regra cadastrada:

![Cadastro de Regra de Estoque de Dispositivo](/img/images/regra_estoque_dispositivo.png)

Após o cadastro, a regra será incluída em uma lista que contém todas as regras cadastradas:

![Cadastro de Regra de Estoque de Dispositivo](/img/images/lista_regra_dispositivo.png)

## Regras de Criação de Pacotes

Através da criação de regras, os pacotes poderão ser gerados automaticamente pela análise de compatibilidade de produtos feita pelo sistema.

:::warning[Importante!]
O sistema testa a compatibilidade de produtos atráves das especificações cadastradas para cada um deles.

:::

### Passo a Passo

- Acesse a página de Regras de Criação de pacotes através da guia Configurações

![caminho regras de pacote](/img/images/aba_regras_pacotes.png)

- Clique no botão **`Cadastrar Nova`** localizado no canto superior direito da tela
- Selecione o tipo de hardware
- Selecione o modelo (opcional)
- Selecione se deseja utilizar as opções
- Digite o tamanho da memória RAM
- Selecione se a RAM será apenas Integrada ou Integrada + Externa
- Selecione o tipo de armazenamento
- Clique em **`Salvar`**

Veja um exemplo de criação de regra de pacote:

![caminho regras de pacote](/img/images/cadastrar_regra_pct.png)

:::warning[Aviso!]

### Informações Importantes

- **O sistema segue uma ordem para definir a compatibilidade entre produtos:** primeiro avalia as regras por opções, em seguida por modelos e, por último, por tipos de hardware.
- **Não é obrigatório selecionar modelos ou opções**, mas se nenhum modelo for selecionado, o sistema irá aplicar a regra cadastrada a todos os tipos de hardware iguais ao que foi selecionado no momento da criação da regra.
  :::
