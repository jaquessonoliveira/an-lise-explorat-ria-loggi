# **Análise Exploratória de Dados de Logística**

---

<center>
<img src="https://logodownload.org/wp-content/uploads/2019/07/loggi-logo-1.png">
    
---
  
  # **Tópicos**

<ol type="1">
  <li>Resumo;</li>
  <li>Pacotes e bibliotecas;</li>
  <li>Exploração de dados;</li>
  <li>Data Wrangling: Transformação e limpeza;</li>
  <li>Enriquecimento dos dados;</li>
  <li>Visualização;</li>
  <li>Insights.</li>
</ol>

  
  #  \. **Resumo**

   > O Loggi Benchmark for Urban Deliveries (BUD) é uma iniciativa da empresa Loggi para disponibilizar dados e códigos relacionados a problemas de logística urbana. Disponível no GitHub, o BUD sintetiza dados de fontes públicas e oferece soluções para problemas típicos enfrentados por empresas de logística, como otimização de rotas de entrega e alocação de entregas em veículos com capacidade limitada.

>Neste projeto de exploração e análise de dados do curso Analista de Dados da EBAC, utilizaremos a base de dados do BUD para realizar uma análise exploratória e gerar insights sobre a logística de entregas na região. O objetivo da análise é identificar oportunidades de melhoria na logística de entregas e fornecer recomendações para tornar as entregas mais rápidas e eficientes. Além disso, serão geradas visualizações gráficas para ajudar na compreensão e análise do cenário atual.
  
---
  
 - **Processamento**:
    > Kaggle Notebook ([link](https://www.kaggle.com/code/jaquessonoliveira/projeto-an-lise-explorat-ria-de-dados-loggi)).
  
---
  
#  \. **Insights**
  
   > **Insight 1:** Analisando o posicionamento dos hubs, a distribuição das entregas no mapa, e a proporção de entregas por região no gráfico de barras, vemos que a maioria das entregas está concentrada nos hubs df-1 e df-2, e que a distância entre os endereços de entrega e os hubs, é bem menor comparado ao hub df-0. 

   > **Insight 2:** Em contrapartida, apesar de o hub df-0 ter o menor número de entregas comparado aos demais, a distância entre o hub e os endereços de entrega é muito maior, o que consequentemente demanda mais tempo nas entregas, e dificuldades no trajeto, justificando o menor número de entregas, apesar de possuir a mesma capacidade de veículos que os demais. 

   > **Insight 3:** Através do Histograma, vemos que em todas as regiões, o tamanho (unidade de peso e volume não especificado nos dados) da entrega comparado a quantidade é muito parecido, e através desses dados, podemos alocar as entregas nos veículos adequados, de acordo com tamanho, distância, podendo poupar tempo, gasto com combustível, e manutenção de veículos. Já no gráfico 'countplot' da pra ver a diferença de quantidade de entrega em cada região, separados pelo tamanho da entrega.
