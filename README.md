Análise de Regressão para Previsão de Degradação de Material
Este repositório contém o código para um modelo de regressão linear desenvolvido para prever a degradação de um determinado material com base nos dados fornecidos. Abaixo está um guia detalhado sobre como usar o código e entender os resultados.

Dados
O conjunto de dados usado para esta análise está armazenado em um arquivo Excel chamado "REGRESSÃO_LINEAR.xlsx". O conjunto de dados consiste em três colunas: 'medida', 'data' e 'velocidade'. Aqui está uma breve descrição de cada coluna:

'medida': Representa a medida de degradação do material.
'data': Representa um determinado parâmetro relacionado ao material.
'velocidade': Representa o parâmetro de velocidade.
Configuração
Para executar este código, você precisará do Python e de várias bibliotecas, incluindo pandas, numpy, matplotlib, seaborn, pandas_profiling e scikit-learn. Você pode instalar as bibliotecas necessárias usando pip:

Copy code
pip install pandas numpy matplotlib seaborn pandas-profiling scikit-learn
Visão Geral do Código
O código está organizado em várias seções:

Exploração e Pré-processamento dos Dados: O conjunto de dados é carregado usando pandas e uma exploração inicial é conduzida usando pandas_profiling para uma visão geral abrangente. Estatísticas básicas e análise de correlação são realizadas para entender a relação entre as variáveis.

Visualização: Gráficos de dispersão são usados para visualizar a relação entre a variável alvo ('medida') e a variável de recurso ('data').

Análise de Regressão: Um modelo de regressão linear simples é ajustado usando a biblioteca statsmodels. O resumo dos resultados da regressão é impresso, incluindo coeficientes, R-quadrado, estatística F e outras estatísticas relevantes.

Avaliação do Modelo: O modelo é avaliado usando a métrica R-quadrado para avaliar seu desempenho em um conjunto de teste.

Executando o Código
Para executar o código:

Clone este repositório para sua máquina local.
Certifique-se de ter Python e as bibliotecas necessárias instaladas.
Abra um terminal ou prompt de comando e navegue até o diretório do repositório.
Execute o script Python.
Interpretação dos Resultados
A análise de regressão fornece insights sobre a relação entre a degradação do material ('medida') e o parâmetro ('data'). Os coeficientes indicam o impacto de 'data' em 'medida'. O valor de R-quadrado indica a qualidade do ajuste do modelo.

Contribuidores
Este código foi desenvolvido por Dioeliton Passos.

Licença
Este projeto está licenciado sob a Licença MIT.
