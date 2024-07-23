---
sidebar_position: 2
title: "Configurações de Testes de Funcionalidade"
---

# Configurações Testes de Funcionalidade

Para realizar os testes de funcionalidade é necessário que os **campos e os destinos dos testes estejam cadastros corretamente**. Além disso, é necessário **definir as regras** que definirão como os cadastrados deverão ser realizados.

Veja abaixo como funciona cada passo.

## Campos de Teste

Para acessar a página de campos de teste siga os passos a seguir:

- Clique na guia **`Configurações`**
- Clique em **`Campos de Teste`**

![caminho campos de teste](/img/images/aba_campos_teste.png)

:::info

### Pré-requisitos

- Ter acesso a página de cadastro de campos de teste.
- Ter acesso de escrita.
- Ter Tipos de Hardware Cadastrados

:::

### Passo a passo

Para cadastrar campos de teste, clique no botão **`Cadastrar Novo Campo`** localizado no canto superior direito da tela e siga os passos abaixo:

1. Selecione o tipo de hardware. Ex: notebook, bateria etc.
2. Selecione o tipo de campo (entrada de texto ou lista de seleção)
3. Selecione o atributo (checkbox, número, radio ou texto para listas; múltiplo para lista de seleção)
4. Digite o nome do campo
5. Digite a categoria do campo
6. Digite a descrição do campo
7. Defina se o campo terá informações sobre relevância. Ex: o produto possui riscos relevantes ou não.
8. Defina se o campo apresentará informações sobre locais danificados.
9. Defina se o campo será incluído no SKU, se sim, defina em qual área do SKU o campo aparecerá.
10. Clique em **`Salvar`**

:::warning[Importante!]
As descrições do campo devem ser claras, curtas e objetivas!
:::

Veja um exemplo de como ficaria o cadastro:

![Tela cadastro de campos](/img/images/cadastro_campo.png)

Após o cadastro do campo, o mesmo será incluído numa lista onde ficará aguardando o cadastro de opções, como pode ser visto abaixo:

![Lista aguardando opções](/img/images/cadastro_opcoes.png)

### Cadastro de Opções

Para seguir com o cadastro, escolha o campo que deseja cadastrar uma opção, clique em **`Visualizar Opções`** e depois clique em **`Cadastrar Nova Opção`**

![Lista aguardando opções](/img/images/cadastrar_opcoes.png)

O sistema irá abrir a tela para cadastro de opções, para concluir o processo siga os seguintes passos:

- Preencha o campo **LABEL** - este definirá apenas a forma que a opção aparecerá no formulário.
- Preencha o campo **Valor** - este definirá a forma que a opção será utilizada para geração do SKU ou apresentada nos formulários.
- Clique em **`Salvar`**

![Cadastro de Opções](/img/images/opcao-cadastrada.png)

### Adicionar Regra

Após o cadastro de opções, o sistema disponibilizará um local para cadastro de regras, que definirão a forma que a opção selecionada pela equipe irá aparecer no SKU.

:::warning[Aviso!]
As regras devem ser criadas apenas para campos que afetam o SKU, levando em consideração a área do mesmo que foi selecionada na momento do cadastro.
:::

O cadastro das regras deve seguir as especificações do cadastro de cada campo, veja abaixo:

- **Chassi e Tela** - as regras podem ser por local, relevância, valor ou _local e relevância_
- **Bateria, Informações Adicionais e Funcionalidade** - as regras devem ser exclusivamente por local

:::info[Importante!]
Para campos com relevância e local selecionados, a regra deve ser **Relevância e Local**; para campos com local selecionado, a regra deve ser **Local**; para campos com relevância selecionado, a regra deve ser **Relevância**; para campos que não possuírem nem relevância, nem local selecionados, a regra deve ser **Valor**
:::

Siga os passos abaixo para cadastrar uma regra:

- Escolha a opção em que deseja cadastrar uma regra
- Clique em **`Visualizar Opções`**
- Clique em **`Adicionar Regras`**
- Escolha o tipo de regra de acordo com as especificações passadas acima
- Especifique o local afetado
- Escolha o destino para onde será enviado o produto
- Clique em **`Salvar`**

![Exemplo regra](/img/images/exemplo_regra.png)

O exemplo a seguir mostra o cadastro de regra para o campo cadastrado no início do tutorial, onde não selecionamos relevância ou local, desta forma devemos utilizar uma regra de **Valor**

![Campo cadastro regra sku](/img/images/regra_sku.png)

## Destinos de Testes de Funcionalidade

O processo de cadastrar destinos para os testes de funcionalidade é simples e rápido.

Para isso, acesse a página de destinos de teste:

![Caminho destino teste de funcionalidade](/img/images/destino_teste.png)

- Clique no botão **`Cadastrar Novo`**, localizado no canto superior direito da tela

## Regras de SKU

## Regras de SKU Dispositivos de Armazenamento
