# SQL
Mini-Projeto SQL – Análise de Vendas e Clientes
📝 Descrição

Este é um mini-projeto de SQL que simula um sistema de vendas de produtos.
O objetivo é demonstrar habilidades em SQL, incluindo criação de tabelas, inserção de dados, relacionamentos, agregações e consultas avançadas.
Ideal para exibir em portfólio ou LinkedIn.

🏗 Estrutura do Banco de Dados
Tabelas

Clientes
  ClienteID (INT, PK) – Identificador único do cliente
  Nome (VARCHAR) – Nome do cliente
  Idade (INT) – Idade do cliente
  Cidade (VARCHAR) – Cidade do cliente
  Estado (VARCHAR) – Estado do cliente

Produtos
  ProdutoID (INT, PK) – Identificador único do produto
  NomeProduto (VARCHAR) – Nome do produto
  Categoria (VARCHAR) – Categoria do produto
  Preco (DECIMAL) – Preço do produto

Vendas
  VendaID (INT, PK) – Identificador único da venda
  ClienteID (INT, FK) – Referência ao cliente
  ProdutoID (INT, FK) – Referência ao produto
  DataVenda (DATE) – Data da venda
  Quantidade (INT) – Quantidade vendida
  
Pagamentos
  PagamentoID (INT, PK) – Identificador único do pagamento
  VendaID (INT, FK) – Referência à venda
  MetodoPagamento (VARCHAR) – Ex: Cartão, Pix, Dinheiro
  ValorPago (DECIMAL) – Valor pago

  
##Observação: As chaves estrangeiras garantem a integridade entre clientes, produtos, vendas e pagamentos.
