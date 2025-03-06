# Análise de Casos de Diabetes

📌 Contexto

Este projeto tem como objetivo a análise de um conjunto de dados relacionado a casos de diabetes, utilizando a linguagem Python e bibliotecas especializadas para manipulação e visualização de dados. O dataset utilizado contém informações sobre diversas variáveis clínicas e o resultado do diagnóstico de diabetes.

📂 Descrição do Dataset

O conjunto de dados contém diversas informações sobre os indivíduos. A seguir, uma descrição das colunas:

📝 Variáveis

- Gravidez: Número de gravidezes da paciente.

- Glicose: Nível de glicose no sangue.

- Pressão: Medida da pressão sanguínea.

- Espessura Pele: Espessura da pele medida em milímetros.

- Insulina: Nível de insulina no corpo.

- IMC: Índice de Massa Corporal.

- Função Diabetes: Indicador de risco de diabetes baseado no histórico familiar.

- Idade: Idade da paciente.

- Resultado: Indica se a paciente possui diabetes (1) ou não (0).

⚙️ Processamento de Dados

As seguintes etapas foram aplicadas ao conjunto de dados:

1. Leitura do Arquivo: O dataset é carregado a partir de um arquivo CSV utilizando a biblioteca Pandas.

2. Renomeação das Colunas: As colunas são renomeadas para uma compreensão mais intuitiva dos dados.

3. Análise Descritiva: São calculadas estatísticas descritivas para entender a distribuição dos dados, como média, desvio-padrão, mínimo, máximo e quartis.

4. Verificação de Dados Nulos: A presença de valores ausentes é verificada para garantir a qualidade dos dados.

5. Remoção de Outliers: Outliers foram identificados utilizando o método IQR (Intervalo Interquartil) e removidos. A função find_outlier_iqr() calcula o intervalo e identifica os valores que estão fora da faixa permitida.

6. Análise de Correlações: A correlação entre a variáveis foi calculada e observada para observar comportamentos que podem impactar na diabetes.

7. Visualizações: Várias visualizações foram feitas para entender melhor a distribuição das variáveis, como Idade e IMC, antes e depois da remoção dos outliers.

📊 Análises e Visualizações

Utilizamos as bibliotecas pandas, numpy, matplotlib e seaborn para explorar o conjunto de dados. Algumas análises incluem:

- Distribuição da qualidade do sono e níveis de estresse.

- Relação entre tempo de tela e qualidade do sono.

- Impacto do uso de dispositivos digitais na saúde ocular.

- Correlação entre atividade física e qualidade do sono.


## Tecnologias Utilizadas

- Python: Linguagem de programação principal do projeto.

- Pandas: Biblioteca utilizada para manipulação e análise de dados.

- NumPy: Para operações matemáticas e numéricas.

- Seaborn e Matplotlib: Para visualização de dados.

- SciPy: Para análises estatísticas.
