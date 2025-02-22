# desafio-banco-de-dados-ecommerce-Heineken
Refinamento do modelo de dados de e-commerce como parte do Desafio de Projeto DIO Heineken

# Refinamento do Modelo de Dados para E-commerce - Desafio de Projeto DIO


## Descrição do Projeto

Este projeto refina um modelo de dados para e-commerce, focando em clientes, pagamentos e entregas, como parte do Desafio de Projeto DIO. O objetivo é criar um esquema de banco de dados mais completo e robusto.

## Objetivos do Refinamento

O modelo foi aprimorado para incluir:

*   **Clientes PF e PJ:** Distinção clara entre Pessoa Física e Jurídica.
*   **Múltiplas Formas de Pagamento:** Suporte para diversas formas de pagamento por cliente.
*   **Rastreamento de Entregas:**  Status e código de rastreio para entregas.

## Modelo de Dados

O esquema inclui as seguintes tabelas principais:

*   **`client`**:  Clientes (base PF/PJ).
*   **`client_pf`**:  Informações de Pessoa Física.
*   **`client_pj`**:  Informações de Pessoa Jurídica.
*   **`payment_method`**: Formas de Pagamento do Cliente.
*   **`product`**: Produtos.
*   **`orders`**: Pedidos (com status e rastreio de entrega).
*   **`productStorage`**: Estoque de Produtos.
*   **`supplier`**: Fornecedores.
*   **`seller`**: Vendedores.
*   **Tabelas de relacionamento**:  `productSeller`, `productOrder`, `storeagelocation`, `ProductSupplier`.

O modelo foi personalizado para diferenciar clientes PF/PJ, suportar múltiplos pagamentos e rastrear entregas.

## Como Executar

1.  Execute o script SQL (ex: `criar_banco_de_dados_ecommerce.sql`) em um cliente MySQL para criar o banco de dados `ecommerce` e as tabelas.
2.  [Opcional] Execute o script de inserção de dados (ex: `inserir_dados_ecommerce.sql`) para popular o banco com exemplos.

## Autor

[Alan Felipe NR]
