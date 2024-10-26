# Análise Fundamentalista do Setor Imobiliário

### > Projeto desenvolvido no intuito de analisar dados referentes ao setor imobiliário Brasileiro - IMOB
- A partir do índice imobiliário brasileiro - IMOB. Tomou-se como Proxy 18 das principais empresas que representam o setor, e a partir destas, geraram-se quatro indicadores para três classes distintas em estrutura financeira, divididas em dois períodos distintos. Como assim? 

#### Indicadores de rentabilidade 
- Lidam diretamente com a eficiência das empresas em rentabilidade e geração de lucro. Para este projeto foram escolhidas duas: ROA (Return on Assets) e Margem líquida.
- O ROA mede a capacidade das empresas em gerar lucro a partir de seus ativos. Pensando para o caso do setor imobiliário, em que parte da rentabilidade de construtoras advém justamente sob estes ativos, faz total sentido ser englobada para melhor visualização.
- Margem líquida é a capacidade das empresas em gerarem lucro líquido a partir de sua receita total. Outro indicador útil para medir a eficiência e não somente retorno bruto.
#### Indicadores de liquidez
- Basicamente são indicadores que referem-se a capacidade das empresas em arcarem com suas dívidas, ou seja, de honrarem seus compromissos.
- Para este caso foi utilizado o índice de Liquidez Seca: 

## Estrutura do Projeto


- `data/`: Contém dados brutos e tratados.
- `notebooks/`: Notebook Jupyter com o fluxo de análise.
- `src/`: Scripts para extração, processamento e visualização de dados.
- `dashboards/`: Painel de visualização em Power BI.

## Metodologia
1. **Extração de Dados**: Extração de dados financeiros das empresas.
2. **Tratamento de Dados**: Limpeza e preparação para análise.
3. **Visualização**: Painel interativo com Power BI.

## Tecnologias Utilizadas
- **Python**: Para processamento e análise de dados.
- **Power BI**: Para visualização e exposição de dados.

## Como Visualizar o Painel
O painel Power BI está disponível no arquivo `dashboards/dashboard.pbix`. Para visualizá-lo, abra o arquivo no Power BI Desktop ou use o link fornecido.
