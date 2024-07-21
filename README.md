# codenames

Simulator for the Codenames board game. Generate clues to get your team to guess the correct words on the board.

## Collecting ideas to see what works.

1. Cosine similarity can be used to measure basic semantic similarity beween words.

   1.1. May work best for words within a category. But produces strange results for words that are not closely related.

2. WordNet relationships can be used to identify categorically or functionally similar words.

   2.1. These relationships can be mapped visually and easily interpreted.

   2.2. Mostly only has synonyms, hypernyms, and hyponyms. Lacking in holonyms and meronyms.

   2.3. WordNet relationships have variable specificity.

   2.4. Could generate new WordNet-like data using a neural network.

## Features that could be implemented.

1. Implement a basic online version of the game.

2. Implement a clue generator, allowing the user to play as the guesser.

3. Implement a prediction model for the guesser, so the user can play as the clue giver.

4. Use an LLM to explain clues and guesses.

5. Use an LLM to generate new WordNet-like relationships, and build a new WordNet graph (doesn't need to handle too many words - maybe 100).

_Inspired by the board game Codenames, by Vlaada Chvátil and [this Medium article](https://towardsdatascience.com/hacking-codenames-with-glove-embeddings-0cf928af0858) by Zhiheng Jian._
