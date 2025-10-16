# Clusterização de Vinhos com PCA e K-Means

Projeto de machine learning não supervisionado que agrupa vinhos com base em características químicas usando PCA para redução dimensional e K-Means para clusterização.

## Objetivo

Identificar grupos naturais de vinhos similares sem usar os rótulos originais, demonstrando como algoritmos não supervisionados descobrem padrões em dados.

## Dataset

- **Fonte**: Wine dataset (Scikit-learn)
- **Amostras**: 178 vinhos
- **Características**: 13 propriedades químicas
- **Classes**: 3 tipos de vinho

## Fluxo do Projeto

1. **Carregamento dos Dados**
   - Importação do dataset
   - Análise exploratória inicial

2. **Pré-processamento**
   - Escalonamento com StandardScaler
   - Normalização dos dados

3. **Redução Dimensional (PCA)**
   - 13 características → 2 componentes
   - Visualização em 2D
   - Análise de variância

4. **Clusterização (K-Means)**
   - Método do cotovelo para determinar K
   - Aplicação do algoritmo
   - Identificação de clusters

5. **Avaliação**
   - Comparação com classes reais
   - Visualização dos resultados
   - Métricas de performance

## Tecnologias

- Python 3
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## Resultados

- PCA mantém ~55-60% da variância com 2 componentes
- K-Means identifica clusters compatíveis com classes reais
- Visualização clara da separação entre grupos

## Insights

- Características químicas discriminam bem os tipos de vinho
- Técnicas não supervisionadas revelam estrutura natural dos dados
- PCA + K-Means é eficaz para análise exploratória

## Como Executar

1. Abrir Google Colab
2. Copiar código em nova célula
3. Executar (Ctrl+F9)
4. Analisar resultados e gráficos

