# Receita-e-Assinantes-da-Netflix
## **Dados**
O conjunto de dados *Netflix OTT Revenue and Number of Paid Subscribers* apresenta informações detalhadas sobre a receita da Netflix em dólares e o número de assinantes pagos, organizados por região e data. As principais colunas incluem:

- **Data:** a data em que os dados foram registrados.
- **Receita:** a receita total da Netflix em dólares para o período especificado.
- **Assinantes por Região:** o número de assinantes pagos categorizados por região geográfica.
- **Região:** a área geográfica específica coberta pelo conjunto de dados, como América do Norte, Europa, Ásia, etc.

> A base de dados foi extraida do *Kaggle* e pode ser encontrada neste [link](https://www.kaggle.com/datasets/mauryansshivam/netflix-ott-revenue-and-subscribers-csv-file/data).

 <br>Com os dados disponibilizados, foi realizada uma análise utilizando a técnica de aprendizado de máquina (**Classificação**), com o objetivo de prever a região (*UCAN*, *EMEA*, *LATM* ou *APAC*) com base em suas características. A análise foi conduzida através da correlação entre as variáveis selecionadas e aplicada ao modelo para a predição de um exemplo pré-processado. Foi feita toda avaliação e precisão do modelo com árvore de desisão e outras métricas de visualização.
 
## **Tecnologias**
- Bibliotecas utilizadas:
  - ``numpy``.
  - ``pandas``.
  - ``matplotlib.pyplot``.
  - ``seaborn``.
  - ``graphviz``.
  - ``sklearn``.
  - ``sklearn.preprocessing``.
  - ``sklearn.model_selection``.
  - ``sklearn.tree``.
  - ``klearn.metrics``.

 ## **Visualização**
**Correlação entre as variáveis:**

![correlacao](https://github.com/user-attachments/assets/4c30f675-0092-4d2d-aa52-491367a47e13)

 **Arvore de decição:**
 
![arvore](https://github.com/user-attachments/assets/3665a59d-b60f-47cc-a95c-1e2ca66d29c5)

**Modelo treinado:**

![modelo](https://github.com/user-attachments/assets/51f6df12-7111-401a-ac68-56dfb3076901)

**Conclusão:** O modelo avaliou e selecionou a região correta com base nas informações extraídas. Essa análise pode ser aplicada para orientar estratégias de marketing e previsões de assinantes, levando em consideração as características temporais e regionais dependendo da análise.
