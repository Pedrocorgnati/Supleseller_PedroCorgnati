# Superseller
COMO É O SISTEMA?
É um PDV de frente de caixa que avisa o empresário todo dia de manhã com mensagens prontas para disparar com um clique as seguintes coisas:
- Produto do cliente está acabando [DISPARAR]
- Promoção de um produto específico que o cliente toma [DISPARAR]
- Cliente fazendo aniversário [DISPARAR]

Além de ser um PDV convencional:
- Vendas
- Gestão de estoque
- Emissão de NF-e

QUAL A ROTINA DO EMPRESÁRIO
Liga o sistema
Faz os disparos do dia
Faz as vendas normalmente
Fecha o sistema

 CADASTROS
Cadastro do produto
Entra o produto com os dados dele.
O tipo de produto que é: pote, frasco, refil, etc.
O tempo que o cliente demora pra tomar ele. Ex: Whey 900g - 30 dias.
Cadastro do cliente
Nome
Gênero
Whatsapp
Aniversário

Padrões de mensagens
Cria um modelo "preenchivel" da mensagem que o sistema vai disparar para cada ocasião (promoção, vendas, aniversários), mensagem pode ser personalizada pelo genero do cliente também(Ex: "Faaala monstro" para eles, "Oi minha querida" para elas). 
Exemplo:
Olá {nome}, estou com uma super promoção do {produto que tá acabando hoje}, lembrei de você, já que você gosta deste produto! Gostaria que eu te enviasse um {recipiente, pote, frasco} nessa promoção?

SISTEMA OPERANDO
1 - Faz a venda de um whey para o João.
2 - Se o João não tiver cadastro ainda, coloca o whatsapp dele e clica em adicionar, vai para um semi-cadastro que você finaliza depois.
3 - Faz a venda dos produtos, 
4 - O sistema lança tudo no banco de dados e prepara as mensagens para os dias certos.
5 - No dia que o whey teoricamente for acabar, logo cedo vai ter um botão piscando na tela "REVISAR E ENVIAR", clicando abre a lista com "nome, produto, motivo do contato", o empresário exclui algum que não for para enviar e faz o disparo em massa.
6 - O sistema vai fazendo ao longo da manhã os disparos com intervalos aleatórios para não gerar bloqueios.
