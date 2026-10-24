# ARCADE/HUB

Biblioteca pessoal de jogos web com experiência visual inspirada em interfaces de console, projetada para tela grande, computador e dispositivos móveis.

## Experiência visual
- Interface imersiva de tela cheia, com papel de parede cinematográfico e camadas de contraste.
- Navegação superior e barra de categorias com estado selecionado destacado.
- Carrossel horizontal de jogos com item em foco ampliado, transições suaves e arte/capa personalizada.
- Atalhos de jogar, detalhes e opções, além de biblioteca organizada em grade.
- Layout responsivo para diferentes dimensões de tela e suporte a preferência por movimento reduzido.

## Recursos
- Cadastro, edição e remoção de jogos por URL, com categoria, modo de abertura, capa e descrição.
- Biblioteca com pesquisa e filtros por categoria e tipo de acesso.
- Tela de detalhes para cada jogo.
- Modo de jogo com iframe para sites que permitem incorporação; opção de abrir o endereço original quando a incorporação é bloqueada.
- Navegação por controle via Gamepad API, além de teclado e mouse.
- Tela cheia e backup por exportação/importação JSON.
- Persistência local via `localStorage`; não há conta nem sincronização na nuvem.

## Executar
Abra `index.html` em um navegador moderno. Para melhor compatibilidade, sirva o projeto por um servidor HTTP estático.

## Publicar
O projeto é estático e não precisa de etapa de build. Importe o repositório no Vercel ou Cloudflare Pages, usando a raiz do projeto como diretório e sem comando de build.

## Importante
- O jogo de exemplo é **Avengers Takedown**: https://www.gameflare.com/online-game/avengers-takedown/
- Portais podem impedir a incorporação por políticas de segurança. O Hub oferece abertura no site original; não consegue remover as restrições impostas por outro site.
- O controle navega pela interface do Hub, mas o suporte dentro do jogo depende do próprio jogo, navegador, sistema e dispositivo.
- A biblioteca fica salva neste navegador. Use o backup JSON para transferir sua coleção para outro dispositivo.
- O Hub organiza links; não baixa nem hospeda jogos de terceiros. Use jogos e capas aos quais você tenha acesso autorizado.
- A experiência em Fire TV/Smart TV depende do navegador instalado, da Gamepad API e das permissões do dispositivo.
- O visual foi atualizado no repositório; a publicação na hospedagem e os testes físicos em TV ainda precisam ser feitos.
