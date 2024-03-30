## **Projeto Data Science: Análise Detalhada do Ranking dos Países Mais Felizes**

### **Introdução**

Este README detalha um projeto de Data Science que analisa o ranking dos países mais felizes do mundo, utilizando dados do "World Happiness Report" de 2015 a 2019. O projeto foi realizado no Jupyter Notebook e utiliza a biblioteca Pandas para manipulação e análise dos dados.

### **Objetivos**

- **Explorar o dataset "World Happiness Report" de 2015 a 2019:**
    - Identificar inconsistências e valores nulos.
    - Visualizar a distribuição das variáveis.
    - Analisar as correlações entre as variáveis.
- **Responder perguntas complexas sobre a felicidade dos países:**
    - **Análise espacial:**
        - Quantas regiões existem no dataset?
        - Qual a média de felicidade por região?
        - Como a felicidade média por região mudou ao longo do tempo?
    - **Análise temporal:**
        - Qual a média de felicidade ao longo do tempo?
        - Qual a mudança da felicidade média por região ao longo do tempo?
    - **Comparação entre países:**
        - Qual o país com a maior pontuação em Generosidade?
        - Quantos países na África têm uma pontuação de felicidade maior do que a pontuação mais baixa na Europa Ocidental?
    - **Análise de mudanças:**
        - Quais países tiveram sua pontuação de felicidade mais aumentada ao longo do tempo?

### **Metodologia**

- **Importação de bibliotecas:** pandas e glob.
- **Carregamento e concatenação dos datasets:**
    - Leitura dos datasets de 2015 a 2019.
    - Verificação da compatibilidade das colunas.
    - Concatenação dos datasets em um único dataframe.
- **Limpeza e tratamento de dados:**
    - Identificação e remoção de valores nulos.
    - Imputação de valores missing.
    - Padronização de nomes de colunas.
- **Análise de dados:**
    - Cálculo de estatísticas descritivas.
    - Visualização de gráficos e tabelas.
    - Aplicação de testes estatísticos.
    - Criação de dashboards interativos.

### **Resultados**

- **Análise espacial:**
    - O dataset possui 10 regiões: América Latina e Caribe, América do Norte, Ásia Oriental, Ásia Meridional, Europa Central e Oriental, Europa Ocidental, Leste Europeu, Oriente Médio e Norte da África, Sudeste Asiático e Subsaariana Africana.
    - A Europa Ocidental apresenta a maior média de felicidade, seguida pela América do Norte e Austrália/Nova Zelândia.
    - A felicidade na Subsaariana Africana e no Sul da Ásia é significativamente menor do que em outras regiões.
    - A felicidade média em todas as regiões, exceto na Europa Oriental, aumentou de 2015 a 2019.
- **Análise temporal:**
    - A média global de felicidade apresentou uma leve tendência ascendente entre 2015 e 2019.
    - A Europa Ocidental e a América do Norte apresentaram as maiores médias de felicidade ao longo do tempo.
    - A Subsaariana Africana e o Sul da Ásia apresentaram as menores médias de felicidade ao longo do tempo.
- **Comparação entre países:**
    - Myanmar foi o país com a maior pontuação em Generosidade em 2019.
    - 9 países da África (Egito, Líbia, Marrocos, Mauritânia, Tunísia, Argélia, África do Sul, Botswana e Seychelles) têm uma pontuação de felicidade maior do que a pontuação mais baixa na Europa Ocidental (Grécia) em 2019.
- **Análise de mudanças:**
    - Benin, Costa do Marfim, Togo, Honduras e Burkina Faso foram os países que apresentaram os maiores aumentos na pontuação de felicidade entre 2015 e 2019.

### **Conclusão**

Este projeto demonstra o potencial da análise de dados para explorar o "World Happiness Report" de forma abrangente e detalhada. Através da manipulação e análise dos dados, foi possível obter insights valiosos sobre a felicidade dos países, tanto em termos espaciais quanto temporais, além de realizar comparações entre países e identificar os que apresentaram as maiores mudanças na pontuação de felicidade ao longo do tempo.
