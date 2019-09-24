# \<DesafioBackendSenior/>

**TESTE DESEVOLVEDOR 3:**

Temos o seguinte cenário. Um desenvolvedor mobile está desenvolvendo uma app que precisa de um backend simples, mas ele não tem conhecimento para desenvolver esse backend.
A Zup quer resolver o problema desse desenvolvedor. A idéia é que através de uma tela simples o desenvolvedor consiga criar um novo “Modelo” e inserir dados (instâncias do “Modelo”) para serem consumidos pela app mobile.


**Um caso de uso de exemplo seria:**

Desenvolvedor cria um novo "Modelo" com o nome "Products"Desenvolvedorconfigura os atributos do modelo: name:string, description:text, price:decimal, category:string

A partir desse cadastro um recurso REST para gerenciamento desse modelo com os seguintes métodos devem estar disponíveis:

GET /products - Lista todos os produtos

GET /products/{id} - Busca um produto por id

POST /products - Cria um novo produto

PUT /products/{id} - Edita um produto 

DELETE /products/{id} - Deleta um produto

Com isso o desenvolvedor consegue criar uma app mobile que utiliza esse conteúdo sem desenvolver um backend. Claro que existem vário outros detalhes necessários para uma solução completa, mas acredito que esses requisitos são suficientes para um MVP.

**O que deve ser feito:**

Pensar na melhor arquitetura para a solução, pensando em evolução, escalabilidade, etc.. Descrever brevemente a arquitetura proposta Desenvolver o backend dessa versão inicial. Se quiser desenvolver o frontend também fique a vontade, mas seria um plus O código-fonte deve ser disponibilizado na sua conta do Github, em um repositório com o nome xy-inc, juntamente com as instruções para execução e testes da aplicação (arquivo README)

**Considerações importantes:**

Você pode utilizar qualquer tecnologia que julgar necessário
Serão avaliados: organização do código, simplicidade da solução (KISS),conhecimentos da linguagem/framework utilizado, cobertura de testes, extensibilidade, manutenibilidade.