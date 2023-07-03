Projeto em Grupo - Módulo 5: Criptomoedas.
Formação em análise de dados - Senac/Resilia

Integrantes:
Davi Moraes,
Jorge William Peixoto,
Matheus Augusto.


E-mails:
isdavimoraes@gmail.com
rj.jorgewill@gmail.com
mataugusto1999@gmail.com


Apresentação do problema:
'Você e a sua equipe foram escalados por uma corretora financeira para realizar uma análise exploratória relacionada à série histórica dos valores de criptomoedas.
As fontes de dados que serão utilizadas no projeto estão disponíveis no Kaggle. Serão utilizados os arquivos de 10 criptomoedas no período entre 2015 e 2018, contendo a série histórica dos preços das criptomoedas nesse período.'

Perguntas a serem respondidas:

Como se comportaram os valores para todas as criptomoedas? Os valores tiveram uma tendência de queda ou de aumento?
Qual os valores médios para todas as criptomoedas?
Em quais anos houve maiores quedas e valorizações?
Existe alguma tendência de aumento ou queda dos valores pelo dia da semana?
Qual moeda se mostra mais interessante em relação à valorização pela análise da série histórica?
Qual moeda se mostra menos interessante em relação à valorização pela análise da série histórica?
Existe correlação entre os valores para todas as criptomoedas?

Utilizamos o Trello como forma de agilizar nosso processo de produção, pois ele se utiliza da metodolia ágil Kanban (que faz utilização de post-its para definir tarefas).

Link para o nosso Trello:
https://trello.com/b/kfYacMbi/kanban-quadro-modelo

Criamos slides para nos ajudar nas apresentações dos problemas, resoluções, resultados e conclusões.

Link para a observação dos slides: https://docs.google.com/presentation/d/1TCy863I_-OjrOPKDl7ot_cm-ky0KNByF1tF4GeW7vTc/edit#slide=id.gdfc0182d06_0_367


Lista de criptomoedas selecionadas para fazermos a análise no período de 2015 a 2018:

Bitcoin (BTC): Lançada em 2009, o Bitcoin foi a primeira criptomoeda e continua sendo a mais conhecida e valiosa até hoje.

Ethereum (ETH): Lançada em 2015, o Ethereum é uma plataforma blockchain que permite a criação e execução de contratos inteligentes e aplicativos descentralizados.

Ripple (XRP): Criada em 2012, a Ripple é uma rede de pagamento em tempo real que utiliza a criptomoeda XRP para facilitar transferências internacionais de dinheiro.

Litecoin (LTC): Lançada em 2011, o Litecoin foi uma das primeiras altcoins a surgir após o Bitcoin. Ela se diferencia por ter tempos de bloqueio mais rápidos e um algoritmo de mineração diferente.

Dash (DASH): Inicialmente lançada como Darkcoin em 2014 e posteriormente renomeada para Dash (Digital Cash), é uma criptomoeda que oferece maior privacidade e transações instantâneas.

Monero (XMR): Lançada em 2014, a Monero é conhecida por seu foco em privacidade e anonimato, usando tecnologias como assinaturas de anel e endereços ocultos.

NEM (XEM): Lançada em 2015, a NEM é uma plataforma blockchain que oferece recursos avançados, como criação de ativos digitais personalizados e mensagens criptografadas.

Stellar (XLM): Criada em 2014, a Stellar é uma plataforma de pagamento e remessa que visa facilitar transferências de dinheiro de forma rápida, barata e segura.

Cardano (ADA): Lançada em 2017, a Cardano é uma plataforma blockchain que busca oferecer maior segurança, escalabilidade e sustentabilidade para a execução de contratos inteligentes.

EOS (EOS): Lançada em 2018, a EOS é uma plataforma blockchain que visa oferecer escalabilidade e facilidade de uso para o desenvolvimento de aplicativos descentralizados.



Link para cada banco de dados a ser utilizado:
https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory
(para todas as criptos exceto DASH)

https://www.kaggle.com/datasets/anasshahid88/crypto-market-data?select=CoinMarketData-dash.csv
(para a cripto DASH)


Esta lista reflete as criptomoedas populares durante o período mencionado.
Algumas dessas moedas surgiram durante esse período de 2015 a 2018. Logo, parte dos dados sobre os valores dessas moedas são nulos no período onde elas ainda não existiam como criptomoedas no mercado.


Explicando cada coluna importante dos dados:
SNo:
número do dado na série.
Name: nome da criptomoeda.
Symbol: simbolo/sigla da moeda no mercado.
Date:
data da observação.
High:
preço mais alto no dia determinado.
Low:
preço mais baixo no dia determinado.
Open:
preço de abertura no dia determinado.
Close:
preço de fechamento no dia determinado.
Volume:
volume de transações no dia determinado.
Marketcap:
também chamado de “capitalização de mercado” ou “valor de mercado”, é um indicador econômico utilizado para determinar o valor de uma empresa no mercado, dado em USD.

Esses dados são retirados do coinmarketcap e o uso dos dados é gratuito.

Link do repositório no Google Drive com os arquivos antes de serem tratados:
https://drive.google.com/drive/folders/1JLWGAq2wGKC82ikCRJXZinAtKRhyvzLO?usp=drive_lin
Link do Power BI:
https://app.powerbi.com/groups/me/reports/430d55e8-9128-460f-8e0b-78eae877981f/ReportSection464b6a57c018bd29db79?experience=power-bi
