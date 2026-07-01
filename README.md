# SuperStore.xlsx
A SuperStore é uma rede de supermercados fictícia. O objetivo desse projeto é resolver os problemas de negócio da empresa utilizando o Excel como ferramenta principal.

# 📊 Análise de Dados com Excel | SuperStore

## 📌 Contexto

A SuperStore é uma das maiores redes de supermercados do país e enfrenta desafios relacionados à retenção de clientes, segmentação de consumidores e desempenho de produtos e regiões.

Apesar de possuir uma grande quantidade de dados sobre clientes, pedidos, produtos e localização, a empresa necessita transformar essas informações em conhecimento para apoiar a tomada de decisões estratégicas.

Este projeto foi desenvolvido utilizando exclusivamente o **Microsoft Excel**, aplicando técnicas de análise de dados, modelagem analítica e construção de dashboards interativos.

---

# 🎯 Desafio

O objetivo deste projeto foi responder às principais perguntas de negócio da empresa através de análises descritivas.

Os desafios foram divididos em três grandes frentes:

### Análise de Cohort
- Avaliar a retenção de clientes ao longo do tempo;
- Identificar quais cohorts apresentam maior retenção;
- Investigar possíveis fatores sazonais.

### Segmentação RFM
- Identificar os clientes Campeões;
- Identificar Clientes em Risco;
- Classificar toda a base de clientes em segmentos comportamentais.

### Desempenho de Produtos e Localizações
- Identificar quais categorias geram maior faturamento;
- Avaliar produtos com baixo desempenho;
- Comparar o desempenho entre regiões.

---

# 💼 Problema de Negócio

## Análise Descritiva

### Definição dos Fatos

Os fatos representam os indicadores principais analisados.

| Fato | Objetivo |
|------|----------|
| Customer ID | Retenção de clientes (Cohort) |
| Order Date | Recência |
| Order ID | Frequência |
| Sales | Monetização |
| Product ID | Desempenho dos produtos |

---

### Definição das Dimensões

As dimensões utilizadas para contextualizar os fatos foram:

- Tempo
  - Order Date
  - Ship Date

- Cliente
  - Customer ID
  - Segment

- Produto
  - Product ID
  - Category
  - Quantity
  - Discount
  - Sales

- Entrega
  - Ship Mode

- Localização
  - Region
  - State
  - City

---

### Combinação Fato × Dimensão

As análises foram construídas a partir da combinação entre fatos e dimensões.

Entre elas:

- Retenção de clientes ao longo dos meses;
- Recência das compras por cliente;
- Frequência de compras;
- Monetização por cliente;
- Receita por categoria;
- Participação percentual das categorias;
- Receita por região;
- Quantidade de pedidos por região.

---

### Definição dos Gráficos

Para comunicar os resultados foram utilizados diferentes tipos de visualização.

| Análise | Visualização |
|----------|--------------|
| Cohort | Heatmap |
| Segmentação RFM | Treemap |
| Evolução do faturamento | Linha |
| Receita por categoria | Barras |
| Participação das categorias | Barras Empilhadas (%) |
| Receita por região | Pizza |
| Categorias por região | Barras Empilhadas |

---

# ⚙️ Método SAPE

A construção do projeto seguiu a metodologia **SAPE**, dividida em três etapas.

## Saída de Dados

### Cohort

Construção da tabela contendo:

- Customer ID
- Data da primeira compra
- Data da compra
- Meses decorridos

### RFM

Cálculo dos indicadores:

- Recência
- Frequência
- Monetização
- Nota R
- Nota F
- Nota M
- Segmentação dos clientes

### Desempenho

Construção da tabela consolidada para geração dos gráficos e dashboards.

---

## Processos

Fluxo de desenvolvimento:

- Tratamento dos dados
- Construção das tabelas auxiliares
- Criação das métricas
- Desenvolvimento das tabelas dinâmicas
- Construção dos gráficos
- Desenvolvimento do Dashboard
- Interpretação dos resultados
- Geração dos insights de negócio

---

## Entrada dos dados

Arquivo Excel contendo os dados brutos para realizar as análises.

# 📈 Interpretação das Análises

## Análise Cohort

A análise mostrou o comportamento da retenção dos clientes ao longo do tempo.

Principais conclusões:

- Identificação dos cohorts com maior retenção;
- Percepção de sazonalidade na recompra;
- Redução da retenção em determinados períodos;
- Recomendações para aumento da fidelização.

---

## Segmentação RFM

A segmentação permitiu identificar grupos estratégicos de clientes.

Principais insights:

- Clientes Campeões;
- Clientes Fiéis;
- Fiéis em Potencial;
- Clientes em Risco;
- Clientes Perdidos.

Essas informações permitem desenvolver campanhas específicas para cada perfil de cliente.

---

## Desempenho de Produtos

A análise identificou:

- Categorias com maior faturamento;
- Produtos com menor participação;
- Evolução das vendas ao longo dos anos;
- Participação percentual das categorias.

---

## Desempenho Regional

Foi realizada uma comparação entre as regiões considerando:

- Receita total;
- Participação percentual;
- Mix de categorias;
- Diferenças de comportamento entre regiões.

---

# 📊 Dashboard

O projeto culmina em um dashboard totalmente desenvolvido no Excel contendo:

- Heatmap de Cohort;
- Segmentação RFM;
- Evolução das vendas;
- Receita por categoria;
- Receita por região;
- Indicadores de desempenho.

---

# 🛠 Ferramentas Utilizadas

- Microsoft Excel
- Power Query
- Tabelas Dinâmicas
- Gráficos Dinâmicos
- Formatação Condicional
- Funções Avançadas
- Dashboard Interativo

---

# 📚 Principais Técnicas Aplicadas

- Análise Cohort
- Segmentação RFM
- Modelagem Fato-Dimensão
- Análise Descritiva
- KPIs
- Storytelling com Dados
- Construção de Dashboards

---

# 🎯 Resultados

Este projeto demonstra como o Microsoft Excel pode ser utilizado como uma plataforma completa para análise de dados, permitindo transformar dados brutos em informações estratégicas para apoiar decisões de negócio.

Os insights obtidos permitem:

- Melhorar a retenção de clientes;
- Criar campanhas segmentadas;
- Otimizar o mix de produtos;
- Direcionar estratégias comerciais por região;
- Apoiar decisões baseadas em dados.
