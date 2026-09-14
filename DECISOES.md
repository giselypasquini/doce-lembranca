# Decisões oficiais — Produtos, preços e receitas

## Catálogo de produtos

- A tela **Produtos e preços** deve exibir todos os doces cadastrados para venda.
- Cada doce deve permitir alteração de preço e ativação/desativação para encomendas.
- Produtos de venda são separados das receitas internas.

## Alteração de preço

- O preço atualizado deve ser usado automaticamente em novos pedidos.
- Pedidos já criados ou confirmados preservam o preço combinado no momento do pedido.
- Alterar o preço de venda não altera a receita interna, seus ingredientes, rendimento ou custos.

## Dados ainda pendentes

- A lista oficial de doces, preços, custos, rendimentos e validades ainda será cadastrada depois dos testes com dados fictícios.

## Compras, lotes e validade

- Uma compra pode ser lançada por embalagem, com conversão para a unidade real de estoque.
- Exemplo: 10 caixas com 27 unidades acrescentam 270 unidades ao estoque; 1 unidade acrescenta 1 unidade.
- Lote e validade podem ser informados quando existirem, mas são opcionais e não podem bloquear o lançamento da compra.
