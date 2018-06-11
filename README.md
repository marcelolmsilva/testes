# testes
Projeto de ABCTestes
Arquivo compactado ABCTestes.zip

A solução ABCTestes é composto de dois projetos:
O Site de Front-end ABCTestes tanto para uso dos clientes como dos vendedores
e a API de Back-end ABCTesteAPI utilizada pelo Front-end para executar o intercâmbio com o banco de dados.
Para criar o banco de dados no SQLServer segue o script Script-criacao-banco-dados.sql
Será criada o banco de dados ABCTestes e a tabela Clientes. Antes verificar no script se o caminho para
criação do banco é o mesmo 'C:\Program Files\Microsoft SQL Server\MSSQL12.SQLEXPRESS\MSSQL\DATA\ABCTestes.mdf'

Após a criação do banco de dados, abra a solução ABCTestes no Visual Studio e 
no projeto ABCTesteAPI procure no web.config a string de conexão connectionStrings ClientesContext com o banco de dados e altere caso seja
necessário para uso no seu ambiente, e caso seja necessário, adicione o User ID e Password para permitir conexão.
Após isso, compile os projetos e execute, se tudo ocorrer bem deverá executar sem problemas.


Atenciosamente,
Marcelo
