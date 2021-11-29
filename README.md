<center>
# O NOVO PARADIGMA DE BANCO DE DADOS: 
# Uma análise prática sobre o banco de dados NewSQL
</center>

O New Structured Query Language (NewSQL) é um paradigma diferente dos bancos de dados atuais seja ele Not Only Structured Query Language (NoSQL) ou Structured Query Language (SQL). Esse tipo de banco de dados está preparado com o melhor dos dois mundos sendo capaz de juntar as propriedades Atomicidade, Consistência, Isolamento e Durabilidade (ACID) do banco de dados SQL (Structured Query Language) com as propriedades de escalabilidade e velocidade do banco de dados NoSQL (Not Only Structured Query Language). 
Empresas de transações online como bancos e mercado financeiro estão a utilizar esse tipo de banco de dados para a gestão dos seus respectivos softwares, esse paradigma ainda é novo, mas mesmo assim conta com diversas documentações de como utilizá-lo e também já existem Sistemas Gerenciadores de Banco de Dados (SGBD) prontos para usar esse tipo de paradigma.

Esse artigo tem o objetivo de mostrar na prática como utilizar esse paradigma, desde a instalação de um Sistemas Gerenciadores de Banco de Dados que fornece suporte a esse banco de dados até a utilização das suas funcionalidades e um teste de benchmarking que foi realizado em uma máquina Linux utilizando o banco de dados VoltDB onde foi inserido 500 mil de registros em uma tabela usando uma procedure e uma aplicação em JAVA,
como complemento foi efetuado um novo teste de benchmarking em um banco de dados MySQL utilizando a linguagem de programação PHP para a parte da aplicação onde foi obtido resultados para realizar uma comparação entre os dois banco de dados.
