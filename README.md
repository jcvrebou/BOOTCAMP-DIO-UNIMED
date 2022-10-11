# BOOTCAMP-DIO-UNIMED - MODELAGEM CONCEITUAL DE BANCO DE DADOS DE E-COMMERCE

### Instâncias Criadas

- Cliente: pode ser pessoa física ou jurídica. Esta instância é retroalimentada pelas instâncias ENDEREÇO e TIPO_PESSOA.

- Parceiro(Vendas): pode ser pessoa física ou jurídica. Esta instância é retroalimentada pelas instâncias ENDEREÇO e TIPO_PESSOA.

- Fornecedor: pessoa jurídica. pode ser pessoa física ou jurídica. Esta instância é retroalimentada pelas instâncias ENDEREÇO e TIPO_PESSOA.	

- Endereço: base com cadastro de endereços que retroalimenta instâncias CLIENTE, FORNECEDOR, PARCEIRO.

- Tipo_Pessoa: base com cadastro de CPF e CNPJ que retroalimenta instâncias CLIENTE, FORNECEDOR, PARCEIRO.

- Estoque: concentra todos os itens e é retroalimentado pela instância FORNECEDOR.

- Formas_Pagamento: concentra todas as formas de pagamento e é retroalimentada pela instância CARTÃO.

- Pedido: concentra os pedidos feitos por CLIENTE e PARCEIRO, sendo retroalimentado por essas instâncias e também por FORMA_PAGAMENTO e ESTOQUE.
