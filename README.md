# projeto-banco-de-dados
## Integrantes do Grupo
Henry Araujo       22.121.129-5


Victor Gnidarxic   22.121.088-3


Luiz Doretto       22.221.023-9

## Banco escolhido
  MongoDB - Document Storage

## 

## Método de normalização das tabelas
  Fizemos a normalização das tabelas utilizando indexadores e os próprios ID's gerados pelo MongoDB, para substituir os ID's que já tinhámos devido a base de dados do livro para os do MongoDB, fizemos um PROCV no Excel com os Dados da Base x ID's que o MongoDB gerou.

## Criação de tabelas ou como chamado no MongoDB "Colletions"
  Para criar as tabelas utilizamos os arquivos Json que estão presentes aqui no diretório. No MongoDB a criação é feita na própria aplicação, clicando no símbolo "+" do lado do nome da sua Database, após criar a "Colletion" basta importar o arquivo Json respectivo que a tabela será populada.
  
  ⚠ É extremamente importante que nas tabelas o tipo de cada coluna esteja de acordo com a DLL da base de dados do livro, pois o tipo de cada campo pode gerar o resultado errado de uma query, devido à comparação que o MongoDB faz com relação aos tipos.

## Execução das Queries
  Cada query no MongoDB deve ser executada dentro de uma Colletion específica, na aba de Aggregations e é necessário mudar o tipo de execução para "TEXT" ao invés de "STAGES"

  Questão 1 - Executar na Colletion Student

  
  Questão 2 - Executar na Colletion Instructor


  Questão 3 - Executar na Colletion Department

## Convite para o Projeto
  Foi enviado um convite do projeto no MongoDB para o email "laferreira@fei.edu.br" para ter certeza que é o nosso projeto essa é a nossa connection uri: mongodb+srv://henryrodrigues3046:yeCXCnH1Lu2J8ucM@projeto.rrilm3i.mongodb.net/
