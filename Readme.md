# Mapa em Tempo Real com Ably e Leaflet

## Visão Geral

Este projeto cria uma aplicação de mapa em tempo real usando Ably e Leaflet. A aplicação permite que os usuários compartilhem sua localização e conversem com outros em tempo real. As localizações dos usuários são exibidas em um mapa e as mensagens podem ser enviadas e recebidas através de uma interface de chat.

## Funcionalidades

- **Compartilhamento de Localização em Tempo Real**: Os usuários podem compartilhar sua localização, que é exibida em um mapa do Leaflet.
- **Funcionalidade de Chat**: Os usuários podem enviar e receber mensagens em tempo real.
- **Lista de Usuários**: Exibe uma lista de usuários online com seus endereços.
- **Notificações**: Notificações em tempo real para eventos de entrada e saída de usuários.
- **Sessão de Usuário Persistente**: Os nomes de usuários são armazenados no `sessionStorage` para sessões persistentes.

## Tecnologias Utilizadas

- **Ably**: Para mensagens em tempo real e compartilhamento de localização.
- **Leaflet**: Para a exibição interativa do mapa.
- **OpenWeatherMap**: (opcional) Para integração de dados meteorológicos.
- **Geolocalização de IP**: Para gerar um nome de usuário único com base no endereço IP do usuário.

## Como Usar

1. **Configuração**:
   - Clone o repositório ou baixe o arquivo HTML.
   - Certifique-se de ter uma chave de API do Ably. Substitua a chave de API no script pelo seu próprio.

2. **Executando a Aplicação**:
   - Abra o arquivo HTML em um navegador web.
   - A aplicação solicitará sua localização e usará seu endereço IP para gerar um nome de usuário único.

3. **Interações do Usuário**:
   - **Compartilhamento de Localização**: Sua localização será compartilhada em tempo real e exibida no mapa.
   - **Chat**: Use o campo de entrada de chat para enviar mensagens. Suas mensagens aparecerão no registro de chat e no popup do marcador da sua localização.
   - **Lista de Usuários**: Clique no contador "Usuários logados" para ver uma lista de usuários online e seus endereços.
   - **Sair**: Clique no botão "Sair da sala" para sair da sessão. Isso limpará seu nome de usuário e interromperá o compartilhamento da sua localização.

4. **Notificações**:
   - Você receberá notificações quando entrar ou sair da sessão.

## Personalização

- **Estilo**: Modifique os estilos CSS dentro da tag `<style>` para alterar a aparência do mapa e da interface de chat.
- **Geolocalização**: Ajuste a lógica de geolocalização e obtenção de IP conforme necessário.
- **Integração com Ably**: Personalize os canais do Ably para diferentes funcionalidades conforme necessário.

## Notas Importantes

- Certifique-se de que a geolocalização esteja ativada no seu navegador para que a aplicação funcione corretamente.
- A aplicação usa `sessionStorage` para armazenar o nome de usuário, que é limpo quando o usuário sai ou fecha a página.
- As mensagens de chat são armazenadas temporariamente e exibidas no registro de chat e nos popups dos marcadores.

## Dependências

- [Leaflet](https://leafletjs.com/)
- [Biblioteca JavaScript do Ably](https://ably.com/)

## Licença

Este projeto é de código aberto e está disponível sob a [Licença MIT](https://opensource.org/licenses/MIT).

## Contato

Para quaisquer dúvidas ou problemas, por favor, entre em contato com o mantenedor do projeto.
[Gui Marx](https://github.com/droidmarx)