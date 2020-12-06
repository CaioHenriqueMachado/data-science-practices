<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1"> Estatística I</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Conceitos gerais](#1)
  - [O que é estatística?](#1_1)

  - [Principais divisões](#1_2)
    - Estatística Descritiva
    - Estatística Probabilística
    - Estatística Inferêncial

  - [Conceitos](#1_3)
    - Observação
    - Experimento

  - [Variaveis](#1_4)

  - [Analise dos resultados](#1_5)

- [Análise exploratória de Dados](#2)

- [Amostragem](#3)
  - [Conceitos](#3_1)
  - [Custo de usar amostra](#3_2)
  - [Principais tipos de amostra](#3_3)

- [Pequenas Amostras](#4)

- [Medidas de Centralidade](#5)
  - [Média](#5_1)
  - [Moda](#5_2)
  - [Mediana](#5_3)

- [Medidas de Variabilidade](#6)
  - [Variância](#6_1)
  - [Desvio Padrão](#6_2)
  - [Amplitude](#6_3)
  - [Não Centrais: Quartis](#6_4)
  - [Notações](#6_5)

- [Probabilidade](#7)
  - [Conceitos](#7_1)
  - [Eventos Excludentes](#7_2)
  - [Eventos não Excludentes](#7_3)
  - [Eventos dependentes](#7_4)
  - [Eventos independentes](#7_5)
  - [Único evento](#7_6)

- [Passeio Aleatório](#8)

- [Estocástico X Deterministico](#9)

- [Probabilidade em jogos de Azar](#10)

- [Distribuição](#11)

- [Distribuição Gaussiana](#12)

- [Teorema central do limite](#13)

- [Estatística não paramétrica](#14)


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1"> CONCEITOS GERAIS</h1>
<br>

<h3 id="1_1"> ESTATÍSTICA </h3>

Estatística é a ciência que se utiliza nas teorias probabilísticas para explicar a frequência da ocorrência de eventos, 
tanto em estudos observacionais quanto em experimentos para modelar a aleatoriedade e a incerteza de forma a estimar ou 
possibilitar a previsão de fenômenos futuros, conforme o caso.

<br>

<h3 id="1_2"> PRINCIPAIS DIVISÕES </h3>

**- Estatística Descritiva:** 

Organizar, demonstrar e resumir dados. A intensão é torna-los apresentaveis.
> Muito usada na analise exploratória e apresentação de resultados.
<br>

**- Estatística Probabilística:** 

Analisar situações sujeitas ao acaso.
> Exemplo: jogar uma moeda e ver se irá dar "cara" ou "coroa".
<br>

**- Estatística Inferêncial:**

Obter respostas sobre um fenômeno com dados representativos.
> Exemplo: Preferência de votos. Não é possível consultar todos eleitores, logo, é coletado apenas uma amostra para tentar fazer a representação de um todo.
<br>


<h3 id="1_3"> CONCEITOS </h3>

**- Observação:**

Estudo em que os elementos analisados não são afetados (Apenas uma pesquisa).
> Exemplo: Preferência de votos. Não tem como mudar a opinião do eleitor, pois você só está perguntando e pesquisando)
<br>

**- Experimentos:**

Condições ou tratamentos são impostos a grupos, para avaliar o resultado. 
> Exemplo: Ver o quanto uma vacina é efetiva. Separa em grupos e em um dos grupos aplica uma vacina Placebo(Será o seu grupo de controle. Sem niguém saber, nem os médicos). Para que você analise uma grupo que tomou e outro que não tomou a vacina e assim veja o nível de efetividade da vacina
<br>

<h1 align="center"  id="1_4">VARIAVEIS </h1>

<div align="center">
  <image src="./image/variaveis.png" alt="Web Version" height="400" width="80%">
</div>

<br>
<h3>EXEMPLOS:</h3>

<h4>QUANTITATIVAS:</h4>

**Contínuas:** Altura; Peso;

**Discretas:** Número de voltas na pista; Idade; Quantidade de filhos;

<h4>QUALITATIVAS:</h4>

<p>**Nominais:** Cores; Animal;</p>
<p>**Ordinais:** Cargo;</p>

<br>

<h3 id="1_5">ANÁLISE DE RESULTADOS</h3>

Estatísca não é exata, é necessário, **INTERPRETAÇÃO**, **ESCOLHAS** e **AVALIAÇÃO**. Uma outra pessoa pode não ter o mesmo resultado que você, pois ela pode ter usado dados ou métodos diferentes. Cabe ao cientista decidicir como ele vai analisar seus resultados.

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"  id="2">ANÁLISE EXPLORATÓRIA DE DADOS (AED)</h1>
<br>

<h3>CONCEITO</h3>

Busca/Obter informações ocultas sobre os dados.

Após essa a técnica (Exploratory Data Analysis) EDA, decidir como buscar a solução para o problema.

<h3>Técnicas para localizar essas informações:</h3>

 - Variação
 - Anomalias
 - Distribuição
 - Tendências
 - Padrões
 - Relações

<div align="center">
  <image src="./image/eda.png" alt="Web Version" height="400" width="80%">
</div>

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3">AMOSTRAGEM</h1>
<br>

É parte de uma população, selecionada usando alguma técnica que dê chances iguais para todos os elementos serem selecionados.

<h3 id="3_1">CONCEITOS:</h3>

**População:** Alvo de estudo.

**Amostra:** Subconjunto da população.

**Censo:** Pesquisa com toda população.

As vezes é trabalhado com amostras pois fazer um censo pode ter um alvo custo ou impossível de se fazer.

Uma amostra feita corretamente, deve representar as mesmas características de onde foi tirada. Terá o mesmo resultado da população inteira.

Se a amostra não representa a população, dizemos que ela é **INVIESADA**.

Trabalhar com uma amostra e inferencia, tem um preço e um risco.

<div align="center">
  <image src="./image/enviesamento.png" alt="Web Version" height="300" width="80%">
</div>


<h3 id="3_2">CUSTO DE USAR AMOSTRA:</h3>

 - Margem de Erro e nível de Confiança.
 - Variação: Amostrar diferentes pode apresentar resultados diferentes.
 - Podemos "medir" a variação esperada.

<h3 id="3_3">PRINCIPAIS TIPOS DE AMOSTRA:</h3>

**- Amostra aleatória simples:**

Um determinado número de elementos é retirado de forma aleatória.
Usar técnica para que todos tenham a mesma chance de ser escolhido.
> Indexar - Dá número para cada elemento da população, após isso, usa um algoritmo para gerar números aleatórios
<br>

**- Amostra aleatória simples com reposição:**

Ao ser escolhido, ele volta para a população podendo ser escolhido novamente. 
<br>
 
**- Amostra aleatória simples sem reposição:**

Ao ser escolhido, não pode ser escolhida novamente.
<br>


**- Amostra Estratificada:**

A população pode ser divididas e chamada por estratos.
> Por exemplo: Dividido a partir do Sexo do elemento. Assim pegando X Homens para um grupo e X mulheres para outro grupo.
<br>

**- Amostra Sistemática:**

É escolhido um número aleatório, e a partir daí vai pulando a cada N elementos.
> Por exemplo: o primeiro número escolhido aleatóreamente é o número 5 e a partir daí vai pulando de três em três. Escolhidos: 5, 8, 11, 14 ...
<br>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"  id="4"> PEQUENAS AMOSTRAS</h1>
<br>


 - Probabilidade de conclusões falsas
 - Não reprodutivo
 - Não comparável



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"  id="5"> MEDIDAS DE CENTRALIDADE</h1>
<br>


<h3 id="5_1">MÉDIA</h3>

- É uma medida de centralidade.
- Somar todos os custos dos elementos e dividir quandidade de elementos.
> Média pode ser influenciada por valores foras do padrão, diferente da Mediana.


<h4>Média Ponderada</h4>

Cada número está sujeito a um peso.

**Exemplo:**
 - Prova A peso 1, nota 7.
 - Prova B peso 2, nota 9.
> CALCULO => média = ( 7*1  +  9*2  ) / (1 + 2)  = 8,3

<br>
<h3  id="5_2">MODA</h3>
<br>


É o valor que mais ocorre. Pode ter 2 valores que mais ocorrem.

**Exemplo:**
 - Idades: 10, 12, 20, 10.
 - A moda é 10.

> Pode não existir uma moda (caso não tenha valores repetidos).

<br>
<h3 id="5_3">MEDIANA</h3>
<br>

 - Valor do meio.

 - Ordena-se os valores em ordem crescente.

 - Se a quantidade de elementos for par, você tira a média dos dois valores no centro e terá a mediana.

 - Se a quandidade de elementos for impar, a mediana será o elemento do meio. 


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6"> MEDIDAS DE VARIABILIDADE</h1>
<br>

<h3 id="6_1">VARIÂNCIA</h3>

- Mostra a regularidade dos dados. Como os dados variam com relação a média.

- Há duas fórmulas, variância do elemento e variância da população.


<h3 id="6_2">DESVIO PADRÃO</h3>

- Quanto maior o desvio, mais os dados estão distantes da média.
- Se for igual a zero, significa que não existe variação nos dados. (Eles são iguais)
> Calculo: Raiz quadrada da Variância.

 
<h3 id="6_3">AMPLITUDE</h3>

- Diferença entre o maior e menor valor.

<h3 id="6_4">NÃO CENTRAIS: QUARTIS</h1>

- Q0: É o menor valor
- Q1: 25% dos menores valores
- Q2: 50% (equivale a mediana)
- Q3: 75% dos maiores valores
- Q4: É o maior valor


<h1 align="center" id="6_5"> NOTAÇÕES</h1>
<div align="center">
  <image src="./image/notacoes.png" alt="data_science" height="300" width="80%">
</div>
<br>
<div align="center">
  <image src="./image/variancia_desvio.png" alt="data_science" height="300" width="80%">
</div>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="7"> PROBABILIDADE</h1>
<br>

É a chance de um evento acontecer.

<br>
<div align="center">
  <image src="./image/probabilidade_1.png" alt="data_science" height="300" width="80%">
</div>


<h3 id="7_1">CONCEITOS</h3>

 - Experimento: O que está sendo estudado
 - Espaço Amostral: Todas as possibilidades de ocorrência do evento.
 - Evento: Resultado ocorrido

**Exemplo:**

 - Experimento: Jogar moeda.
 - Espaço Amostral: Cara ou Coroa.
 - Evento: "Deu coroa !".


<h3 id="7_2">EVENTOS EXCLUDENTES</h3>

- Eventos que não podem ocorrer ao mesmo tempo.
> Exemplo 1: Jogar um dado e ser 1 e par

> Exemplo 2: Jogar um dado e dar 1 ou par: (1/6 + 3/6)  P = 4/6, P = 0,66

<h3 id="7_3">EVENTOS NÃO EXCLUDENTES</h3>

- Eventos que podem ocorrer ao mesmo tempo.
> Exemplo 1: Jogar um dado e ser 2 e par

> Exemplo 2: Jogar um dado e dar 2 ou par: (1/6 + 3/6 - 1/6)  P = 3/6, P = 0,5

<h3 id="7_4">EVENTOS DEPENDENTES</h3>

- A ocorrência de um evento afeta o outro. Um tem que ocorrer para depois que o outro ocorra.
> Exemplo 1: Tirar duas cartas do baralho sem repor. Sendo que a segunda carta deve ser dama de paus

> Exemplo 2: Com 6 cartas na mão (A, 2, 3, 4, 5, 6), qual a probabilidade de primeiro evento tirar A e no segundo evento tirar 4.
> RESULTADO: P = (1/6 * 1/5) = 1/30 => 0,033 


<br>
<h3 id="7_5">EVENTOS INDEPENDENTES</h3>

- A ocorrência de um evento não afeta o outro.
> Exemplo 1: jogar um dado. A probabilidade de dar 3 é sempre a mesma.

> Qual a probabilidade de jogar dois dados, e dar 1 e 6: (dois eventos independentes)
> REPOSTA: P = (1/6 * 1/6) => P = 1/36 => 0,027

<br>
<h3 id="7_6">ÚNICO EVENTO</h3>

**Calculo** 

- P = (Ocorrência Esperada) / (Número de Eventos Possíveis)


**Exemplos:**

- Jogar uma moeda e dar cara: P = 1/2, P = 0,5

- Jogar um dado e dar 6: P = 1/6, P = 0,16

- Jogar um dado e dar 1 ou 6: P = 2/6, P = 0,33

- Jogar um dado e dar 1, 2, 3, 4, 5 ou 6: P = 6/6, P = 1

- Jogar um dado e dar ímpar ou maior que 4: P = 4/6, P = 0,66


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="8"> PASSEIO ALEATÓRIO</h1>
<br>

<br>
<div align="center">
  <image src="./image/passeio_aleatorio.png" alt="data_science" height="300" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="9"> ESTOCÁSTICO X DETERMINISTICO</h1>
<br>


**Processo Estocástico:**

Com um algoritmo. Dada uma mesma entrada, a saída pode variar.
<br>

**Processo Deterministico:**

Com um algoritmo. Dada uma mesma entrada, apresenta sempre a mesma saída.




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="10"> PROBABILIDADE EM JOGOS DE AZAR</h1>
<br>

 - São eventos independentes.

 - A probabilidade de sortear:
   -  1,2,3,4,5 e 6
   - Os seus números favoritos.
   - Ou qualquer outra combinação.

> São as mesmas probabilidades !!!


<br>
<div align="center">
  <image src="./image/mega.png" alt="data_science" height="300" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="11"> DISTRIBUIÇÃO</h1>
<br>


- Usado principalmente na teoria da probabilidade
- Mostra o comportamento de dados aleatórios
- Uma forma de analisar é por meio de um histograma



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="12"> DISTRIBUIÇÃO NORMAL OU GAUSSIANA</h1>
<br>

 - É uma distribuição onde os dados se apresentam como sino e nele tem uma simetria dos dados.
 - A maioria dos dados em uma distribuição normal estão distante até no máximo três desvios padrão da média.
 - Usada para calculo de probabilidade.
 - Ver se os dados estão normalmente distribuidos.

<br>
<div align="center">
  <image src="./image/distribuicao_normal_1.png" alt="data_science" height="300" width="80%">
</div>

<br>
<h3>DISTRIBUIÇÃO NORMAL PADRÃO (Z)</h3>

<br>
<div align="center">
  <image src="./image/distribuicao_normal_2.png" alt="data_science" height="300" width="80%">
</div>
<br>

<h3>CALCULO</h3>

 - Como a distribuição normal é complexa de ser calculada, é aplicado os valores em uma fórmula é depois utiliza-se a Tabela Z.

<br>
<div align="center">
  <image src="./image/formula.png" alt="data_science" height="300" width="80%">
</div>

- Sempre que o enunciado pedir probabilidade **"Mais que ..."** tem que fazer: z = 1 - z 

<h3>EXEMPLO</h3>

<br>
<div align="center">
  <image src="./image/exemplo_distri.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distri_2.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distri_3.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distri_4.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distri_5.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/exemplo_distri_6.png" alt="data_science" height="300" width="80%">
</div>


<h3>OBSERVAÇÃO</h3>

 - Distribuição Normal: É Contínua, a busca da probavbilidade é feita por intervalos.

 - Não se busca probabilidades discretas! (não se busca a probabilidade de um valor exato).

 - Probabilidade Discreta: Usa-se Distribuição Binomial.


<h3>COMO SABER SE É NORMAL ?</h3>

- O método mais simples é gerar um Histograma. 
> Quanto mais a amostras, mais ela vai representar a realidade

- Se ele parecer um sino, diz que ele está normalmente distribuido.

- Temos também o Diagrama de probabilidade normal (ou também, QQPLOT).
> Se os dados seguem a linha, tem indicios que estão normalmente distribuidos.

- Teste de Shapiro-Wilk
> Aplica a formula e se P for maior que 0,05 ele tem indicio que é normalmente distribuido.


<h3>OBSERVAÇÃO</h3>

- Nem sempre os dados precisam ser rigorosamente normais. Dados aproximadamente normais são suficientes para a maioria dos casos.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="13">TEOREMA CENTRAL DO LIMITE</h1>
<br>


<br>
<div align="center">
  <image src="./image/teorema_central_limite.png" alt="data_science" height="300" width="80%">
</div>
<br>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="14">ESTATÍSTICA NÃO PARAMÉTRICA</h1>
<br>

- Não é abordado esta parte no curso.

- Estatística paramétrica
  - Requer que os dados estejam em conformidade com alguma distribuição.
  > Ex: Distribuição Normal.  

<br>
<div align="center">
  <image src="./image/nao_parametrica.png" alt="data_science" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/nao_parametrica_2.png" alt="data_science" height="300" width="80%">
</div>












