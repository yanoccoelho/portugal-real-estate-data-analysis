# Análise de Preços de Imóveis em Portugal

## Visão Geral
Este projeto tem como objetivo analisar os preços de imóveis em Portugal utilizando dados do dataset "Portugal Real Estate 2024" do Kaggle. A análise inclui a exploração de tendências, variações temporais, distribuição geográfica dos preços e possíveis fatores que influenciam os valores dos imóveis.

## Estrutura do Projeto
O projeto está estruturado da seguinte forma:

```
📂 portugal-real-estate-data-analysis/
│── 📂 data/
│   │── 📂 raw/  (dados brutos, sem modificações)
│   │── 📂 processed/  (dados limpos e transformados)
│
│── 📂 notebooks/
│   │── data_import_and_preprocessing.ipynb  (importação e tratamento inicial)
│   │── data_transformation.ipynb  (engenharia de features e normalização)
│   │── exploratory_analysis.ipynb  (análise exploratória de dados - EDA)
│   │── missing_data_and_outliers.ipynb  (tratamento de valores ausentes e outliers)
│   │── statistical_analysis.ipynb  (estatísticas descritivas e inferências)
│   │── model_building.ipynb  (modelos preditivos para preços de imóveis)
│
│── 📂 src/  (scripts auxiliares)
│
│── .gitignore  (arquivos que não serão versionados)
│── README.md  (documentação do projeto)
│── requirements.txt  (lista de bibliotecas necessárias)
```

## Etapas do Projeto
1. **Importação e Limpeza dos Dados**
   - Carregar o dataset do Kaggle.
   - Tratar valores ausentes e inconsistentes.
   - Padronizar os dados para facilitar a análise.

2. **Transformação e Engenharia de Features**
   - Criar novas variáveis a partir dos dados existentes.
   - Converter variáveis categóricas em numéricas.

3. **Análise Exploratória (EDA)**
   - Examinar a distribuição dos preços dos imóveis.
   - Avaliar correlação entre variáveis relevantes.
   - Visualizar a distribuição geográfica dos preços.

4. **Tratamento de Valores Ausentes e Outliers**
   - Identificar e corrigir dados faltantes.
   - Lidar com valores extremos que possam distorcer as análises.

5. **Testes Estatísticos e Modelagem Preditiva**
   - Realizar testes de significância estatística.
   - Construir modelos preditivos para estimar preços de imóveis.

## Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** pandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels, plotly, geopandas, folium
- **Versionamento:** Git e GitHub

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/yanoccoelho/portugal-real-estate-data-analysis.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Acesse os notebooks na pasta `notebooks/` e execute as etapas conforme desejado.

## Contribuição
Caso queira contribuir com o projeto, sinta-se à vontade para criar um **fork**, abrir **issues** ou enviar um **pull request** com sugestões e melhorias.

## Autor
- [Yan Coelho](https://github.com/yanoccoelho)

---
Este projeto está em desenvolvimento e será atualizado continuamente.

