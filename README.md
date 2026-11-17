# Dashboard de Salários na Área de Dados

Dashboard interativo desenvolvido em **Python** para exploração e visualização de dados salariais na área de dados, com filtros dinâmicos, KPIs e gráficos interativos.

---

## Funcionalidades

- **Filtros Dinâmicos na Barra Lateral:** seleção por ano, senioridade, tipo de contrato e porte da empresa.
- **Indicadores Principais (KPIs):** salário médio anual, salário máximo, total de registros e cargo mais frequente.
- **Visualizações Interativas (Plotly):**
  - Top 10 cargos por salário médio (gráfico de barras horizontal)
  - Distribuição de salários anuais (histograma)
  - Proporção por modalidade de trabalho (gráfico de rosca)
  - Salário médio de *Data Scientist* por país (mapa coroplético)
- **Tabela Detalhada:** visualização completa dos dados filtrados.

---

## Stack Tecnológica

- **Python**
- **Pandas** (`2.2.3`) — tratamento, filtragem e agregação de dados
- **Streamlit** (`1.44.1`) — interface web interativa
- **Plotly** (`5.24.1`) — gráficos dinâmicos e mapa geográfico
- **Jupyter Notebook** (`codigos_aula.ipynb`) — análise exploratória inicial

---

## Como Executar Localmente

```bash
# 1. Clonar o repositório
git clone https://github.com/Edudu720/imers-o-dados-panda.git
cd imers-o-dados-panda

# 2. Instalar as dependências
pip install -r requirements.txt

# 3. Executar a aplicação Streamlit
streamlit run app.py
```
