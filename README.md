# 🚚 Inteligência de Mercado e Logística: E-Commerce Olist

MBA em Data Science & Advanced Analytics


### 🎯 Objetivo 

O objetivo foi mapear indicadores comerciais e entender o impacto da distribuição geográfica e dos custos de envio no desempenho do e-commerce brasileiro.
Atuando sob a ótica de **Inteligência de Logística**, o projeto realizou a integração de múltiplas bases de dados (clientes, pedidos e itens faturados) para diagnosticar o comportamento do faturamento, identificar assimetrias de mercado e avaliar como o valor do frete dita o comportamento de compra entre os estados.

---

### 🔍 Diagnóstico dos Dados e Resultados Estratégicos

#### 1. Comportamento Financeiro e Impacto de Outliers
* **Assimetria de Faturamento:** O estudo identificou que a receita do e-commerce possui uma forte concentração em faixas específicas, apresentando alta assimetria.
* **Média vs. Mediana:** A grande divergência entre a média e a mediana evidenciou a presença de pedidos de valor muito elevado (*outliers*). Enquanto a média é puxada para cima por compras corporativas ou de grandes volumes, a mediana revelou o valor real gasto pelo consumidor padrão.

#### 2. Análise de Logística e Fretes: O Cenário Regional
* **Concentração de Demanda:** Como esperado no cenário logístico nacional, a região Sudeste (liderada por São Paulo) concentra a maior fatia do volume de pedidos e receita total.
* **O Paradoxo do Ticket Médio na Região Norte:** Embora registre um volume menor de transações, a região Norte destacou-se com o **maior ticket médio por pedido**.
* **Elasticidade do Frete:** O cruzamento de dados comprovou que esse fenômeno é diretamente impulsionado pelo **custo de envio (frete)** para essa localidade. Para compensar as barreiras logísticas e o frete mais oneroso, o consumidor nortista altera sua estratégia de compra, concentrando o consumo em produtos de maior valor agregado ou agrupando mais itens por pedido.

#### 3. Mapeamento Geoespacial Interativo
Para consolidar os achados de logística e mercado, foi estruturada uma visualização em mapa que detalha, por Unidade Federativa (UF):
1. **Faturamento Total** (Concentração de receita).
2. **Volume de Pedidos** (Densidade de entregas por estado).
3. **Concentração de Clientes** (Pólos de demanda ativa).

---

### 🛠️ Ferramentas Utilizadas
* **Python**: Linguagem utilizada para o tratamento dos dados.
* **Pandas & NumPy**: Fusão de tabelas (`merge`), tratamento de nulos e modelagem dos indicadores descritivos.
* **Plotly**: Construção de gráfico de barras e mapa em gradiente com parametrização geoespacial (update_layout, update_geos) interativos.

---

#### 🗃️ Sobre a Base de Dados
O estudo utiliza dados públicos reais da **Olist**, disponíveis no Kaggle.
