# Evidências dos Testes e Correções — PIT II

**Aluno:** Gustavo Henrique Amaro Beato da Costa  
**RGM:** 34168451  
**Projeto:** Aplicativo de vendas online para loja de cupcakes gourmet  
**Data dos testes:** 15/11/2026

## Participantes
- Eduardo Henrique Batista
- Renata Cristina Oliveira
- Caio Augusto Pereira
- Gabriela Martins Teixeira
- Leonardo Alves Ribeiro

## 1. Mensagem do carrinho
**Problema identificado:** a mensagem exibida após adicionar um cupcake apresentava pouco destaque.

**Correção aplicada:** foram criadas mensagens distintas para sucesso e erro, com melhor contraste e texto mais claro.

**Evidência:** classes `msg ok` e `msg erro` e função `mensagem()` adicionadas ao `index.html`.

## 2. Validação dos campos obrigatórios
**Problema identificado:** a orientação para campos não preenchidos era pouco específica.

**Correção aplicada:** o sistema passou a verificar nome, telefone, endereço, pagamento e entrega, listando os campos faltantes.

**Evidência:** nova lógica de validação no evento de finalização.

## 3. Acompanhamento do pedido
**Problema identificado:** a etapa atual do pedido não possuía destaque suficiente.

**Correção aplicada:** a fase “Pedido recebido” passou a ser destacada e identificada como “atual”.

**Evidência:** atualização do componente de status no `index.html`.

## 4. Responsividade
**Problema identificado:** alguns elementos ficavam muito próximos em telas pequenas.

**Correção aplicada:** foram ampliados os espaçamentos entre campos, botões, itens e etapas do pedido.

**Evidência:** novas regras no media query para telas de até 600 pixels.

## 5. Confirmação final
**Problema identificado:** a confirmação apresentava poucas informações.

**Correção aplicada:** foi incluído um resumo com número do pedido, nome do cliente, forma de pagamento, modalidade de entrega e status atual.

**Evidência:** novo bloco `confirmacao` na interface.

## Nova verificação
Após os ajustes, foram revistos catálogo, carrinho, mensagens de retorno, validações, pagamento, entrega, acompanhamento, confirmação e responsividade. O fluxo principal apresentou funcionamento satisfatório.

## Funcionalidades ainda não implementadas
- cadastro e login;
- processamento real de pagamentos;
- rastreamento em tempo real;
- histórico de pedidos;
- área administrativa;
- testes em maior variedade de dispositivos e navegadores.
