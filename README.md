###### Resumo Api Rest <h6>

#### Api REST e RESTFul <h4>



#### Diferenças entre REST e RESTFul <h4>



#### HTTP verbs <h4>

são usados para indicar a ação desejada a ser realizada em um recurso identificado. Cada solicitação HTTP é composta por um método que especifica a ação a ser executada. Aqui estão alguns dos métodos HTTP mais comuns:

Método   |  Descrição
-------- | ------
 GET     | Solicita a representação de um recurso. GET deve ser seguro e idempotente, o que significa que executar a solicitação várias vezes deve produzir o mesmo resultado.
 POST    | Envia dados para serem processados para um recurso identificado. Geralmente usado para criar novos recursos.
 PUT     | Atualiza a representação de um recurso ou cria um recurso se ele não existir. Deve ser idempotente.
 DELETE  | Remove um recurso identificado.
 PATCH   | Aplica modificações parciais a um recurso.
 HEAD    | Similar ao GET, mas utilizado para obter apenas os cabeçalhos da resposta, sem o corpo da mensagem. É útil para verificar metadados sem recuperar o corpo da resposta.
 OPTIONS | Retorna os métodos HTTP suportados em um recurso, bem como outras informações sobre as capacidades do servidor.
 TRACE   | Usado para testar a conectividade entre o cliente e o servidor. Cada servidor ao longo do caminho da requisição retorna a solicitação TRACE de volta ao cliente, permitindo que este veja quais modificações foram feitas no caminho.
 CONNECT | É utilizado para converter a conexão de solicitação em um túnel direto para o servidor identificado.

Referência: <https://www.tutorialspoint.com/http/http_methods.htm>

#### HTTP Status Code <h4>

Os códigos de status HTTP são retornados pelo servidor web para indicar o resultado de uma solicitação feita pelo cliente. Eles são divididos em cinco classes:

SN   | Código e Descrição
---- | ------
 1   | 1xx: Informativo - Isso significa que a solicitação foi recebida e o processo continua.
 2   | 2xx: Sucesso - Significa que a ação foi recebida, compreendida e aceita com sucesso.
 3   | 3xx: Redirecionamento - Isso significa que outras ações devem ser tomadas para concluir a solicitação.
 4   | 4xx: Erro do cliente - Isso significa que a solicitação contém sintaxe incorreta ou não pode ser atendida.
 5   | 5xx: Erro do servidor - Isso significa que o servidor não atendeu a uma solicitação aparentemente válida.

Referência: <https://www.tutorialspoint.com/http/http_status_codes.htm>
---

Autor do resumo: Giovanna Pergentino - 01565341
