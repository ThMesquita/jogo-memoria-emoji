# Jogo da Memória com Emojis

Este é um jogo simples de memória onde o jogador deve encontrar pares de emojis correspondentes. As cartas são embaralhadas no início do jogo e o objetivo é clicar nas cartas para descobrir quais emojis estão emparelhados.

## Funcionalidade

- **Embaralhamento Automático**: Os emojis são embaralhados quando o jogo começa.
- **Interação com Cartas**: O jogador pode clicar nas cartas para tentar combinar os pares de emojis.
- **Condição de Vitória**: O jogo termina quando todos os pares de emojis forem encontrados e uma mensagem de vitória é exibida.

## Como Jogar

1. **Objetivo**: O objetivo é encontrar todos os pares de emojis correspondentes.
2. **Regras**:
   - Clique em uma carta para virá-la.
   - Clique em outra carta para virá-la.
   - Se as cartas forem iguais, elas permanecem viradas.
   - Se as cartas não forem iguais, elas são viradas de volta após um breve intervalo.
3. **Vença o Jogo**: O jogo termina quando todos os pares de emojis são encontrados. Uma mensagem "Você venceu!" será exibida.

## Como o Jogo Funciona

### 1. **Embaralhamento de Emojis**
   Os emojis são embaralhados ao iniciar o jogo para garantir uma nova disposição das cartas a cada jogada.

### 2. **Cartas de Emojis**
   O jogo contém 8 tipos de emojis, sendo cada um repetido uma vez, totalizando 16 cartas. Cada carta é gerada dinamicamente e exibida no tabuleiro.

### 3. **Mecânica do Jogo**
   - Ao clicar em uma carta, ela se vira.
   - O jogador pode clicar em uma segunda carta, e se ambas forem iguais, elas ficam viradas.
   - Se as cartas não forem iguais, elas são viradas de volta depois de um breve intervalo.

### 4. **Condição de Vitória**
   O jogo é vencido quando o jogador encontra todos os pares de emojis. Quando isso acontece, uma mensagem "Você venceu!" é exibida.

## Como Jogar no Seu Computador

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no seu navegador para começar a jogar.
3. Divirta-se encontrando os pares de emojis!

## Tecnologias Usadas

- **HTML** para a estrutura do jogo.
- **CSS** para o design e animação das cartas.
- **JavaScript** para a lógica do jogo, embaralhamento dos emojis, e interação com as cartas.
