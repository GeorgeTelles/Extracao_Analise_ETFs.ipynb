<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# **Extração e Análise de ETFs**
## Visão Geral

Este projeto em Python tem como objetivo extrair e analisar dados relacionados a ETFs (Exchange-Traded Funds) negociados no Brasil. O processo envolve a coleta de informações de ETFs, a obtenção de dados de cotação, e a realização de análises para identificar o desempenho e a liquidez desses fundos.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GeorgeTelles/Extracao_Analise_ETFs.ipynb/blob/main/Extra%C3%A7%C3%A3o_e_An%C3%A1lise_de_ETFs.ipynb)

## Funcionalidades

1. **Coleta de Dados**: 
   - **Fonte**: O projeto inicia com a coleta de dados de ETFs a partir do site [Investing.com](https://br.investing.com/etfs/brazil-etfs) usando web scraping.
   - **Processo**: Os nomes, códigos e informações sobre os ETFs são extraídos e processados para análise.

2. **Extração de Cotações**:
   - **Ferramenta**: Utiliza-se a biblioteca `yfinance` para baixar dados históricos de cotação dos ETFs.
   - **Limpeza**: Os dados são filtrados para garantir que apenas ETFs com dados de cotação consistentes sejam analisados. Valores faltantes são tratados e preenchidos.

3. **Análise de Desempenho**:
   - **Normalização**: Os dados são normalizados para facilitar a comparação do desempenho ao longo do tempo.
   - **Top ETFs**: Identificação dos 10 ETFs com o melhor desempenho ao final do período analisado.
   - **Visualização**: Geração de gráficos para ilustrar a performance histórica dos principais ETFs.

4. **Análise de Liquidez**:
   - **Volume de Negociação**: Determinação dos ETFs mais negociados com base no volume médio de transações.
   - **Visualização**: Gráficos que mostram a cotação histórica dos ETFs mais negociados.

## Objetivo

O projeto visa fornecer insights valiosos sobre os ETFs negociados no Brasil, permitindo aos investidores e analistas identificar quais fundos têm apresentado melhor desempenho e quais são os mais negociados no mercado. A análise detalhada e as visualizações resultantes ajudam a tomar decisões informadas sobre investimentos em ETFs.
