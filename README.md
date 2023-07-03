# Projeto em Grupo - Módulo 5: Criptomoedas. <br>
## **Formação em análise de dados - Senac/Resilia** <br>

**Integrantes:** <br>
Davi Moraes, <br>
Jorge William Peixoto, <br>
Matheus Augusto. <br>
<br>

**E-mails:** <br>
isdavimoraes@gmail.com <br>
rj.jorgewill@gmail.com <br>
mataugusto1999@gmail.com <br>


**Apresentação do problema:** <br>
'Você e a sua equipe foram escalados por uma corretora financeira para realizar uma análise exploratória relacionada à série histórica dos valores de criptomoedas. <br>
As fontes de dados que serão utilizadas no projeto estão disponíveis no Kaggle. Serão utilizados os arquivos de 10 criptomoedas no período entre 2015 e 2018, contendo a série histórica dos preços das criptomoedas nesse período.' <br>
<br>
**Perguntas a serem respondidas:** <br>

1. Como se comportaram os valores para todas as criptomoedas? Os valores tiveram uma tendência de queda ou de aumento?
2. Qual os valores médios para todas as criptomoedas?
3. Em quais anos houve maiores quedas e valorizações?
4. Existe alguma tendência de aumento ou queda dos valores pelo dia da semana?
5. Qual moeda se mostra mais interessante em relação à valorização pela análise da série histórica?
6. Qual moeda se mostra menos interessante em relação à valorização pela análise da série histórica?
7. Existe correlação entre os valores para todas as criptomoedas?
<br>
Utilizamos o Trello como forma de agilizar nosso processo de produção, pois ele se utiliza da metodolia ágil Kanban (que faz utilização de post-its para definir tarefas). <br>
<br>

**Link para o nosso Trello:** <br>
https://trello.com/b/kfYacMbi/kanban-quadro-modelo
<br>
Criamos slides para nos ajudar nas apresentações dos problemas, resoluções, resultados e conclusões.

**Link para a observação dos slides:** <br>
https://docs.google.com/presentation/d/1TCy863I_-OjrOPKDl7ot_cm-ky0KNByF1tF4GeW7vTc/edit#slide=id.gdfc0182d06_0_367


**Lista de criptomoedas selecionadas para fazermos a análise no período de 2015 a 2018:** <br>

1. Bitcoin (BTC): Lançada em 2009, o Bitcoin foi a primeira criptomoeda e continua sendo a mais conhecida e valiosa até hoje.

2. Ethereum (ETH): Lançada em 2015, o Ethereum é uma plataforma blockchain que permite a criação e execução de contratos inteligentes e aplicativos descentralizados.

3. Ripple (XRP): Criada em 2012, a Ripple é uma rede de pagamento em tempo real que utiliza a criptomoeda XRP para facilitar transferências internacionais de dinheiro.

4. Litecoin (LTC): Lançada em 2011, o Litecoin foi uma das primeiras altcoins a surgir após o Bitcoin. Ela se diferencia por ter tempos de bloqueio mais rápidos e um algoritmo de mineração diferente.

5. Dash (DASH): Inicialmente lançada como Darkcoin em 2014 e posteriormente renomeada para Dash (Digital Cash), é uma criptomoeda que oferece maior privacidade e transações instantâneas.

6. Monero (XMR): Lançada em 2014, a Monero é conhecida por seu foco em privacidade e anonimato, usando tecnologias como assinaturas de anel e endereços ocultos.

7. NEM (XEM): Lançada em 2015, a NEM é uma plataforma blockchain que oferece recursos avançados, como criação de ativos digitais personalizados e mensagens criptografadas.

8. Stellar (XLM): Criada em 2014, a Stellar é uma plataforma de pagamento e remessa que visa facilitar transferências de dinheiro de forma rápida, barata e segura.

9. Cardano (ADA): Lançada em 2017, a Cardano é uma plataforma blockchain que busca oferecer maior segurança, escalabilidade e sustentabilidade para a execução de contratos inteligentes.

10. EOS (EOS): Lançada em 2018, a EOS é uma plataforma blockchain que visa oferecer escalabilidade e facilidade de uso para o desenvolvimento de aplicativos descentralizados.



**Link para cada banco de dados a ser utilizado:** <br>
https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory <br>
(para todas as criptos exceto DASH) <br>
<br>
https://www.kaggle.com/datasets/anasshahid88/crypto-market-data?select=CoinMarketData-dash.csv <br>
(para a cripto DASH) <br>

<br>
Esta lista reflete as criptomoedas populares durante o período mencionado.
Algumas dessas moedas surgiram durante esse período de 2015 a 2018. Logo, parte dos dados sobre os valores dessas moedas são nulos no período onde elas ainda não existiam como criptomoedas no mercado.

<br> <br>

**Explicando cada coluna importante dos dados:** <br>
**SNo:** <br>
número do dado na série. <br>
**Name:** <br>
nome da criptomoeda. <br>
**Symbol:** <br>
simbolo/sigla da moeda no mercado. <br>
**Date:** <br>
data da observação. <br>
**High:** <br>
preço mais alto no dia determinado. <br>
**Low:** <br>
preço mais baixo no dia determinado. <br>
**Open:** <br>
preço de abertura no dia determinado. <br>
**Close:** <br>
preço de fechamento no dia determinado. <br>
**Volume:** <br>
volume de transações no dia determinado. <br>
**Marketcap:** <br>
também chamado de “capitalização de mercado” ou “valor de mercado”, é um indicador econômico utilizado para determinar o valor de uma empresa no mercado, dado em USD. <br>
<br>
Esses dados são retirados do coinmarketcap e o uso dos dados é gratuito. <br>
<br>
**Link do repositório no Google Drive com os arquivos antes de serem tratados:** <br>
https://drive.google.com/drive/folders/1JLWGAq2wGKC82ikCRJXZinAtKRhyvzLO?usp=drive_link
<br>
**Link do repositório no Google Drive com os arquivos depois de serem tratados:** <br>
https://drive.google.com/drive/folders/13Gn_3K7xMR0aYOiZqidEgxLx3lUDE36T?usp=sharing
