# (ENG) Ultimate Fantasy Soccer

**Ultimate Fantasy Soccer** is a multiplayer soccer project developed on
**Roblox**, built around competitive gameplay, persistent progression,
and structured team-based matches.

The project went through dozens of iterations during development and
combines gameplay systems, client-server networking, data persistence,
artificial intelligence, user interfaces, customization, and
cross-platform support.

**Play on Roblox:** https://www.roblox.com/games/3433744349

## Soccer Gameplay

The game features a complete set of mechanics developed specifically for
multiplayer soccer matches:

-   **Ball possession system**
-   **Shots with multiple power levels**
-   **Passing**
-   **Chips and dribbling**
-   **Tackles and challenges**
-   **Pass request system**
-   **Goal detection and processing**
-   **Assists**
-   **Saves**
-   **Ball control and physics**
-   **Cooldowns for different actions**
-   **Animations and visual effects tied to player actions**

A large part of these mechanics uses a **client-server architecture**,
keeping authority over important match actions on the server while the
client handles elements such as input, camera, HUD, animations, and
visual effects.

## Matches and Positions

Matches have their own team-management system and support different
roles that players can take on the field.

Available positions include:

-   **Goalkeeper**
-   **Defender**
-   **Winger**
-   **Striker**

The system tracks occupied positions independently for each team and
organizes players according to their roles during a match.

A complete **match flow system** is also responsible for player
preparation, match start, score management, goals, match time, and match
completion.

## Goalkeeper AI

If a team does not have a player occupying the goalkeeper position, the
game can use an **AI-controlled goalkeeper**.

The AI uses different behaviors and states for situations such as:

-   Positioning relative to the goal and ball
-   Detecting dangerous situations
-   Saving shots
-   Diving
-   Interception attempts
-   Recovery after a save
-   Ball control

When a player takes the goalkeeper position, the system can replace the
AI-controlled goalkeeper.

## DataStore and Statistics

The project includes a **DataStore-based persistence system**, allowing
player progression and statistics to be preserved between sessions.

Stored data includes:

-   Goals
-   Assists
-   Saves and tackles
-   Successful dribbles
-   Experience
-   Level
-   Currency
-   General career statistics

The project also includes **persistent ranking systems**, allowing
selected statistics to be compared between players.

## Level and XP

Players have their own **experience-based progression system**.

Participating in matches and performing specific actions awards XP and
allows the account to level up, with progression preserved between
sessions.

This system is integrated with the player's other persistent statistics.

## Lobby and Customization

Before matches, players have access to a lobby containing several
preparation and customization systems:

-   **Character customization**
-   **Club/team customization**
-   **Cosmetic selection and management**
-   **Shop**
-   **Persistent currency system**
-   **Emote system**
-   **Match preparation**

Relevant customization choices and purchases can be preserved through
the game's persistence system.

## Shop and Economy

The project features its own **economy system**, with currency linked to
the player's account and stored through DataStore.

This currency can be spent in the in-game shop on available content and
customization.

## Cutscenes and Celebrations

Goals include an additional presentation layer through **cutscenes and
celebration cameras**.

After certain plays, the system can highlight the player who scored and
temporarily change the match presentation to create celebrations closer
to those seen in traditional soccer games.

Systems for presenting standout players and **MVPs** were also
developed.

## Mobile Support

The game was developed with mobile players in mind.

The main gameplay actions support **mobile controls**, allowing the
soccer mechanics to be used on both computers and Roblox-compatible
smartphones and tablets.

## Main Systems

Overall, the project includes the development and integration of:

-   Multiplayer soccer gameplay
-   Client-server architecture
-   Match management
-   Team and position management
-   Artificial intelligence
-   DataStore and persistence
-   Rankings
-   Level and XP progression
-   Career statistics
-   Economy and shop
-   Character customization
-   Club customization
-   Emotes
-   HUD and user interfaces
-   Animations
-   Visual effects
-   Cameras and cutscenes
-   Mobile support

**Ultimate Fantasy Soccer** is one of my most extensive Roblox projects
and represents the integration of many independent systems into a single
multiplayer experience, ranging from low-level match mechanics to
persistence, progression, AI, and game presentation.


# (PT-BR) Ultimate Fantasy Soccer

**Ultimate Fantasy Soccer** é um projeto de futebol multiplayer desenvolvido no **Roblox**, criado com foco em gameplay competitivo, progressão persistente e partidas estruturadas entre equipes.

O projeto passou por dezenas de iterações durante seu desenvolvimento e reúne sistemas de gameplay, networking cliente-servidor, persistência de dados, inteligência artificial, interfaces, customização e suporte multiplataforma.

O jogo está atualmente hospedado no Roblox:

**Ultimate Fantasy Soccer:** https://www.roblox.com/games/3433744349

## Sistema de Futebol

O gameplay possui um conjunto completo de mecânicas desenvolvidas especificamente para partidas de futebol multiplayer:

* **Sistema de posse de bola**
* **Chutes com diferentes níveis de força**
* **Passes**
* **Chapéus e dribles**
* **Desarmes e divididas**
* **Sistema de pedido de passe**
* **Detecção e processamento de gols**
* **Assistências**
* **Defesas**
* **Controle e física da bola**
* **Cooldowns para diferentes ações**
* **Animações e efeitos visuais associados às ações do jogador**

Grande parte dessas mecânicas utiliza uma arquitetura **cliente-servidor**, mantendo no servidor a autoridade sobre ações importantes da partida enquanto o cliente processa elementos como input, câmera, HUD, animações e efeitos visuais.

## Partidas e Posições

As partidas possuem gerenciamento próprio de equipes e das diferentes funções que cada jogador pode assumir dentro de campo.

Entre as posições disponíveis estão:

* **Goleiro**
* **Zagueiro**
* **Ala**
* **Atacante**

O sistema controla as posições ocupadas de cada equipe e permite organizar os jogadores de acordo com suas funções durante a partida.

Também existe um sistema completo responsável pelo **fluxo da partida**, incluindo preparação dos jogadores, início do jogo, controle do placar, gols, tempo da partida e encerramento.

## IA de Goleiro

Caso uma equipe não possua um jogador ocupando a posição de goleiro, o jogo pode utilizar um **goleiro controlado por IA**.

A IA possui diferentes comportamentos e estados para situações como:

* Posicionamento em relação ao gol e à bola
* Identificação de situações de perigo
* Defesa
* Mergulho
* Tentativa de interceptação
* Recuperação após uma defesa
* Controle da bola

Quando um jogador assume a posição, o sistema pode substituir o goleiro controlado artificialmente.

## DataStore e Estatísticas

O projeto possui um sistema de **persistência de dados utilizando DataStore**, permitindo manter a progressão e as estatísticas dos jogadores entre diferentes sessões.

Entre os dados registrados estão estatísticas como:

* Gols
* Assistências
* Defesas e desarmes
* Dribles realizados com sucesso
* Experiência
* Nível
* Moeda
* Estatísticas gerais de carreira

O projeto também possui sistemas de **ranking persistente**, permitindo comparar determinadas estatísticas entre jogadores.

## Level e XP

Os jogadores possuem um sistema próprio de **progressão por experiência**.

Participar das partidas e realizar determinadas ações permite acumular XP e aumentar o nível da conta, mantendo essa progressão salva entre sessões.

Esse sistema é integrado às demais estatísticas persistentes do jogador.

## Lobby

Antes das partidas, os jogadores possuem acesso a um lobby que concentra diferentes sistemas de preparação e personalização.

O lobby inclui:

* **Customização do personagem**
* **Customização de clube/time**
* **Seleção e gerenciamento de elementos cosméticos**
* **Loja**
* **Sistema de moeda persistente**
* **Sistema de emotes**
* **Preparação para entrada nas partidas**

As customizações e compras relevantes podem ser mantidas através do sistema de persistência do jogo.

## Loja e Economia

O projeto possui um sistema próprio de **economia**, com moeda vinculada à conta do jogador e armazenada utilizando DataStore.

Essa moeda pode ser utilizada dentro do sistema de loja para aquisição de conteúdos e customizações disponíveis no jogo.

## Cutscenes e Comemorações

Os gols possuem uma camada adicional de apresentação através de **cutscenes e câmeras de comemoração**.

Após determinadas jogadas, o sistema pode destacar o jogador responsável pelo gol e alterar temporariamente a apresentação da partida para criar uma comemoração mais próxima de jogos tradicionais de futebol.

Também foram desenvolvidos sistemas de apresentação de jogadores de destaque e **MVPs**.

## Suporte Mobile

O jogo foi desenvolvido considerando também jogadores de dispositivos móveis.

As principais ações possuem suporte a **controles mobile**, permitindo que as mecânicas de futebol sejam utilizadas tanto em computadores quanto em smartphones e tablets compatíveis com Roblox.

## Principais Sistemas

Em conjunto, o projeto envolve desenvolvimento e integração de:

* Gameplay de futebol multiplayer
* Arquitetura cliente-servidor
* Sistema de partidas
* Gerenciamento de equipes e posições
* Inteligência artificial
* DataStore e persistência
* Rankings
* Level e XP
* Estatísticas de carreira
* Economia e loja
* Customização de personagem
* Customização de clubes
* Emotes
* HUD e interfaces
* Animações
* Efeitos visuais
* Câmeras e cutscenes
* Suporte mobile

O **Ultimate Fantasy Soccer** é um dos meus projetos mais extensos no Roblox e representa a combinação de diversos sistemas independentes em uma única experiência multiplayer, envolvendo desde mecânicas de baixo nível da partida até persistência, progressão, IA e apresentação do jogo.
