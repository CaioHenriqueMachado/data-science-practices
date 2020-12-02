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












