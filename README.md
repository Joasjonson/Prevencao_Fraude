 ****Prevenção de Fraude Financeira - Análise de dados e Modelagem Preditiva****

**Descrição:**

Este projeto envolveu a análise e modelagem preditiva de dados financeiros de um conjunto de dados com mais de 80.000 registros de clientes, com o objetivo de prever possíveis fraudes nas transações financeiras. O projeto passou por várias etapas para compreender, preparar e modelar os dados a fim de alcançar resultados eficazes na detecção de fraudes. A seguir, cada etapa do projeto:

**1. Conjunto de Dados Inicial:**
   - O projeto começou com um conjunto de dados contendo informações financeiras de clientes, incluindo variáveis categóricas e numéricas.

**2. Análise Exploratória de Dados (EDA):**
   - Realizado uma análise exploratória de variáveis categóricas e numéricas para entender a distribuição e as relações entre as variáveis. Isso incluiu a geração de gráficos e visualizações para identificar padrões e insights.

**3. Tratamento de Valores Missing (Nulos):**
   - Identificado valores ausentes e implementado estratégias para preencher ou eliminar esses valores ausentes, garantindo que os dados estivessem completos e prontos para análise.

**4. Análise Estatística de Variáveis:**
   - Calculado estatísticas descritivas das variáveis para obter informações sobre médias, desvios-padrão, quartis e distribuições.

**5. Tratamento de Dados:**
   - Realizado transformações nos dados, como remoção de duplicatas e remoção de colunas irrelevantes.

**6. Engenharia de Atributos:**
   - Criado novos atributos a partir dos dados existentes para melhorar a capacidade de prever fraudes. Isso incluiu a criação de características relevantes para o problema.

**7. Gráficos:**
   - Gerado gráficos para visualizar relacionamentos e padrões nos dados, o que ajudou a entender melhor as características das transações financeiras.

**8. Tratamento de Outliers:**
   - Identificado e tratado outliers, garantindo que esses valores não prejudicassem a precisão do modelo.

**9. Normalização e Padronização de Dados:**
   - Normalizado e padronizado as características numéricas para garantir que todas estivessem na mesma escala, o que é fundamental para algoritmos sensíveis à escala, como SVM e k-NN.

**10. Balanceamento da Variável Alvo (TARGET):**
   - Como a classe "fraude" era significativamente maior que a classe "não fraude", foi aplicado a técnica de SMOTE para balancear as classes, garantindo que o modelo não fosse tendencioso em direção à classe majoritária.

**11. One-Hot Encoding:**
   - Convertido variáveis categóricas em representações numéricas usando a técnica de one-hot encoding.

**12. Criação, Treino e Teste dos Modelos Preditivos:**
   - Utilizado três algoritmos de machine learning diferentes: Random Forest, Suport Vector Machine (SVM) e k-Nearest Neighbors (k-NN). Treinado e testado cada modelo usando os dados de treinamento e teste, avaliando a precisão e desempenho de cada algoritmo.

O projeto resultou na criação de modelos preditivos capazes de detectar possíveis fraudes em transações financeiras, com base em dados cuidadosamente preparados e explorados. O balanceamento das classes e a engenharia de atributos desempenharam um papel crucial na construção de modelos eficazes. Os insights obtidos durante a análise exploratória também contribuíram para a compreensão dos padrões nos dados. Em suma, o projeto abrangeu uma série de etapas essenciais para a detecção de fraudes em dados financeiros, resultando em modelos eficazes para prevenir possíveis fraudes.


## Stack utilizada

**Python:** pandas, matplotlib, seaborn, sklearn

