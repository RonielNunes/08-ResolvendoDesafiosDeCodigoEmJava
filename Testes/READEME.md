# **_Quiz - Conhecendo o ambiente e resolvendo um desafio_**

### Quais são os principais meios de pedir ajuda para realizar os desafios de código?

Comunidade de Devs da DIO online e fórum do bootcamp referente ao desafio de código realizado.

### Qual a importância da utilização do parseInt?
O parseInt é utilizado para armazenar nas variáveis “a” e “b” o dado como inteiro, pois ao contrário ele seria lido como uma String.


### Qual a finalidade da utilização do BufferedReader e StringTokenizer na questão resolvida?

O BufferedReader criará um buffer (área para o armazenamento temporário de dados) a partir da entrada padrão do Java (System.in). O StringTokenizer, por sua vez, é uma abstração que facilitará a leitura dos dados de entrada no formato em questão (separado por espaços).

### De que forma os desafios de código exercitam o pensamento computacional?

Exigindo a criação de uma solução algorítmica implementada com um conjunto de entradas e saídas esperadas.

### Qual a finalidade dos testes abertos e dos testes fechados?
Os testes fechados permitem a validação do seu código em casos não previstos, verificando se ele atende a várias condições, assim como o mundo real. Já os testes abertos validam se o código funciona em situações minimamente previstas e permitem a verificação e correção dos erros antes da submissão envolvendo os testes fechados.

## _**Parte2**_

## Dado o código a seguir:

String sql = "...";
PreparedStatement stmt = conn.prepareStatement(sql);
stmt.setString(1 , aluno.getNome());
stmt.setInt(2, aluno.getIdade());
stmt.setString(3 , aluno.getEstado());

Para o objeto stmt ser corretamente executado, a reticências (...) da variável “sql” deve ser substituída por:

INSERT INTO aluno(nome, idade, estado) VALUES(?, ?, ?)

## A anotação ________ indica a aplicação que os OBJETOS da classe especificada serão persistidos no banco de dados. Também podem ser utilizadas outras anotações para auxiliar no mapeamento da classe, tais como: @id, @column, @table, @OneToMany e @ManyToOne.

@Entity

## Quais são os parâmetros passados a um dos métodos getConnection da classe DriverManager para iniciar uma conexão?

url, user e database

## Um(a) _______ armazena dados de forma estruturada, tornando o acesso e atualização dos dados mais rápido, pois aumenta a eficiência computacional (menor “gasto“ de memória, processamento e tempo).

Banco de Dados


## A alternativa INCORRETA é:

A classe Connection usa o método executeQuery para execução de uma consulta.

## A interface _______  é utilizada para gerenciar o ciclo de vida das entidades. Os principais utilizados são find, persist e remove.

EntityManager

## O _______ é uma linguagem de consulta independente orientada a objetos definida pelo JPA. Existe uma alternativa a essa linguagem a partir do JPA 2.0 chamada _______, que é muito fácil para construir consultas dinâmicas, pois é possível detectar erros no momento de compilação.

Java Persistence Query Language (JPQL) - JPA Criteria API

## Qual classe ou interface NÃO pertence ao pacote "java.sql"?

MySQL

## Uma aplicação JAVA que esteja utilizando as especificações do JPA terão que criar o arquivo _________ para configurar os parâmetros de conexão com o banco de dados.

persistence.xml


## Foi proposto um modelo de mapeamento chamado ______ para representar tabelas de um banco de dados relacional através de classes Java. Neste modelo as tabelas, colunas e tuplas do banco de dados são representadas como classes, atributos e objeto respectivamente.

Mapeamento Objeto Relacional (ORM)
