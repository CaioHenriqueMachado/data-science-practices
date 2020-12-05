<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center"> Estatística I</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Intervalos de Confiança](#1)

- [Testes de Hipótese](#2)

- [T de Student](#3)

- [Distribuição Binomial](#4)

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

