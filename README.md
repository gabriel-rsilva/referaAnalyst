# Questão de negócio

O objetivo deste projeto é analisar os dados e em seguida responder as perguntas propostas e também descobrir novos insights. As perguntas são: 
- Do que se trata o negócio por trás dos dados? 
- A performance de vendas tem melhorado ao longo dos anos? 
- Existe algum tipo de sazonalidade no ano? 
- Algum cliente tem maior relevância de vendas? 
- Existe funcionários sem venda? Por que ?
- Quais categorias de produto vendem mais? Isso é um padrão em todos os países? 
- Existe relação entre o preço e o volume de vendas de um produto? 

# Estratégia da Solução

O produto final será um arquivo .csv agrupado com os campos necessários para a análise e um dashboard feito no PowerBI Desktop. 

## Ferramentas
- Python 3.9; 
- Jupyter Notebook; 
- PowerBI Desktop;
- Metodologia CRISP-DM.

## Procedimentos
- Coletar os dados; 
- Realizar a Limpeza dos Dados: tratar dados faltantes, outliers, duplicidades, etc;
- Derivar algumas variáveis (mês que a venda foi realizada por exemplo); 
- Realizar a análise exploratórios: descobrir novos insights; 
- Responder as perguntas propostas.

# Insights sobre o negócio

- <b>A média de vendas na Europa é 25% maior.</b>
    - O gráfico mostra que a média de venda na América do Norte comparada com a Europa é 25% menor. Então essa hipótese é VERDADEIRA.
<br></br>

- <b>A média de vendas na américa do Sul é 20% maior no Brasil.</b>
    - Falsa: Como mostra o gráfico, a média de vendas no Brasil é 770% maior.
<br></br>

- <b>Funcionários do escritorio 3 vendem 15% a mais, na média.</b>
    - Falsa: O escritório 3 possui a menor média de vendas
<br></br>

- <b>A média de vendas aumenta 10% a medida em que a meta aumenta.</b>
    - Falsa: não existe crescimento linear nesse caso, pelo contrário, a maior média de vendas está concentrada em vendedores com meta de 320.000.
<br></br>

- <b>A média de vendas da categoria Sportwear é 30% maior.</b>
    - Falsa: as categorias que se destacam no quesito de média de vendas são: Childrens wear, Mens Footwear, Womens wear.
<br></br>

- <b>A média de vendas de produtos dos fornecedores do Reino Unido é 10% maior.</b>
    - Falsa: a média de vendas de produtos dos fornecedores de UK é uma das menores .
<br></br>

- <b>A média de vendas do ano 2016 aumentou 20%.</b>
    - Falsa: na verdade a média para esse ano aumento 31% comparado ao ano 2015.
<br></br>

- <b>A média de vendas é maior no final de semana.</b>
    - Verdadeira: Outro fato é que a média para os dias de domingo é maior que a média para terça,quarta e quinta.



