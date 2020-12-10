<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1">Machine Learning</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução](#1)
- [Aplicações](#2)
- [Conceitos](#3)
- [Tarefas](#4)
- [Classificação](#5)
- [Classificação II - Matriz de confusão](#6)
- [Classificação III - Custo](#7)
- [Codificação de Categorias](#8)
- [Agrupamentos](#9)
- [Regra de associação](#10)
<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1"> INTRODUÇÃO</h1>
<br>

**_MACHINE LEARNING:O PROCESSO DO COMPUTADOR APRENDER USANDO ALGORITMOS DE INTELIGÊNCIA ARTIFICIAL. TEM COMO OBJETIVO ENSINAR O COMPUTADOR;_**

- Processo de adquirir conhecimento.
- **Porque processo ?**
  - Porque é contínuo e evolutivo.
- **Como ocorre ?**
  - Através da Relação com o Ambiente.

<br>
<h3>E uma máquina ?</h3>
- Interagem com o ambiente - Através de dados.
- Dados são usados para a máquina aprender.
- O Aprendizado pode ser persistido através de um "modelo".
- O aprendizado deve melhorar.
- O aprendizado pode ser medido.

<br>
<h3>Como uma máquina funciona ?</h3>
1. Se passa os dados para o computador.
2. Ele processa de acordo com o algoritmo.
3. Você testa com um novo dado. 
4. Ele vai processar o dado no modelo, e vai tentar prever.
5. A previsão tem uma porcentagem de está certa.


<br>
<h3>Aprendizado</h3>

- **Contínuo:**
  - Com dados melhores, o computador pode melhorar seu modelo, ou seja, aprender mais sobre as condições do tempo.

- **Mensurável:** 
  - Podemos medir o quanto o computador aprendeu.
  > Por exemplo, em 100 previsões, acertou 83 e errou 17.

<br>
<h3>Até aonde o computador pode aprender ?</h3>

- **Limites físicos:** memória, processamento, armazenamento.

- **Limites lógicos:** algoritmo utilizado.

- **Limites de ambiente:** dados.
> Existem dados que interferem no resultado mas você não tem controle sobre eles e não é possível medi-los.

  - Dados que temos:
    - Temperatura, umidade, aparência, vento.
  - O que causa a chuva ?
    - Temperatura, umidade, ventos.
    - Posição e deslocamento das massas de ar.

<br>
<h3>MINERAÇÃO DE DADOS</h3>

- São processos de exlorar e analisar grandes volumes de dados em busca de padrões, previsões, erros, associações.



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2"> APLICAÇÕES</h1>
<br>

- **Marketing:**
  - Quais clientes irão responder a quais promoções ?
  - Qual a combinação de produtos que mais vende ?
  - Quais clientes irão comprar mesmo sem ofertas ?
  - Identificação de consumidores Alfa.

- **Educação:**
  - Quais alunos irão abandonar o curso e por quê?
  - Quais alunos são mais fiéis ?
  - Quais cursos serão mais rentaveis ?
  - quais cursos, com quais características, atraem mais alunos ?


- **Recursos Humanos:**
  - Qual o perfil de talentos é mais adequado para quais vagas ?
  - Qual o perfil de funcionários que abandonarão o emprego e quando ?
  - Quais ações são efetivas na produtividade ?

- **Finanças/ Contabilidade:**
  - Prever a performance financeira da organização.
  - Mitigação de riscos futuros.
  - Fraude




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3"> CONCEITOS</h1>
<br>



<br>
<h3 align="center">ESTRUTURA DE DADOS</h3>
<div align="center">
  <image src="./image/machine_learning_estrutura_dados.png" alt="Machine Learning" height="400" width="80%">
</div>


<br>
<h3 align="center">TIPOS DE DADOS</h3>
<div align="center">
  <image src="./image/machine_learning_tipo_dados.png" alt="Machine Learning" height="400" width="80%">
</div>


- **Nominais:** Dados em texto.
- **Numéricos:** Dados em números.


<br>

<br>
<h3>TAREFAS</h3>

Machine learning está dividido em 4 tarefas:

- Classificação: Previsão de uma informação **_CATEGÓRICA_**
> Ex: SIM ou NÃO
> Ex: Espécie de planta: se é A, B ou C
> Ex: Identificar um animal através de imagem.

- Regressão: Previsão de uma informação **_NUMÉRICA_**
> Ex: Prever quantas cilindradas tem o motor.
> Ex: Prever quanto vai gastar em campanha de marketing.

- Agrupamentos: (Não é previsão) Unir elementos com características semelhantes.
>  Agrupamentos são tarefas não superviondas. Não contém classes.
> Ex: Separar os clientes em grupos baseado em características.

- Regras de Associação: Usado para buscar uma semelhança em diferentes elementos.
> Ex: Quem comprou o produto A, também comprou o produto B.

<br>
<h3 align="center">TESTE</h3>
<div align="center">
  <image src="./image/machine_learning_tipo_dados_teste.png" alt="Machine Learning" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4"> TAREFAS</h1>
<br>



<h3 align="center"> CLASSIFICAÇÃO</h3>

- Previsão de uma informação **_CATEGÓRICA_**

<br>
<div align="center">
  <image src="./image/machine_learning_cassificacao.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_descricao.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center"> REGRESSÃO</h3>
<div align="center">
  <image src="./image/machine_learning_descricao_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">AGRUPAMENTOS</h3>
<div align="center">
  <image src="./image/machine_learning_descricao_2.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">REGRA DE ASSOCIAÇÃO</h3>
<div align="center">
  <image src="./image/machine_learning_descricao_3.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">EXEMPLO</h3>
<div align="center">
  <image src="./image/machine_learning_descricao_4.png" alt="Machine Learning" height="400" width="80%">
</div>



<h3 align="center">SUPERVISIONADAS X NÃO SUPERVISIONADA</h3>

- **SUPERVISIONADA:** Quando você tem uma classe, algo que você quer prever. Nela você pode fazer a comparação da previsão com o resultado, pois existe uma classe.

- **NÃO SUPERVISIONADA:**  No agrupamento por exemplo, nele você não tem uma classe. Sendo assim não tem como saber se está correto ou errado os grupos criados

<br>
<h3 align="center">TAREFA NÃO É ALGORITMO</h3>

<div align="center">
  <image src="./image/machine_learning_tarefa_algoritmo.png" alt="Machine Learning" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5"> CLASSIFICAÇÃO</h1>
<br>

- Queremos descobrir ou descrever a classe de um fato.

- Normalmente a classe em uma relação esta representada em um atributo especial, posicionado como último atributo da relação.

<br>
<h3 align="center">EXEMPLOS DE CLASSIFICAÇÃO</h3>

<div align="center">
  <image src="./image/machine_learning_iris.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_exemplos.png" alt="Machine Learning" height="400" width="80%">
</div>



<br>
<h3 align="center">AVALIAÇÃO</h3>
<h4 align="center">Não é tão usado pois pode ter super ajuste</h4>
<div align="center">
  <image src="./image/machine_learning_avaliacao_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_avaliacao_2.png" alt="Machine Learning" height="400" width="80%">
</div>


<br>
<div align="center">
  <image src="./image/machine_learning_avaliacao_3.png" alt="Machine Learning" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6"> CLASSIFICAÇÃO: MATRIZ DE CONFUSÃO</h1>

<br>
<div align="center">
  <image src="./image/machine_learning_matriz_confusao_exemplo.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_matriz_confusao_exemplo_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>

<h3>SUPER AJUSTE X SUB AJUSTE</h3>

**CAUSAS:**
- Dados não representativos.
- Dados não significativos(poucos)
- Forma de treinamento.
- Classe rara.
> Ex: Transações de Fraude: a fraude é uma classe rara. O modelo pode ter dificuldade de aprender essa classe.
**SOLUÇÃO: Estratificação**
- Modelo incorreto.

<br>
<div align="center">
  <image src="./image/machine_learning_sub_super.png" alt="Machine Learning" height="400" width="80%">
</div>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6"> CLASSIFICAÇÃO III: CUSTO</h1>

- Ajustar diferentes variaveis do modelo pode trazer uma diferença significativa no resultado.

<br>
<div align="center">
  <image src="./image/machine_learning_custo.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_melhorar_modelo.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_metrica.png" alt="Machine Learning" height="400" width="80%">
</div>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6"> CLASSIFICAÇÃO IV: TIPOS DE ALGORITMOS</h1>

- Árvores de Decisão.
- Regras.
- Naive Bayes.
- Redes Bayesianas.
- Redes Neurais Artificiais e aprendizado Profundo.
- Máquina de Vetor de Suporte.
- Métodos de Grupos.
- Aprendizado baseado em instâncias.

<br>
<div align="center">
  <image src="./image/machine_learning_arvore_decisao.png" alt="Machine Learning" height="400" width="80%">
</div>

<h3>NAIVE BAYES</h3>

- Baseado na teoria das probabilidades e que supõe que os atributos vão influenciar a classe de forma independente.


<br>
<h3>REDE BAYESIANAS</h3>
<div align="center">
  <image src="./image/machine_learning_rede_bayesiana.png" alt="Machine Learning" height="400" width="80%">
</div>



<br>
<h3>MÁQUINA DE VETOR DE SUPORTE</h3>
<div align="center">
  <image src="./image/machine_learning_svm.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>


<h3>MÉTODOS DE GRUPOS</h3>

São grupos de classificadores.


- Florestas Aleatórias.
- Boosting.


<h3>APRENDIZADO BASEADO EM INSTÂNCIA</h3>

- Ele busca uma semelhança entre os dados históricos e o dado que você quer classificar.

<br>
<div align="center">
  <image src="./image/machine_learning_instancia.png" alt="Machine Learning" height="400" width="80%">
</div>



<br>
<h3>SELEÇÃO DE ATRIBUTOS</h3>
<div align="center">
  <image src="./image/machine_learning_atributos.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_atributos_1.png" alt="Machine Learning" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="7"> CODIFICAÇÃO DE CATEGORIAS</h1>

- Algoritmos entendem números
- **_Categorial encoding_** é o processo de transformar categorias em números
- **Duas formas:**
  - Label encoding
  - One-hot encoding


<br>
<h3>LABEL ENCODING</h3>
<div align="center">
  <image src="./image/machine_learning_label_encoding.png" alt="Machine Learning" height="400" width="80%">
</div>

**PROSSÍVEL PROBLEMA:**

- Problema: O algoritmo pode correlacionar os dados como uma ordem de grandeza !  
> EX: tem ordem de grandeza: prata, ouro, diamante.
> Ex: não tem ordem de grandeza: casado, solteiro, divorciado.


<br>
<h3>ONE HOT ENCODING</h3>
<div align="center">
  <image src="./image/machine_learning_one_hot_encoding.png" alt="Machine Learning" height="400" width="80%">
</div>

**PROSSÍVEL PROBLEMA:**

- Problema: Pode acabar tendo muitos atributos.
- DUMMY VARIABLE TRAP


<br>
<h3>DUMMY VARIABLE TRAP</h3>
<div align="center">
  <image src="./image/machine_learning_dummy.png" alt="Machine Learning" height="400" width="80%">
</div>


<br>
<div align="center">
  <image src="./image/machine_learning_usar.png" alt="Machine Learning" height="400" width="80%">
</div>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="8"> DIMENSIONAMENTO DE CARACTERÍSTICAS</h1>

- Processo de transformação de dados númericos.
- Variáveis em escalas diferentes.
  - Contribuem de forma desbalanceada para o modelo.
  > Ex: Salário e Altura.

- **_Gradient Descent_** converge mais rapidamente para o mínimo local.

<br>

**TÉCNICAS**

- Padronização (Z-score)
- Normalização (Min-Max)


<br>
<h3 align="center">PADRONIZAÇÃO (Z-score)</h3>
<div align="center">
  <image src="./image/machine_learning_padronizacao.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">NORMALIZAÇÃO (Min-Max)</h3>
<div align="center">
  <image src="./image/machine_learning_normalizacao.png" alt="Machine Learning" height="400" width="80%">
</div>



<br>
<h3 align="center">EXEMPLO</h3>
<div align="center">
  <image src="./image/machine_learning_normalizacao_exemplo.png" alt="Machine Learning" height="400" width="80%">
</div>


<h3>OBSERVAÇÕES</h3>

- Não vai necessáriamente melhorar seu modelo !
- Arvores de decisão não precisam de nenhum tipo.
- Não se aplica a atributos categóricos transformados.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="9"> AGRUPAMENTOS</h1>

**CONCEITOS:**

- Tarefas não supervisionadas
- Não existem classes
- Objetivo é criar grupos a partir de atributos(características) das instâncias.


<br>
<h3 align="center">TIPOS</h3>
<div align="center">
  <image src="./image/machine_learning_agrupamento_tipos_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_agrupamento_tipos_2.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_agrupamento_tipos_3.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">ALGORITMOS DE AGRUPAMENTOS</h3>
<div align="center">
  <image src="./image/machine_learning_agrupamento_algoritmos_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/machine_learning_agrupamento_algoritmos_2.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">DBSCAN</h3>
<div align="center">
  <image src="./image/machine_learning_agrupamento_algoritmos_3.png" alt="Machine Learning" height="400" width="80%">
</div>

- DBSCAN Não é bom em grupos cujas densidades variam muito.


<br>
<h3 align="center">HIERÁRQUICO</h3>
<div align="center">
  <image src="./image/machine_learning_agrupamento_hierarquico.png" alt="Machine Learning" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="10"> REGRA DE ASSOCIAÇÃO</h1>

**DEFINIÇÃO**

Busca a relação entre itens.

> Ex: Pessoas que compraram o produto X, também compraram o produto Y.

CONCEITOS

**A => B**

- SUPORTE: Número de transações que contém todos os itens da transação.
- CONFIANÇA: Indica a proporção de vezes que, em uma transação contendo o elemento A, também tem B.
- LIFT: O quanto aumenta a frequência de B com a ocorrência de A.


**SUPORTE**

Não adianta os produtos aparecerem com frequência juntos, se raramente são comprados.


**CONFIANÇA**

Não adianta um produto ser muito comprado, se dificilmente eles aparecem juntos.


<br>
<h3 align="center">EXEMPLO 1</h3>
<div align="center">
  <image src="./image/machine_learning_regra_associacao.png" alt="Machine Learning" height="400" width="100%">
</div>

<br>
<h3 align="center">EXEMPLO 2</h3>
<div align="center">
  <image src="./image/machine_learning_regra_associacao_2.png" alt="Machine Learning" height="400" width="100%">
</div>

<br>
<h3 align="center">EXEMPLO 3</h3>
<div align="center">
  <image src="./image/machine_learning_regra_associacao_3.png" alt="Machine Learning" height="400" width="100%">
</div>


<br>
<h3 align="center">ALGORITMOS ASSOCIADORES</h3>
<div align="center">
  <image src="./image/machine_learning_algoritmo_associacao.png" alt="Machine Learning" height="400" width="100%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="11"> REFERÊNCIAS ADICIONAIS</h1>


Livro: _Introduction to Data Mining_

Livro: _Data mining: Practical Machine Learning Tools and Techniques_