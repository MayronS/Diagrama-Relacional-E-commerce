# Diagrama-Relacional-E-commerce

#### Descrição:
O modelo de banco dados relacional criado tem como objetivo demostrar uma conexão simples de um E-commerce.

##
Começando pela parte Cliente onde foi criado uma generalização de conta PJ e conta PF.

A conta PJ e conta PF estão se relacionando com o pedido e com a forma de pagamento. Onde as contas podem ter 1 ou mais formas de pagamento e 1 ou mais pedidos.

Agora pela parte de Pedido ele tem uma relação *N* para *M* com o produto onde 1 pedido pode ter varios produtos e 1 produto pode ter varios pedidos e também está se relacionando com o rastreio onde 1 pedido pode ter um rastreio.

Partindo para a parte do Produto onde ele tem relacionamento com um vendedor-terceiro, um fornecedor e com o estoque:

- O Produto ele pode ser vendido por varios vendedores externos(terceiros) e os vendedores externos pode vender varios tipos de produtos.
- O produto pode ser vendido por varios fornecedores(vendedores internos) e os fornecedores podem vender varios produtos diferentes.
- Os produtos são guardados no estoque e pode conter varios estoques separados.

##
Todo esse projeto foi feito junto com a DIO atráves do Bootcamp Heineken - Inteligência Artificial Aplicada a Dados com Copilot.
