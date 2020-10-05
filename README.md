# publicadesafio

COMO EXECUTAR PROGRAMA

Baixe todos os arquivos da 'main'.

Extraia o arquivo CRUD_SQLite.zip

Na pasta onde o arquivo foi extraído siga o caminho:
-> CRUD_SQLite\CRUD_SQLite.SemCamadas\bin\Debug 

Execute o programa "CRUD_SQLite.SemCamadas.exe";


DOCUMENTAÇÃO

Ao iniciar o programa, ele irá criar um arquivo SQLite, que irá guardar as informações, como um pseudo-banco de dados.


Botão "Inserir"

Esse botão irá abrir uma nova janela onde você poderá informar o placar da nova partida, ao salvar, ele irá criar um novo registro no banco e irá atualizar a lista de partidas.


Funções:

AtualizarRecordes(ref int placar, ref int minTemp, ref int maxTemp, ref int qbrMinRecorde, ref int qbrMaxRecorde)
  Caso não seja o primeiro registro, essa função irá fazer a verificação e o controle se houveram novos recordes quebrados, e irá retornar os valores atualizados.

CarregaDados()
  Caso seja a primeira vez que o banco é carregado ele irá criar a tebela de controle de partidas. Após isso, ele irá selecionar todos os novos registros atualizando o grid de registros.
