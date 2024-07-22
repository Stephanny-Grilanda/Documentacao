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
3. Selecione o atributo

:::info
Os atributos disponíveis para entrada de texto são checkbox, número, radio e texto, enquanto a lista de seleção engloba apenas o atributo "múltiplo".
:::

4. Digite o nome do campo
5. Digite a categoria do campo
6. Digite a descrição do campo

:::warning[Importante!]
As descrições devem ser claras, curtas e objetivas!
:::

7. Defina se o campo terá informações sobre relevância. Ex: o produto possui riscos relevantes ou não.
8. Defina se o campo apresentará informações sobre locais danificados.
9. Defina se o campo será incluído no SKU, se sim, defina em qual área do SKU o campo aparecerá.
10. Clique em **`Salvar`**

![Tela cadastro de campos](/img/images/cadastro_campo.png)

### Cadastro de Opções

Após o cadastro do campo, o mesmo será incluído numa lista onde ficará aguardando o cadastro de opções, como pode ser visto abaixo:

![Lista aguardando opções](/img/images/cadastro_opcoes.png)

Para cadastrar as opções clique primeiro no botão **`Visualizar Opções`**, depois clique em **`Nova Opção`**

![Lista aguardando opções](/img/images/cadastrar_opcoes.png)

O sistema irá abrir a tela para cadastro de opções, para concluir o processo siga os seguintes passos:

- Preencha o campo **LABEL** - este definirá apenas a forma que a opção aparecerá no formulário.
- Preencha o campo **Valor** - este definirá a forma que a opção será utilizada para geração do SKU ou apresentada nos formulários.
- Clique em **`Salvar`**

![Cadastro de Opções](/img/images/opcao-cadastrada.png)

:::warning
Caso a opção SKU tenha sido selecionada na hora de cadastrar o campo, será necessário incluir as regras de SKU para as opções cadastradas.
:::

### Adicionar Regra

## Destinos de Testes de Funcionalidade

## Regras de SKU

## Regras de SKU Dispositivos de Armazenamento
