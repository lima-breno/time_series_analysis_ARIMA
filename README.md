# 📈 **Análise e Previsão de Séries Temporais Não Estacionárias com ARIMA**
Este projeto foca na análise de séries temporais não estacionárias, aplicando técnicas de decomposição, testes de estacionariedade e autocorrelação para, finalmente, modelar e prever a série 
utilizando o modelo ARIMA (Autoregressive Integrated Moving Average). O objetivo principal é identificar a estrutura da série, garantir sua estacionariedade para modelagem e avaliar a performance das previsões.

🎯**Objetivo:** identificar a estrutura da série, garantir sua estacionariedade e avaliar a performance das previsões.

# 📜 **Workflow do Projeto**
1. **Preparação, Tratamento e Carregamento de Dados**
2. **Análise Exploratória e Decomposição da Série Temporal**
3. **Testes de Estacionariedade e Autocorrelação**
4. **Separação de Bases de Treino e Teste**
5. **Modelagem de Séries Temporais (ARIMA)**
6. **Avaliação e Interpretação do Modelo**

# 📈 **Resultados do Projeto**
* **Modelo Final:**
ARIMA(3,1,3) com AIC de 1194.053.
**Previsões:** O modelo realizou previsões que, em média, superestimam os valores reais (Erro Médio: -31.3).
**Métricas de Erro:**

  **MAE:** 42.4 (Em média, as previsões diferem dos valores reais em 42.4 unidades).
  
  **RMSE:** 56.9 (Indica que erros maiores tiveram um impacto mais significativo).

  **MAPE:** 8.4 % (As previsões apresentam um desvio percentual médio de 8.4% dos valores reais, considerado razoável para a aplicação).

# 📝 **Conclusão**

O projeto demonstrou a aplicação bem-sucedida das etapas de análise e modelagem de séries temporais não estacionárias utilizando o modelo ARIMA(3,1,3). Apesar de apresentar um desempenho razoável com um MAPE 
de 8.4%, há espaço para melhorias, especialmente na abordagem da heteroskedasticidade dos resíduos e na otimização da ordem q dos termos de média móvel. A exploração de modelos SARIMAX (ARIMA Sazonal) 
seria um próximo passo lógico para incorporar explicitamente a sazonalidade e potencialmente lidar com a variância não constante dos erros, visando a obtenção de previsões ainda mais precisas e robustas


#**🛠️ Tech Stack** 

🐍 **Python** * 

🐼 **Pandas** * 

📊 **Matplotlib** * 

🔢 **NumPy** * 

📉 **Statsmodels** (para decomposição, testes ADF, ACF, PACF e SARIMAX)
