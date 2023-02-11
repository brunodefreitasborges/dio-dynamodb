# DIO DynamoDB

Este repositório contém exemplos de códigos para provisionar um banco de dados no DynamoDB, um serviço NoSQL da Amazon Web Services (AWS).

## Conteúdo
batchmusic.json: Arquivo JSON que contém uma lista de músicas para serem adicionadas ao banco de dados como lote (batch).
itemmusic.json: Arquivo JSON que contém um item de música para ser adicionado ao banco de dados individualmente.
keyconditions.json: Arquivo JSON que contém condições de pesquisa para serem utilizadas como filtros na consulta ao banco de dados.

## Estrutura do Banco de Dados
As músicas armazenadas no banco de dados são representadas como itens, cada item possui as seguintes informações:

- Artist: Nome do artista da música.
- SongTitle: Título da música.
- AlbumTitle: Título do álbum da música.
- SongYear: Ano de lançamento da música.
Todas as informações são armazenadas como tipo String (S).

## Como usar
1. Crie uma conta na AWS e configure o acesso ao DynamoDB.
2. Crie uma tabela no DynamoDB.
3. Importe os arquivos de exemplo em seu projeto.
4. Utilize os exemplos de código fornecidos para adicionar itens ao banco de dados e realizar consultas.
<br>
Observação: É recomendado que você leia a documentação da AWS sobre o DynamoDB antes de começar a utilizar este repositório.
