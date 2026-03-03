## Projeto Analise Taxis
Este projeto analisa dados de serviços de taxi na cidade de Chicago com o objetivo de identificar padrões de consumo e validar uma hipótese sobre a operação de transporte. Através da manipulação de múltiplos conjuntos de dados, o código foca em relatar a performance das empresas, popularidade de bairros de destino e a influência do clima no tráfego.

O projeto está dividido nas seguintes etapas:

Análise Exploratória Inicial: Inspeção de dados sobre empresas de táxi, bairros e registros climáticos.

Pré-processamento de Dados: Limpeza de duplicatas, tratamento de tipos de dados (conversão de datas) e preparação das tabelas para análise estatística.

Identificação de Tendências: Ranking dos 10 bairros de destino mais frequentes e das empresas líderes de mercado.

Teste de Hipótese: Aplicação de um teste t de Student para comparar a duração média das viagens de um bairro específico (ex: Loop para o Aeroporto O'Hare) em sábados chuvosos versus sábados de tempo bom.

## Estrutura dos Dados
O projeto utiliza três bases de dados principais:

trips.csv: Estatísticas de corridas por empresa de táxi.

neighborhoods.csv: Média de corridas finalizadas em diferentes bairros de Chicago.

trips_climate.csv: Dados detalhados de viagens individuais contendo carimbo de tempo, condição climática e duração em segundos.

## Tecnologias Utilizadas
Python

Pandas: Limpeza e manipulação de dados.

Matplotlib & Seaborn: Visualização de dados e gráficos de barras.

SciPy (stats): Realização de testes de hipóteses estatísticas (Teste de Levene e Teste t independente).
