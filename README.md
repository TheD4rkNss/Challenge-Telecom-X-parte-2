
# 📊 Análise de Churn - Telecom X

Este repositório apresenta uma análise completa de dados para previsão de evasão (churn) de clientes da Telecom X, utilizando técnicas modernas de ciência de dados e machine learning.

---

## 🚀 Objetivo

Identificar os principais fatores que levam à evasão de clientes e construir modelos preditivos para antecipar o churn, permitindo à empresa adotar estratégias de retenção mais eficazes.

---

## 🛠️ Pipeline de Análise

O pipeline implementado neste projeto inclui as seguintes etapas:

1. **Carregamento e Análise Inicial dos Dados**
   - Importação do dataset tratado.
   - Análise exploratória e estatísticas descritivas.

2. **Tratamento de Valores Ausentes**
   - Imputação de valores nulos com estratégias adequadas para variáveis numéricas e categóricas.

3. **Análise e Tratamento de Outliers**
   - Detecção de outliers via método IQR e visualização com boxplots.

4. **Feature Engineering**
   - Criação de novas variáveis relevantes para o negócio (ex: valor médio mensal, cliente de alto valor, total de serviços adicionais).

5. **Encoding de Variáveis Categóricas**
   - Aplicação de técnicas como label encoding, one-hot encoding e binary encoding.

6. **Normalização dos Dados**
   - Padronização das variáveis numéricas para modelos sensíveis à escala.

7. **Divisão Treino/Teste**
   - Separação estratificada dos dados em conjuntos de treino e teste (80/20 e 70/30).

8. **Modelagem Preditiva**
   - Treinamento e avaliação de dois modelos: Regressão Logística e Random Forest.
   - Comparação de desempenho (Acurácia, ROC AUC, F1-score).

9. **Ajuste de Hiperparâmetros**
   - Tuning do Random Forest com GridSearchCV e seleção de features importantes.

10. **Análise de Importância das Variáveis**
    - Interpretação dos coeficientes da Regressão Logística e importâncias do Random Forest.

11. **Visualizações e Relatório Final**
    - Geração de gráficos, matrizes de correlação e relatório analítico com recomendações de retenção.

---

## 📁 Estrutura do Projeto

```
.
├── dados_tratados.csv         # Base de dados utilizada 
├── Telecom_X_BR.ipynb # Script principal de análise e modelagem
├── README.md                  # Este arquivo
```

---

## 🧰 Principais Bibliotecas Utilizadas

- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📈 Principais Resultados

- **Modelos treinados:** Regressão Logística e Random Forest
- **Melhor desempenho:** (ver relatório final)
- **Principais fatores de churn:** Tempo de serviço, cobrança total, taxas mensais, engajamento com serviços adicionais, tipo de contrato e forma de pagamento.

---

## 💡 Estratégias de Retenção Sugeridas

- Programas de onboarding e engajamento inicial
- Revisão de preços e planos
- Promoção de serviços adicionais
- Foco em clientes de alto valor
- Incentivo a contratos de longo prazo
- Facilitação e segurança no pagamento
- Aprimoramento do suporte técnico

---

## 📄 Relatório Analítico

O relatório completo com análise dos fatores de evasão, desempenho dos modelos e recomendações de negócio está disponível ao final do notebook.

---

## 👤 Autor

- [Alvaro Vinicius]([https://github.com/seu-usuario](https://github.com/TheD4rkNss))

---
