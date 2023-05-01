# API com AdonisJS

Esse é um projeto de uma API feita com AdonisJS desenvolvido no curso do [Matheus Battisti](https://www.youtube.com/watch?v=y8XfJJYhXPE).

## Sumário

- [Instalação](#instalação)
- [Uso](#uso)
- [Rotas](#rotas)
- [Licença](#licença)

## Instalação

1. Clone o repositório: `git clone https://github.com/matheusbattisti/curso_adonis_api_yt.git`
2. Entre na pasta do projeto: `cd curso_adonis_api_yt`

## Uso

Para utilizar a API, você pode fazer requisições através de ferramentas como [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/).

## Rotas

A API possui as seguintes rotas:

### Moments

- `GET /api/moments` - Retorna todos os momentos
- `GET /api/moments/:id` - Retorna um momento específico
- `POST /api/moments` - Cria um novo momento
- `PUT /api/moments/:id` - Atualiza um momento existente
- `DELETE /api/moments/:id` - Deleta um momento existente

### Comments

- `POST /api/moments/:momentId/comments` - Cria um novo comentário para um momento específico

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.
