# ARCADE/HUB

Biblioteca pessoal de jogos web com visual de console, pensada para TV, computador e dispositivos móveis.

## Recursos
- Cadastro manual de jogos por URL, com nome, tipo de acesso, capa e descrição.
- Biblioteca com pesquisa e filtro.
- Modo de jogo com iframe para sites que permitem incorporação e botão para abrir o endereço original em nova aba.
- Navegação do Hub por controle compatível com a Gamepad API, além de teclado e mouse.
- Solicitação de tela cheia.
- Exportação e importação de backup JSON.
- Persistência local via `localStorage`.

## Executar
Abra `index.html` em um navegador moderno. Para melhor compatibilidade, sirva os arquivos por um servidor HTTP estático.

## Publicar
O projeto é estático e não precisa de etapa de build. Importe o repositório no Vercel ou Cloudflare Pages, usando a raiz do projeto como diretório e sem comando de build.

## Importante
- O jogo inicial de exemplo é **Avengers Takedown**: https://www.gameflare.com/online-game/avengers-takedown/
- Alguns sites bloqueiam iframes por políticas de segurança; nesse caso, use **Abrir original**.
- A navegação por controle no Hub não garante que o jogo em si aceite controle. Isso depende do jogo, do navegador e do dispositivo.
- A biblioteca é local neste navegador. Use o backup JSON para transferir os dados; ainda não há contas nem sincronização na nuvem.
- O Hub organiza links, não baixa nem hospeda jogos de terceiros. Use jogos e capas que você tenha permissão para acessar.
- A experiência em Fire TV/Smart TV depende do navegador instalado, suporte a Gamepad API e permissões do dispositivo.
