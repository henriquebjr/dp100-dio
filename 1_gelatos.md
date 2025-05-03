# 1. Previsão de demanda de sorvetes

1. Cria-se o recurso e o Azure Machine Learning.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/1_criar_ml.png)

2. Configura o ML Automatizado.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/3_ml_automatizado.png)

3. Optar por regressão, pois a avaliação de dados históricos para prever dados futuros pode ser resolvido com uma equação de regressão linear.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/4_ml_automatizado.png)

4. É necessário fazer o upload dos dados de entrada (![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/sorveteria.csv)) e informar como será utilizado. Optei por dividir os dados para utilizar 10% para validação.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/5_ml_automatizado_validacao.png)

5. Após um período de treinamento (limitei em 30 minutos e 1000 ciclos) é obtido o resultado.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/6_resultado_treinamento.png)

6. Métricas obtidas.

![](https://raw.githubusercontent.com/henriquebjr/dp100-dio/main/resources/7_metricas.png)

7. Considerações:

Optei por utilizar o ML Automatizado pela facilidade, que se provou eficiente. Porém é interessante conhecer outros processos, pois o Azure Machine Learning é bem completo.