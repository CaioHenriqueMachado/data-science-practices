<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1"> Regressão Linear</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução](#1)
- [Correlação (R)](#2)
- [Previsão](#3)
- [Resíduos](#4)
- [Outliers](#5)
- [Extrapolação](#6)
- [Condição para regressão linear](#7)
- [Regressão linear simples e múltipla](#8)
- [Cálculos](#9)
- [Observações](#10)

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1"> INTRODUÇÃO</h1>
<br>

- Ao ver os dados a partir de um gráfico, podemos ver que eles são **linearmente distribuidos**, ou seja, tem uma linha imaginária onde os dados ficam distribuidos, podendo assim fazer a previsão de um novo dado. 

<br>
<h3>EXEMPLO</h3>
<div align="center">
  <image src="./image/grafico_1.png" alt="regressão_linear" height="400" width="80%">
</div>



**VARIÁVEIS**

- Existe uma relação matemática entre duas variáveis ?
- Se existe, como posso medir sua força ?
- Poderia usar pra fazer previsões ?


**REGRESSÃO SIMPLES**

- Uma variável explanatória (ou independente) para explicar uma variável dependente (variável de resposta).



**GRAFICO DE DISPERSSÃO**

- **(Eixo Y)Variável de resposta ou Dependente:** Na regressão é o que queremos prever.
- **(Eixo X)Variável de explanatória ou Independente:** Na regressão é o que explica, ou usamos para prever.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2"> CORRELAÇÃO (R)</h1>
<br>

- Mostra a força e direção entre variáveis.
- Pode ser um valor entre -1 e 1.
- A correlação de **A ~ B** é a mesma que **B ~ A**


<br>
<h3>FORÇA E DIREÇÃO</h3>
<div align="center">
  <image src="./image/forca_direcao.png" alt="regressão_linear" height="400" width="80%">
</div>



<br>
<h3>GRAFICO DE DISPERSÃO (FORTE e FRACA)</h3>
<div align="center">
  <image src="./image/graficos_correlacao_01.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<h3>GRAFICO DE DISPERSÃO</h3>
<div align="center">
  <image src="./image/graficos_correlacao_02.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h3>COEFICIENTE DE DETERMINAÇÃO (R^2)</h3>
<div align="center">
  <image src="./image/coeficiente_determinacao.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h3> EXEMPLO COEFICIENTE DE DETERMINAÇÃO (R^2)</h3>
<div align="center">
  <image src="./image/exemplo_coeficiente_determinacao.png" alt="regressão_linear" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3"> PREVISÃO</h1>
<br>

- Se constroí a **Linha de regressão** ou **Linha de melhor ajuste**.
- Após isso, é possível fazer uma previsão com base na linha.

- A **linha** pode eventualmente coincidir com os pontos do grafico, mas de maneira geral não.

- Previsão baseadas nas **linhas(modelo de previsão)** e não nos **pontos(dados)**, mesmo se já tiver a informação daquele ponto.

<br>
<h3> COMO A LINHA É CONSTRUÍDA ?</h3>
<div align="center">
  <image src="./image/linha_construida.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h3> EXEMPLO</h3>
<div align="center">
  <image src="./image/exemplo_linha_previsao.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<h3> COMO PREVER ?</h3>
<div align="center">
  <image src="./image/exemplo_linha_previsao_1.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h3> QUAL A MELHOR ?</h3>
<div align="center">
  <image src="./image/exemplo_linha_previsao_2.png" alt="regressão_linear" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4">RESÍDUOS</h1>
<br>


- A distancia entre a linha de previsão e o dado é chamado de **Resíduo**.

<br>
<h3> VALOR DO RESÍDUO</h3>
<div align="center">
  <image src="./image/valor_residuo.png" alt="regressão_linear" height="400" width="80%">
</div>



<br>
<h3> VALORES AJUSTADOS</h3>
<div align="center">
  <image src="./image/valores_ajustados.png" alt="regressão_linear" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5">OUTLIERS</h1>
<br>

- É um dado que passa da média.

- Uma variavel que pode mudar completamente o modelo.

- Deve-se avaliar se o caso vai fazer parte de modelo.

- Deve verificar se o caso vai acontecer novamente ou se não foi um valor digitado errado.

- Não uma regra para o caso, deve ser analisado.

<br>
<h3> EXEMPLO</h3>
<div align="center">
  <image src="./image/outliers.png" alt="regressão_linear" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6">EXTRAPOLAÇÃO</h1>
<br>

- Tentar prever um dado que está fora do range de analise.
> Exemplo: Não faz sentido prever valor do plano de saúde para a idade de 140 anos.

- Não uma regra para o caso, deve ser analisado.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="7">CONDIÇÕES PARA REGRESSÃO LINEAR</h1>
<br>

- Se espera que a **_correlação_** das variáveis explanatória(X) e variável de resposta(Y)  seja **Moderada** ou **Forte**

COEFICIENTE DE DETERMINAÇÃO (R^2):

- maior que 0,7: ÓTIMO
- Entre eles: ? (Fica ao seu critério se irá avaliar se vai criar o modelo ou não).
- 0 até 0,3: Ruim

<br>
<h3>EXEMPLO</h3>
<div align="center">
  <image src="./image/residuais_padronizados.png" alt="regressão_linear" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="8">REGRESSÃO LINEAR SIMPLES E MÚLTIPLA</h1>
<br>

- A quantidade de variável explanatória não diz se o modelo vai ser bom ou não.

- **Simples**
  - Uma variável explanatória para prever uma variavel dependente.
  - **_Y ~ X_**

- **Múltipla**
  - Duas variáveis explanatórias para prever uma variavel dependente.
  - **_Y ~ X1 + X2 + Xn_**


<h2> ANALISAR CADA X COM Y</h2>

- Analisar cada variável independente com Y individualmente.

- Geral gráficos de dispersão individuais.

- Buscar redundâncias (mesmos efeitos de X sobre Y)


<br>
<div align="center">
  <image src="./image/coeficiente_determinacao_multipla.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/colinearidade_parcimonia.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h2>REQUISITOS BÁSICOS</h2>

1. Linearidade entre a variável dependente e as variáveis independentes.
2. Pouca ou nenhuma Colinearidade.


<br>
<h2>RESÍDUOS</h2>

- Próximos a distribuição normal.
- Variância constante em relação a linha de melhor ajuste.
- Independentes (Sem padrão).

<br>
<h2 align="center">EXEMPLO DE CORRELOGRAMA</h2>
<div align="center">
  <image src="./image/correlograma.png" alt="regressão_linear" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="9">CÁLCULOS</h1>
<br>

<br>
<h2 align="center">ETAPAS</h2>
<div align="center">
  <image src="./image/calculos_etapas.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h2>CORRELAÇÃO</h2>

- É usado o cálculo da **Covariância**
> COVARIÂNCIA: Grau de Dependência, ou relação matemática, entre duas variáveis numéricas.

<br>
<h2 align="center">CÁLCULO DA CORRELAÇÃO</h2>
<div align="center">
  <image src="./image/calculos_correlacao.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h2 align="center">CÁLCULO DA INCLINAÇÃO</h2>
<div align="center">
  <image src="./image/calculos_inclinacao.png" alt="regressão_linear" height="400" width="80%">
</div>

<br>
<h2 align="center">CÁLCULO DA INTERCEPTAÇÃO</h2>
<div align="center">
  <image src="./image/calculos_interceptacao.png" alt="regressão_linear" height="400" width="80%">
</div>


<br>
<h2 align="center">CÁLCULO DA PREVISÃO</h2>
<div align="center">
  <image src="./image/calculos_previsao.png" alt="regressão_linear" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="10">OBSERVAÇÕES</h1>
<br>

- Correlação não é causa.

- Não é porque diferentes tipos de dados tem o mesmo crescimento que ela tem uma relação.
