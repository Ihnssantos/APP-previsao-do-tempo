# Previsão do Tempo

Este é um projeto simples de previsão do tempo que permite ao usuário consultar as condições climáticas de qualquer cidade ao redor do mundo. A aplicação utiliza a [WeatherAPI](https://www.weatherapi.com/) para buscar as informações e exibi-las de forma clara e acessível.

## Funcionalidades

- **Busca de cidade**: O usuário pode digitar o nome de uma cidade e buscar a previsão do tempo para aquele local.
- **Exibição de informações**:
  - Temperatura em °C
  - Condição do clima (ex: ensolarado, nublado)
  - Ícone representativo da condição climática
  - Humidade relativa do ar (%)
  - Velocidade do vento (em km/h)

## Tecnologias Utilizadas

- **HTML**: Estruturação do conteúdo da página.
- **CSS**: Estilização da página com foco em uma interface simples e moderna.
- **JavaScript**: Lógica para fazer a requisição à API de previsão do tempo e atualizar os dados dinamicamente na página.

## Como Rodar o Projeto

1. Clone este repositório em sua máquina:
    ```bash
    git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
    ```
2. Navegue até a pasta do projeto:
    ```bash
    cd nome-do-repositorio
    ```
3. Abra o arquivo `index.html` em seu navegador para ver o projeto funcionando.

## Configuração da API

1. Crie uma conta no [WeatherAPI](https://www.weatherapi.com/) e obtenha sua chave de API.
2. Substitua a chave da API no arquivo `src/js/index.js` pela sua chave válida:
    ```javascript
    const chaveDaApi = `SUA_CHAVE_AQUI`;
    ```

## Contribuições

Contribuições são bem-vindas! Se você encontrar um bug ou desejar adicionar uma nova funcionalidade, por favor, crie uma *issue* ou envie um *pull request*.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).