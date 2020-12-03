<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center"> Estatística I</h2>


### SUMÁRIO

- Conceitos gerais
    - O que é estatística?

    - Principais divisões
      - Estatística Descritiva
      - Estatística Probabilística
      - Estatística Inferêncial

    - Conceitos
      - Observação
      - Experimento

    - Variaveis

    - Analise dos resultados

- Análise exploratória de Dados

- Amostragem
    - Conceitos
    - Custo de usar amostra
    - Principais tipos de amostra

- Medidas de centralidade
    - Média
    - Moda
    - Mediana

- Medidas de variabilidade
   - Variância
   - Desvio Padrão
   - Amplitude
   - Não Centrais: Quartis

- Probabilidade



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> CONCEITOS GERAIS</h1>
<br>

### ESTATÍSTICA

Estatística é a ciência que se utiliza nas teorias probabilísticas para explicar a frequência da ocorrência de eventos, tanto em estudos observacionais quanto em experimentos para modelar a aleatoriedade e a incerteza de forma a estimar ou possibilitar a previsão de fenômenos futuros, conforme o caso.

<br>

### PRINCIPAIS DIVISÕES:

 - Estatística Descritiva
 - Estatística Probabilística
 - Estatística Inferêncial


### Estatística Descritiva: 

Organizar, demonstrar e resumir dados. A intensão é torna-los apresentaveis.
(Muito usada na analise exploratória e apresentação de resultados)


### Estatística Probabilística: 

Analisar situações sujeitas ao acaso.
(Exemplo: jogar uma moeda e ver se irá dar "cara" ou "coroa")

### Estatística Inferêncial:

Obter respostas sobre um fenômeno com dados representativos.
(Exemplo: Preferência de votos. Não é possível consultar todos eleitores, logo, é coletado apenas uma amostra para tentar fazer a representação de um todo)

<br>

### CONCEITOS:

### Observação: 

Estudo em que os elementos analisados não são afetados (pesquisa).
(Exemplo: Preferência de votos. Não tem como mudar a opinião do eleitor, pois você só está perguntando e pesquisando)

### Experimentos: 

Condições ou tratamentos são impostos a grupos, para avaliar o resultado. 
(Exemplo: Ver o quanto uma vacina é efetiva. Separa em grupos e em um dos grupos aplica uma vacina Placebo(Será o seu grupo de controle. Sem niguém saber, nem os médicos). Para que você analise uma grupo que tomou e outro que não tomou a vacina e assim veja o nível de efetividade da vacina)


<h1 align="center">VARIAVEIS </h1>

<div align="center">
  <image src="./image/variaveis.png" alt="Web Version" height="400" width="80%">
</div>

<br>

### EXEMPLOS:

### QUANTITATIVAS:

<p>Contínuas: Altura; Peso;</p>
<p>Discretas: Número de voltas na pista; Idade; Quantidade de filhos;</p>

### QUALITATIVAS:

<p>Nominais: Cores; Animal;</p>
<p>Ordinais: Cargo;</p>

<br>

### ANÁLISE DE RESULTADOS

Estatísca não é exata, é necessário, INTERPRETAÇÃO, ESCOLHAS e AVALIAÇÃO. Uma outra pessoa pode não ter o mesmo resultado que você, pois ela pode ter usado dados ou métodos diferentes. Cabe ao cientista decidicir como ele vai analisar seus resultados.

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center">ANÁLISE EXPLORATÓRIA DE DADOS (AED)</h1>

Busca/Obter informações ocultas sobre os dados.

Após essa a técnica (Exploratory Data Analysis) EDA, decidir como buscar a solução para o problema.

### Técnicas para localizar essas informações

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
<h1 align="center">AMOSTRAGEM</h1>

É parte de uma população, selecionada usando alguma técnica que dê chances iguais para todos os elementos serem selecionados.

CONCEITOS:

População: Alvo de estudo.

Amostra: Subconjunto da população.

Censo: Pesquisa com toda população.

As vezes é trabalhado com amostras pois fazer um censo pode ter um alvo custo ou impossível de se fazer.

Uma amostra feita corretamente, deve representar as mesmas características de onde foi tirada. Terá o mesmo resultado da população inteira.

Se a amostra não representa a população, dizemos que ela é INVIESADA.

Trabalhar com uma amostra e inferencia, tem um preço e um risco.

<div align="center">
  <image src="./image/enviesamento.png" alt="Web Version" height="300" width="80%">
</div>


CUSTO DE USAR AMOSTRA:

 - Margem de Erro e nível de Confiança.
 - Variação: Amostrar diferentes pode apresentar resultados diferentes.
 - Podemos "medir" a variação esperada.

### PRINCIPAIS TIPOS DE AMOSTRA:

 - Amostra aleatória simples.
 - Amostra Estratificada.
 - Amostra Sistemática.


### Amostra aleatória simples

Um determinado número de elementos é retirado de forma aleatória.
Usar técnica para que todos tenham a mesma chance de ser escolhido.
(Indexar - Dá número para cada elemento da população, após isso, usa um algoritmo para gerar números aleatórios)

Amostra aleatória simples COM REPOSIÇÃO:

Ao ser escolhido, ele volta para a população podendo ser escolhido novamente. 

 
Amostra aleatória simples SEM REPOSIÇÃO:

Ao ser escolhido, não pode ser escolhida novamente.


### Amostra Estratificada

A população pode ser divididas e chamada por estratos.
(Por exemplo: Dividido a partir do Sexo do elemento. Assim pegando X Homens para um grupo e X mulheres para outro grupo)

### Amostra Sistemática

É escolhido um número aleatório, e a partir daí vai pulando a cada N elementos.
(Por exemplo: o primeiro número escolhido aleatóreamente é o número 5 e a partir daí vai pulando de três em três. Escolhidos: 5, 8, 11, 14 ...)



<img src="./image/line.png" alt="line" width="100%">
<h1 align="center"> MEDIDAS DE CENTRALIDADE</h1>
<br>


### MÉDIA

### Média 

É uma medida de centralidade.

Somar todos os custos dos elementos e dividir quandidade de elementos.

Média pode ser influenciada por valores foras do padrão, diferente da Mediana.

### Média Ponderada

Cada número está sujeito a um peso.

Exemplo:
 - Prova A peso 1, nota 7.
 - Prova B peso 2, nota 9.

média = ( 7*1  +  9*2  ) / (1 + 2)  = 8,3

### MODA

É o valor que mais ocorre. Pode ter 2 valores que mais ocorrem.

Exemplo:
 - Idades: 10, 12, 20, 10.
 - A moda é 10.

Pode não existir uma moda (caso não tenha valores repitidos).

### MEDIANA

 - Valor do meio.

 - Ordena-se os valores em ordem crescente.

 - Se a quantidade de elementos for par, você tira a média dos dois valores no centro e terá a mediana.

 - Se a quandidade de elementos for impar, a mediana será o elemento do meio. 


<img src="./image/line.png" alt="line" width="100%">
<h1 align="center"> MEDIDAS DE VARIABILIDADE</h1>
<br>

### VARIÂNCIA

Mostra a regularidade dos dados. Como os dados variam com relação a média.

Há duas fórmulas, variância do elemento e variância da população.


### DESVIO PADRÃO

Quanto maior o desvio, mais os dados estão distantes da média.

Se for igual a zero, significa que não existe variação nos dados. (Eles são iguais)

Calculo: Raiz quadrada da Variância.

 
### AMPLITUDE

Diferença entre o maior e menor valor.

### NÃO CENTRAIS: QUARTIS

São três quartis:

 - Q0: É o menor valor
 - Q1: 25% dos menores valores
 - Q2: 50% (equivale a mediana)
 - Q3: 75% dos maiores valores
 - Q4: É o maior valor


<h1 align="center"> NOTAÇÕES</h1>
<div align="center">
  <image src="./image/notacoes.png" alt="data_science" height="300" width="80%">
</div>
<br>
<div align="center">
  <image src="./image/variancia_desvio.png" alt="data_science" height="300" width="80%">
</div>



<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> PROBABILIDADE</h1>
<br>

É a chance de um evento acontecer.

<br>
<div align="center">
  <image src="./image/probabilidade_1.png" alt="data_science" height="300" width="80%">
</div>


### CONCEITOS

 - Experimento: O que está sendo estudado
 - Espaço Amostral: Todas as possibilidades de ocorrência do evento.
 - Evento: Resultado ocorrido

### Exemplo: 

 - Experimento: Jogar moeda.
 - Espaço Amostral: Cara ou Coroa.
 - Evento: "Deu coroa !".


### EVENTOS EXCLUDENTES

Eventos que não podem ocorrer ao mesmo tempo.
(Exemplo: Jogar um dado e ser 1 e par)

- Jogar um dado e dar 1 ou par: (1/6 + 3/6)  P = 4/6, P = 0,66

### EVENTOS NÃO EXCLUDENTES

Eventos que podem ocorrer ao mesmo tempo.
(Exemplo: Jogar um dado e ser 2 e par)

- Jogar um dado e dar 2 ou par: (1/6 + 3/6 - 1/6)  P = 3/6, P = 0,5

### EVENTOS DEPENDENTES

A ocorrência de um evento afeta o outro. Um tem que ocorrer para depois que o outro ocorra.
(Exemplo: Tirar duas cartas do baralho sem repor. Sendo que a segunda carta deve ser dama de paus)

Com 6 cartas na mão (A, 2, 3, 4, 5, 6), qual a probabilidade de primeiro evento tirar A e no segundo evento tirar 4.

P = (1/6 * 1/5) = 1/30 => 0,033


### EVENTOS INDEPENDENTES

A ocorrência de um evento não afeta o outro.
(Exemplo: jogar um dado. A probabilidade de dar 3 é sempre a mesma)

Qual a probabilidade de jogar dois dados, e dar 1 e 6: (dois eventos independentes)
REPOSTA:	P = (1/6 * 1/6) => P = 1/36 => 0,027

### Único evento

Calculo 

P = (Ocorrência Esperada) / (Número de Eventos Possíveis)


Exemplos:

- Jogar uma moeda e dar cara: P = 1/2, P = 0,5

- Jogar um dado e dar 6: P = 1/6, P = 0,16

- Jogar um dado e dar 1 ou 6: P = 2/6, P = 0,33

- Jogar um dado e dar 1, 2, 3, 4, 5 ou 6: P = 6/6, P = 1

- Jogar um dado e dar ímpar ou maior que 4: P = 4/6, P = 0,66


<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> PEQUENAS AMOSTRAS</h1>
<br>


 - Probabilidade de conclusões falsas
 - Não reprodutivo
 - Não comparável



<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> PASSEIO ALEATÓRIO</h1>
<br>

<br>
<div align="center">
  <image src="./image/passeio_aleatorio.png" alt="data_science" height="300" width="80%">
</div>


<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> ESTOCÁSTICO X DETERMINISTICO</h1>
<br>


### Processo Estocástico

Com um algoritmo. Dada uma mesma entrada, a saída pode variar.


### Processo Deterministico

Com um algoritmo. Dada uma mesma entrada, apresenta sempre a mesma saída.



<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> PROBABILIDADE EM JOGOS DE AZAR</h1>
<br>

 - São eventos independentes.

 - A probabilidade de sortear:
   -  1,2,3,4,5 e 6
   - Os seus números favoritos.
   - Ou qualquer outra combinação.

São as mesmas probabilidades !!!


<br>
<div align="center">
  <image src="./image/mega.png" alt="data_science" height="300" width="80%">
</div>


<br>
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center"> DISTRIBUIÇÃO</h1>
<br>


- Usado principalmente na teoria da probabilidade
- Mostra o comportamento de dados aleatórios
- Uma forma de analisar é por meio de um histograma

















