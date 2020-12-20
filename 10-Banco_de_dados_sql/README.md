<h1 align="center"> DATA SCIENCE</h1>

<h2 align="center" id="0_1">Banco de dados e Linguagem SQL</h2>

<img src="./image/line.png" alt="line" width="100%">
<br>

### SUMÁRIO

- [Introdução](#1)
- [DDL: Data definition Language](#2)
- [Select Básico](#3)
- [Joins](#4)
- [DML: Data Manipulation Language](#5)
- [Referências Adicionais](#6)


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
  <image src="./image/resumo1.png" alt="Machine Learning" height="400" width="80%">
</div>


<img src="./image/line.png" alt="line" width="100%">
<br>
<h1 align="center" id="2">DATA DEFINITION LANGUAGE (DDL)</h1>
<br>


`SELECT * FROM CLIENTES_TBL;`
> Selecionar todos os atibutos da entidade Cliente


`SELECT clientes,sexo,status FROM CLIENTES_TBL;`
> Selecionar os atibutos sexo, cliente e status da entidade Cliente
