<div align="center">

# RESUMO SOBRE MÉTRICAS E KPIs, NEGÓCIO, ESTRUTURA ORGANIZACIONAL E ANÁLISE DE NEGÓCIOS 

### Análise de Dados 

Conjunto de Métricas e KPIs mais utilizados para Análise de Dados, conceito sobre Estrutura Organizacional, Negócios e seus objetivos e Análise de Negócios(Business Analysis).

<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge" />

</div>

---

# 1. MÉTRICAS E KPIs
Essa sequência representa praticamente toda a cadeia de valor de uma empresa. Os KPIs abaixo são os mais utilizados em empresas de varejo, indústria, e-commerce, SaaS e serviços. Além das fórmulas, é importante entender por que cada KPI existe e como ele apoia decisões

## Clientes

Objetivo: Conhecer o perfil dos clientes, medir fidelização, retenção e comportamento de compra.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Total de Clientes | — | Quantidade de clientes cadastrados | COUNT(ClientID) | Medir tamanho da base |
| Clientes Ativos | — | Clientes que compraram no período | COUNT(Clientes que compraram) | Medir engajamento |
| Clientes Inativos | — | Clientes sem compras no período | Total − Ativos | Recuperação de clientes |
| Ticket Médio | — | Valor médio gasto por pedido | Receita ÷ Pedidos | Avaliar valor das compras |
| Frequência de Compra | — | Média de compras por cliente | Pedidos ÷ Clientes | Medir recorrência |
| LTV | Lifetime Value | Valor gerado por um cliente durante o relacionamento | Ticket Médio × Compras/Ano × Tempo de Retenção | Estimar o valor de longo prazo do cliente |
| Churn Rate | Taxa de Cancelamento | Percentual de clientes perdidos | Clientes Perdidos ÷ Clientes Iniciais × 100 | Medir perda de clientes |
| Taxa de Retenção | — | Percentual de clientes mantidos | Clientes Retidos ÷ Clientes Iniciais × 100 | Medir fidelização |

## Marketing

Objetivo: Atrair potenciais clientes e gerar oportunidades de venda.

| KPI |	Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Leads | — | Pessoas interessadas | COUNT(Leads) | Medir geração de oportunidades |
| Visitantes | — | Acessos ao site | COUNT(Visitantes) | Medir alcance |
| CTR | Click Through Rate | Taxa de cliques | Cliques ÷ Impressões ×100 | Avaliar anúncios |
| CPC | Cost Per Click | Custo por clique | Investimento ÷ Cliques | Controlar custos |
| CPM | Cost Per Mille | Custo por mil impressões | Investimento ÷ (Impressões/1000) | Avaliar campanhas |
| CAC | Customer Acquisition Cost | Custo de aquisição de cliente | (Marketing + Vendas) ÷ Novos Clientes | Medir eficiência da aquisição |
| Conversão Visitante→Lead | — | Visitantes que viram leads | Leads ÷ Visitantes ×100 | Avaliar captura de leads |
| Conversão Lead→Cliente | — | Leads que compraram | Clientes ÷ Leads ×100 | Avaliar qualidade dos leads |
| ROI | Return on Investment | Retorno sobre investimento | (Receita − Investimento) ÷ Investimento ×100 | Medir retorno financeiro |

## Vendas

Objetivo: Converter oportunidades em receita.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Receita | — | Valor vendido	SUM(Vendas)	Medir faturamento |
| Número de Pedidos | — | Quantidade de vendas | COUNT(Pedido) | Volume comercial |
| Ticket Médio | — | Valor médio por pedido | Receita ÷ Pedidos | Avaliar vendas |
| Taxa de Conversão | — | Oportunidades convertidas | Vendas ÷ Oportunidades ×100 | Eficiência comercial |
| Receita por Vendedor | — | Média por vendedor | Receita ÷ Nº Vendedores | Avaliar desempenho |
| Meta Atingida | — | Percentual da meta alcançada | Receita ÷ Meta ×100 | Acompanhar resultados |
| Ciclo de Venda | — | Tempo médio para vender | Dias Totais ÷ Nº Vendas | Medir agilidade |
| Cancelamentos | — | Vendas canceladas | Cancelamentos ÷ Pedidos ×100 | Controlar perdas |
| Upsell | — | Receita de vendas adicionais | Receita Upsell ÷ Receita Total ×100 | Aumentar valor por cliente |

## Produção / Operação

Objetivo: Produzir com qualidade, eficiência e menor custo.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Produção Total | — | Quantidade produzida | SUM(Unidades) | Medir produção |
| Eficiência | — | Produção realizada em relação ao planejado | Produzido ÷ Planejado ×100 | Avaliar execução |
| OEE | Overall Equipment Effectiveness | Eficiência global dos equipamentos | Disponibilidade × Performance × Qualidade | Medir desempenho das máquinas |
| Retrabalho | — | Produtos refeitos | Retrabalho ÷ Produção ×100 | Medir desperdício |
| Refugo | — | Produtos descartados | Refugo ÷ Produção ×100 | Avaliar perdas |
| Produtividade | — | Produção por colaborador | Produção ÷ Funcionários | Medir rendimento |
| Utilização de Máquinas | — | Tempo efetivo de uso | Tempo Produzindo ÷ Tempo Disponível ×100 | Avaliar capacidade |

## Entrega

Objetivo: Garantir que o produto chegue corretamente e no prazo.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| OTD | On Time Delivery | Entregas no prazo | Entregas no Prazo ÷ Total ×100 | Medir pontualidade |
| Tempo Médio de Entrega | — | Tempo entre venda e entrega | Dias Totais ÷ Entregas | Avaliar rapidez |
| Frete Médio | — | Custo médio do frete | Frete Total ÷ Pedidos | Controlar custos |
| Taxa de Atraso | — | Percentual de atrasos | Entregas Atrasadas ÷ Total ×100 | Melhorar logística |
| Devoluções | — | Produtos devolvidos | Devoluções ÷ Entregas ×100 | Medir problemas |
| Avarias | — | Produtos danificados | Avarias ÷ Entregas ×100 | Avaliar qualidade logística |

## Pós-venda

Objetivo: Medir satisfação e fidelização dos clientes.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| NPS | Net Promoter Score | Índice de recomendação | % Promotores − % Detratores | Medir lealdade |
| CSAT | Customer Satisfaction Score | Índice de satisfação | Clientes Satisfeitos ÷ Total ×100 | Avaliar atendimento |
| CES | Customer Effort Score | Esforço do cliente | Média das notas da pesquisa | Medir facilidade de atendimento |
| Tempo | Médio de Atendimento | — | Tempo por chamado | Tempo Total ÷ Chamados | Avaliar eficiência |
| FCR | First Call Resolution | Resolução no primeiro contato | Casos Resolvidos no Primeiro Contato ÷ Total ×100 | Medir qualidade do suporte |
| Taxa de Recompra | — | Clientes que voltaram a comprar | Clientes com Nova Compra ÷ Clientes ×100 | Medir fidelização |
| Churn | — | Clientes perdidos | Clientes Perdidos ÷ Clientes ×100 | Monitorar evasão |

## Financeiro

Objetivo: Garantir sustentabilidade financeira e lucratividade.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Receita | — | Total faturado | SUM(Vendas) | Medir faturamento |
| Custos | — | Gastos diretamente ligados à operação | SUM(Custos) | Controlar custos |
| Despesas | — | Gastos administrativos e operacionais | SUM(Despesas) | Controlar despesas |
| Lucro Bruto | — | Receita menos custo dos produtos/serviços | Receita − Custo dos Produtos Vendidos | Medir rentabilidade operacional |
| Lucro Líquido | — | Resultado final após todos os custos e despesas | Receita − Custos − Despesas − Impostos | Avaliar resultado financeiro |
| Margem Líquida | — | Percentual de lucro sobre a receita | Lucro Líquido ÷ Receita ×100 | Medir rentabilidade |
| EBITDA | Earnings Before Interest, Taxes, Depreciation and Amortization | Lucro antes de juros, impostos, depreciação e amortização | Lucro Operacional + Depreciação + Amortização | Avaliar desempenho operacional |
| Fluxo de Caixa | — | Entradas menos saídas de caixa | Entradas − Saídas | Medir liquidez |
| Inadimplência | — | Contas em atraso | Valores em Atraso ÷ Total a Receber ×100 | Avaliar risco financeiro |
| Prazo Médio de Recebimento | PMR | Tempo médio para receber dos clientes | Soma dos Dias até Receber ÷ Nº de Recebimentos | Gerenciar capital de giro |

## Diretoria

Objetivo: Acompanhar o desempenho global da empresa e apoiar decisões estratégicas.

| KPI | Sigla | Significado | Fórmula | Objetivo |
| --- | ----- | ----------- | ------- | -------- |
| Receita Total | — | Faturamento consolidado | SUM(Vendas) | Medir crescimento |
| Lucro Líquido | — | Resultado final | Receita − Custos − Despesas | Avaliar desempenho financeiro |
| Crescimento da Receita | — | Evolução do faturamento | (Receita Atual − Receita Anterior) ÷ Receita Anterior ×100 | Acompanhar expansão |
| ROI | Return on Investment | Retorno sobre investimentos | (Lucro − Investimento) ÷ Investimento ×100 | Avaliar projetos e investimentos |
| ROE | Return on Equity | Retorno sobre o patrimônio líquido | Lucro Líquido ÷ Patrimônio Líquido ×100 | Medir retorno aos acionistas |
| ROA | Return on Assets | Retorno sobre os ativos | Lucro Líquido ÷ Ativos Totais ×100 | Medir eficiência no uso dos ativos |
| EBITDA | Earnings Before Interest, Taxes, Depreciation and Amortization | Indicador operacional consolidado | Conforme cálculo financeiro | Comparar desempenho entre empresas |
| Market Share | Participação de Mercado | Participação nas vendas do mercado | Vendas da Empresa ÷ Vendas Totais do Mercado ×100 | Avaliar competitividade |
| Receita por Funcionário | — | Produtividade da empresa | Receita ÷ Número de Funcionários | Medir eficiência organizacional |

## Como um analista de dados utiliza esses KPIs

Na prática, um Analista de Dados ou de BI normalmente percorre um fluxo semelhante a este:

1. Extrai os dados de sistemas como ERP, CRM, e-commerce ou banco de dados.
2. Calcula os KPIs usando SQL (com agregações, JOIN, window functions e CTEs) ou Python (pandas).
3. Valida as regras de negócio com os responsáveis por cada área (Marketing, Vendas, Financeiro etc.), garantindo que os cálculos reflitam a realidade do negócio.
4. Apresenta os resultados em dashboards e relatórios com gráficos, tabelas e comparações históricas.
5. Interpreta os indicadores, respondendo perguntas como:
* Por que o CAC aumentou este mês?
* Qual fator reduziu a margem líquida?
* Quais regiões têm menor taxa de entrega no prazo?
* Quais campanhas geraram o maior ROI?
6. Propõe ações com base nos dados, transformando números em recomendações para apoiar decisões estratégicas da empr

---

# 2. NEGÓCIOS
## O que é um negócio?

Um negócio é uma organização criada para gerar valor.

Esse valor pode ser:

* lucro (empresas privadas)
* impacto social (ONGs)
* serviços públicos (governo)
* educação
* saúde

Toda organização possui praticamente a mesma estrutura.
```
Clientes
    ↓
Marketing
    ↓
Vendas
    ↓
Produção / Operação
    ↓
Entrega
    ↓
Pós-venda
    ↓
Financeiro
    ↓
Diretoria
```
## Como funciona uma empresa (visão geral)

Imagine uma loja virtual.

Ela possui vários departamentos.
```
                      CEO
                       ↓
      ──────────────────────────────────
      ↓          ↓          ↓          ↓
  Financeiro  Marketing   Vendas    Operações
      ↓          ↓          ↓          ↓
     RH         TI     Logística  Atendimento
```
Cada departamento possui indicadores próprios.

## Fluxo completo de uma empresa
### 1. Planejamento

A empresa define objetivos.

Exemplos:

* Aumentar vendas em 20%
* Reduzir custos
* Contratar funcionários
* Abrir novas lojas
* Lançar novos produtos

Aqui surgem os KPIs.

Exemplo:

Meta:
```
Aumentar faturamento em 15%
```
Indicadores:

* Receita
* Lucro
* Ticket médio
* Clientes ativos

### 2. Marketing

Objetivo:

Atrair clientes.

Dados comuns:

* Visitas ao site
* Campanhas
* Anúncios
* Origem do cliente
* Custo por clique
* Taxa de conversão

Perguntas de negócio:

* Qual campanha trouxe mais clientes?
* Qual anúncio deu prejuízo?
* Quanto custa adquirir um cliente?

KPIs:

* CAC
* ROI
* Conversão
* Leads

### 3. Vendas

Objetivo:

Converter clientes.

Dados:

* Pedidos
* Quantidade
* Descontos
* Vendedores
* Produtos
* Regiões

Perguntas:

* Qual vendedor vende mais?
* Qual produto vende melhor?
* Em qual cidade vende mais?

KPIs:

* Receita
* Ticket médio
* Conversão
* Número de vendas

### 4. Produção

Se a empresa fabrica produtos.

Dados:

* Matéria-prima
* Tempo de produção
* Desperdício
* Máquinas
* Produtividade

Perguntas:

* Qual máquina produz mais?
* Onde existe desperdício?
* Quanto custa produzir?

### 5. Logística

Objetivo:

Entregar.

Dados:

* Transportadoras
* Frete
* Prazo
* Estoque
* Devoluções

Perguntas:

* Qual transportadora atrasa mais?
* Quanto custa entregar?
* Qual cidade gera mais frete?

KPIs:

* Tempo médio de entrega
* Frete médio
* Índice de atraso

### 6. Atendimento

Depois da venda.

Dados:

* Chamados
* Reclamações
* Satisfação
* Tempo de atendimento

KPIs:

* NPS
* CSAT
* Tempo médio de resposta

Perguntas:

* Quais clientes reclamam mais?
* Qual problema é mais frequente?

### 7. Financeiro

Talvez seja o setor mais importante para análise.

Dados:
* Receitas
* Custos
* Despesas
* Impostos
* Lucro
* Fluxo de caixa

## O que um analista de dados precisa perguntar antes de criar qualquer gráfico?

Em vez de pensar apenas em "qual gráfico usar?", procure entender o contexto do negócio. Algumas perguntas essenciais são:

* Qual problema a empresa quer resolver?
* Quem vai usar essa análise?
* Que decisão será tomada com base nela?
* Quais indicadores são relevantes?
* Como medir sucesso?
* Quais fatores podem influenciar esse resultado?
* Os dados disponíveis são suficientes e confiáveis?

Essas perguntas ajudam a transformar uma análise descritiva em uma análise útil para a tomada de decisão.

## Um roteiro de estudos em negócios para análise de dados

Uma boa sequência para construir conhecimento é:

### 1. Fundamentos de Administração
* Estrutura organizacional
* Áreas funcionais (Marketing, Vendas, Finanças, RH, Operações)
* Planejamento estratégico
### 2. Processos de Negócio
* Cadeia de valor
* Mapeamento de processos
* Indicadores de desempenho (KPIs)
### 3. Finanças para Não Financeiros
* Receita, custos, despesas e lucro
* Margem
* Fluxo de caixa
* Demonstrativos financeiros básicos
### 4. Marketing e Vendas
* Jornada do cliente
* Funil de vendas
* Segmentação
* CAC, LTV, conversão e retenção
### 5. Operações e Logística
* Gestão de estoque
* Compras
* Produção
* Supply chain
### 6. Business Intelligence e Analytics
* KPIs
* Dashboards
* Storytelling com dados
* Tomada de decisão baseada em dados
### 7. Estratégia
* Modelos de negócio
* Vantagem competitiva
* Planejamento estratégico
* Análise de mercado
---



---

## Licença
Este projeto está licenciado sob MIT License.

## Desenvolvedor focado em:

- Data Engineering
- Analytics
- R Programming
- Python Programming
- Automação de processos
- Engenharia de Software

## Contato
* Autor: Carlos da Costa
* Recife, PE - Brasil
* Telefone: +55 81 99712 9140
* Telegram: @jcarlossc
* Blogger linguagem R: https://informaticus77-r.blogspot.com/
* Blogger linguagem Python: https://informaticus77-python.blogspot.com/
* Email: jcarlossc1977@gmail.com
* LinkedIn: https://www.linkedin.com/in/carlos-da-costa-669252149/
* GitHub: https://github.com/jcarlossc
* Kaggle: https://www.kaggle.com/jcarlossc/
* Twitter/X: https://x.com/jcarlossc1977
