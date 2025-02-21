📦 E-commerce Database

📖 Visão Geral

Este banco de dados foi projetado para gerenciar pedidos, produtos, fornecedores e entregas em um sistema de e-commerce.

# Estrutura das Tabelas

📌 Tabela Entrega

A tabela Entrega armazena informações sobre o envio de pedidos, incluindo o status da entrega e o código de rastreamento.

🔹 Relacionamento

Cada pedido pode ter no máximo uma entrega (relação 1:1).

A tabela Entrega contém uma chave estrangeira (pedido_idPedido), que referencia a tabela Pedido.

O cliente não está diretamente armazenado na Entrega, pois pode ser obtido através da relação com Pedido.

