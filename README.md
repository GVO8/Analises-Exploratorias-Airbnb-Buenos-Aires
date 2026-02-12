# 📊 Análise Exploratória de Dados – Airbnb Buenos Aires

Notebooks produzidos na matéria de análise exploratória, do curso de ciência de dados do Infnet.

Este repositório apresenta um estudo de **Análise Exploratória de Dados (EDA)** aplicado a anúncios do **Airbnb na cidade de Buenos Aires**. O trabalho foi desenvolvido com o objetivo de compreender padrões de precificação, disponibilidade, avaliações e características das acomodações, utilizando técnicas estatísticas, análises temporais e modelos de regressão.

O notebook principal do projeto é:

📓 **`Guilherme_Vogt_dr3_at.ipynb`**

---

## 🎯 Objetivos do Estudo

Os principais objetivos deste notebook são:

* Realizar a **limpeza e preparação dos dados**, incluindo amostragem para viabilizar a análise computacional;
* Explorar estatisticamente variáveis relevantes do Airbnb, como:

  * `price`
  * `minimum_nights`
  * `availability_365`
  * `number_of_reviews`
* Aplicar **medidas de tendência central e dispersão** (média, mediana, moda, variância, desvio padrão e quartis);
* Identificar **correlações entre variáveis** e sua influência sobre o preço das hospedagens;
* Analisar **comportamentos temporais** relacionados à disponibilidade e preços;
* Utilizar **modelos de regressão** para apoiar interpretações e tomadas de decisão no contexto de locações temporárias.

---

## 🗂️ Organização do Notebook

O notebook está estruturado em etapas bem definidas:

### 1. Preparação e Limpeza dos Dados

* Importação dos datasets de *listings* e *calendar* do Airbnb;
* Filtragem temporal dos registros;
* Seleção de colunas relevantes;
* Amostragem de aproximadamente **25% dos dados**, visando melhor desempenho computacional;
* Junção (*merge*) entre bases de anúncios e calendário.

### 2. Estatísticas Descritivas

* Cálculo e interpretação das medidas estatísticas básicas;
* Avaliação da dispersão e assimetria das variáveis numéricas;
* Identificação de possíveis outliers e inconsistências nos dados.

### 3. Visualizações Exploratórias

* Distribuições de preços e disponibilidade;
* Relação entre preço e capacidade de acomodação;
* Comparação de preços por tipo de acomodação;
* Análises gráficas para suporte à interpretação estatística.

### 4. Análise Temporal

* Avaliação de padrões sazonais na disponibilidade;
* Uso de janelas deslizantes para suavização de séries temporais;
* Discussão sobre como o comportamento ao longo do tempo pode influenciar decisões de precificação.

### 5. Modelagem e Regressão

* Construção de modelos de regressão linear;
* Avaliação da influência das variáveis explicativas sobre o preço;
* Interpretação dos coeficientes do modelo.

---

## 🔎 Principais Constatações

A partir das análises realizadas, destacam-se os seguintes achados:

* 🏠 **Tipo de acomodação é o fator com maior impacto no preço**: imóveis inteiros apresentam valores significativamente mais altos quando comparados a quartos privados ou compartilhados.
* 👥 **Capacidade de hóspedes** é a variável contínua mais relevante para o aumento do preço.
* ⭐ Variáveis relacionadas a avaliações e número de reviews exercem influência menor no preço quando comparadas às características físicas do imóvel.
* 📉 Foram identificadas **inconsistências em colunas de preço**, com valores extremamente baixos ou altos, indicando possíveis problemas de qualidade dos dados ou necessidade de normalização adicional.
* 📅 A análise temporal evidencia **variações sazonais**, importantes para estratégias de ocupação e precificação dinâmica.

---

## 📌 Conclusão

Este estudo demonstra como técnicas de **análise exploratória, estatística descritiva, visualização de dados, análise temporal e regressão** podem ser aplicadas de forma integrada para compreender o mercado de locações temporárias.

Os resultados obtidos reforçam a importância do tipo de imóvel e da capacidade de acomodação na formação de preços, além de mostrar como análises temporais podem apoiar decisões estratégicas de hosts e plataformas.

Como extensões futuras, o trabalho pode evoluir para:

* Modelos de regressão não linear;
* Técnicas de *machine learning* para previsão de preços;
* Segmentação de bairros com base em perfil de oferta;
* Análises comparativas entre diferentes cidades.

---

## 🚀 Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib / Seaborn
* Estatística descritiva
* Modelos de regressão

---

## 👤 Autor

**Guilherme Vogt**
Projeto desenvolvido para fins acadêmicos e de estudo em análise de dados.
