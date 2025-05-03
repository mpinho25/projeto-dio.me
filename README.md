# Previsão de Vendas com Machine Learning

Este projeto utiliza algoritmos de aprendizado supervisionado para prever vendas futuras com base em dados históricos. A proposta é construir um modelo robusto, escalável e pronto para produção, utilizando Python, bibliotecas de ciência de dados e serviços em nuvem.

## 📊 Prints do Processo

### 1. Pré-processamento dos Dados
![Pré-processamento](./prints/preprocessamento.png)

### 2. Treinamento do Modelo
![Treinamento](./prints/treinamento.png)

### 3. Avaliação do Modelo
![Avaliação](./prints/avaliacao.png)

### 4. Predição em Tempo Real
![Deploy](./prints/deploy.png)

---

## 🔄 Etapas do Processo

1. **Coleta e Preparação dos Dados**
   - Remoção de valores nulos, encoding de categorias e normalização.
   - Ferramentas: `pandas`, `numpy`.

2. **Escolha de Modelos e Treinamento**
   - Modelos testados: Regressão Linear, Random Forest, XGBoost.
   - Frameworks: `scikit-learn`, `xgboost`, `keras`.

3. **Avaliação**
   - Métricas: MAE, RMSE, R².
   - Visualização de resíduos e curva de previsão.

4. **Implantação**
   - Modelo hospedado com `Flask` + `Docker`.
   - Deploy em `AWS EC2` com API para consumo em tempo real.

---

## 💡 Insights Aprendidos

- **A importância da engenharia de atributos**: Variáveis derivadas com base em datas (como dia da semana ou feriado) aumentaram significativamente a acurácia.
- **Modelos ensemble como Random Forest e XGBoost** tiveram desempenho superior à regressão linear tradicional.
- **Overfitting** foi um problema comum em modelos muito complexos; regularização e validação cruzada foram fundamentais.
- **O deploy em nuvem** com `Docker` permitiu criar uma API escalável para integrar o modelo a sistemas externos.

---

## 🚀 Possibilidades Futuras

- Integração com dashboards (ex: Power BI, Streamlit).
- Re-treinamento automático com novos dados.
- Detecção de anomalias para alertar sobre quedas bruscas nas vendas.
- Uso de séries temporais com `Prophet` ou `ARIMA` para modelos mais especializados.

---

## 📁 Estrutura do Projeto

