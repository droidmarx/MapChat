# Map Chat

Bem-vindo ao Map Chat! Este projeto é uma aplicação web que combina geolocalização em tempo real e previsão do tempo, integrando diversas tecnologias para proporcionar uma experiência interativa e informativa.

## Tecnologias Utilizadas

- **OpenWeatherMap**: Para obter dados de previsão do tempo.
- **Leaflet**: Biblioteca JavaScript para mapas interativos.
- **Ably**: Plataforma de mensagens em tempo real para compartilhar localização.
- **JavaScript**: Linguagem principal para desenvolvimento do script.
- **HTML/CSS**: Para estrutura e estilização da página.

## Funcionalidades

- **Geolocalização em Tempo Real**: O site obtém e compartilha sua localização atual.
- **Previsão do Tempo**: Mostra a previsão do tempo para sua localização atual.
- **Armazenamento de UUID**: O UUID do usuário é salvo no local storage para reutilização em visitas futuras.
- **Compartilhamento de Localização**: Envia sua localização para outra página em tempo real, mesmo que ela esteja fechada.

## Como Usar

1. **Acesse o Site**: Visite [Map Chat](https://map-chat-flame.vercel.app/).
2. **Permitir Acesso à Localização**: Quando solicitado, permita que o site acesse sua localização.
3. **Visualize o Mapa**: Veja sua localização atual no mapa interativo.
4. **Previsão do Tempo**: Confira a previsão do tempo para sua localização.
5. **Compartilhe a Localização**: Sua localização será automaticamente compartilhada com outras instâncias do site em tempo real.

## Instalação e Desenvolvimento

Se você deseja clonar e executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/map-chat.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd map-chat
    ```
3. Instale as dependências:
    ```sh
    npm install
    ```
4. Crie um arquivo `.env` na raiz do projeto e adicione suas chaves de API:
    ```env
    VITE_OPENWEATHERMAP_API_KEY=sua_chave
    VITE_ABLY_API_KEY=sua_chave
    ```
5. Inicie o servidor de desenvolvimento:
    ```sh
    npm run dev
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ♥ por [Gui Marx](https://github.com/droidmarx).