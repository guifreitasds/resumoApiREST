# Api REST e RESTFul

Uma API REST é uma imposição de condições de como uma API deve funcionar, possibilitando uma comunicação confiável e de alta performance em escala. Quando um cliente faz uma solicitação para uma API RESTful, ela transfere uma representação do estado do recurso ao seu solicitante (Representational State Transfer).

## O que é uma API?

Uma API é um conjunto de definições e regras que definem como um aplicativo pode se conectar ou comunicar com outras aplicações.

## Diferenças entre REST e RESTFul

A principal diferença entre REST e RESTFul está no nível de aderência aos princípios REST, ou seja se uma API adere rigidamente a esses princípios, ela pode ser considerada RESTFul, já uma abordagem REST adere ao design REST, mas de uma forma mais básica.

### Características de uma API REST
* Utilização dos métodos HTTP
* Uso de URLs
* Transferência de dados entre cliente e servidor em um formato padrão
* Manutenção do estado da aplicação no cliente, em vez do servidor

### Características de uma API RESTFul
* Todas acima+ 
* A API deve ter uma interface uniforme, consistente e padronizada
* Cada solicitação enviada do cliente para o servidor deve conter informações necessárias para entendê-la, sem intervenção do servidor
* As ações realizadas pela API devem ser por URLs únicas

## HTTP verbs

O protocolo HTTP define um conjunto de métodos para indicar a ação a ser executada com o recurso solicitado

### GET 

Retorna apenas os dados requisitados

### HEAD

Retorna dados do cabeçalho da requisição 

### POST 

É utilizado para fazer uma adição a o estado do recurso no servidor

### PUT 

Substitui todas as atuais representações do recurso no destino pela carga de dados da requisição

### DELETE

Remove um recurso específico

### CONNECT

Estabelece um tunnel para o servidor identificado pelo recurso de destino 

### OPTIONS

Descreve as opções de comunicação para o recurso alvo

### PATCH

Utilizado para fazer alterações parciais em um recurso



## HTTP Status Code

Os códigos de status do HTTP indicam se uma requisição foi concluída com sucesso ou não.

### 1xx
Nesse intervalo são dados respostas informativas como: Continue (100), Mudando de Protocolo (101), Processando (102), etc.

### 2xx

Nesse intervalo, são dadas respostas de sucesso como: OK(200), Criado (201), Aceito (202), Não há conteúdo (204), etc.

### 3xx

Nesse intervalo, são dadas mensagens de redirecionamento como: Multíplas escolhas (300), Movido permanentemente (301), etc.

### 4xx

Nesse intervalo, são dadas mensagens de erro como: Erro no pedido (400), Não autorizado (401), Não encontrado (404), etc.

### 5xx

Nesse intervalo, são dadas mensagens de erro do servidor como: Erro interno do servidor (500), Erro de gateway (502), Serviço indísponivel (503), etc.

---

Autor do resumo: Guilherme Freitas dos Santos - 01564838