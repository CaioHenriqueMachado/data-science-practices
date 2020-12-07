<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1">Séries temporais</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução](#1)
- [Componentes de uma série temporal](#2)
- [Exemplos de uma série temporal](#3)
- [Previsões com ARIMA](#4)

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1"> INTRODUÇÃO</h1>
<br>

**Série Atemporal:** Quando os dados não tem relações com o tempo.

**Séries temporais:**

- Uma série temporal é uma mesma variável.

- Supõe que exista alguma dependência entre os intervalos(auto correlação)

- Deve estar relacionada a um intervalo REGULAR de tempo.

- Dependência (ordem) no tempo.

- Não é possível analisar mais de uma amostra a cada intervalo.

<br>

<h3>ANALISE DE SERIES TEMPORAIS</h3>

- Estudar o comportamento de uma variável contínua ao longo do tempo.

- O intervalo de coleta é feita de forma regular.

- O intervalo deve ser sempre o mesmo, único em toda série.
>Ex: milisegundo, dias, horas, semanas, meses

<br>

<h3>PORQUE ANALISAR SERIES TEMPORAIS ?</h3>

- Explicação / Compreensão de características importantes.

- Previsão

- Controle

<br>

<h3>ONDE SÃO APLICADAS</h3>

- Econometria

- Previsão do tempo

- Previsões financeiras

- Previsão de erupção vulcânica.

- Epidemias / doenças.

- Vendas

- Ocupação de Hotel

- Evasão Escolar

<br>
<h3>SERIES TEMPORAIS </h3>

- **Estacionárias:** Flutuam em torno de uma mesma média e variância.

- **Não estacionárias**


<br>
<h3>CATEGORIAS</h3>

- **Estocásticas:** Formula + fator aleatório que não pode ser explicado. 
> Maioria dos casos

- **Determinísticas:** Explicadas através de uma fórmula/função


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2"> COMPONENTES DE UMA SÉRIE TEMPORAL</h1>
<br>

- Valores que podem ou não ocorrer em uma série temporal.

- Valores Observados
  - Tendência
  - Sazonalidade
  - Aleatoriedade


<h3>Tendência</h3>

- É o efeito de um elemento que ocorre tendendo á subir ou descer em grande maioria do tempo.

<br>
<h3>Sazonalidade</h3>

- É o efeito de um elemento que ocorre em intevalos regulares.
> Ex: Transporte escolar tem menor frequencia em período de férias.

<br>
<h3>Aleatoriedade</h3>

- É o efeito de um elemento que não podem ser explicados por efeitos matematicos.
> Ex: Transporte escolar tem menor frequencia em período de férias.


<br>
<h3 align="center">DECOMPOSIÇÃO</h3>
<div align="center">
  <image src="./image/series_temporais_decomposicao.png" alt="regressão_linear" height="400" width="60%">
</div>


<br>
<h3>CICLOS</h3>

- São variações que não estão relacionadas a um intervalo de tempo, tendem a durar mais e ter picos maiores que o ciclo sazonal.
> Ex: Ciclos temporais como El ninho. Ciclo economico que afeta a bolsa de valores



<h3 align="center">EXEMPLO CLICOS</h3>
<div align="center">
  <image src="./image/series_temporais_ciclos.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h3>PREVISÃO</h3>

- Se a informação contêm dados que são possíveis serem explicados matematicamente, é possível fazer previsão.

- Uma técnica de previsão é o **_ARIMA_** e **_Redes neurais artificiais, recorrente (LSTN)_**



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3"> EXEMLOS DE UMA SÉRIE TEMPORAL</h1>
<br>


<h3 align="center">TRANSPORTE DE PASSAGEIROS</h3>
<h3 align="center">(Efeito Sazonal, Efeito Tendência)</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_1.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>


<h3 align="center">MILHAS PERCORRIDAS POR AVIÕES</h3>
<h3 align="center">(Efeito Tendência)</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_2.png" alt="regressão_linear" height="400" width="80%">
</div>




<h3 align="center">BOLSAS DE VALORES DE ALGUSN PAÍSES</h3>
<h3 align="center">(Clico Econômico )</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_3.png" alt="regressão_linear" height="400" width="80%">
</div>




<h3 align="center">MEDIDA DE NÍVEL DE UM LAGO</h3>
<h3 align="center">(Efeito Aleatório)</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_4.png" alt="regressão_linear" height="400" width="80%">
</div>




<h3 align="center">TEMPERATURA MÉDIA DE UM CASTELO</h3>
<h3 align="center">(Efeito Sazonal)</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_5.png" alt="regressão_linear" height="400" width="80%">
</div>




<h3 align="center">USO DO CINTO DE SEGURANÇA</h3>
<div align="center">
  <image src="./image/series_temporais_exemplo_6.png" alt="regressão_linear" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4"> ARIMA</h1>
<br>

- Técnica usada para fazer previsões.

- **Robusto:** Pode ser usado em praticamente qualquer tipo de Série temporal.

- **Requer dados estacionários:** pode  ser transformada usando diferenciação: remove tendências.


<h3>COMPOSIÇÃO</h3>

É composto por 3 elementos:

- **AR - Autoregressivo:** Avalia a relação entre os períodos(lags): autocorrelação.

- **I - Integrated:** Aplica a diferenciação, se necessária.

- **MA - Moving Average:** Avalia erros entre períodos e extrai estes erros.


<br>
<div align="center">
  <image src="./image/arima.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<h3>ARIMA SAZONAL</h3>


- Inclui, além (p, d, q), os elementos (P, D, Q)

<br>
<h3 align="center">Como saber qual melhor modelo ?</h3>
<div align="center">
  <image src="./image/arima_melhor_modelo.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/arima_pdq.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<div align="center">
<h3 align="center">COMO FAZER ?</h3>
  <image src="./image/arima_como_fazer.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<div align="center">
<h3 align="center">SOLUÇÃO</h3>
  <image src="./image/arima_solucao.png" alt="regressão_linear" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5"> REFERÊNCIAS ADICIONAIS</h1>
<br>


- **Livro:** _The Analysis o Time Series_ 
> Mais técnico.

- **Livro:** _Forecasting: Principles and Practice_
> Gratuito, em linguagem R.

