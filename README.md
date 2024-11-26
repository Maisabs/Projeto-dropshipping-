
# Sistema de Gestão de Dropshipping

Este repositório contém o código-fonte e a estrutura de banco de dados desenvolvidos para um sistema de gestão de dropshipping, focado em facilitar o gerenciamento de clientes, produtos, fornecedores e pedidos.

## Descrição do Projeto

O projeto foi desenvolvido para atender um grupo de empreendedores que trabalham com dropshipping. A solução criada permite gerenciar informações essenciais, automatizar o controle de estoque e pedidos, e integrar fornecedores e clientes de forma eficiente.

## Funcionalidades

- **Cadastro de Clientes:** Armazenamento de informações de contato e endereço dos clientes.
- **Gestão de Produtos:** Registro de produtos com detalhes como nome, descrição, preço e estoque.
- **Controle de Fornecedores:** Cadastro e consulta de fornecedores associados aos produtos.
- **Gerenciamento de Pedidos:** Criação e acompanhamento de pedidos, com cálculo automático do total.
- **Itens dos Pedidos:** Associação de produtos específicos a cada pedido.

## Estrutura das Tabelas

- **Clientes:** id, nome, email, telefone, endereço.
- **Produtos:** id, nome, descrição, preço, quantidade_estoque, fornecedor_id.
- **Fornecedores:** id, nome, contato, endereço.
- **Pedidos:** id, cliente_id, data_pedido, status, total.
- **Itens_Pedido:** id, pedido_id, produto_id, quantidade, preco.

## Tecnologias Utilizadas

- **Banco de Dados:** Supabase (PostgreSQL)
- **Desenvolvimento:** SQL
- **Hospedagem:** GitHub

## Instalação e Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/Maisabs/Projeto-dropshipping-.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd Projeto-dropshipping-
   ```

3. Importe o script SQL no Supabase ou em qualquer banco PostgreSQL compatível.


## Contato

Para dúvidas ou sugestões, entre em contato comigo através do [GitHub](https://github.com/Maisabs).

