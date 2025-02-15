# Desafio-de-projeto-Construa-um-Projeto-L-gico-de-Banco-de-Dados-do-Zero



1. Definição do Objetivo

Objetivo do Projeto:

Criar um banco de dados relacional para um sistema de E-commerce, que possibilita o cadastro de usuários, gerenciamento de produtos, pedidos, pagamentos, e outras funcionalidades necessárias para operação de uma loja online.


---

2. Levantamento de Requisitos

Funcionalidades principais:

Cadastro de usuários (admin, cliente, vendedor).

Gerenciamento de produtos (nome, descrição, preço, estoque).

Processamento de pedidos (status do pedido, itens do pedido).

Pagamentos (metódos de pagamento, status).



---

3. Modelo Lógico de Dados

Entidades principais e suas tabelas:

1. Usuários: id_usuario, nome, email, senha, tipo_usuario


2. Produtos: id_produto, nome, descricao, preco, estoque


3. Pedidos: id_pedido, id_usuario, data, status


4. Itens do Pedido: id_item_pedido, id_pedido, id_produto, quantidade, preco


5. Pagamentos: id_pagamento, id_pedido, metodo_pagamento, status, valor




---

4. Diagrama ER (Entidade-Relacionamento)

O diagrama ER descreve a estrutura do banco de dados e os relacionamentos entre as entidades. Vou criar um diagrama ER para representar visualmente as tabelas e suas relações.


---
