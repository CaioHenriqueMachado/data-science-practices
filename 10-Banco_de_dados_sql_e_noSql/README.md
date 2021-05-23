<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1">Banco de dados e Linguagem SQL e NoSQL</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução SQL](#1)
- [DDL: Data definition Language](#2)
- [DQL: Data Query Language](#3)
- [Joins](#4)
- [DML: Data Manipulation Language](#5)
- [Referências Adicionais](#6)
- [Introdução NoSQL](#7)

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="1">INTRODUÇÃO</h1>
<br>

**- Linguagem declarativa:** Você não precisa explicar como deve ser feito, você apenas faz sua consulta e ele se vira pra te dar a respostas.

**- Modelo normalizado:** entidades relacionadas a partir de chaves primárias e estrangeiras.

**Primary Key:** É um atributo ou um conjunto de atributos cuja a propriedade é identificar de forma única um registro/linha.

**Foreign Key:** É nada mais que chave primária em outra tabela.

**Entidade:** São as tabelas do banco de dados.

**Atributo:** São as colunas da tabela.

Linguagem de consulta: 
- **DQL - Data Query Language**
  - Select


Definir estruturas de Dados:
- **DDL - Data Definition Language**
  - CREATE TABLE
  - CREATE INDEX
  - CREATE VIEW
  - ALTER TABLE
  - ALTER INDEX
  - DROP INDEX
  - DROP VIEW

Definir estruturas de Dados:
- **DML - Data Manipulation Language**
  - Delete;
  - Update;
  - Delete;



<br>
<h2 align="center" >RESUMO</h2>
<div align="center">
  <image src="./image/resumo1.png" alt="Machine Learning" height="400" width="100%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2">DATA DEFINITION LANGUAGE (DDL)</h1>
<br>




<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="3">DATA QUERY LANGUAGE (DQL)</h1>
<br>



`SELECT * FROM CLIENTES_TBL;`
> Selecionar todos os atributos da entidade Cliente.


`SELECT cliente,sexo,status FROM CLIENTES_TBL;`
> Selecionar os atributos cliente, sexo e status da entidade Cliente.


`SELECT cliente,sexo,status FROM CLIENTES_TBL;`
> Selecionar os atributos cliente, sexo e status da entidade Cliente.

`SELECT cliente, sexo, status FROM CLIENTES_TBL WHERE status = IN ('silver','plantinum')`
> Selecionar os atributos cliente, sexo e status da entidade Cliente onde tenha status 'silver' ou 'platinum'.

`SELECT cliente, sexo, status FROM CLIENTES_TBL WHERE cliente like '%Alb%'`
> Selecionar os atributos cliente, sexo e status da entidade Cliente onde o dado cliente tenha como subconjunto "Alb".


`SELECT * FROM VENDAS_TLB WHERE total > 6000`
> Selecionar todos os atributos da entidade Cliente onde o total seja maior que 6000.

`SELECT cliente FROM cliente order by cliente`
> Selecionar o atributo cliente da entidade Cliente com atributo cliente em ordem crescente.

`SELECT cliente, status FROM cliente order by cliente DESC`
> Selecionar o atributo cliente e status da entidade Cliente com atributo cliente em ordem decrescente.

`SELECT cliente, status FROM cliente order by cliente desc, status`
> Selecionar o atributo cliente, status da entidade Cliente com atributo cliente e depois status em ordem crescente.

`SELECT * FROM VENDAS_TLB WHERE total  between 6000 and 8000`
> Selecionar todos os atributos da entidade Cliente onde o atributo total esteja entre 6000 e 8000.

`SELECT * FROM VENDAS_TLB  limit 10`
> Selecionar todos os atributos da entidade Cliente limitando os registros em 10.

`SELECT distinct status from clientes`
> Selecionar o atributo Status da entidade Clientes  onde sejam distintos (Vai trazer as opções de status).

`Select count(*) from vendas`
> Irá contar a quantidade de registros na tabelas vendas.

`Select count(*) from vendas WHERE total > 6000`
> Irá contar valores com total maior que 6000.

**AGRUPANDO:**
`select idvendedor, count(idvendedor) from vendas GROUP BY idvendedor`
>  Traz o id do vendedor, contando quantas vezes cada um apareceu.

**AGRUPANDO COM HAVING:**

`select idvendedor, count(idvendedor) from vendas GROUP BY idvendedor HAVING count(idvendedor) > 40`
>  Traz o id do vendedor, contando quantas vezes cada um apareceu. Sendo essa contagem maior que 40 vendas.

**AGREGAÇÃO:**

**- MIN():** Menor valor
**- MAX():** Maior valor
**- AVG():** Média entre valores
**- SUM():** Soma dos valores


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="4">JOINS</h1>
<br>

Joins: Unir dados Através de PK e FK.

<br>
<h2 align="center" >TIPOS</h2>
<div align="center">
  <image src="./image/joins.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h2 align="center" >INNER JOIN</h2>
<div align="center">
  <image src="./image/innerjoin.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h2 align="center" >LEFT JOIN</h2>
<div align="center">
  <image src="./image/leftjoin.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h2 align="center" >RIGHT JOIN</h2>
<div align="center">
  <image src="./image/rightjoin.png" alt="Machine Learning" height="400" width="80%">
</div>

<br>
<h2 align="center" >FULL JOIN</h2>
<div align="center">
  <image src="./image/fulljoin.png" alt="Machine Learning" height="400" width="80%">
</div>

<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="5">DML: DATA MANIPULATION LANGUAGE</h1>
<br>

**INSERT:**

`INSERT INTO clientes(idcliente, cliente, estado, sexo, status) VALUES (251, 'Fernando Amaral', 'RS', 'M', 'Silver');`
> Insere um dado na tabela clientes.


**UPDATE:**

`UPDATE clientes SET estado='MS', status='Platinum' WHERE idcliente=251;`
> Atualiza um dado na tabela clientes.


**DELETE:**

`DELETE FROM clients WHERE idcliente=251;`
> Deleta um dado na tabela clientes.


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="6">REFERÊNCIAS ADICIONAIS</h1>
<br>

Livro: _SQL Practice Problems_


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="7">INTRODUÇÃO NOSQL</h1>
<br>

O banco de dados NoSql veio como uma alternativa de se trabalhar com dados,
existem casos e casos no qual cada tipo de banco tem um melhor desempenho.


<div align="center">
  <image src="./image/NoSQL.png" alt="NoSql" height="300" width="80%">
</div>

Os produtos buscam resolver problemas específicos de certas aplicações, que eram
mais difíceis de resolver no modelo relacional:
- Processamento eficiente
- Paralelismo
- Escalabilidade
- Custo

<div align="center">
  <image src="./image/ForTypes.png" alt="types" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/KVP.png" alt="KVP" height="350" width="80%">
</div>


<br>
<div align="center">
  <image src="./image/ColOrdenadas.png" alt="Colunas ordenadas" height="350" width="80%">
</div>


<br>
<div align="center">
  <image src="./image/BD_grafos.png" alt="BD grafos" height="300" width="80%">
</div>

<br>
<div align="center">
  <image src="./image/BD_documents.png" alt="BD documents" height="350" width="80%">
</div>


**EXEMPLOS DE APLICAÇÕES:**

- Sessão de Usuário em Aplicações Web
- Conteúdo como e-books, artigos e documentos em geral
- Agregação ou Repositório Central de Dados
- Plataformas de Anúncios Direcionados
- EHR (Eletronic Healthcare Records)
- Analise de Serie Temporal
- Dados do crachá sociométrico


<br>
<div align="center">
  <image src="./image/ranking.png" alt="ranking" height="350" width="60%">
</div>

Ranking: https://db-engines.com/en/ranking
