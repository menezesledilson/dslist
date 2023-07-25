API REST DSList Intensivão Java Spring - Nelio Alves

Descrição

Esta é uma API REST desenvolvida em Java Spring para gerenciar listas usando o DSList Intensivão.
A API permite que os usuários criem, leiam, atualizem e excluam itens em suas listas.
Dependências

Certifique-se de ter as seguintes dependências do Spring Boot instaladas em seu projeto:

    Spring Web: Responsável por criar os endpoints REST e lidar com as solicitações HTTP.
    Spring Data JPA: Facilita a interação com o banco de dados, permitindo que a API armazene e recupere informações.
    H2 Database: Banco de dados SQL em memória para desenvolvimento e testes.
    PostgresSQL Driver: Driver JDBC para conexão com o banco de dados PostgreSQL.

Ferramentas Recomendadas

O uso das seguintes ferramentas é altamente recomendado para desenvolver e testar a API:

    Spring Tools Suite: Uma ferramenta útil que facilita o desenvolvimento do projeto e oferece funcionalidades para escrever códigos com maior qualidade. Recomendado para aumentar a eficiência do desenvolvimento.
    Postman: Uma ferramenta para testar as chamadas à API. É possível fazer requisições HTTP usando os métodos GET e POST para listar e enviar dados para a API, respectivamente. É importante utilizar corretamente os métodos HTTP para garantir o bom funcionamento da API e obter os resultados desejados.

Endpoints

A API possui os seguintes endpoints principais:

    GET /api/listas: Retorna a lista completa disponível.
    POST /api/listas: Envia uma requisição para adicionar um novo item à lista.

Certifique-se de usar corretamente os métodos HTTP apropriados para acessar os endpoints e manipular as informações da lista.
Exemplo de Uso

Para listar todos os itens da lista, faça uma requisição usando o método GET para o endpoint /api/listas.

Para adicionar um novo item à lista, faça uma requisição usando o método POST para o endpoint /api/listas, incluindo os dados necessários na requisição.
