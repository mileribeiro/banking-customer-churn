# 📊 Análise de Churn de Clientes Bancários

Este projeto tem como objetivo analisar o comportamento de clientes de um banco com o intuito de entender os fatores que influenciam a saída dos clientes (churn). A análise envolve técnicas de exploração de dados, visualização, avaliação de dependência entre variáveis e aplicação de algoritmos de machine learning para identificar as variáveis mais importantes na previsão de churn.

---

## 🔍 Objetivos

- Realizar análise exploratória univariada, bivariada e multivariada.
- Avaliar a independência entre as variáveis.
- Visualizar contingências entre variáveis qualitativas.
- Identificar variáveis mais relevantes para previsão de churn com um modelo supervisionado.
- Fornecer insights de negócio que ajudem a reter clientes.

---

## 🛠 Tecnologias e Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- itertools

---

## 📊 Etapas da Análise

### 1. Análise Univariada
Exploração das variáveis numéricas e categóricas individualmente, incluindo histogramas e contagens absolutas.

### 2. Análise Bivariada
Relações entre pares de variáveis usando gráficos de dispersão, boxplots e barras agrupadas.

### 3. Análise Multivariada
- **Correlação entre variáveis numéricas** via heatmap.
- **Contingência entre variáveis categóricas** com visualizações controladas para evitar poluição visual.

### 4. Pré-processamento
- Tratamento de valores faltantes.
- Codificação de variáveis categóricas com One-Hot Encoding.

### 5. Modelagem
- Utilização do `ExtraTreesClassifier` para avaliar a importância relativa das variáveis.
- Visualização da importância com gráfico de barras ordenado.

---

## 📈 Principais Insights

- **Idade** é a variável que mais influencia o churn.
- Clientes **ativos** que abandonaram o banco são um grupo de atenção especial.
- Clientes da **Alemanha** apresentaram maior taxa de saída.
- Ter **cartão de crédito** está relacionado à permanência.

---

## ✅ Conclusão

A análise permite identificar padrões relevantes que contribuem para a evasão de clientes. Com esses insights, a empresa pode adotar estratégias mais eficazes de retenção e direcionar melhor seus recursos.

---

## 💡 Próximos Passos

- Testar modelos de classificação como Random Forest, XGBoost ou LightGBM.
- Realizar tuning de hiperparâmetros.
- Aplicar técnicas de balanceamento de classes.
- Implementar um pipeline automatizado de modelagem.

---

## 📬 Contato

Caso tenha dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

**Milena Vasconcelos Ribeiro**  
[LinkedIn](https://www.linkedin.com/in/seu-link-aqui) | [Email](mailto:seuemail@dominio.com)

