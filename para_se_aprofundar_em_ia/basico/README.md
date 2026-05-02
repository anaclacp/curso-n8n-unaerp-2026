# Básico

Esta trilha é para construir base. Antes de pensar em agentes mais sofisticados, vale garantir que você entende como sistemas conversam entre si e tem noções suficientes de lógica para montar integrações com mais segurança.

## O que estudar

- O que é uma API.
- Como funciona uma chamada HTTP.
- Métodos como `GET`, `POST`, `PUT`, `PATCH` e `DELETE`.
- O que são `headers`, `body`, `query params` e `status codes`.
- O que é JSON e por que ele aparece tanto em automações.
- Como testar uma API com `curl`, Postman, Insomnia ou pelo próprio n8n.
- O que é autenticação por API key, token ou OAuth.
- Noções básicas de programação: variáveis, funções, listas, dicionários, condicionais e loops.

## Python como linguagem para começar

Se você quiser aprender uma linguagem de programação, Python é uma ótima escolha. Ela é uma linguagem agradável, legível e muito usada em automação, análise de dados, backend, APIs e inteligência artificial.

Você não precisa dominar Python para usar n8n, mas em casos que o n8n não é uma boa opção, ou para criar scripts mais personalizados, Python é uma escolha boa. Ele tem uma sintaxe simples, uma comunidade enorme e muitas bibliotecas para facilitar o trabalho com APIs, dados e IA.

Assuntos úteis para começar:

- Variáveis e tipos de dados.
- Listas e dicionários.
- Condicionais com `if`.
- Repetições com `for` e `while`.
- Funções.
- Leitura e escrita de arquivos.
- Como instalar pacotes com `pip`.
- Como fazer chamadas HTTP com bibliotecas como `requests`.

## Práticas recomendadas

- Pegue uma API pública simples e faça uma chamada `GET`.
- Transforme a resposta da API dentro do n8n.
- Crie um fluxo que recebe um dado, chama uma API e devolve uma resposta organizada.
- Leia mensagens de erro com calma. Status `400`, `401`, `403`, `404` e `500` contam bastante sobre o problema.
- Faça um script pequeno em Python que chama uma API e imprime a resposta.
- Tente transformar um JSON em uma informação mais simples usando Python.

## Materiais

- HTTP, MDN Web Docs: https://developer.mozilla.org/en-US/docs/Web/HTTP
- JSON, MDN Web Docs: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/JSON
- O que é uma API, Red Hat: https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces
- Documentação do n8n: https://docs.n8n.io/
- Python para iniciantes, documentação oficial: https://docs.python.org/pt-br/3/tutorial/
- Automate the Boring Stuff with Python: https://automatetheboringstuff.com/

Recomendação de cursos de python (que eu fiz quando comecei): 
- https://www.udemy.com/share/101ufc3@9gqeP1n66LEMQqTjELkUFVQAbiio1V7eEDkfsgdly1fB9UPhz36KIpf_Ub7Xk6iWaw==/
- https://www.udemy.com/share/101YDa3@loM4xIZI117t3rSa7BMTX64_Bjmhr_P0VYVw4Lgql-C7cKfK1qqOn0ifatlT9VCm7A==/

> Você não precisa fazer um curso inteiro completo, mas fazer alguns módulos pode ser muito útil. O importante é praticar com projetos.