![Markdown](https://img.shields.io/badge/Markdown-%23%23302c9b.svg?style=for-the-badge&logo=markdown&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![Versão](https://img.shields.io/badge/Versão-1.0-blue?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)


# GDD Template

Este repositório contém um template completo para um Documento de Design de Jogo (GDD) em português, estruturado em Markdown. Esse template visa fornecer uma base sólida e organizada para que desenvolvedores de jogos possam documentar todos os aspectos importantes do design de seus jogos de maneira detalhada e estruturada.


## Objetivo

O objetivo principal deste repositório é ajudar desenvolvedores de jogos, desde iniciantes até veteranos, a criarem documentos de design bem estruturados e abrangentes. Este template cobre uma ampla gama de tópicos importantes, incluindo mecânicas de jogo, narrativa, design de níveis, arte, áudio, monetização, e muito mais.

## Para quem é destinado

- **Desenvolvedores de Jogos:** Que estão no processo de criar e documentar seus jogos.
- **Estudantes de Game Design:** Que desejam aprender e praticar a criação de GDDs.
- **Equipes de Desenvolvimento:** Que precisam de uma estrutura clara e colaborativa para planejar e documentar o design do jogo.
- **Entusiastas de Jogos:** Que têm interesse em entender melhor o processo de design de jogos.

## Estrutura do Documento

O template é dividido nas seguintes seções principais:
1. **Informações Gerais:** Detalha as informações básicas sobre o jogo, como título, plataforma, gênero e público-alvo.
2. **Mecânicas de Jogo:** Descreve as regras, controles, objetivos, sistema de pontuação, interações, progressão, IA, dinâmicas e economia do jogo.
3. **Narrativa:** Apresenta a história principal, personagens, cenários, missões e diálogos do jogo.
4. **Design de Níveis:** Estrutura, mapas, desafios, fluxo e balanceamento de dificuldade dos níveis.
5. **Arte e Estilo Visual:** Detalha o estilo artístico, personagens, cenários, interface do usuário e paleta de cores.
6. **Áudio:** Descreve a trilha sonora, efeitos sonoros, dublagem e som ambiente.
7. **Progresso e Salvamento:** Explica os sistemas de progressão e salvamento do jogo.
8. **Monetização:** Detalha o modelo de negócio e itens pagos.
9. **Testes e Qualidade:** Plano de testes e coleta de feedback dos jogadores.
10. **Conclusão:** Resume os principais pontos do GDD e os próximos passos no desenvolvimento do jogo.

## Como Utilizar

1. **Clone o Repositório:** `git clone https://github.com/allefrodrigo/gdd-template.git`
2. **Edite o Template:** Abra o arquivo Markdown e preencha cada seção com as informações do seu jogo.
3. **Personalize:** Adapte e adicione seções conforme necessário para atender às necessidades específicas do seu projeto.

Esperamos que este template ajude você a criar jogos incríveis e bem documentados!

# Sumário

1. [Informações Gerais](#1-informações-gerais)

    1.1. [Título do Jogo](#11-título-do-jogo)  
    1.2. [Plataforma](#12-plataforma)  
    1.3. [Gênero](#13-gênero)  
    1.4. [Público-Alvo](#14-público-alvo)  
    1.5. [Visão Geral do Jogo](#15-visão-geral-do-jogo)  

2. [Mecânicas de Jogo](#2-mecânicas-de-jogo)

    2.1. [Regras Básicas](#21-regras-básicas)  
    2.2. [Controles](#22-controles)  
    2.3. [Objetivos e Metas](#23-objetivos-e-metas)  
    2.4. [Sistema de Pontuação](#24-sistema-de-pontuação)  
    2.5. [Mecânicas de Interação](#25-mecânicas-de-interação)  
    2.6. [Sistemas de Progressão e Recompensas](#26-sistemas-de-progressão-e-recompensas)  
    2.7. [Inteligência Artificial (IA)](#27-inteligência-artificial-ia)  
    2.8. [Dinâmicas de Jogo](#28-dinâmicas-de-jogo)  
    2.9. [Economia do Jogo](#29-economia-do-jogo)  

3. [Narrativa](#3-narrativa)

    3.1. [História Principal](#31-história-principal)  
    3.2. [Personagens](#32-personagens)  
    3.3. [Cenários](#33-cenários)  
    3.4. [Missões e Quests](#34-missões-e-quests)  
    3.5. [Roteiro e Diálogos](#35-roteiro-e-diálogos)  

4. [Design de Níveis](#4-design-de-níveis)

    4.1. [Estrutura dos Níveis](#41-estrutura-dos-níveis)  
    4.2. [Mapas e Layouts](#42-mapas-e-layouts)  
    4.3. [Desafios e Puzzles](#43-desafios-e-puzzles)  
    4.4. [Fluxo dos Níveis](#44-fluxo-dos-níveis)  
    4.5. [Balanceamento de Dificuldade](#45-balanceamento-de-dificuldade)  

5. [Arte e Estilo Visual](#5-arte-e-estilo-visual)

    5.1. [Estilo Artístico](#51-estilo-artístico)  
    5.2. [Personagens e Animações](#52-personagens-e-animações)  
    5.3. [Cenários e Ambientes](#53-cenários-e-ambientes)  
    5.4. [Interface do Usuário (UI)](#54-interface-do-usuário-ui)  
    5.5. [Paleta de Cores](#55-paleta-de-cores)  

6. [Áudio](#6-áudio)

    6.1. [Trilha Sonora](#61-trilha-sonora)  
    6.2. [Efeitos Sonoros](#62-efeitos-sonoros)  
    6.3. [Dublagem](#63-dublagem)  
    6.4. [Ambiente Sonoro](#64-ambiente-sonoro)  

7. [Progresso e Salvamento](#7-progresso-e-salvamento)

    7.1. [Sistema de Progressão](#71-sistema-de-progressão)  
    7.2. [Sistema de Salvamento](#72-sistema-de-salvamento)  

8. [Monetização](#8-monetização)

    8.1. [Modelo de Negócio](#81-modelo-de-negócio)  
    8.2. [Itens Pagos](#82-itens-pagos)  

9. [Testes e Qualidade](#9-testes-e-qualidade)

    9.1. [Testes de Jogo](#91-testes-de-jogo)  
    9.2. [Feedback dos Jogadores](#92-feedback-dos-jogadores)  

10. [Conclusão](#10-conclusão)

    10.1. [Sumário](#101-sumário)  
    10.2. [Próximos Passos](#102-próximos-passos)  

## 1. Informações Gerais

### 1.1. Título do Jogo
*[Dica: Escolha um título que capture a essência do jogo.]*
- **Título:** 

### 1.2. Plataforma
*[Dica: Especifique todas as plataformas onde o jogo estará disponível (PC, console, mobile).]*

### 1.3. Gênero
*[Dica: Defina o gênero do jogo (ex: RPG, FPS, Puzzle).]*

### 1.4. Público-Alvo
*[Dica: Descreva o público-alvo do jogo (faixa etária, interesses, etc.).]*

### 1.5. Visão Geral do Jogo
*[Dica: Forneça uma breve descrição do jogo, destacando os principais elementos de gameplay e história.]*
- **Descrição:**

## 2. Mecânicas de Jogo

### 2.1. Regras Básicas
*[Dica: Explique as regras fundamentais do jogo.]*
- **Regras:**

### 2.2. Controles
*[Dica: Descreva os controles básicos para cada plataforma.]*
- **Controles:**

### 2.3. Objetivos e Metas
*[Dica: Defina os principais objetivos e metas que o jogador deve alcançar.]*
- **Objetivos:**

### 2.4. Sistema de Pontuação
*[Dica: Descreva como os pontos são atribuídos e quais são os critérios de pontuação.]*
- **Pontuação:**

### 2.5. Mecânicas de Interação
*[Dica: Detalhe como os jogadores interagem com o ambiente e outros personagens.]*
- **Interação:**

### 2.6. Sistemas de Progressão e Recompensas
*[Dica: Explique como o jogador progride no jogo e quais são as recompensas.]*
- **Progressão:**
- **Recompensas:**

### 2.7. Inteligência Artificial (IA)
*[Dica: Descreva o comportamento da IA e como ela interage com o jogador.]*
- **IA:**

### 2.8. Dinâmicas de Jogo
*[Dica: Detalhe as dinâmicas de jogo que emergem das mecânicas.]*
- **Dinâmicas:**

### 2.9. Economia do Jogo
*[Dica: Explique como a economia do jogo funciona, incluindo moedas, recursos, e sistema de comércio.]*
- **Economia:**

## 3. Narrativa

### 3.1. História Principal
*[Dica: Apresente um resumo da história principal do jogo.]*
- **Resumo:**

### 3.2. Personagens
*[Dica: Liste e descreva os personagens principais e suas características.]*
- **Personagens:**

### 3.3. Cenários
*[Dica: Descreva os principais cenários e ambientes do jogo.]*
- **Cenários:**

### 3.4. Missões e Quests
*[Dica: Detalhe as principais missões e quests do jogo, incluindo objetivos e recompensas.]*
- **Missões:**

### 3.5. Roteiro e Diálogos
*[Dica: Inclua trechos de diálogos importantes e o roteiro geral do jogo.]*
- **Diálogos:**

## 4. Design de Níveis

### 4.1. Estrutura dos Níveis
*[Dica: Explique a estrutura e progressão dos níveis.]*
- **Estrutura:**

### 4.2. Mapas e Layouts
*[Dica: Inclua esboços ou descrições dos mapas e layouts dos níveis.]*
- **Mapas:**

### 4.3. Desafios e Puzzles
*[Dica: Detalhe os principais desafios e puzzles que o jogador encontrará.]*
- **Desafios:**

### 4.4. Fluxo dos Níveis
*[Dica: Descreva o fluxo e ritmo dos níveis, como os jogadores avançam de um nível para outro.]*
- **Fluxo:**

### 4.5. Balanceamento de Dificuldade
*[Dica: Explique como a dificuldade dos níveis será balanceada.]*
- **Dificuldade:**

## 5. Arte e Estilo Visual

### 5.1. Estilo Artístico
*[Dica: Descreva o estilo artístico geral do jogo (ex: pixel art, 3D realista).]*
- **Estilo:**

### 5.2. Personagens e Animações
*[Dica: Inclua detalhes sobre a arte e animações dos personagens.]*
- **Arte dos Personagens:**

### 5.3. Cenários e Ambientes
*[Dica: Descreva a arte dos cenários e ambientes.]*
- **Arte dos Cenários:**

### 5.4. Interface do Usuário (UI)
*[Dica: Detalhe o design da interface do usuário, incluindo menus e HUD.]*
- **Interface:**

### 5.5. Paleta de Cores
*[Dica: Especifique a paleta de cores a ser usada no jogo.]*
- **Paleta de Cores:**

## 6. Áudio

### 6.1. Trilha Sonora
*[Dica: Descreva o estilo e os principais temas da trilha sonora.]*
- **Trilha Sonora:**

### 6.2. Efeitos Sonoros
*[Dica: Liste os principais efeitos sonoros e seu propósito no jogo.]*
- **Efeitos Sonoros:**

### 6.3. Dublagem
*[Dica: Inclua detalhes sobre a dublagem dos personagens, se aplicável.]*
- **Dublagem:**

### 6.4. Ambiente Sonoro
*[Dica: Explique como o som ambiente será utilizado para criar imersão.]*
- **Som Ambiente:**

## 7. Progresso e Salvamento

### 7.1. Sistema de Progressão
*[Dica: Explique como o jogador progride no jogo (níveis, habilidades, etc.).]*
- **Progressão:**

### 7.2. Sistema de Salvamento
*[Dica: Descreva como e quando o jogo salva o progresso do jogador.]*
- **Salvamento:**

## 8. Monetização

### 8.1. Modelo de Negócio
*[Dica: Detalhe o modelo de monetização do jogo (compra única, microtransações, etc.).]*
- **Modelo:**

### 8.2. Itens Pagos
*[Dica: Liste os itens ou conteúdos que estarão disponíveis para compra.]*
- **Itens:**

## 9. Testes e Qualidade

### 9.1. Testes de Jogo
*[Dica: Descreva o plano de testes para garantir a qualidade do jogo.]*
- **Plano de Testes:**

### 9.2. Feedback dos Jogadores
*[Dica: Explique como o feedback dos jogadores será coletado e usado.]*
- **Feedback:**

## 10. Conclusão

### 10.1. Sumário
*[Dica: Resuma os principais pontos do GDD.]*
- **Sumário:**

### 10.2. Próximos Passos
*[Dica: Liste as próximas etapas no desenvolvimento do jogo.]*
- **Próximos Passos:**
