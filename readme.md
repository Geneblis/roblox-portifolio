# (ENG) Roblox Projects Portfolio

This repository showcases some of the projects and prototypes I
developed in Roblox Studio, with a focus on gameplay systems,
client-server architecture, user interfaces, data persistence,
artificial intelligence, and combat and sports mechanics.

## Fantasy Soccer

A multiplayer soccer project that evolved through dozens of iterations,
reaching **v88**. It was built as a complete match system, featuring
soccer gameplay distributed between client and server, team and position
management, persistent statistics, artificial intelligence, and its own
presentation, animation, and visual-effects layer.

### Developed Systems

-   **Ball possession and control system**, including possession
    tracking, client-server synchronization, and local visual
    representation for more responsive controls.
-   **Chargeable shooting**, with multiple power levels, charging
    animations, visual feedback, and specific handling for stronger
    shots.
-   **Passing, dribbling, tackling, and chipping**, each with its own
    rules, cooldowns, and server communication.
-   **Pass request system**, with animations and visual feedback for
    other players.
-   **Gameplay VFX** for shooting, possession, dribbling, tackling,
    charging, and other actions.
-   **Dynamic ball trail**, enabled according to ball velocity.
-   **Match HUD**, including score, timer, and real-time match
    information.
-   **Goal celebration cameras and cutscenes**, temporarily highlighting
    the player who scored.
-   **Team and position system**, supporting roles such as goalkeeper,
    defender, winger, and striker.
-   **Position slot management**, independently tracking occupied
    positions for each team.
-   **Player- or NPC-controlled goalkeeper**, automatically replacing
    the AI goalkeeper when needed.
-   **State-based goalkeeper AI**, including positioning, alert
    behavior, tackling, diving, recovery, saves, and ball possession.
-   **Complete match flow system**, handling preparation, start, end,
    score, goals, match time, and transitions between areas.
-   **MVP room and presentation system**, showcasing the best-performing
    players after matches.
-   **Match and career statistics**, including goals, assists, tackles,
    saves, and other actions.
-   **Experience and level progression**, rewarding participation and
    performance.
-   **DataStore persistence**, using `UpdateAsync` to save statistics,
    progression, and other player data.
-   **Persistent rankings with OrderedDataStore** for multiple
    competitive statistics.
-   **Persistent currency and economy system**, integrated with player
    progression.
-   **Shop system**, allowing persistent currency to be spent on content
    and customization.
-   **Lobby with character and club/team customization**.
-   **Emote system**.
-   **Mobile support**, adapting the main gameplay actions for mobile
    devices.
-   **Gameplay animation system**, integrated with the player's primary
    actions.
-   **Separation between authority and presentation**, keeping important
    game rules on the server while input, HUD, camera, animations, and
    effects are handled by the client.

This is the most extensive project in the collection, combining
real-time gameplay, networking, AI, persistence, progression, UI, and
multiplayer match management.

------------------------------------------------------------------------

## Football Gameplay Prototype

An earlier prototype focused on the fundamental mechanics of a
multiplayer soccer game.

### Developed Systems

-   Ball possession control.
-   Shooting power based on how long the input is held.
-   Passing between players.
-   Dribbling with a temporary protection period against ball steals.
-   Tackling with dedicated range and cooldown rules.
-   Ball chipping using vertical and horizontal impulses.
-   Ball pickup and release system.
-   Physics switching between controlled and free-ball states.
-   Client-server communication through `RemoteEvents`.
-   Server authority over the main gameplay actions.
-   Cooldown system to prevent ability spam.

This prototype served as an experimentation base for several mechanics
that were later expanded in Fantasy Soccer.

------------------------------------------------------------------------

## SPH Gun Testing Field

A testing environment used to develop, integrate, and validate weapon
systems and FPS mechanics.

### Implemented and Tested Systems

-   Configurable weapons through stat modules.
-   Multiple weapon and projectile types.
-   Magazine and reserve ammunition system.
-   Multiple reload models, including magazine reloads and individual
    round insertion.
-   Bolt operation and chambered-ammunition control.
-   Configurable fire rate.
-   Recoil and first-person weapon behavior.
-   Projectile and impact processing.
-   Tracers and firing effects.
-   Shell casing ejection.
-   First- and third-person animations.
-   Weapon switching and dropping.
-   Synchronized reloading.
-   Aiming and weapon movement system.
-   Lasers and visual attachments.
-   Left and right leaning.
-   Crouch and prone stances.
-   Integration between movement, stance, camera, and equipped weapon.
-   Support for melee weapons and other combat tools.

The project works as an experimentation field for more complex FPS
systems, allowing weapon behavior, animations, and synchronization to be
tested independently.

------------------------------------------------------------------------

## Lost Signals Build

A gameplay build that integrates FPS systems into a more complete
environment, using combat systems previously developed and tested.

### Implemented and Integrated Systems

-   Advanced first-person weapon system.
-   Synchronization of shots, sounds, reloads, and weapon movement.
-   Leaning and multiple movement stances.
-   Recoil, aiming, lasers, animations, and bolt operation.
-   Ammunition and magazine management.
-   Interaction with weapons available in the environment through
    prompts.
-   Visual feedback for weapons and interactive objects.
-   Ragdoll system after death.
-   Persistent bodies in the environment.
-   Integration between combat, character, and environment.

The goal of this build was to bring systems previously tested in
isolation into a structure closer to a complete FPS experience.


# (PT-BR) Roblox Projects Portfolio

Este repositório reúne alguns dos projetos e protótipos que desenvolvi no Roblox Studio, com foco em sistemas de gameplay, arquitetura cliente-servidor, interfaces, persistência de dados, inteligência artificial e mecânicas de combate e esporte.

## Fantansy Soccer

Projeto de futebol multiplayer que evoluiu por dezenas de iterações, chegando à **v88**. O projeto foi construído como um sistema completo de partida, com lógica de futebol executada entre cliente e servidor, gerenciamento de posições, estatísticas persistentes e uma camada própria de apresentação e efeitos.

### Sistemas desenvolvidos

* **Sistema de posse e controle de bola**, com identificação do jogador em posse, sincronização cliente-servidor e representação visual local para tornar o controle mais responsivo.
* **Chute carregável**, com diferentes níveis de força, animações de carregamento, feedback visual e tratamento para chutes mais fortes.
* **Passe, drible, tackle e chip**, cada ação com regras, cooldowns e comunicação própria com o servidor.
* **Sistema de pedido de passe**, com animações e feedback visual para os demais jogadores.
* **VFX de gameplay** para chute, posse, drible, tackle, carregamento e outras ações.
* **Trail dinâmico da bola**, ativado de acordo com sua velocidade.
* **HUD de partida**, incluindo placar, relógio e informações atualizadas em tempo real.
* **Câmera de comemoração de gol**, destacando temporariamente o jogador responsável pelo gol.
* **Sistema de equipes e posições**, com funções como goleiro, defensor, pontas e atacante.
* **Controle de vagas por posição**, mantendo separadamente as posições ocupadas em cada equipe.
* **Goleiro controlado por jogador ou NPC**, substituindo automaticamente o goleiro artificial quando necessário.
* **IA de goleiro baseada em estados**, com posicionamento, alerta, tackle, mergulho, recuperação, defesa e posse da bola.
* **Sistema completo de partida**, controlando preparação, início, término, placar, gols e transições entre áreas.
* **Sala e apresentação de MVPs**, exibindo os jogadores de maior destaque após as partidas.
* **Estatísticas por partida**, incluindo gols, assistências e tackles.
* **Progressão por experiência e níveis**, premiando participação e desempenho.
* **Persistência com DataStore**, utilizando `UpdateAsync` para salvar estatísticas de carreira e progressão.
* **Rankings persistentes com OrderedDataStore** para gols, assistências, tackles e nível.
* **Sistema de animações de gameplay**, integrado às principais ações do jogador.
* **Separação entre lógica de autoridade e apresentação**, mantendo regras importantes no servidor enquanto input, HUD, câmera e efeitos são processados pelo cliente.

Este é o projeto mais extenso da coleção e reúne sistemas de gameplay em tempo real, networking, IA, persistência, UI e gerenciamento de partidas multiplayer.

---

## Football Gameplay Prototype

Protótipo anterior focado nas mecânicas fundamentais de um jogo de futebol multiplayer.

### Sistemas desenvolvidos

* Controle de posse da bola.
* Chute com força baseada no tempo em que o botão permanece pressionado.
* Passe entre jogadores.
* Drible com período temporário de proteção contra roubadas de bola.
* Tackle com alcance e cooldown próprios.
* Chip da bola utilizando impulso vertical e horizontal.
* Sistema de pickup e soltura da bola.
* Física alternando entre bola controlada e bola livre.
* Comunicação cliente-servidor através de `RemoteEvents`.
* Servidor responsável pela autoridade das principais ações.
* Sistema de cooldowns para evitar spam de habilidades.

Esse protótipo serviu como base de experimentação para diversas mecânicas posteriormente expandidas no DGG Soccer.

---

## SPH Gun Testing Field

Ambiente de testes utilizado para desenvolver, integrar e validar sistemas de armas e mecânicas de FPS.

### Sistemas implementados e testados

* Armas configuráveis através de módulos de estatísticas.
* Diferentes tipos de armas e projéteis.
* Sistema de munição com carregadores e reserva.
* Múltiplos modelos de recarga, incluindo carregadores e inserção individual de munição.
* Operação de ferrolho e controle de munição na câmara.
* Cadência de tiro configurável.
* Recoil e comportamento da arma em primeira pessoa.
* Processamento de projéteis e impactos.
* Tracers e efeitos de disparo.
* Ejeção de cápsulas.
* Animações em primeira e terceira pessoa.
* Troca e descarte de armas.
* Recarga sincronizada.
* Sistema de mira e movimentação da arma.
* Laser e acessórios visuais.
* Lean para esquerda e direita.
* Posturas como crouch e prone.
* Integração entre movimentação, postura, câmera e arma equipada.
* Suporte a armas corpo a corpo e outras ferramentas de combate.

O projeto funciona como um campo de experimentação para sistemas de FPS mais complexos, permitindo testar comportamento, animação e sincronização das armas isoladamente.

---

## Lost Signals Build

Build de gameplay que integra sistemas de FPS a um ambiente mais completo, utilizando sistemas de combate previamente desenvolvidos e testados.

### Sistemas implementados e integrados

* Sistema avançado de armas em primeira pessoa.
* Sincronização de disparos, sons, recargas e movimentação das armas.
* Lean e diferentes posturas de movimentação.
* Recoil, mira, laser, animações e operação do ferrolho.
* Gerenciamento de munição e carregadores.
* Interação com armas disponíveis no cenário através de prompts.
* Feedback visual para armas e objetos interativos.
* Sistema de ragdoll após a morte.
* Manutenção de corpos no cenário.
* Integração entre combate, personagem e ambiente.

O objetivo da build foi levar sistemas anteriormente testados isoladamente para uma estrutura mais próxima de uma experiência FPS completa.

---
