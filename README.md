# Documentação do Projeto: BlitzStar

## 1. Visão Geral
   **Tecnologia Utilizada:** Python + Pygame + Random  
   **Inspiração:** Space Invaders  
   **Descrição:** *BlitzStar* é uma reconstrução do clássico *Space Invaders*, utilizando *Pygame* para a implementação gráfica e lógica do jogo e *Random* para a aleatoriedade de elementos como movimentação e spawn de inimigos.  
   **Objetivo:** Criar um modelo funcional semelhante ao jogo inspirado com recursos básicos como pontuação, controle da nave e disparo, visando implementações futuras baseadas nas necessidades de melhoria e expansões.
   
## 2. Detalhamento do Projeto

### O que é *BlitzStar*?
*BlitzStar* é um jogo inspirado em *Space Invaders*, onde o jogador controla uma nave e deve derrotar inimigos usando disparos estratégicos. O desafio envolve reflexos rápidos e precisão para atingir os adversários antes que eles alcancem o solo.

### História do jogo
Em um futuro distante, uma frota alienígena ameaça a sobrevivência da humanidade. Como defensor da Terra, você pilota a nave *BlitzStar* e deve repelir os invasores antes que seja tarde demais.

Cada inimigo derrotado representa um pequeno avanço na batalha pela sobrevivência. No entanto, a frota alienígena não recua facilmente. Será que sua nave terá recursos suficientes para resistir ao ataque?

## 2.1 Funcionalidades Principais

### Motor do jogo:
- Geração de inimigos aleatória.
- Movimentação horizontal da nave.
- Sistema de pontuação baseado em acertos.
- Progressão de dificuldade ao longo do jogo.

### Interface gráfica:
- HUD com pontuação.
- Tela inicial, tela de pausa e tela de *game over*.
- Botões de comando para disparo e movimentação.

### Extras:
- Efeitos sonoros de disparo e impacto.
- Música de fundo imersiva.
- *Easter eggs* e bônus ocultos.
## 2.2 Arquitetura do Código
```
blitzstar/
├── main.py # Ponto de entrada (inicialização do jogo)
├── game.py # Lógica principal (estado do jogo, loop do jogo)
├── player.py # Controle da nave do jogador (movimentação, tiros)
├── aliens.py # Definição dos inimigos e padrões de ataque
├── projectiles.py # Gerenciamento de tiros e colisões
├── ui/ # Interface do usuário
│ ├── render.py # Renderização gráfica (Pygame)
│ ├── sounds.py # Sistema de áudios
│ └── hud.py # Exibição de pontuação, vidas e status
```
## 3. Etapas de entrega (Cronograma detalhado) 

### Etapa 1: Lógica do jogo ( Semana 1 a 4 ) 
- Controle da nave (teclado)
- Alternância de menu inicial e outras telas (pausa/game over/final/rodando)
- Compreensão de colisões
- Efeitos sonoros e scores
### Etapa 2: Criação das artes ( Semana 5 a 8) 
- Criação de ambiente, telas (pausa/game over/final/rodando)
- Artes principais (nave, itens, inimigos etc)
- animação de sprites "segretos"
### Etapa 3: Protótipo básico ( Semana 9 a 14 ) 
- Funcionabilidade de layout
- Estruturação legível
### Etapa 4: Testes e Entrega Final ( Semana 15 a 18 ) 
- Testes de usabilidade
- Correção de erros
- Implementação de requisitos faltosos
- Documentação final
## 4. Requisitos técnicos
python==3.13.3 

pygame==2.6.0 

random==3.13.3 
