# 7DaysOfCodeDados

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/7DaysOfCodeDados)


| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **#7DaysOfCode - Ciência de Dados**
| :label: Tecnologias | python
| :rocket: URL         | https://github.com/fab-souza/7DaysOfCodeDados/
| :fire: Desafio     | [7 Days Of Code](https://7daysofcode.io/matricula/data-science)


![](https://user-images.githubusercontent.com/67301805/196429854-c14b2ec3-d886-4e35-a5af-3c180ad2c073.jpg#vitrinedev)

## Sobre o desafio 📚
Desafios propostos no #7DaysOfCode sobre ciência de dados.

## Minha prática 👩🏻‍💻

### Desafio 1/7: Data Cleaning and Preparation

Baixar um dataset do portal do [CEAPS](https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Ci%C3%AAncia+de+Dados+1%2F7%3A+Data+Cleaning+and+Preparation&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Java%29+Dia+1%2F7%3A+Consumir+uma+API+de+filmes) (Cota para Exercício da Atividade Parlamentar dos Senadores) e aplicar processos de tratamento e limpeza de dados.

Ao final do tratamento dos dados, gerei uma amostra do dataset final, com registros referentes de 2018 a 2022.

![desafio1](https://user-images.githubusercontent.com/67301805/196568820-104b4574-699b-4d09-a4c3-efc1a205ccdf.jpg)

---

### Desafio 2/7: Data Visualization & Storytelling
Investigar os dados e gerar visualizações para identificar padrões estranhos ou estatísticas interessantes.

Entre os padrões estranhos, haviam registros de 2002 cadastrados em 2022 e também de datas posteriores à última atualização do CEAPS.

![image](https://user-images.githubusercontent.com/67301805/211164338-665df1e1-1518-41c9-9c58-5d08f198b6c2.png)



---

### Desafio 3/7: Forecasting

Utilizar técnicas de Machine Learning e ferramentas estatísticas para prever o futuro.

Neste caso, criar um modelo que irá prever quanto os senadores vão gastar nos próximos três meses.

Para fazer este desafio, utilizei o dataset disponibilizado, que é composto por duas colunas: ‘ds’ (datas) e ‘y’ (valor acumulado daquele dia). As datas vão do dia 01/01/2018 até 31/12/2022, acumulando o total de 1461 registros. Para solucionar este desafio, foi apresentada duas opções:
- usar o [Prophet, do Facebook](https://facebook.github.io/prophet/docs/quick_start.html#python-api);
- ou usar a [Regressão Linear](https://matheusfacure.github.io/2017/07/19/MQO-sklearn/?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Ci%C3%AAncia+de+Dados+3%2F7%3A+Forecasting&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Java%29+Dia+3%2F7%3A+Modelando+um+dom%C3%ADnio), do Scikit Learning.

Com o Prophet, o resultado foi o seguinte:

![image](https://user-images.githubusercontent.com/67301805/212771766-8136d574-1d19-49a3-9b36-f6e0c398e78f.png)



---

### Desafio 4/7: Sistemas de recomendação

A proposta deste desafio é simples e atual, pois, diante os diversos streams no mercado, devo desenvolver um código que recomende 5 filmes de acordo com o histórico de consumo/avaliação de um usuário, a partir do banco de dados da [MovieLens](https://grouplens.org/datasets/movielens/100k/?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Ci%C3%AAncia+de+Dados+4%2F7%3A+%F0%9F%91%A9%F0%9F%8F%BD%E2%80%8D%F0%9F%92%BB+Sistemas+de+recomenda%C3%A7%C3%A3o&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Java%29+Dia+4%2F7%3A+Gerando+o+HTML).

---

### Desafio 5/7: Servindo modelos em API

Criar uma API que irá consumir seu modelo de Machine Learning e receber requisições.




---

### Desafio 6/7: Teste A/B e Testes de Hipótese

Baixar um dataset e executar um teste de hipótese.



---

### Desafio 7/7: Documente e crie seu portfólio





## Ferramentas utilizadas 🧰
<p> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
    <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
    <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a>
    <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" alt="numpy" width="40" height="40"/> </a>
    </p>
