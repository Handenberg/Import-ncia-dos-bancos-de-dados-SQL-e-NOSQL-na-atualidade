# Import-ncia-dos-bancos-de-dados-SQL-e-NOSQL-na-atualidade
Importância dos bancos de dados SQL e NOSQL na atualidade


Os bancos de dadostem suma importância dentro de uma oragnização ou empresa. Ele organiza e armazena as informações sobre um domínio específico. De forma mais simples, é o agrupamento de dados que tratam do mesmo assunto e que precisam de segurança. Facilitando a busca, filtragem e minração de dados em grandes volumes, facilitando a busca por dados especificos.
  
O que é NoSQL?
NoSQL é a denominação de bancos de dados não tabulares, que armazenam dados em esquemas diferentes das tabelas relacionais, como documentos, grafos, pares chave-valor ou colunas.

Bancos de dados nao relacional:

NoSQL: bancos de dados não tabulares
A definição acima é sucinta e correta. Mas vamos combinar: mais “complica” do que “explica” NoSQL, não é? Para entender esta tecnologia, primeiro precisamos conhecer bancos de dados relacionais e SQL.

Bancos de dados relacionais
Imagem mostra o terminal de um computador, com uma tabela que contém dados de funcionários de uma empresa, como nome, cargo e horas trabalhadas por dia.
Dados de funcionários organizados em linhas e colunas no banco de dados relacional MySQL. Fonte: w3cschoool.com
Banco de dados relacional é um software que armazena informações em tabelas com linhas e colunas, como planilhas do Excel.

Cada linha é um registro, como dados de um cliente. Já as colunas descrevem atributos de cada cliente, como nome, endereço e cartão de crédito, por exemplo. 

Um banco de dados relacional pode ter diversas tabelas, as quais se relacionam entre si. Podemos ter uma tabela “Compras”. Como cada compra é feita por um cliente, a tabela “Compras” se relacionará com a tabela “Clientes”, para sabermos qual compra foi feita por qual cliente.

São exemplos de bancos de dados relacionais: SQLite, MySQL, MariaDB, Microsoft SQL Server, PostgreSQL, Oracle, entre outros.

SQL
SQL é a sigla para Structured Query Language (“Linguagem de Consulta Estruturada”, em tradução livre). É a linguagem padrão para operações em bancos de dados relacionais. Por isso, tornou-se comum chamá-los de “bancos de dados SQL”.

Por meio de SQL, é possível criar (create), ler (read), alterar (update) e excluir (delete) dados — o famoso “CRUD” — em bancos relacionais.

Bancos de dados NoSQL
Agora, NoSQL fica fácil! Bancos de dados desse tipo são softwares que armazenam dados de forma diferente dos bancos de dados relacionais. 

Não usam tabelas, mas outros esquemas, que veremos a seguir. Também não adotam a linguagem SQL, mas linguagens próprias. Algumas, porém, são parecidas com SQL tanto na sintaxe quanto nos fundamentos.

Uma curiosidade: NoSQL não significa “não SQL”, mas “not only SQL” (“não somente SQL”, em tradução livre).

Vantagens de NoSQL
NoSQL surgiu para lidar com big data, conjuntos de dados gigantescos e complexos surgidos com a web, após os anos 2000. 

Como bancos relacionais podem ser ineficientes para grandes quantidades de dados, principalmente dados não estruturados — que não podem ser dispostos em linhas e colunas, como o conteúdo de textos, áudios e vídeos —, NoSQL surgiu como solução.

Isso não quer dizer que bancos de dados NoSQL sejam melhores que bancos SQL, apenas que se destinam a finalidades diferentes.

Tipos de bancos de dados NoSQL
Bancos de dados NoSQL podem ter os seguintes esquemas (formas de organizar os dados):

1. Documentos
Imagem mostra diferentes textos em inglês, contendo campos com nome, sobrenome, e-mail, entre outros, agrupados por por chaves e separados por vírgula.
Forma como dados são armazenados em um banco de dados NoSQL baseado em documentos. Fonte: digitalocean.com
Neste esquema, os dados são armazenados em “textos”. Por exemplo, dados de clientes estarão organizados de forma sequencial, como uma folha de formulário.

Tais textos podem ser altamente estruturados (ter campos bem definidos e comuns a todos os documentos, como CPF e nome de cada cliente) ou podem ser semiestruturados ou não estruturados (quando não há padronização dos campos).

MongoDB, Elasticsearch e CouchDB são exemplos populares de bancos NoSQL baseados em documentos.

2. Chave-valor
Imagem mostra um desenho com retângulos à esquerda, que indicam chaves, com números sequenciais dentro delas, e retângulos à direita com informações diversas, como nome e idade de uma pessoa ou o número “42”.
Forma como dados são armazenados em um banco de dados NoSQL baseado em pares chave-valor. Fonte: dev.to
Bancos NoSQL do tipo chave-valor são como “dicionários”. Eles permitem cadastrar uma chave (um registro único e inconfundível) e associar quaisquer valores (informações) a essas chaves.

Isso permite muita flexibilidade e rapidez nas consultas. Podemos associar muitos campos de dados diferentes a uma única chave, bastando acessar tal chave para recuperá-los.

Redis, Apache Ignite e Memcached são exemplos populares de bancos NoSQL que usam o esquema chave-valor.

3. Grafo
Imagem mostra um desenho com bonecos que indicam pessoas e bolas que indicam a preferência por filmes ou livros; setas entre um boneco e outro ou entre um boneco e uma bola indicam quem é amigo de quem ou quem gosta de quais atividades.
Forma como dados são armazenados em um banco de dados NoSQL baseado em grafos. Fonte: docs.aws.amazon.com
Um grafo é uma coleção de nós ligados por arestas. Em bancos de dados do tipo, os dados são os nós e os relacionamentos entre eles, as arestas. Neles, podemos relacionar facilmente clientes aos produtos que mais compram, por exemplo. 

Tanto que são muito usados para mecanismos de recomendação (indicar um produto que o cliente pode gostar, com base em suas preferências) e para detecção de fraude (comparar se o número de cartão de crédito usado por ele é sempre o mesmo).

São exemplos populares de bancos NoSQL baseados em grafos: Neo4J, OrientDB, AllegroGraph, entre outros.

4. Colunas
Imagem mostra uma tabela com linhas e colunas.
Forma como dados são armazenados em um banco de dados NoSQL baseado em colunas. Fonte: scylladb.com
Questões técnicas são os maiores trunfos de bancos de dados NoSQL baseados em colunas. Eles reduzem a necessidade de leitura em disco durante consultas aos dados e utilizam menos memória para exibir as informações.

São usados principalmente em aplicativos analíticos, que precisam realizar muito cálculos com extrema rapidez, e em data warehouses (“armazéns de dados”), grandes repositórios de dados usados por empresas.

Amazon DynamoDB, Bigtable, Cassandra, Hbase, Google Cloud Datastore, entre outros, são exemplos populares de bancos NoSQL colunares.

Como usar bancos de dados NoSQL?
Cada software de banco de dados NoSQL tem suas características. Por isso, é necessário conhecer aquele que melhor se adequa às suas necessidades ou às de sua empresa para aprofundar-se neles.

O interessante é que muitos já possuem ótima documentação e permitem usar a linguagem de programação de sua preferência para operá-los.

MongoDB, um banco NoSQL baseado em documentos, por exemplo, é muito utilizado por startups, por meio da linguagem Javascript e da tecnologia Node.js, para publicar sites e sistemas web escaláveis rapidamente. No curso de Programação Back-End da Awari, você tem uma introdução ao assunto.

Já bancos de dados colunares, como Hbase, Cassandra e DynamoDB, são comuns no dia a dia da Engenharia de Dados ou até, em alguns casos, na etapa de obtenção de dados da Ciência de Dados.
