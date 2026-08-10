# Detec-o-anomalias-em-transa-es-com-Python
Projeto desafio de código DIO - Bradesco para detecção de anomalias em transações bancárias utilizando Python

# Deteccao de Fraudes em Transacoes de Cartao de Credito

Projeto de Machine Learning para deteccao de transacoes fraudulentas em cartoes de credito, utilizando o dataset publico de transacoes europeias. O desafio principal e o desbalanceamento extremo dos dados: menos de 0,17% das transacoes sao fraudes.

## Sobre o Projeto

O dataset utilizado e o `creditcard.csv`, disponivel publicamente e amplamente usado em estudos de deteccao de fraude. Ele contem 284.807 transacoes reais anonimizadas, onde as variaveis V1 a V28 sao resultado de uma transformacao PCA para proteger a identidade dos clientes.

O projeto percorre o pipeline completo de Machine Learning:

- Analise exploratoria e visualizacao do desbalanceamento
- Pre-processamento: remocao de duplicatas, feature engineering, padronizacao
- Modelo base (Regressao Logistica) e avaliacao honesta com metricas adequadas
- Balanceamento com SMOTE
- Modelos robustos: Random Forest e XGBoost
- Ajuste de threshold para otimizar o Recall
- Explicabilidade com SHAP

## Tecnologias Utilizadas

- Python 3
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- XGBoost
- SHAP
- matplotlib, seaborn

## Como Executar

1. Abra o notebook `deteccao_fraudes.ipynb)` no Google Colab ou Jupyter Notebook
2. O dataset e carregado automaticamente via URL publica, nao e necessario baixar nada manualmente
3. Execute as celulas em ordem

### Instalando dependencias locais
```bash
pip install -r requirements.txt
