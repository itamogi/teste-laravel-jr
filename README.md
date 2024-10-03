# Teste Prático - Desenvolvedor Júnior (PHP/Laravel)

## Objetivo

O objetivo deste teste é avaliar suas habilidades em PHP, Laravel, MySQL, HTML, CSS e integração de APIs, especificamente com o Mercado Livre.

## Instruções Gerais

1. Certifique-se de fornecer instruções claras sobre como rodar seu projeto.
2. Você precisará criar uma aplicação no [Mercado Livre Developer](https://developers.mercadolivre.com.br/) para obter as credenciais de API (client_id, client_secret e token de acesso).

---

## Desafio 1: Cadastro de Produtos via API do Mercado Livre

Crie um pequeno sistema em Laravel que permita realizar o cadastro de produtos diretamente no Mercado Livre utilizando a API oficial.

### Requisitos do Cadastro:

1. Um produto deve ter os seguintes atributos:
   - Nome
   - Descrição
   - Preço
   - Quantidade em estoque
   - Categoria (você pode buscar categorias válidas usando a API de Mercado Livre)
   - Imagem (upload de uma imagem que será enviada junto ao produto)

2. As seguintes funcionalidades devem ser implementadas:
   - Formulário para cadastro de um novo produto.
   - Envio das informações do produto para a API do Mercado Livre.
   - Exibição da resposta retornada pela API (se o produto foi criado com sucesso ou se houve algum erro).

3. Utilize o MySQL para armazenar um histórico dos produtos cadastrados.

4. Use HTML e CSS simples para o front-end do formulário.

---

## Desafio 2: Integração com API do Mercado Livre

Para realizar a integração, você deverá utilizar as credenciais de API obtidas no Mercado Livre Developer. O fluxo de autenticação OAuth deve ser implementado.

### Requisitos da integração:

1. Implemente o fluxo OAuth2 para obter o token de acesso ao Mercado Livre.
2. O token deve ser utilizado para fazer chamadas autenticadas à API do Mercado Livre, especificamente para o endpoint de criação de produtos (`/items`).
3. Exiba os dados retornados pela API após o produto ser criado (ID do produto, status, etc).

### Links úteis:

- [Documentação da API do Mercado Livre](https://developers.mercadolivre.com.br/pt_br/itens-e-buscas)
- [Autenticação OAuth Mercado Livre](https://developers.mercadolivre.com.br/pt_br/autenticacao-e-autorizacao)

---

## Desafio 3: Documentação

Crie um arquivo `README.md` com:

1. Instruções de como instalar e rodar o projeto.
2. Explicação sobre como configurar as variáveis de ambiente para a integração com o Mercado Livre (client_id, client_secret, redirect_uri, etc.).
3. Passos detalhados de como gerar o token de acesso para autenticação via OAuth.

---

## Bônus (opcional):

- Implementação de um sistema de autenticação no Laravel para proteger o acesso ao formulário de cadastro de produtos.
- Validação de dados no formulário (ex: preços negativos, descrição vazia, etc.).
- Utilização de um framework CSS (ex: Bootstrap ou Tailwind) para melhorar a interface.

---

## O que será avaliado:

1. Organização do código.
2. Boas práticas em PHP e Laravel.
3. Implementação da integração com a API do Mercado Livre.
4. Validação e tratamento de erros na comunicação com a API.
5. Interface simples e funcional.

---

Após finalizar o seu código, suba ele em um repositório público e envie um e-mail para psymics@gmail.com informando a URL.

**Boa sorte!**
