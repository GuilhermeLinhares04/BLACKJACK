# Blackjack - Jogo em React Native com Expo

Este projeto é um jogo de **Blackjack** desenvolvido em React Native utilizando o Expo. O objetivo é proporcionar uma experiência divertida e simples do clássico jogo de cartas, onde o jogador enfrenta o dealer (banca).

## Sobre o Jogo

O Blackjack, também conhecido como 21, é um dos jogos de cartas mais populares do mundo. O objetivo é somar 21 pontos ou chegar o mais próximo possível desse valor, sem ultrapassá-lo. As cartas de 2 a 10 valem seu valor de face, as cartas J, Q e K valem 10 pontos e o Ás pode valer 1 ou 11 pontos.

### Regras Básicas
- O jogador e o dealer recebem duas cartas no início.
- O jogador pode escolher "Hit" (comprar carta) ou "Stand" (parar).
- Se a soma das cartas do jogador passar de 21, ele perde (estoura).
- Após o jogador parar, o dealer compra cartas até atingir pelo menos 17 pontos.
- Ganha quem tiver a maior pontuação sem ultrapassar 21.

## Como Jogar
1. Instale as dependências:
   ```bash
   npm install
   ```
2. Inicie o app:
   ```bash
   npx expo start
   ```
3. Abra no emulador Android/iOS, Expo Go ou navegador web.
4. Use os botões "Hit" para comprar carta e "Stand" para parar.
5. O resultado da rodada será exibido na tela.

## Tecnologias Utilizadas
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Native Paper](https://callstack.github.io/react-native-paper/)
- [@faker-js/faker](https://fakerjs.dev/) (para nomes aleatórios)

## Estrutura do Projeto
- `app/` - Telas e navegação do app
- `src/gameLogic.js` - Lógica do jogo Blackjack
- `components/` - Componentes reutilizáveis
- `assets/` - Imagens e fontes

## Resetar o Projeto
Se quiser começar do zero, execute:
```bash
npm run reset-project
```
