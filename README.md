# Bootcamp-CDIA
Projeto Final do Bootcamp Ciência de Dados e IA - Hub de IA SC

## 📌 Contextualização
Este projeto foi desenvolvido como entrega final do *Bootcamp de Ciência de Dados e IA, com foco em **manutenção preditiva de máquinas industriais*.  
O objetivo é construir um sistema inteligente capaz de identificar falhas em máquinas a partir de dados coletados por dispositivos IoT, prevendo o tipo de falha e a probabilidade associada.

---

## 📊 Descrição dos Dados
O dataset contém medições sensoriais e metadados referentes às máquinas, com os seguintes campos principais:

- id, id_produto, tipo
- temperatura_ar, temperatura_processo, umidade_relativa
- velocidade_rotacional, torque, desgaste_da_ferramenta
- falha_maquina (binária)
- Tipos específicos de falha (FDF, FDC, FP, FTE, FA)

---

## 🧪 Metodologia
1. *Análise Exploratória de Dados (EDA)*
   - Identificação de outliers e valores ausentes
   - Análise de distribuição e correlação
   - Estudo de desbalanceamento entre classes

2. *Pré-processamento*
   - Normalização/Padronização de variáveis contínuas
   - Codificação de variáveis categóricas
   - Técnicas de balanceamento
   - 
3. *Modelagem*
   - Teste de diferentes abordagens:
     - Classificação binária (falha vs. não falha)
     - Classificação multiclasse (tipo de falha)
     - Classificação multirrótulo (falhas específicas em paralelo)
   - Algoritmos testados: Regressão Logística, Random Forest, SVM, XGBoost

4. *Avaliação*
   - Métricas utilizadas: *Accuracy, Precision, Recall, F1-score, AUC*
   - Avaliação com validação cruzada

---

## 📈 Resultados
- Modelo final escolhido: *[Inserir algoritmo]*
- Melhor desempenho obtido nas métricas:
  - Accuracy: XX%
  - Recall: XX%
  - F1-score: XX%
- Visualizações geradas:
  - Matrizes de confusão
  - Curvas ROC
  - Distribuições dos atributos relevantes

---

## 🛠️ Tecnologias Utilizadas
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, imbalanced-learn)
- Jupyter Notebook
- Git/GitHub para versionamento

*Extras (se aplicável):*
- FastAPI para servir o modelo
- Streamlit para dashboard interativo
- Docker para reprodutibilidade

---

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/projeto-bootcamp-cdia.git
   cd projeto-bootcamp-cdia
