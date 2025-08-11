🛒 Modelo de Banco de Dados - E-commerce
Este repositório contém o modelo conceitual e lógico de um sistema de E-commerce, desenvolvido no MySQL Workbench.
O objetivo é demonstrar a estrutura de tabelas, chaves e relacionamentos necessários para gerenciar um fluxo básico de comércio eletrônico.

📌 Visão Geral
O modelo foi projetado para contemplar:

Cadastro de clientes

Gestão de produtos

Controle de estoque

Relacionamento com fornecedores e terceiros

Pedidos e formas de pagamento

Processo de entrega

🗂 Estrutura do Modelo

📋 Descrição das Entidades Principais
1. Cliente
Armazena informações sobre os clientes.

Nome, tipo (PF/PJ), endereço, telefone, documento.

2. Produto
Representa os itens disponíveis para venda.

Categoria, descrição, valor.

3. Fornecedor
Fornecedores que disponibilizam produtos.

Razão social, CNPJ.

4. Estoque
Controle de quantidade de produtos por local.

5. Pedido
Pedidos realizados por clientes, com status, endereço e valor do frete.

6. Forma de Pagamento
Suporte a Cartão de Crédito e Boleto.

7. Entrega
Controle de transportadora, status e código de rastreio.

🔗 Relacionamentos Importantes
Um cliente pode fazer vários pedidos.

Um produto pode ser fornecido por um ou mais fornecedores.

Um pedido pode conter vários produtos (relação N:N).

Um produto pode estar em diferentes estoques.

Uma forma de pagamento pode estar ligada a detalhes específicos (cartão ou boleto).

🛠 Ferramentas Utilizadas
MySQL Workbench – Modelagem do banco de dados.

MySQL – Banco de dados relacional.

🚀 Como Utilizar
Abra o arquivo do modelo no MySQL Workbench.

Gere o script SQL a partir do diagrama.

Execute no seu servidor MySQL.

Use o banco para testes de operações de e-commerce.

📄 Licença
Este projeto é livre para estudo e pode ser adaptado para fins acadêmicos e pessoais.
