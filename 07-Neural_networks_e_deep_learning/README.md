<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1">Redes Neurais Artificiais e Deep Learning</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução](#1)
- [Redes Neurais Artificiais](#2)
- [Função de Ativação](#3)
- [Gradient Descent](#4)
- [Deep Learning](#5)
- [Referências Adicionais](#6)

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1">INTRODUÇÃO</h1>
<br>

- Machine Learning
  - Redes Neurais Artificiais
  - Deep Learning

**Machine Learning:**
É a capacidade do computador aprender através de técnicas de aprendizado.


**Redes Neurais Artificiais:**
É uma técnica de aprendizado.


**Deep Learning:**

- São redes neurais artificiais mais complexas.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2">REDES NEURAIS ARTIFICIAIS</h1>
<br>

- Simular as redes neurais biologicas no computador. Para que ele aprenda como tomar decisões.

- A base de uma rede neural artificial é o neurônio artificial.

- O **neurônio artificial** recebe entradas, podendo ter pesos nessas entradas.

-**BACKPROPAGATION:** O **peso** é ajustado caso a rede neural erre a previsão. (Ele para de ajustar ao acertar na previsão).

-**Epock:** É a passagem de todos os dados para ajustar o peso.

- O PESO pode ser ajustado a cada dado processado, ou a cada Epock.

- Dá para definir quando parar: X números de Epock, Parar quando atingir uma métrica de erro, etc.

<br>
<h3 align="center">PERCEPTRON</h3>
<div align="center">
  <image src="./image/rn_perceptron.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">EXEMPLO</h3>
<div align="center">
  <image src="./image/rn_perceptron_exemplo.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">MULTILAYER PERCEPTRON</h3>
<div align="center">
  <image src="./image/rn_multilayer_perceptron.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">BACKPROPAGATION</h3>
<div align="center">
  <image src="./image/rn_backpropagation.png" alt="Machine Learning" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3">FUNÇÃO DE ATIVAÇÃO</h1>
<br>

- "Define" se o sinal será propagado pela rede.

- Dá a RNA a não linearidade.


**_PRINCIPAIS:_**

- Threshold
  > Retorna zero ou um.
- Sigmoid
  > Utilizada mais na camada de estatistica.
- Relu
- Ranh

<br>
<h3 align="center">THRESHOLD</h3>
<div align="center">
  <image src="./image/funcao_ativacao_threshold.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">SIGMOID</h3>
<div align="center">
  <image src="./image/funcao_ativacao_sigmoid.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">HELU</h3>
<div align="center">
  <image src="./image/funcao_ativacao_helu.png" alt="Machine Learning" height="400" width="80%">
</div>


<br>
<h3 align="center">RANH</h3>
<div align="center">
  <image src="./image/funcao_ativacao_tanh.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">GERALMENTE USADO</h3>
<div align="center">
  <image src="./image/funcao_ativacao_uso_comum.png" alt="Machine Learning" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4">GRADIENT DESCENT</h1>
<br>

Ajuda o processo de encontrar os pesos de forma calculada em vez de buscar um peso aleatóriamente.

**Loss Function/ Cost Function:** É a diferença entre a previsão e o valor real.

- Requer que a função de custo seja convexa.

<br>
<h3 align="center">EXEMPLO PARA LOCALIZAR DIFERENÇA</h3>
<div align="center">
  <image src="./image/gd_rmse.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">COMO CALCULAR</h3>
<div align="center">
  <image src="./image/gd_loss_function.png" alt="Machine Learning" height="400" width="80%">
</div>



<br>
<h3>Ajustando pesos</h3>

- **Learning Rate:** Taxa de Aprendizado
- Como ajustar Peso ? Aumentar, diminuir ? Em quanto ?
- Lembrando que podemos ter muitos pesos para ajustar!

<br>
<h3 align="center">QUANTIDADE DE PESOS</h3>
<div align="center">
  <image src="./image/gd.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">GRADIENT DESCENT</h3>
<div align="center">
  <image src="./image/gd_1.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">STOCHASTIC GRADIENT DESCENT</h3>
<div align="center">
  <image src="./image/gd_2.png" alt="Machine Learning" height="400" width="80%">
</div>



<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5">DEEP LEARNING</h1>
<br>

**Redes neurais profundas: com muitas camadas**

**ARQUITETURAS DE REDES NEURAIS PROFUNDAS:**

- Redes Neurais Convolucionais
> Muito usado para reconhecimento de imagens
- Redes Neurais Recorrentes
- Self Organizing Maps
- Boltzmann Machines
  > Utilizada em sistemas de recomendação, reconhecimento de falas, usada em sistemas que carecem de dados.
- Autoencoders
  > São direcionados, recebe entrada e saída é semelhante a entrada. (Não supervisionado)
  > Usado em detecção de caracteristicas, sistema de recomendação.



<br>
<h3 align="center">REDES NEURAIS CONVOLUCIONAIS</h3>
<div align="center">
  <image src="./image/rn_convolucional.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">REDES NEURAIS RECORRENTES</h3>
<div align="center">
  <image src="./image/rn_recorrentes.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">SELF ORGANIZING MAPS</h3>
<div align="center">
  <image src="./image/rn_som.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">BOLTZMANN MACHINES</h3>
<div align="center">
  <image src="./image/rn_boltzmann.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h3 align="center">AUTOENCODERS</h3>
<div align="center">
  <image src="./image/rn_autoencoders.png" alt="Machine Learning" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6">REFERÊNCIAS ADICIONAIS</h1>


Livro: _Deep Learning (Adaptative Computation and Machine Learning series)_

Livro: _"http://neuralnetworkanddeeplearning.com/"_