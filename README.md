# API Fake Spotify

Este projeto simula a plataforma do Spotify utilizando **HTML**, **CSS** e **JavaScript**.

## 📌 Funcionalidades

- **Listagem de artistas**: Exibe uma lista de artistas com suas respectivas informações (nome, imagem, etc.).
- **Detalhes do artista**: Ao clicar em um artista, o usuário é redirecionado para uma página com informações detalhadas sobre ele (músicas, álbuns, etc.).
- **Reprodução de músicas**: Permite ao usuário reproduzir trechos das músicas dos artistas.
- **Busca de artistas**: Possibilita ao usuário buscar por artistas específicos.

## 🚀 Tecnologias utilizadas

- **HTML**: Estrutura a página web.
- **CSS**: Estiliza a página web.
- **JavaScript**: Adiciona interatividade à página web, como a reprodução de músicas e a busca de artistas.
- **JSON Server**: Simula uma API RESTful para fornecer os dados dos artistas e músicas.

## ⚙️ Como rodar a API fake

1. Abra o terminal do **VSCode** (ou o terminal de sua preferência).
2. Navegue até a pasta raiz do projeto.
3. Execute o seguinte comando:

```sh
json-server --watch api-artists/artists.json --port 3000
```

Este comando irá iniciar o servidor **JSON Server**, que irá servir os dados dos artistas e músicas a partir do arquivo `artists.json`. A API estará disponível na porta **3000**.

## 🔗 Como usar a API fake

A API fake fornece os seguintes endpoints:

- `GET /artists` → Retorna uma lista de todos os artistas.
- `GET /artists/:id` → Retorna as informações de um artista específico.
- `GET /songs` → Retorna uma lista de todas as músicas.
- `GET /songs/:id` → Retorna as informações de uma música específica.

Você pode usar esses endpoints para consumir os dados da API fake em seu projeto.

## 🔍 Observações

- Este projeto é **apenas uma simulação** da plataforma do Spotify, com funcionalidades limitadas.
- Os dados dos artistas e músicas são fictícios e foram armazenados no arquivo `artists.json`.
- Para adicionar novas funcionalidades ou modificar os dados existentes, você pode editar o arquivo `artists.json` e os arquivos **HTML, CSS e JavaScript** do projeto.

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tiver alguma sugestão, ideia ou encontrar algum problema, por favor, **abra uma issue** ou **envie um pull request**.

## 📜 Licença

Este projeto está sob a licença **MIT**.
