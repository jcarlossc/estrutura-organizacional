<div align="center">

# RESUMO SOBRE MÉTRICAS E KPIs, NEGÓCIO, ESTRUTURA ORGANIZACIONAL E ANÁLISE DE NEGÓCIOS 

### Análise de Dados 

Conjunto de Métricas e KPIs mais utilizados para Análise de Dados, conceito sobre Estrutura Organizacional, Negócios e seus objetivos e Análise de Negócios(Business Analysis).

<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge" />

</div>

---

# 1. MÉTRICAS E KPIs

## Quais as diferenças?

A principal diferença é que uma métrica é um dado bruto e geral, enquanto um KPI é o indicador-chave que mostra se o negócio está atingindo suas metas estratégicas. Todo KPI é uma métrica, mas nem toda métrica é um KPI.

Para entender melhor essa relação e como aplicar cada conceito na prática:

O que é uma métrica?

* Dado bruto: Mede um evento, ação ou comportamento sem focar em uma meta específica.
* Função: Monitorar volumes e operações diárias.
* Exemplos: Número de visitas em um site, quantidade de curtidas em uma rede social ou número de ligações atendidas.

O que é um KPI (Key Performance Indicador)?

* Indicador-chave: É a métrica mais importante para a estratégia da empresa, sempre atrelada a um objetivo e a uma meta temporal.
* Função: Guiar a tomada de decisão e avaliar o sucesso de um plano.
* Exemplos: Taxa de conversão de visitantes em clientes, custo de aquisição de clientes (CAC) ou margem de lucro líquido.

A sequência a seguir representa praticamente toda a cadeia de valor de uma empresa. Os KPIs abaixo são os mais utilizados em empresas de varejo, indústria, e-commerce, SaaS e serviços. Além das fórmulas, é importante entender por que cada KPI existe e como ele apoia decisões

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

# 3. ESTRUTURA ORGANIZACIONAL
A estrutura organizacional é a forma como uma organização divide, organiza, coordena e controla suas atividades, recursos e pessoas para alcançar seus objetivos estratégicos. Ela define quem faz o quê, quem responde a quem, como as decisões são tomadas, como as informações circulam e como os diferentes departamentos trabalham em conjunto.

Em outras palavras, a estrutura organizacional é o "esqueleto" da empresa, estabelecendo a distribuição de responsabilidades, autoridade e comunicação entre todos os níveis da organização.

## Definição técnica

A estrutura organizacional pode ser definida como:

> O conjunto de regras, responsabilidades, cargos, departamentos, níveis hierárquicos, fluxos de comunicação e mecanismos de coordenação que organizam o funcionamento de uma empresa.

Ela procura responder perguntas como:

* Quem toma decisões?
* Quem executa cada atividade?
* Quem supervisiona quem?
* Como os departamentos interagem?
* Como o trabalho é dividido?
* Como os recursos são distribuídos?

## Objetivos da estrutura organizacional

Uma boa estrutura busca:

* Organizar o trabalho;
* Evitar conflitos de responsabilidade;
* Aumentar a produtividade;
* Facilitar a comunicação;
* Melhorar o controle das operações;
* Permitir crescimento da empresa;
* Apoiar a estratégia do negócio.

## Principais componentes
### 1. Divisão do trabalho

É a separação das atividades em tarefas menores.

Exemplo:

Uma empresa de e-commerce pode dividir suas atividades em:

* Compras
* Estoque
* Marketing
* Financeiro
* Atendimento
* Logística
* Tecnologia

Cada área possui responsabilidades específicas.

### 2. Especialização

Cada profissional executa atividades específicas nas quais possui conhecimento.

Exemplo:

Departamento Financeiro

* Contador
* Analista Financeiro
* Tesoureiro

Departamento de TI

* Desenvolvedor
* Cientista de Dados
* Engenheiro de Dados
* Analista de Infraestrutura

### 3. Hierarquia

Mostra os níveis de autoridade.

Exemplo:
```
Diretor
    ↓
Gerente
    ↓
Coordenador
    ↓
Supervisor
    ↓
Analista
    ↓
Assistente
```
Quanto mais alto o nível, maior o poder de decisão.

### 4. Cadeia de comando

Define para quem cada funcionário responde.

Exemplo:
```
Analista
↓
Coordenador
↓
Gerente
↓
Diretor
```
Isso evita conflitos de liderança.

### 5. Autoridade

É o poder formal para tomar decisões.

Exemplo:

Um gerente pode:

* Aprovar férias;
* Contratar pessoas;
* Definir orçamento;
* Distribuir tarefas.

### 6. Responsabilidade

É o dever de executar determinada atividade.

Exemplo:

O analista financeiro é responsável por elaborar o fluxo de caixa.

### 7. Delegação

Consiste em transferir autoridade para outra pessoa executar determinada atividade.

Exemplo:

O gerente delega ao coordenador a responsabilidade por acompanhar um projeto.

### 8. Amplitude de controle (span of control)

Representa quantas pessoas um gestor supervisiona diretamente.

Exemplo:
```
Gerente
↓
Analista A
Analista B
Analista C
Analista D
Analista E
```
Amplitude = 5 colaboradores.

Uma amplitude muito grande pode dificultar a supervisão; uma muito pequena pode aumentar custos administrativos.

### 9. Centralização

As decisões ficam concentradas nos níveis superiores.

Exemplo:

Somente a diretoria pode aprovar compras.

Vantagens:

* Maior controle;
* Padronização.

Desvantagens:

* Decisões mais lentas;
* Pouca autonomia.

### 10. Descentralização

As decisões são distribuídas entre vários níveis.

Exemplo:

Cada gerente aprova compras até determinado valor.

Vantagens:

* Rapidez;
* Autonomia;
* Inovação.

Desvantagens:

* Menor padronização;
* Risco de decisões inconsistentes.

### 11. Formalização

Representa o nível de regras existentes.

Uma empresa altamente formalizada possui:

* Procedimentos;
* Normas;
* Políticas;
* Documentação;
* Manuais.

### 12. Coordenação

É o mecanismo utilizado para integrar os departamentos.

Exemplo:

Marketing precisa comunicar campanhas para:

* Vendas;
* Estoque;
* Logística.

## Departamentalização

É a forma de dividir a empresa.

Existem diversos tipos.

### 1. Funcional

Agrupa pessoas pela função.
```
Empresa
├── Financeiro
├── RH
├── Marketing
├── TI
├── Comercial
```
É o modelo mais comum.
### 2. Por produto
```
├── Linha A
├── Linha B
├── Linha C
```
Cada produto possui equipe própria.
### 3. Por cliente
```
Empresa
├── Pessoa Física
├── Pessoa Jurídica
├── Governo
```
### 4. Por região
```
Empresa
├── Norte
├── Nordeste
├── Sul
├── Exterior
```
### 5. Por processo
```
Produção
↓
Montagem
↓
Qualidade
↓
Distribuição
```
Muito usado na indústria.
### 6. Matricial
O colaborador responde para dois gestores.

Exemplo:
```
           Diretor
          /       \
 Gerente TI      Gerente Projeto
         \        /
        Desenvolvedor
```
É comum em empresas de tecnologia e consultorias.

## Tipos de estrutura organizacional
### 1. Estrutura funcional

Organizada por departamentos especializados.

Vantagens:

* Especialização;
* Eficiência;
* Economia de recursos.

Desvantagens:

* Pouca integração entre áreas;
* Comunicação em "silos".

### 2. Estrutura divisional

Cada divisão possui praticamente todos os departamentos necessários.

Exemplo:
```
Divisão Celulares
Divisão Computadores
Divisão Tablets
```
Cada divisão tem:

* RH;
* Financeiro;
* Marketing;
* Vendas.

### 3. Estrutura matricial

Mistura estrutura funcional e por projetos.

Muito utilizada em:

* Tecnologia;
* Engenharia;
* Consultorias.

### 4. Estrutura em rede

A empresa terceiriza várias atividades.

Exemplo:

* Produção terceirizada;
* Logística terceirizada;
* Marketing terceirizado.

A empresa atua como coordenadora das operações.

### 5. Estrutura horizontal

Poucos níveis hierárquicos.

Características:

* Autonomia;
* Equipes multidisciplinares;
* Decisões rápidas;
* Menor burocracia.

Muito comum em startups.

## Organograma

É a representação gráfica da estrutura organizacional.

Exemplo:
```
CEO
├── Diretor Financeiro
│      ├── Contabilidade
│      └── Tesouraria
│
├── Diretor Comercial
│      ├── Vendas
│      └── Marketing
│
├── Diretor de Operações
│      ├── Produção
│      └── Logística
│
└── Diretor de TI
       ├── Infraestrutura
       ├── Desenvolvimento
       └── Dados
```

## Fluxo de comunicação

Pode ocorrer de diferentes formas:

* Vertical descendente: da diretoria para os colaboradores.
* Vertical ascendente: dos colaboradores para a gestão.
* Horizontal: entre pessoas do mesmo nível hierárquico.
* Diagonal: entre diferentes áreas e níveis.

## Relação com a estratégia

A estrutura organizacional deve estar alinhada aos objetivos da empresa.

Exemplos:

* Uma startup pode adotar uma estrutura horizontal para ganhar agilidade.
* Uma multinacional tende a utilizar estruturas divisionais ou matriciais para coordenar operações em diferentes mercados.
* Uma fábrica pode organizar-se por processos para otimizar a produção.

## Importância para a Análise de Dados

Para um analista de dados, compreender a estrutura organizacional é essencial porque ela influencia como os dados são gerados, utilizados e compartilhados. Alguns benefícios práticos são:

* Identificar os responsáveis por cada conjunto de dados (data owners);
* Entender como os processos de negócio atravessam diferentes departamentos;
* Interpretar corretamente indicadores de desempenho (KPIs) de cada área;
* Mapear fluxos de informação e gargalos;
* Facilitar a comunicação com gestores e equipes técnicas;
* Apoiar a definição de requisitos para projetos de dados e inteligência de negócios.

Por exemplo, ao analisar uma queda nas vendas, um analista pode precisar integrar informações do Comercial, Marketing, Logística, Estoque e Financeiro. Conhecer a estrutura organizacional ajuda a entender como essas áreas se relacionam e quem deve ser envolvido na investigação.

## Resumo

A estrutura organizacional é o modelo que define como uma empresa distribui funções, responsabilidades, autoridade e comunicação para executar suas atividades e atingir seus objetivos. Ela engloba a divisão do trabalho, a hierarquia, a departamentalização, os mecanismos de coordenação e os fluxos de decisão, servindo como base para a gestão eficiente das operações e para o alinhamento entre pessoas, processos e estratégia. Para profissionais de análise de dados, esse conhecimento é fundamental para interpretar o contexto de negócio e transformar dados em informações úteis para a tomada de decisão.

---

# 4. ANÁLISE DE NEGÓCIOS (Business Analysis)
Esses conhecimentos fazem parte da análise de negócios (Business Analysis) e da governança de dados (Data Governance). Um analista de dados não trabalha apenas com tabelas e gráficos; ele precisa entender como a empresa funciona para transformar dados em decisões.

## 1. Identificar os responsáveis por cada conjunto de dados (Data Owners)
Definição

O Data Owner (dono do dado) é a pessoa ou área responsável pela qualidade, regras de negócio e uso de um conjunto de dados.

Ele não é necessariamente quem mantém o banco de dados.

O banco pode ser administrado pela TI, mas o dono da informação normalmente é uma área de negócio.

Por exemplo:
| Conjunto de dados | Data Owner |
| ----------------- | ---------- |
| Clientes | Comercial |
| Funcionários | RH |
| Produtos | Compras |
| Estoque | Logística |
| Vendas | Comercial |
| Financeiro | Financeiro |

### Exemplo 1

Você possui a tabela:
```
Clientes
---------
id
nome
cpf
telefone
email
```
O telefone está errado.

Quem decide qual é o telefone correto?

Não é o DBA.

Não é o Analista de Dados.

É a área Comercial (ou Atendimento), que é dona dessa informação.

### Exemplo 2

Tabela
```
Funcionarios
-----------
Nome
Salario
Cargo
```
Você percebe salários incorretos.

Quem deve validar?

O RH.

### Exemplo 3

Tabela
```
Produtos
--------
Nome
Preço
Categoria
```
O preço está errado.

Quem decide o preço?

A área Comercial ou Produtos.

### Analogia

Imagine uma biblioteca.

O bibliotecário organiza os livros.

Mas quem escreveu o livro é o autor.

O DBA organiza os dados.

O Data Owner é o "autor" das regras daquele dado.

## 2. Entender como os processos de negócio atravessam diferentes departamentos
### Definição

Um processo de negócio raramente acontece dentro de apenas um departamento.

Normalmente ele passa por diversas áreas.

### Exemplo: Compra em um e-commerce
```
Cliente faz pedido
↓
Comercial recebe
↓
Financeiro aprova pagamento
↓
Estoque separa produto
↓
Logística envia
↓
Cliente recebe
```
Temos cinco departamentos envolvidos.

### Exemplo empresarial

Pedido de compra:
```
Solicitação
↓
Compras
↓
Financeiro
↓
Fornecedor
↓
Recebimento
↓
Estoque
```
Cada etapa gera dados diferentes.

### Exemplo bancário

Pedido de empréstimo
```
Cliente
↓
Agência
↓
Análise de crédito
↓
Jurídico
↓
Financeiro
↓
Liberação
```
Cada departamento cria informações.

### O que o analista precisa entender?
* Onde nasce o dado?
* Onde ele é alterado?
* Quem utiliza?
* Quem aprova?
* Quem depende dele?

## 3. Interpretar corretamente indicadores de desempenho (KPIs)
### Definição

KPI (Key Performance Indicator) é uma métrica usada para medir se um objetivo está sendo alcançado.

Nem toda métrica é um KPI.

## Exemplo

Uma loja vende: 1000 produtos.

Isso é uma métrica.

Agora:

Meta: 900 vendas

Resultado: 1000 vendas

Agora virou um KPI porque mede desempenho.

## Exemplo prático

Você vê:
```
Receita = R$ 8 milhões
```
Isso significa pouco.

Agora:

Meta: R$ 10 milhões

Realizado: R$ 8 milhões

Resultado: 80%

Agora faz sentido.

## 4. Mapear fluxos de informação e gargalos
### Definição

Fluxo de informação é o caminho percorrido pelos dados dentro da empresa.

Gargalo é um ponto onde esse fluxo fica lento ou problemático.
### Exemplo
```
Pedido online
↓
ERP
↓
Financeiro
↓
Estoque
↓
Transportadora
↓
Cliente
```
Se o estoque demora dois dias para atualizar...

Esse é um gargalo.

### Outro exemplo
```
Cadastro
↓
Validação
↓
Aprovação
↓
Banco
↓
Dashboard
```
Se a aprovação demora uma semana...

Há um gargalo

### Como descobrir?
* Perguntar:
* Quem gera?
* Quem recebe?
* Quanto tempo demora?
* Quem altera?
* Onde costuma dar erro?

## 5. Facilitar a comunicação com gestores e equipes técnicas
### Definição

O analista de dados é frequentemente uma ponte entre quem toma decisões e quem implementa soluções.

### Gestor fala:

"Quero saber quais clientes são mais lucrativos."

### Desenvolvedor entende:

Preciso calcular:
```
Lucro
=
Receita
-
Custos
```
### Analista traduz

Precisamos:
* Tabela de vendas
* Tabela de custos
* Tabela de clientes
* Relacionamentos
* Regra de cálculo

### Outro exemplo

Gestor:

"Quero clientes ativos."

Analista pergunta:

O que significa "ativo"?

Comprou nos últimos 30 dias?

90 dias?

12 meses?

Sem essa definição, a análise pode estar errada.

## 6. Apoiar a definição de requisitos para projetos de dados e BI
##Definição

Antes de construir um dashboard ou relatório, é preciso definir claramente o que será entregue.

Esses requisitos evitam retrabalho.

## Exemplo

Gestor pede:

"Quero um dashboard de vendas."

Isso é muito genérico.

O analista deve detalhar.

## Requisitos

Quais indicadores?

Por período?

Por estado?

Por vendedor?

Atualização diária?

Mensal?

Exportação para Excel?

Filtros?

Gráficos?

### Exemplo completo

Pedido inicial:

"Quero acompanhar as vendas."

Após levantamento dos requisitos:

* Receita diária
* Receita mensal
* Ticket médio
* Clientes novos
* Produtos mais vendidos
* Comparação com mês anterior
* Filtro por estado
* Filtro por vendedor
* Atualização automática às 6h

Agora existe uma especificação clara para a equipe técnica implementar.

## Exemplo integrando todas as etapas

Imagine que a diretoria deseja um dashboard para acompanhar as vendas.

* Identificar os responsáveis pelos dados: você conversa com o Comercial (vendas), Financeiro (pagamentos) e Logística (entregas) para entender quais dados cada área fornece e quem pode validar inconsistências.
* Entender o processo de negócio: mapeia o fluxo completo: cliente faz o pedido → pagamento é aprovado → estoque separa o produto → transportadora entrega → financeiro registra a receita.
* Definir os KPIs: com os gestores, estabelece indicadores como faturamento, ticket médio, percentual de entregas no prazo e taxa de cancelamento.
Mapear fluxos e gargalos: identifica que os dados de entrega só chegam ao banco uma vez por dia, fazendo com que o dashboard apresente informações defasadas.
* Facilitar a comunicação: traduz a necessidade do gestor ("quero acompanhar atrasos nas entregas") em requisitos técnicos ("calcular a diferença entre a data prevista e a data efetiva de entrega, por transportadora").
D* efinir os requisitos do projeto: documenta quais fontes de dados serão utilizadas, quais filtros o dashboard terá, a frequência de atualização, as regras de cálculo dos KPIs e quais usuários terão acesso.

Esse ciclo é comum em projetos de Business Intelligence (BI) e Analytics. Quanto melhor o analista compreender o negócio, mais útil será a solução de dados entregue para a empresa.

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
