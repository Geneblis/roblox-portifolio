
<div align="center">

![Banner](https://capsule-render.vercel.app/api?type=waving&height=270&color=0:080b1e,45:4432a8,100:00a2ff&text=ROBLOX%20PORTFOLIO&fontColor=ffffff&fontSize=48&fontAlignY=36&animation=fadeIn&desc=GENEBLIS%20%7C%20GAME%20DEVELOPMENT%20ARCHIVE&descSize=18&descAlignY=57)

### GAMEPLAY SYSTEMS · MULTIPLAYER · AI · COMBAT

**A personal collection of Roblox projects, gameplay systems and experimental prototypes.**

<br>

[![Roblox Studio](https://img.shields.io/badge/ROBLOX_STUDIO-00A2FF?style=for-the-badge&logo=robloxstudio&logoColor=white)](https://create.roblox.com/)
[![Luau](https://img.shields.io/badge/LUAU-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://luau.org/)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-8957E5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Geneblis/roblox-portifolio)

<br>

![Stars](https://img.shields.io/github/stars/Geneblis/roblox-portifolio?style=flat-square&color=00a2ff)
![Last Commit](https://img.shields.io/github/last-commit/Geneblis/roblox-portifolio?style=flat-square&color=8957e5)
![Repository Size](https://img.shields.io/github/repo-size/Geneblis/roblox-portifolio?style=flat-square&color=30c9b0)

<br>

[**ENGLISH**](#english) •
[**PORTUGUÊS**](#portugues) •
[**TECH STACK**](#tech-stack) •
[**AUTHOR**](#author)

</div>

---

<div align="center">

## THE ARCHIVE

### FOUR PROJECTS. MULTIPLE SYSTEMS. YEARS OF EXPERIMENTATION.

| Project | Category | Focus |
|:---|:---:|:---|
| **Fantasy Soccer** | Multiplayer Sports | Networking, AI, progression and match management |
| **Football Gameplay Prototype** | Gameplay Prototype | Ball physics, movement and multiplayer mechanics |
| **SPH Gun Testing Field** | FPS Sandbox | Weapons, ballistics, animation and combat systems |
| **Lost Signals Build** | FPS Gameplay | Integrated combat, character and environment systems |

</div>

---

<a id="english"></a>

# 🇺🇸 ENGLISH

## Overview

This repository showcases projects and prototypes developed in Roblox Studio, focusing on gameplay systems, client-server architecture, user interfaces, data persistence, artificial intelligence, and combat and sports mechanics.

The collection contains both experimental prototypes and larger gameplay builds, documenting the development of independent systems and their integration into more complete experiences.

---

## 01 — Fantasy Soccer

<div align="center">

![Fantasy Soccer](https://img.shields.io/badge/FANTASY_SOCCER-V88-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORY-MULTIPLAYER_SPORTS-8957E5?style=for-the-badge)
![Networking](https://img.shields.io/badge/NETWORKING-CLIENT_SERVER-222222?style=for-the-badge)

**MULTIPLAYER FOOTBALL · ARTIFICIAL INTELLIGENCE · PERSISTENT PROGRESSION**

</div>

Fantasy Soccer is a multiplayer soccer project that evolved through dozens of iterations, reaching **version 88**.

It was developed as a complete match system, featuring soccer gameplay distributed between client and server, team and position management, persistent statistics, artificial intelligence, and its own presentation, animation, and visual-effects layer.

### 1. Ball Control & Core Gameplay

- **Ball possession and control:** Possession tracking, client-server synchronization, and local visual representation for more responsive controls.
- **Chargeable shooting:** Multiple power levels, charging animations, visual feedback, and specific handling for stronger shots.
- **Passing:** Dedicated passing mechanics with their own rules, cooldowns, and server communication.
- **Dribbling:** Individual dribbling mechanics integrated with ball possession and multiplayer gameplay.
- **Tackling:** Ball-stealing mechanics with dedicated rules and server communication.
- **Chipping:** Ball-lifting mechanics integrated with the main gameplay system.
- **Pass requests:** Players can request passes from teammates, with animations and visual feedback visible to other players.
- **Gameplay animations:** Character animations integrated with the player's primary actions.

### 2. Visual Effects & Match Presentation

- **Gameplay VFX:** Visual effects for shooting, possession, dribbling, tackling, charging, and other actions.
- **Dynamic ball trail:** A visual trail activated according to the ball's velocity.
- **Match HUD:** Real-time score, match timer, and other gameplay information.
- **Goal celebration cameras and cutscenes:** Temporary camera sequences highlighting the player who scored.
- **MVP room:** Post-match presentation showcasing the best-performing players.

### 3. Team & Position Management

- **Team management:** Systems responsible for organizing players into teams.
- **Player positions:** Support for goalkeeper, defender, winger, and striker roles.
- **Position slots:** Independent tracking of occupied positions for each team.
- **Goalkeeper replacement:** Support for player- or NPC-controlled goalkeepers, automatically replacing the AI goalkeeper when necessary.

### 4. Goalkeeper Artificial Intelligence

The project includes a state-based goalkeeper AI with multiple gameplay behaviors:

- Automatic positioning.
- Alert behavior.
- Tackling.
- Diving.
- Recovery.
- Ball saves.
- Ball possession.

The system also supports the transition between an AI-controlled goalkeeper and a player-controlled goalkeeper.

### 5. Match Management

A complete match-flow system manages the different stages of multiplayer matches, including:

- Match preparation.
- Match start and end.
- Score and goal tracking.
- Match time.
- Transitions between different areas.
- Post-match MVP presentation.

### 6. Statistics & Player Progression

- **Match and career statistics:** Goals, assists, tackles, saves, and other gameplay actions.
- **Experience system:** Rewards players for participating in matches and performing gameplay actions.
- **Level progression:** Persistent progression based on accumulated experience.
- **DataStore persistence:** Uses `UpdateAsync` to save player statistics, progression, and other player data.
- **Competitive rankings:** Persistent leaderboards using `OrderedDataStore` for multiple competitive statistics.

### 7. Economy & Customization

- Persistent currency and economy system integrated with player progression.
- Shop system allowing persistent currency to be spent on content and customization.
- Lobby with character and club/team customization.
- Player emote system.

### 8. Mobile Support

The project includes mobile support, adapting the main gameplay actions and controls for mobile devices.

### 9. Client-Server Architecture

The game's architecture separates gameplay authority from visual presentation.

**Server responsibilities:**
- Important gameplay rules.
- Match authority.
- Multiplayer synchronization.
- Persistent progression and statistics.

**Client responsibilities:**
- Player input.
- HUD.
- Camera behavior.
- Animations.
- Visual effects.

This separation keeps authoritative game rules on the server while allowing the client to handle presentation and responsive controls.

> Fantasy Soccer is the most extensive project in this collection, combining real-time gameplay, multiplayer networking, artificial intelligence, persistent data, progression, UI, and match management.

---

## 02 — Football Gameplay Prototype

<div align="center">

![Prototype](https://img.shields.io/badge/FOOTBALL-GAMEPLAY_PROTOTYPE-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORY-SPORTS_GAMEPLAY-8957E5?style=for-the-badge)

**BALL PHYSICS · CLIENT-SERVER COMMUNICATION · GAMEPLAY EXPERIMENTATION**

</div>

An earlier prototype focused on the fundamental mechanics of a multiplayer soccer game.

The project served as an experimentation environment for testing ball control, gameplay actions, synchronization, and server authority before these systems were expanded into more complex implementations.

### Developed Systems

- **Ball possession control:** Basic possession and ball-control mechanics.
- **Chargeable shooting:** Shooting power determined by how long the player holds the input.
- **Passing:** Ball passing between players.
- **Dribbling:** Includes a temporary protection period against ball steals.
- **Tackling:** Dedicated range and cooldown rules.
- **Ball chipping:** Uses vertical and horizontal impulses.
- **Ball pickup and release:** Mechanics for acquiring and releasing the ball.
- **Dynamic ball physics:** Switches between controlled and free-ball states.
- **Client-server communication:** Gameplay communication through `RemoteEvents`.
- **Server authority:** The server validates and controls the main gameplay actions.
- **Cooldown management:** Prevents players from repeatedly spamming abilities.

### Purpose

This prototype provided an experimentation base for fundamental multiplayer football mechanics, several of which were subsequently expanded in Fantasy Soccer.

---

## 03 — SPH Gun Testing Field

<div align="center">

![FPS](https://img.shields.io/badge/SPH-GUN_TESTING_FIELD-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORY-FPS_SANDBOX-8957E5?style=for-the-badge)
![Combat](https://img.shields.io/badge/FOCUS-WEAPON_SYSTEMS-222222?style=for-the-badge)

**WEAPON FRAMEWORK · BALLISTICS · ANIMATIONS · MOVEMENT**

</div>

SPH Gun Testing Field is a testing environment used to develop, integrate, and validate weapon systems and first-person shooter mechanics.

The project provides an experimentation field for testing complex FPS systems independently, including weapon behavior, animations, combat mechanics, and synchronization.

### 1. Weapon Configuration

- Configurable weapons through stat modules.
- Multiple weapon types.
- Multiple projectile types.
- Configurable fire rate.
- Support for melee weapons and other combat tools.

### 2. Ammunition & Reloading

- Magazine and reserve ammunition management.
- Multiple reloading models.
- Standard magazine reloads.
- Individual round insertion.
- Bolt operation.
- Chambered-ammunition control.
- Synchronized reloading.

### 3. Shooting & Ballistics

- Recoil and first-person weapon behavior.
- Projectile processing.
- Impact processing.
- Bullet tracers.
- Firing effects.
- Shell casing ejection.

### 4. Weapon Handling & Animations

- First-person animations.
- Third-person animations.
- Weapon switching.
- Weapon dropping.
- Aiming mechanics.
- Weapon movement.
- Lasers and visual attachments.

### 5. Character Movement & Combat Stances

- Left and right leaning.
- Crouch stance.
- Prone stance.
- Integration between character movement, stance, camera, and equipped weapon.

### Purpose

The project functions as a testing field for more complex FPS systems, allowing weapon behavior, animations, and synchronization to be developed and validated independently.

---

## 04 — Lost Signals Build

<div align="center">

![Lost Signals](https://img.shields.io/badge/LOST_SIGNALS-GAMEPLAY_BUILD-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORY-FPS_GAMEPLAY-8957E5?style=for-the-badge)
![Integration](https://img.shields.io/badge/FOCUS-SYSTEM_INTEGRATION-222222?style=for-the-badge)

**FIRST-PERSON COMBAT · CHARACTER SYSTEMS · ENVIRONMENT INTERACTION**

</div>

Lost Signals is a gameplay build that integrates FPS systems into a more complete environment, using combat mechanics previously developed and tested independently.

The project combines weapon handling, player movement, interaction, and character systems into a structure closer to a complete first-person shooter experience.

### 1. Combat & Weapon Systems

- Advanced first-person weapon system.
- Synchronization of shots.
- Sound synchronization.
- Synchronized reloading.
- Weapon-movement synchronization.
- Recoil.
- Aiming.
- Lasers.
- Weapon animations.
- Bolt operation.
- Ammunition and magazine management.

### 2. Character Movement

- Left and right leaning.
- Multiple movement stances.
- Integration between movement and the equipped weapon.

### 3. Environment Interaction

- Interaction with weapons available in the environment through prompts.
- Visual feedback for weapons.
- Visual feedback for interactive objects.

### 4. Death & Ragdoll Systems

- Ragdoll system after death.
- Persistent bodies in the environment.

### 5. System Integration

Integration between combat, character, and environment.

### Purpose

The goal of this build was to bring systems previously tested in isolation into a structure closer to a complete FPS experience.

---

<a id="portugues"></a>

# 🇧🇷 PORTUGUÊS

## Visão geral

Este repositório reúne alguns dos projetos e protótipos que desenvolvi no Roblox Studio, com foco em sistemas de gameplay, arquitetura cliente-servidor, interfaces, persistência de dados, inteligência artificial e mecânicas de combate e esporte.

A coleção reúne desde protótipos experimentais até projetos mais extensos, documentando o desenvolvimento de sistemas independentes e sua integração em experiências mais completas.

---

## 01 — Fantasy Soccer

<div align="center">

![Fantasy Soccer](https://img.shields.io/badge/FANTASY_SOCCER-V88-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORIA-FUTEBOL_MULTIPLAYER-8957E5?style=for-the-badge)
![Networking](https://img.shields.io/badge/NETWORKING-CLIENTE_SERVIDOR-222222?style=for-the-badge)

**FUTEBOL MULTIPLAYER · INTELIGÊNCIA ARTIFICIAL · PROGRESSÃO PERSISTENTE**

</div>

Fantasy Soccer é um projeto de futebol multiplayer que evoluiu por dezenas de iterações, chegando à **versão 88**.

O projeto foi construído como um sistema completo de partida, com lógica de futebol distribuída entre cliente e servidor, gerenciamento de equipes e posições, estatísticas persistentes, inteligência artificial e uma camada própria de apresentação, animações e efeitos visuais.

### 1. Controle de Bola e Gameplay

- **Sistema de posse e controle de bola:** Identificação do jogador em posse, sincronização cliente-servidor e representação visual local para tornar o controle mais responsivo.
- **Chute carregável:** Diferentes níveis de força, animações de carregamento, feedback visual e tratamento específico para chutes mais fortes.
- **Passe:** Mecânica de passe com regras, cooldowns e comunicação própria com o servidor.
- **Drible:** Sistema individual de drible integrado ao controle de bola e ao gameplay multiplayer.
- **Tackle:** Mecânica de roubada de bola com regras específicas e comunicação com o servidor.
- **Chip:** Mecânica para levantar a bola, integrada às principais ações de gameplay.
- **Pedido de passe:** Permite solicitar passes aos companheiros, com animações e feedback visual para os demais jogadores.
- **Sistema de animações:** Animações de gameplay integradas às principais ações do jogador.

### 2. Efeitos Visuais e Apresentação

- **VFX de gameplay:** Efeitos visuais para chute, posse, drible, tackle, carregamento e outras ações.
- **Trail dinâmico da bola:** Ativado conforme a velocidade da bola.
- **HUD de partida:** Placar, relógio e informações atualizadas em tempo real.
- **Câmeras e cutscenes de comemoração:** Destacam temporariamente o jogador responsável pelo gol.
- **Sala de MVPs:** Apresentação pós-partida dos jogadores de maior destaque.

### 3. Gerenciamento de Equipes e Posições

- **Sistema de equipes:** Organização dos jogadores em equipes.
- **Sistema de posições:** Suporte para goleiro, defensor, pontas e atacante.
- **Controle de vagas:** Gerenciamento independente das posições ocupadas em cada equipe.
- **Substituição de goleiro:** Permite utilizar goleiros controlados por jogadores ou NPCs, substituindo automaticamente o goleiro artificial quando necessário.

### 4. Inteligência Artificial do Goleiro

O projeto possui uma IA de goleiro baseada em estados, com diferentes comportamentos:

- Posicionamento automático.
- Estado de alerta.
- Tackle.
- Mergulho.
- Recuperação.
- Defesa.
- Posse da bola.

O sistema também permite a transição entre goleiros controlados pela inteligência artificial e por jogadores.

### 5. Gerenciamento das Partidas

Um sistema completo controla o fluxo das partidas multiplayer, incluindo:

- Preparação da partida.
- Início e término.
- Controle do placar.
- Registro de gols.
- Tempo da partida.
- Transições entre áreas.
- Apresentação dos MVPs ao final da partida.

### 6. Estatísticas e Progressão

- **Estatísticas de partida e carreira:** Gols, assistências, tackles, defesas e outras ações.
- **Sistema de experiência:** Recompensa participação e desempenho.
- **Progressão por níveis:** Evolução persistente baseada na experiência acumulada.
- **Persistência com DataStore:** Utiliza `UpdateAsync` para salvar estatísticas, progressão e outros dados dos jogadores.
- **Rankings persistentes:** Utiliza `OrderedDataStore` para diferentes estatísticas competitivas.

### 7. Economia e Personalização

- Sistema de moeda e economia persistente integrado à progressão dos jogadores.
- Loja que permite utilizar a moeda persistente para adquirir conteúdos e personalizações.
- Lobby com personalização de personagem e clube/equipe.
- Sistema de emotes.

### 8. Suporte para Dispositivos Móveis

O projeto possui suporte para dispositivos móveis, adaptando as principais ações e controles de gameplay para essas plataformas.

### 9. Arquitetura Cliente-Servidor

A arquitetura do jogo separa a autoridade das regras de gameplay da camada de apresentação visual.

**Responsabilidades do servidor:**
- Regras importantes do gameplay.
- Autoridade das partidas.
- Sincronização multiplayer.
- Estatísticas e progressão persistentes.

**Responsabilidades do cliente:**
- Input do jogador.
- HUD.
- Comportamento da câmera.
- Animações.
- Efeitos visuais.

Essa separação mantém as regras importantes sob autoridade do servidor, enquanto o cliente processa a apresentação e oferece controles mais responsivos.

> Fantasy Soccer é o projeto mais extenso da coleção, reunindo gameplay em tempo real, networking multiplayer, inteligência artificial, persistência de dados, progressão, UI e gerenciamento completo de partidas.

---

## 02 — Football Gameplay Prototype

<div align="center">

![Prototype](https://img.shields.io/badge/FOOTBALL-GAMEPLAY_PROTOTYPE-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORIA-PROTOTIPO_DE_FUTEBOL-8957E5?style=for-the-badge)

**FÍSICA DA BOLA · COMUNICAÇÃO CLIENTE-SERVIDOR · EXPERIMENTAÇÃO**

</div>

Protótipo anterior focado nas mecânicas fundamentais de um jogo de futebol multiplayer.

O projeto serviu como ambiente de experimentação para testar controle da bola, ações de gameplay, sincronização e autoridade do servidor antes da expansão dessas mecânicas para implementações mais complexas.

### Sistemas Desenvolvidos

- **Controle de posse da bola:** Mecânicas fundamentais de posse e controle.
- **Chute carregável:** Força determinada pelo tempo em que o jogador mantém o botão pressionado.
- **Passe:** Mecânica de passe entre jogadores.
- **Drible:** Inclui um período temporário de proteção contra roubadas de bola.
- **Tackle:** Regras próprias de alcance e cooldown.
- **Chip:** Utiliza impulsos verticais e horizontais.
- **Pickup e soltura da bola:** Mecânicas para adquirir e liberar a bola.
- **Física dinâmica:** Alternância entre os estados de bola controlada e bola livre.
- **Comunicação cliente-servidor:** Utilização de `RemoteEvents`.
- **Autoridade do servidor:** O servidor é responsável pelas principais ações de gameplay.
- **Sistema de cooldowns:** Impede a utilização excessiva das habilidades.

### Objetivo

Esse protótipo serviu como base de experimentação para diversas mecânicas de futebol multiplayer, posteriormente expandidas no Fantasy Soccer.

---

## 03 — SPH Gun Testing Field

<div align="center">

![FPS](https://img.shields.io/badge/SPH-GUN_TESTING_FIELD-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORIA-FPS_SANDBOX-8957E5?style=for-the-badge)
![Combat](https://img.shields.io/badge/FOCO-SISTEMAS_DE_ARMAS-222222?style=for-the-badge)

**SISTEMAS DE ARMAS · BALÍSTICA · ANIMAÇÕES · MOVIMENTAÇÃO**

</div>

SPH Gun Testing Field é um ambiente de testes utilizado para desenvolver, integrar e validar sistemas de armas e mecânicas de FPS.

O projeto funciona como um campo de experimentação para sistemas de FPS mais complexos, permitindo desenvolver e validar separadamente o comportamento das armas, suas animações, mecânicas de combate e sincronização.

### 1. Configuração de Armas

- Armas configuráveis por meio de módulos de estatísticas.
- Diferentes tipos de armas.
- Diferentes tipos de projéteis.
- Cadência de tiro configurável.
- Suporte a armas corpo a corpo e outras ferramentas de combate.

### 2. Munição e Recarga

- Gerenciamento de munição com carregadores e reserva.
- Múltiplos modelos de recarga.
- Recarga utilizando carregadores.
- Inserção individual de munição.
- Operação de ferrolho.
- Controle de munição na câmara.
- Recarga sincronizada.

### 3. Disparos e Balística

- Recoil e comportamento da arma em primeira pessoa.
- Processamento de projéteis.
- Processamento de impactos.
- Tracers.
- Efeitos de disparo.
- Ejeção de cápsulas.

### 4. Manuseio e Animações

- Animações em primeira pessoa.
- Animações em terceira pessoa.
- Troca de armas.
- Descarte de armas.
- Sistema de mira.
- Movimentação da arma.
- Lasers e acessórios visuais.

### 5. Movimentação e Posturas

- Lean para esquerda e direita.
- Crouch.
- Prone.
- Integração entre movimentação, postura, câmera e arma equipada.

### Objetivo

O projeto funciona como um ambiente de experimentação para sistemas de FPS mais complexos, permitindo testar individualmente comportamento, animações e sincronização das armas.

---

## 04 — Lost Signals Build

<div align="center">

![Lost Signals](https://img.shields.io/badge/LOST_SIGNALS-GAMEPLAY_BUILD-00A2FF?style=for-the-badge)
![Category](https://img.shields.io/badge/CATEGORIA-FPS_GAMEPLAY-8957E5?style=for-the-badge)
![Integration](https://img.shields.io/badge/FOCO-INTEGRACAO_DE_SISTEMAS-222222?style=for-the-badge)

**COMBATE EM PRIMEIRA PESSOA · PERSONAGEM · INTERAÇÃO COM O AMBIENTE**

</div>

Lost Signals é uma build de gameplay que integra sistemas de FPS a um ambiente mais completo, utilizando mecânicas de combate previamente desenvolvidas e testadas de maneira independente.

O projeto combina manuseio de armas, movimentação do jogador, interação e sistemas de personagem em uma estrutura mais próxima de uma experiência completa de tiro em primeira pessoa.

### 1. Sistemas de Combate e Armas

- Sistema avançado de armas em primeira pessoa.
- Sincronização de disparos.
- Sincronização de sons.
- Recargas sincronizadas.
- Sincronização da movimentação das armas.
- Recoil.
- Mira.
- Lasers.
- Animações.
- Operação do ferrolho.
- Gerenciamento de munição e carregadores.

### 2. Movimentação do Personagem

- Lean para esquerda e direita.
- Diferentes posturas de movimentação.
- Integração entre movimentação e arma equipada.

### 3. Interação com o Ambiente

- Interação com armas disponíveis no cenário por meio de prompts.
- Feedback visual para armas.
- Feedback visual para objetos interativos.

### 4. Morte e Ragdoll

- Sistema de ragdoll após a morte.
- Manutenção dos corpos no cenário.

### 5. Integração dos Sistemas

Integração entre combate, personagem e ambiente.

### Objetivo

O objetivo dessa build foi reunir sistemas anteriormente testados de maneira isolada em uma estrutura mais próxima de uma experiência FPS completa.

---

<a id="tech-stack"></a>

# 🛠️ Tech Stack

<div align="center">

### DEVELOPMENT ECOSYSTEM

[![Technologies](https://skillicons.dev/icons?i=lua,git,github&theme=dark)](https://skillicons.dev)

<br>

[![Roblox Studio](https://img.shields.io/badge/ROBLOX_STUDIO-GAME_ENGINE-00A2FF?style=for-the-badge&logo=robloxstudio&logoColor=white)](https://create.roblox.com/)

[![Luau](https://img.shields.io/badge/LUAU-SCRIPTING_LANGUAGE-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://luau.org/)

[![GitHub](https://img.shields.io/badge/GITHUB-PROJECT_ARCHIVE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Geneblis/roblox-portifolio)

<br>

### SYSTEMS & TECHNOLOGIES

![Multiplayer](https://img.shields.io/badge/NETWORKING-CLIENT_SERVER-8957E5?style=flat-square)
![DataStore](https://img.shields.io/badge/PERSISTENCE-DATASTORE-00A2FF?style=flat-square)
![AI](https://img.shields.io/badge/ARTIFICIAL_INTELLIGENCE-STATE_BASED-30C9B0?style=flat-square)
![RemoteEvents](https://img.shields.io/badge/COMMUNICATION-REMOTEEVENTS-8957E5?style=flat-square)

</div>

### Technical Areas

| Area | Technologies and Systems |
|:---|:---|
| **Game Engine** | Roblox Studio |
| **Programming** | Luau |
| **Networking** | Client-server architecture, RemoteEvents |
| **Persistence** | DataStore, OrderedDataStore, UpdateAsync |
| **Artificial Intelligence** | State-based goalkeeper AI |
| **Gameplay** | Football mechanics, FPS systems, weapon handling |
| **Presentation** | HUD, cameras, animations, VFX |
| **Physics** | Ball physics, projectiles, impacts, ragdolls |

---

<a id="author"></a>

# 👤 Author

<div align="center">

### GENEBLIS

<a href="https://github.com/Geneblis">
  <img src="https://github.com/Geneblis.png" width="120" alt="Geneblis" />
</a>

<br><br>

**GAME DEVELOPMENT · GAMEPLAY PROGRAMMING · SYSTEM DESIGN**

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-GENEBLIS-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Geneblis)

[![Portfolio](https://img.shields.io/badge/ROBLOX-PORTFOLIO-00A2FF?style=for-the-badge&logo=robloxstudio&logoColor=white)](https://github.com/Geneblis/roblox-portifolio)

<br>

[**EXPLORE MY REPOSITORIES →**](https://github.com/Geneblis?tab=repositories)

</div>

---

<div align="center">

### THANKS FOR VISITING

**ROBLOX PROJECTS PORTFOLIO**

*A personal archive of gameplay systems, prototypes and game development projects.*

<br>

[![Repository](https://img.shields.io/badge/EXPLORE_THE_REPOSITORY-00A2FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Geneblis/roblox-portifolio)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00a2ff,100:4432a8&height=120&section=footer)

</div>
