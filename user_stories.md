This is going to be a 2 - 4 player competitive trivia game.

The hook of the game is that all players will start with 500 (?) points and unlike most trivia games, you can't earn points, you can only lose them. Instead of having a winner, this game will have one loser. The idea is to create something fun and humourous by juxstiposing the cynical and almost fatalistic tone of game with the glitzy appearance of a tv game show.

USERS

Users will be able to start a game by selecting the number of players, and entering player names. These names will persist accross pages from the title screen to the screen where the game is actually played.

Each round will scramble the player order. One player will get a question and will be asked if they want to try to answer the question themselves, or if they want to force another player to answer. Once a choice is made, the four possible answers will be displayed. 

If a player chooses to answer the question themself and gets it right, they will be protected from challanges in the next round (or they will perhaps have a 50/50 chance the next time they are asked a question?) but if they get it wrong, they will lose 100 points.

If a player forces another player to answer, the challenged player will lose 100 points if they fail to answer correctly. But if they get it right, the player that forced them to answer loses 200 points.

The first player to loose all of their points is the looser for that game.

DEVELOPERS

The aim for our MVP is to deliver a trivia game in which players select categories and answer trivia questions. This will require the following object constructors...

Player {
  name: string,
  score: number,
  protection: boolean
}

Category {
  title: string,
  questions: array,
}

Question {
  question: string,
  answers: array,
  asked: boolean,
}

We want to have at least five categories with ten questions each. Stretch goals will be all about adding as many questions as we can.