# Like

Wordpress plugin de adicionar like para usuarios logados

## Como funciona

Criei uma tabela no banco de dados que tem 3 colunas(id, post_id, user_id), ao ativar o plugin. Quando usuário estiver logado, tem opção de clicar em um coração, em que se o usuário clicar, é enviado uma requisição assincrona para backend, utilizando nonce por segurança, para validar se o click corresponde a um like ou dislike.

* OBS.: Só funciona com usuários logados