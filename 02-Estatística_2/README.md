<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center"> Estatística I</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Intervalos de Confiança](#1)

- [Testes de Hipótese](#2)

- [T de Student](#3)

- [Distribuição Binomial](#4)

- [Distribuição de Poisson](#5)

- [Qui-Quadrado](#6)


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1"> INTERVALOS DE CONFIANÇA</h1>
<br>

- É possível inferir características de uma população a partir de uma amostra.

- Porque fazer amostra?
  - Custo
  - Viabilidade
  - Etc.
- Preço: erro padrão / nível de confiança
- Riscos: dados ruins, enviesamento


- A cada amostra pesquisada pode ter uma variação.
> É possível medir esse nível de variação

**Intervalo de confiança:** 
- O parâmetro mais o menos a margem de erro estimada.
<br>

**Parâmetro:**
- Valor a ser estimado.
<br>

**Margem de erro:** 
- Variabilidade, para mais ou para menos.
<br>

**Nível de Confiança:** 
- De 80 a 99%
<br>

**Tamanho da Amostra(n)**

<br>
<h3>TABELA</h3>
<div align="center">
  <image src="./image/nivel_confianca.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<h3>EXEMPLO</h3>
<div align="center">
  <image src="./image/nivel_confianca_exemplo.png" alt="estatistica_2" height="400" width="80%">
</div>

<div align="center">
  <image src="./image/nivel_confianca_exemplo_2.png" alt="estatistica_2" height="400" width="80%">
</div>

<div align="center">
  <image src="./image/compensacao.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h3>INTERVALO DE CONFIANÇA PARA A MÉDIA</h3>

- O objetivo do calculo de intervalo de confiança é achar a **Margem de erro**.

<h4>EXEMPLO</h4>
<div align="center">
  <image src="./image/nivel_confianca_exemplo_3.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/nivel_confianca_conclusao.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h3>INTERVALO DE CONFIANÇA PARA A PROPORÇÃO</h3>

<br>
<h4>EXEMPLO</h4>
<div align="center">
  <image src="./image/nivel_confianca_exemplo_4.png" alt="estatistica_2" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2">TESTES DE HIPÓTESE</h1>
<br>

- Teste de hipótese é para confirmar ou negar uma premissa usando amostra.
> Exemplo: "56% dos brasileiros não gostam de estatistica" Você vai fazer a mesma pesquisa e vai tentar ver se o resultado bate.

- Se você chegar ao resultado de 55%, ainda não é o suficiente, basta ver se a diferença é estatisticamente significante.

- Teste de hipótese é sempre feito com amostra. Se fosse feito com a população toda não é um teste de hipótese pois você já vai está chegando no valor **real** e não uma estimativa.

<br>
<div align="center">
  <image src="./image/teste_hipotese_conceito.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h4>ALFA E VALOR-P</h4>

**_Alfa:_**
- 0,05 ou
- 0,01

**_Interpretar valor-P:_**

- **valor-P** >= **alfa**
> Não rejeita H0
<br>

- **valor-P** < **alfa**
> Rejeita H0
<br>

- **valor-P** se for MUITO PRÓXIMO **alfa**
> Tem pessoas que dizem que o teste foi INCONCLUSIVO. (Vai depender da sua interpretação)
<br>

<h4>ETAPAS</h4>

1. Definir o tamanho da sua amostra.
2. Coletar dados.
3. Calcular a média e o desvio padrão.
4. Definir as duas hipóteses: *H0* e *Ha*.
5. Definir seu *alfa*
6. Padronizar seus dados gerando a estatística de teste.
7. Encontrar o *valor-p* na Tabela Z.
8. Comparar com seu *alfa*.
9. Emitir seu veredito.

<br>
<h2 align="center" id="2">EXEMPLO TESTE DE HIPÓTESE PARA MÉDIA</h2>

<br>
<div align="center">
  <image src="./image/teste_hipotese_exemplo_media.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<h2 align="center" id="2">EXEMPLO TESTE DE HIPÓTESE PARA PROPORÇÃO</h2>

<br>
<div align="center">
  <image src="./image/teste_hipotese_exemplo_proporcao.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/escolha_alfa.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h4>VALOR IDEAL</h4>

- Amostra grande
- Alfa pequeno


<br>
<h2 align="center" id="2">AVALIAR RESULTADO</h2>

<br>
<div align="center">
  <image src="./image/avaliar_resultado.png" alt="estatistica_2" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3">DISTRIBUIÇÃO T DE STUDENT</h1>
<br>

- Utilizada quando a amostra é pequena (menor que 30).
- E não se conhece o desvio padrão da população.
- Custo: Maior variabilidade.
> Por exemplo: Em um teste de hipótese.
- Tendência maior de encontrar valores nas caudas(caudas maiores).
- Se n >= 30, vai dar na mesma que uma distribuição normal.

**- Você pode usar T de Student para:**
  - Calcular probabilidades
  - Calcular Intervalos de Confiança
  - Executar testes de Hipótese

**- Como usar T de Student:**
  - Calculamos o valor T
  - Consultamos uma tabela de Distribuição T

<br>
<div align="center">
  <image src="./image/grau_liberdade.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h2 align="center" id="2">EXEMPLO T  DE STUDENT</h2>

<br>
<div align="center">
  <image src="./image/exemplo_t_student.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_t_student_2.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_t_student_3.png" alt="estatistica_2" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4">DISTRIBUIÇÃO BINOMIAL</h1>
<br>

- Distribuição de Probabilidade discreta.
- Ou seja, usada para contar a probabilidade de **eventos discretos**
> Eventos discretos: eventos que se pode contar.
- Diferente da **Distribuição normal** que não se pode contar e é calculada por intervalos (maior que, menor que).

<h4>PRÉ-REQUISITOS</h4>

- Número Fixo de Experimentos.
- Cada Experimento pode ter 2 resultados apenas: sucesso ou fracasso.
- A probabilidade de sucesso deve ser a mesma em cada experimento.
- Os experimentos são independentes.


<br>
<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_1.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_2.png" alt="estatistica_2" height="400" width="80%">
</div>


<h4>CONVENÇÕES</h4>

- **X:** Total de sucesso esperado do experimento.
- **p:** probabilidade de sucesso.
- **n:** Número de experimentos.
- **1-p:** Probabilidade de sucesso


<br>
<h2 align="center" id="2">FÓRMULA</h2>

<div align="center">
  <image src="./image/formula_distribuicao_binomial.png" alt="estatistica_2" height="400" width="80%">
</div>




<br>
<h2 align="center" id="2">EXEMPLOS</h2>

<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_3.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>

<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_4.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<h2 align="center" id="2">EXEMPLO USANDO A TABELA</h2>
<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_5.png" alt="estatistica_2" height="400" width="80%">
</div>

<div align="center">
  <image src="./image/exemplo_distribuicao_binomial_6.png" alt="estatistica_2" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5">DISTRIBUIÇÃO DE POISSON</h1>
<br>

- Mede a probabilidade da ocorrência de eventos em **intervalo de tempo**, em vez de um certo número de experimentos.
- Os eventos a cada intervalo devem ser independentes.
- Existem tabelas de probabilidade.

<br>
- Ao saber a ocorrência:
 - P(X = x)
 - P(X < x)
 - P(X > x)

<br>
<h2 align="center" id="2">FÓRMULA de POISSON</h2>

<div align="center">
  <image src="./image/formula_distribuicao_poisson.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>
<h2 align="center" id="2">EXEMPLO</h2>

<div align="center">
  <image src="./image/exemplo_distribuicao_poisson_1.png" alt="estatistica_2" height="400" width="80%">
</div>

<br>

<div align="center">
  <image src="./image/exemplo_distribuicao_poisson_2.png" alt="estatistica_2" height="400" width="80%">
</div>


<div align="center">
  <image src="./image/exemplo_distribuicao_poisson_3.png" alt="estatistica_2" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6">QUI-QUADRADO</h1>
<br>

- **Hipótese nula (H0):** Não existe diferença significativa além do acaso.

- Se **_p-value_** > 0,05
> Não Rejeita H0

- Se **_p-value_** < 0,05
> Tem inidicios de diferença significativa e pode Rejeitar H0.


<br>
<h2 align="center" id="2">EXEMPLO</h2>

<div align="center">
  <image src="./image/exemplo_qui_quadrado.png" alt="estatistica_2" height="400" width="80%">
</div>


<br>
<h2 align="center" id="2">EXEMPLO</h2>

<div align="center">
  <image src="./image/exemplo_qui_quadrado.png" alt="estatistica_2" height="400" width="80%">
</div>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="7">TESTE T DE STUDENT</h1>
<br>

- Teste de Hipótese
- Compara duas médias
- Pré-requisitos:
  - Duas populações são independentes.
  - Variável dependente normalmente distribuída.
  - Variância entre duas variáveis é aproximada.

-**H0:** Não há diferença significativa.


<div align="center">
  <image src="./image/teste_t_student.png" alt="estatistica_2" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="8">ANALISE DE VARIÂNCIA (ANOVA)</h1>
<br>

- Anova mostra se existe ou não variação significativa, mas não aonde!

- Teste de Hipótese.
- Usada para comparar 3 ou mais grupos.
- Uma variável quantitativa e uma ou mais variáveis categóricas.
- Em vez de comparações em pares de grupos, **"olha"** todo o conjunto.
- Busca a variação entre os grupos comparado a variação **"dentro"** dos grupos.



PARA VER SE HÁ DIFERENÇA É REALIZADO O **_TESTE F_**



<h4>TESTE F</h4>

- F(X, Y)
- X = Graus de liberdade: número de grupos -1
- Y = Graus de liberade no denominador: número de observações - número de grupos

- **Hipótese nula(H0):** Não há diferença significativa entre os grupos.

- **Valor-p < alfa:** Há diferença significativa entre os grupos


<h4>ANOVA</h4>

- Anova mostra se existe ou não variação significativa, mas não aonde!
- Para ver quais existem diferenças significativas: **_TESTE DE TUKEY_**


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="9">TESTE DE TUKEY</h1>
<br>

- **Hipótese nula(H0):** Não há diferença significativa entre as duplas.

- Se **_valor-p_** > **alfa**, tem uma diferença significativa na dupla comparada.



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="10">MÉTRICAS DE ERROS</h1>
<br>

- Existe uma diferença entre a previsão e o que ocorreu...
- Temos que medir esta diferença!
  - Para saber a qualidade do nosso modelo!
  - Para podermos melhora-lo.
  - Para podermos fazer benchmarks.

  

