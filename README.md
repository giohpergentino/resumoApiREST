* #### RESUMO SOBRE API REST <h4> 

#### Api REST e RESTFul <h4>

Uma API, ou interface de programação aplicativos, é um conjunto de regras que definem como aplicativos ou dispositivos podem se conectar e se comunicar uns com os outros. Uma *API de REST* é uma API que se adéqua aos princípios de design do REST ou o estilo de arquitetura do Representational State Transfer.  Por esta razão, *as APIs de REST são muitas vezes chamadas de APIs de RESTful.*

Algumas APIs, como SOAP ou XML-RPC, impõe um framework restrito para os desenvolvedores. Porém, as APIs de REST podem ser desenvolvidas usando praticamente qualquer linguagem de programação e oferecem suporte a uma variedade de formatos de dados. O único requisito é que eles devem alinhar aos seis princípios de design de REST a seguir, conhecidos como restrições de arquitetura:
1. Interface uniforme;
2. Desacoplamento do cliente-servidor;
3. Sem estado definido;
4. Capacidade de armazenamento em cache;
5. Arquitetura de sistema em camadas;
6. Código sob demanda (opcional).

*Como as APIs de REST funcionam:*

As APIs de REST se comunicam via solicitações de HTTP para executar funções padrão do banco de dados como criar, ler, atualizar e excluir registros (também conhecidos como CRUD) em um recurso. Por exemplo, uma API de REST usaria uma solicitação GET para recuperar um registro, uma solicitação POST para criar um registro, uma solicitação PUT para atualizar um registro e uma solicitação DELETE para excluir um registro. Todos os métodos HTTP podem ser usados em chamadas da API. Uma API de REST bem projetada é semelhante a um website em execução em um navegador da web com funcionalidade HTTP integrada.

A *API RESTful* é uma interface que dois sistemas de computador usam para trocar informações de forma segura pela internet. A maioria das aplicações de negócios precisa se comunicar com outras aplicações internas e de terceiros para executar várias tarefas. Por exemplo, para gerar contracheques mensais, seu sistema interno de contas precisa compartilhar dados com o sistema bancário de seu cliente a fim de automatizar o faturamento e se comunicar com uma aplicação interna de planilha de horas. As APIs RESTful suportam essa troca de informações porque seguem padrões de comunicação de software seguros, confiáveis e eficientes.

Referência: <https://aws.amazon.com/pt/what-is/restful-api/>, <https://www.ibm.com/br-pt/topics/rest-apis>

#### Diferenças entre REST e RESTFul <h4>

*REST* é uma arquitetura de estilo para projetar sistemas de software na web.
*Características Principais:*
* Baseia-se no conceito de recursos (resouces), que são identificados por URLs.
* Utiliza métodos HTTP (GET, POST, PUT, DELETE) para operar sobre esses recursos.
* Não mantém estado entre as solicitações do cliente; cada solicitação do cliente para o servidor contém toda a informação necessária para entender e processar a solicitação.
* Responde com representações dos recursos no formato desejado (JSON, XML, HTML, etc.).

*RESTful* é uma abordagem específica para implementar serviços web usando os princípios do REST.
*Características Principais:*
* Usa URIs (Uniform Resource Identifiers) para identificar recursos.
* Utiliza métodos HTTP (GET, POST, PUT, DELETE) para operar sobre esses recursos.
* Responde com representações dos recursos no formato desejado.
* Geralmente, segue os princípios do REST de maneira rigorosa.

*Diferenças Chave:*

* *REST* é uma arquitetura, enquanto *RESTful* é a implementação dessa arquitetura.

* *REST* é um conjunto de princípios, enquanto *RESTful* é a aplicação desses princípios.

* Portanto, todos os serviços RESTful são REST, mas nem todos os serviços REST são necessariamente RESTful, dependendo de quão estritamente eles aderem aos princípios do REST. 

* O termo "RESTful" é frequentemente usado para descrever serviços web que seguem de perto os princípios do REST.

Referência: <https://aws.amazon.com/pt/what-is/restful-api/>

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
