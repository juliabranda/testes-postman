# testes-postman
Este projeto contém uma coleção de testes básicos para a API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com), criada no Postman. O objetivo é validar o funcionamento de endpoints REST usando scripts simples de teste.

Endpoints testados:
GET /posts
- Verifica se o status da resposta é `200 OK`
- Confirma que a resposta contém uma lista de posts

POST /posts
- Verifica se o status da resposta é `201 Created`
- Confirma que o corpo da resposta contém o campo `id`
- Valida se o título do post criado está correto

Ferramentas utilizadas:
- Postman
- Scripts de teste com `pm.test`
- API JSONPlaceholder

Arquivo incluído:
- api-tests-julia.postman_collection.json: coleção com os testes automatizados

Julia Rodrigues 
Analista de Qualidade de Software.
