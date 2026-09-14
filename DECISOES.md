# Decisões oficiais — Produtos, preços e receitas

## Catálogo de produtos

- A tela **Produtos e preços** deve exibir todos os doces cadastrados para venda.
- Cada doce deve permitir alteração de preço e ativação/desativação para encomendas.
- Produtos de venda são separados das receitas internas.
- Produtos e preços devem aparecer em uma lista geral, sem caixas de cadastro; cada item terá a opção Editar.
- Cada doce terá uma foto única compartilhada entre receita, pedido e Produtos e preços.
- Toda receita de doce vendável deve gerar automaticamente um item correspondente na lista Produtos e preços.
- Receitas classificadas como Preparos internos são exceção e não entram na lista de produtos de venda.

## Alteração de preço

- O preço atualizado deve ser usado automaticamente em novos pedidos.
- Pedidos já criados ou confirmados preservam o preço combinado no momento do pedido.
- Alterar o preço de venda não altera a receita interna, seus ingredientes, rendimento ou custos.

## Dados ainda pendentes

- A lista oficial de doces, preços, custos, rendimentos e validades ainda será cadastrada depois dos testes com dados fictícios.

## Compras, lotes e validade

- A compra deve seguir um lançamento simples, como em um depósito ou mercado: item, categoria, unidade-base, unidade da compra, quantidade comprada, valor total pago e data.
- A quantidade é informada na unidade em que foi comprada e convertida para a unidade-base do estoque quando necessário.
- Exemplo: leite condensado com estoque em g: 5 kg acrescentam 5.000 g; 395 g acrescentam 395 g. Utensílios usam unidade.
- As compras têm somente três categorias: Material de consumo, Utensílio e Equipamento. Ingredientes, confeitos e embalagens entram como Material de consumo.
- Lote e validade podem ser informados quando existirem, mas são opcionais e não podem bloquear o lançamento da compra.
- Lote e validade devem poder ser desativados em Configurações; quando desativados, os campos ficam ocultos no lançamento de compras.
