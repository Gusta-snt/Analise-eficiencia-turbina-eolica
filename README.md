# Análise de Eficiência de Turbina Eólica

Este projeto de análise de dados foi desenvolvido como parte do meu portfólio, com o objetivo de avaliar a eficiência de uma turbina eólica com base na potência real gerada e na potência teórica esperada para diferentes velocidades do vento.

## Objetivo

A principal meta deste estudo é verificar se a turbina eólica em questão está operando de forma eficiente. Para isso, comparamos a potência real gerada com a potência teórica que a turbina deveria gerar, conforme a velocidade do vento registrada. A análise se baseia nos seguintes passos:

1. **Cálculo do Desvio Padrão**: Determinação do desvio padrão dos dados de potência real para entender a variabilidade nas medições.
   
2. **Cálculo da Incerteza Tipo A**: Aplicação do método de incerteza Tipo A para quantificar a incerteza associada à média das medições.

3. **Visualização dos Dados**: Agrupamento dos dados e criação de um gráfico colorido para identificar visualmente os pontos onde a potência real está em desacordo com a potência teórica. Esses pontos podem indicar possíveis ineficiências ou problemas operacionais na turbina.

Este estudo é fundamental para identificar possíveis áreas de melhoria na operação da turbina, ajudando a garantir uma maior eficiência energética e confiabilidade no fornecimento de energia.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

1. **Importação dos Dados**: Os dados são importados a partir de um arquivo CSV chamado `turbina.csv`.
   
2. **Preparação dos Dados**: Ajuste dos nomes das colunas e limpeza dos dados.

3. **Análise Estatística**: Cálculo do desvio padrão e incerteza Tipo A para as medições de potência.

4. **Visualização dos Resultados**: Criação de gráficos que mostram a eficiência da turbina em relação às condições teóricas.

## Como Utilizar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/Gusta-snt/Analise-eficiencia-turbina-eolica.git
   cd Analise-eficiencia-turbina-eolica

2. **Execute a Análise**:
  Execute o Jupyter Notebook Análise_Turbina_Eólica.ipynb para reproduzir os resultados e visualizações.

Você também pode utilizar o google colab. Basta fazer o download do notebook e do csv, abrir o notebook no ambiente do colab e fazer o upload do csv na mesma pasta.

## Licença
  Este projeto é licenciado sob a Mozilla Public License Version 2.0. Veja o arquivo LICENSE para mais detalhes.
  
<div id="author">
    <h2>Autor</h2>
    <img src="https://i.ibb.co/vzScnhD/417425706-1534810987359184-8145526133549744564-n.jpg" width="120px">
    <p>Feito por Gusta ❤️. Onde me encontrar:</p>
    <a href="https://www.instagram.com/gustavo_santosfr/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
    <a href="https://www.linkedin.com/in/gustavo-ferreira-dos-santos-a3b6b1231/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
    <a href="https://github.com/Gusta-snt" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
</div>
