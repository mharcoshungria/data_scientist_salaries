<img src="https://i.imgur.com/YX6UATs.png"  width="160">

# **Projeto Final - Data Science**

Este repositório é parte das tarefas da Formação Intensiva de Data Science da [Awari](https://awari.com.br/). 

### Sobre o projeto:

O projeto tem como objetivo identificar se características da empresa influênciam no salário ofertado. 

Iremos analisar se o título do cargo, localização da sede, tamanho da empresa ou faturamento influênciam diretamente no salário dos funcionários. 

---

### **Resumo sobre as seções:**

*   **Coleta de dados:** A primeira etapa é carregar ou importar todas as bibliotecas e pacotes necessários para obter os resultados desejados. Uma vez que as bibliotecas são carregadas, precisamos carregar os dados.

*   **Preparação dos dados:** Depois de entender os dados, vamos transformá-los para torná-los adequados para que os algoritmos processem e trabalhem com mais eficiência, a fim de fornecer resultados com maior accurácia e precisão. Este é o estágio mais importante e mais demorado de qualquer projeto de ML.

*   **Análise exploratória:** Com os dados coletados e preparados para análise. Chegou o momento de explorar os dados de duas formas. A primeira é analisando as estatísticas descritivas, como o nome sugere, descreve os dados em termos de estatísticas - média, desvio padrão, quantis, etc. A segunda é através de visualizações gráficas.

*   **Modelagem:** Agora que nossos dados estão prontos, vamos verificar o desempenho em dois algoritmos de regressão. Primeiro, vamos separar em dados de treino e teste. Segundo, criamos o modelo e análisamos e rodamos. Por último, os modelos precisam ser avaliados com base em um determinado conjunto de métricas de avaliação que precisam ser definidas. Para algoritmos de regressão, algumas das métricas comuns são - MSE e R Square.

---

### **Coleta de dados:**

Coleta de dados: A primeira etapa é carregar ou importar todas as bibliotecas e pacotes necessários para obter os resultados desejados. Uma vez que as bibliotecas são carregadas, precisamos carregar os dados.

Nesse projeto vamos utilizar a coleta de dados secundária que consiste em coletar os dados de alguma base já criada por outra pessoa, empresa ou organização.


**Conjunto de dados:**

O conjunto de dados que iremos utilizar foi coletado da plataforma Kaggle. Uma comunidade on-line de cientistas de dados e profissionais de aprendizado de máquina.

**Descrição do dados:**

O arquivo que vamos utilizar é o data_scraped.csv, nele encontramos as seguintes informações:

- Unnamed: 0: indice segundário;
- Job Title: Titulo do cargo;
- Salary Estimate: Salário estimado;
- Job Description: Descrição do trabalho;
- Rating: Ranking;
- Company Name: Nome da empresa;
- Location: Localização da empresa;
- Headquarters: Localização da sede;
- Size: Tamanho da empresa;
- Founded: Ano que a empresa foi fundada;
- Type of ownership: Tipo de sociedade;
- Industry: Industria da empresa;
- Sector: Setor da empresa;
- Revenue: Faturamento;
- Competitors: Não identificado.

---

### **Preparação dos dados:**

Preparação dos dados: Depois de entender os dados, vamos transformá-los para torná-los adequados para que os algoritmos processem e trabalhem com mais eficiência, a fim de fornecer resultados com maior accurácia e precisão. Este é o estágio mais importante e mais demorado de qualquer projeto de ML.

Os dados da vida real não são organizados e apresentados de maneira adequada e em um dataframe sem anormalidades. Os dados geralmente têm muitas das chamadas anormalidades, como valores ausentes, muitos recursos com formato incorreto, recursos em escalas diferentes, etc. Tudo isso precisa ser tratado manualmente, o que leva muito tempo e requer muito tempo de programação.

- Durante essa etapa, alguns dos procedimentos que serão realizados:
- Remoção de colunas e dados indesejados;
- Tratamento de dados ausentes;
- Ajustes dos tipos de dados ( datetime, floats, integers, strings , etc...);
- Tratamento de Strings.

---

### **Análise exploratória:**

Análise exploratória: Com os dados coletados e preparados para análise. Chegou o momento de explorar os dados de duas formas. A primeira é analisando as estatísticas descritivas, como o nome sugere, descreve os dados em termos de estatísticas - média, desvio padrão, quantis, etc. A segunda é através de visualizações gráficas.

As visualizações de dados são muito importantes porque são a maneira mais rápida de conhecer os dados e os padrões - se eles existem ou não. As visualizações usando Matplotlib, Seaborn podem ser usadas para verificar as correlações, gráficos de dispersão de dados, histogramas e boxplots para verificar a propagação e assimetrias.

---

### **Modelagem:**

Modelagem: Agora que nossos dados estão prontos, vamos verificar o desempenho em dois algoritmos de regressão. Primeiro, vamos separar em dados de treino e teste. Segundo, criamos o modelo e análisamos e rodamos. Por último, os modelos precisam ser avaliados com base em um determinado conjunto de métricas de avaliação que precisam ser definidas. Para algoritmos de regressão, algumas das métricas comuns são - MSE e R Square.

Os dados em mãos podem ser divididos de antemão como conjunto de treinamento e conjunto de validação. Esta divisão possui várias técnicas mas nesse projeto vamos usar a técnica de Train Test Split.

Os modelos precisam ser avaliados com base em um determinado conjunto de métricas de avaliação que precisam ser definidas. Para algoritmos de regressão, algumas das métricas comuns são - MSE e R Square.

---

### **Conclusão:**

Podemos concluir que existe uma correlação positiva expressiva entre o Valor Máximo pago pelas empresas e o Valor Mínimo mas, não identificamos uma correlação entre as características das empresas analisadas com os valores salariais. Apoiado nessa conclusão, criamos a hipótese de que os valores salariais ofertados pelas empresas são correlacionados com as habilidades dos candidatos. Habilidades essas operacionais e ou comportamentais.

Também acredito que a amostra analisada possuia poucos valores de determinados cargos, o que pode ter influênciado algumas análises.

Para uma análise mais profunda é necessário pesquisar banco de dados mais completos que contenham as informações exigidas para a candidatura dos profissionais e não apenas as características das empresas contratantes.
