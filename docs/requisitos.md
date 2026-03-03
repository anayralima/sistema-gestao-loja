REQUISITOS FUNCIONAIS

Cadastros

RF01 – O sistema deve permitir manter cadastro de produtos (incluir, alterar, excluir e consultar).
RF02 – O sistema deve permitir manter cadastro de clientes.
RF03 – O sistema deve permitir manter cadastro de fornecedores.
RF04 – O sistema deve permitir manter cadastro de usuários.

Vendas

RF05 – O sistema deve permitir registrar uma venda.
RF06 – O sistema deve permitir adicionar produtos à venda.
RF07 – O sistema deve calcular automaticamente o valor total da venda.
RF08 – O sistema deve permitir selecionar a forma de pagamento (dinheiro, cartão de crédito ou cheque).
RF09 – O sistema deve emitir NFCe ao finalizar a venda.
RF10 – O sistema deve atualizar automaticamente o estoque após a conclusão da venda.

Pedidos

RF11 – O sistema deve permitir registrar pedido quando o produto não estiver disponível em estoque.
RF12 – O sistema deve associar o pedido ao cliente.
RF13 – O sistema deve permitir registrar e comparar cotações entre fornecedores.
RF14 – O sistema deve permitir registrar a entrada de produtos no estoque.
RF15 – O sistema deve permitir registrar o aviso ao cliente sobre a chegada do produto.

Controle de Caixa

RF16 – O sistema deve registrar automaticamente as movimentações de caixa.
RF17 – O sistema deve gerar relatório diário de fechamento de caixa.
RF18 – O sistema deve permitir registrar a conferência dos valores recebidos por forma de pagamento.

Comissão

RF19 – O sistema deve calcular automaticamente a comissão mensal de cada vendedor.
RF20 – O sistema deve gerar relatório com o total vendido por vendedor e o valor da comissão.

REQUISITOS NÃO FUNCIONAIS

RNF01 – O sistema deve exigir autenticação por login e senha para acesso.
RNF02 – O sistema deve permitir controle de acesso por perfil de usuário.
RNF03 – O sistema deve permitir o registro de vendas mesmo sem conexão com o servidor.
RNF04 – O sistema deve recuperar automaticamente a venda em andamento após reinicialização do computador.

REGRAS DE NEGÓCIO

RN01 – O vendedor deve receber comissão de 10% sobre o total de vendas realizadas no mês.
RN02 – A venda somente pode ser finalizada após definição da forma de pagamento.
RN03 – O produto somente pode ser vendido se houver quantidade disponível em estoque.

REQUISITO NORMATIVO

RNOR01 – O sistema deve emitir Nota Fiscal de Consumidor Eletrônica (NFCe), conforme legislação vigente.

REQUISITOS DE IMPLEMENTAÇÃO

Não há.

