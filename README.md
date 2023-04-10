# Previsão de Demanda de Passagens Aéreas - Porto Seguro, Bahia
Este projeto tem como objetivo desenvolver um modelo de regressão para previsão de demanda de passagens aéreas para vôos fretados por uma operadora de turismo com destino à Porto Seguro, Bahia, saindo de Porto Alegre. Para isso será desenvolvido um código em python utilizando as bibliotecas Pandas, para manipulação dos dados, e o módulo Time Series da biblioteca Pycaret para criar o modelo. 

## Sobre a base de dados
A base de dados utilizada neste projeto está localizada na aba "univariate" do arquivo "Base_analise_voos_colab". Nela contém a informação de passageiros que compraram a passagem com a operadora de turismo confirmados nos vôos fretados pela operadora, com origem em Porto Alegre com destiono à Porto Seguro, Bahia, entre os anos de 2015 e 2019. Os dados estão organizados em frequência diária e foram obtidos a partir do sitema de gerenciamento da operadora de turismo.
### Dicionário de dados
![image](https://user-images.githubusercontent.com/119333189/230811567-38822f32-782f-4322-9c76-4d670da970da.png)


## Metodologia
A metodologia utilizada neste projeto será a univariada, que é uma técnica de previsão de séries temporais que considera apenas a série em si e não outras variáveis externas. Para construir o modelo de previsão de demanda, utilizaremos a biblioteca PyCaret, que é uma plataforma de machine learning de código aberto para Python. O módulo de séries temporais da PyCaret será utilizado para treinar e testar diversos modelos, como ARIMA, SARIMA, Prophet, entre outros.

O primeiro passo será realizar uma análise exploratória dos dados para identificar padrões e tendências na série temporal. Em seguida, utilizaremos o módulo de séries temporais da PyCaret para treinar e testar diversos modelos, ajustando seus hiperparâmetros para obter o melhor desempenho possível. O desempenho dos modelos será avaliado utilizando métricas como erro médio absoluto (MAE), erro quadrático médio (RMSE) e R². Após escolhido o melhor modelo, será feita uma previsão da demanda para os próximos 90 dias utilizando o modelo.

