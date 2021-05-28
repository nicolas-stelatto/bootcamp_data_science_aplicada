## Descrição do método utilizado para aquisição dos dados
  Desafio do Módulo 01 do Bootcamp de Ciência de Dados da Alura
  
### Dados selecionados:
Óbitos por Ano/mês processamento segundo Unidade da Federação
Período: Jan/2008-Mar/2021
  
### Local onde dados estão hospedados e critérios para aquisição:
- Aqui dentro do site do governo, no Ministério da Saúde, temos o Datasus, e dentro do Datasus tem o Tabnet, um sistema de acesso aos bancos de dados que nos permite fazer várias análises.
    - Link: [https://datasus.saude.gov.br/informacoes-de-saude-tabnet/](https://datasus.saude.gov.br/informacoes-de-saude-tabnet/);
- O banco de dados que vamos usar é Assistência à Saúde >> Produção Hospitalar (SIH/SUS);
- Depois disso vamos estudar Dados Consolidados AIH (RD), por local de internação, a partir de 2008 e selecionamos do Brasil por região e unidade da federação
    - Selecionamos em Linha: Unidade da Federação
    - Selecionamos em Coluna: Ano/mês processamento
    - Selecionamos em Conteúdo: Óbitos
      - Em períodos disponíveis, nós selecionamos todos os períodos disponíveis desde 2008 até a data de hoje
- Clicar em "Mostrar"
- Depois que gerar e carregar os conteúdos clicamos em Copia como .CSV

### Explicações e detalhamentos
Ano/mês processamento (esse é o mês em que o dinheiro ou atendimento é processado → seja porque foi aprovado naquela data) ≠ do ano/mês de atendimento (esse é o mês em que o paciente é realmente atendido) → Analogia com faturamento de uma venda com cartão e recebimento do dinheiro
