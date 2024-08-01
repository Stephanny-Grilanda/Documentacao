---
sidebar_position: 5
title: "Controle de Pacotes"
---

# Controle de Pacotes

Os pacotes são conjuntos de produtos selecionados que serão vendidos como um único produto.

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
O título dos pacotes gerados automaticamente conforme as regras de criação é definido pelo sistema, seguindo o padrão abaixo:

1. Título do produto (SKU)
2. Quantidade de memória ram
3. Quantidade de armazenamento
4. Estado da bateria externa

Prioritariamente, o sistema segue esta sequência, exceto para os produtos que não incluem algum desses itens em suas regras de criação de pacotes.
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

### Precificar Pacote

Para precificar um pacote, clique em **`$ Precificar`**, defina o preço e clique em **`Salvar`**

![Tela precificação](/img/images/preco_pct_manual.png)

:::info
Após a finalização, o preço do pacote e seu ID na Tiny serão incluídos no cadastro do pacote.
:::

![Tela precificação](/img/images/lista_preco_manual.png)

---

## Cadastro Automático de Pacote

O cadastro automático de pacotes depende da existência de **[regras de criação de pacotes](docs\settings\stock.md)** cadastradas.

No cadastro automático, os produtos são agrupados por compatibilidade, complementando uns aos outros. Ex: Um notebook poderá ter como complemento uma bateria, memória ram etc.

### Passo a Passo

1. Na parte superior da tela de controle de pacotes, clique em **`QTD SKUS SEM PACOTES`**

![Dashboard pacotes](/img/images/dash_pacotes.png)

2. Perceba que o pacote não possui um Tiny ID cadastrado, desta forma é necessário **enviar o cadastro para Tiny** para que este fique disponível para venda e você consiga gerar o pacote.

![Dashboard pacotes](/img/images/tiny_id.png)

3. Após enviar o cadastro para Tiny, clique em **`Gerar Pacote`**

![Dashboard pacotes](/img/images/cadastro_automatico_pacote.png)

4. Caso o pacote tenha sido gerado corretamente, o sistema irá gerar a mensagem abaixo:

![Dashboard pacotes](/img/images/pacote_criado.png)

5. O pacote será incluído na lista onde poderá ser gerenciado. Clique em **`Registar Tiny`** para o pacote ser enviado para o ERP de vendas.

![Dashboard pacotes](/img/images/registrar_tiny.png)

6. Clique em **`$ Precificar`** para definir o preço do pacote, digite o valor desejado e clique em **`Salvar`**

![Dashboard pacotes](/img/images/precificar_pacote.png)

:::warning[ATENÇÃO!]

## Informações Importantes

- Se o produto não possuir um Tiny ID, ele não vai aparecer na Tiny quando o pacote for cadastrado. No entanto, caso o pacote seja vendido e o pedido caia no GAG, o sistema irá considerar que o produto está dentro do pacote.

- Produtos podem ser adicionados ou removidos do pacote, para isto basta clicar em **`Gerenciar Pacote`** e seguir os passos:

  - **Para adicionar:** selecione o item ou SKU, a quantidade desejada e depois clique em **`Adicionar`**
  - **Para remover:** selecione o produto e clique em **`Arquivar`**
  - Feche a página de gerenciamento e clique em **`Atualizar`**

- Sempre que adicionar ou remover produtos de um pacote, você deverá clicar em **`Atualizar Tiny`**

:::

Veja nas próximas páginas como os processos de vendas são realizados!
