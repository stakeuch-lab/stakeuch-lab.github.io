---
layout: default
title: Research Introduction
---

# Research in Game Informatics Lab.
We conduct research in the field of game informatics and engage in game programming. Our work includes creating strong game players for board games such as Shogi and Go, as well as exploring new research themes based on the premise of having strong players. 

Additionally, we are exploring new research topics such as tasks that humans can perform but AI cannot yet accomplish, and the development of game players that surpass human abilities. Fundamentally, our work revolves around the use of AI in games, particularly board games and card games, to discover effective methods for AI utilization. 

Below are the topics handled in our laboratory. 

## Cooperation Among (Board) Game AIs
We are conducting research on how to better utilize multiple players. 

Also see: [Cutting edge Research (Research Introduction in Kochi University of Technology)](https://www.kochi-tech.ac.jp/english/power/research/pioneering-a-new-generation-of-games-focusing-in-on-the-concept-of-diversity-in-artificial-intellige.html)

### Majority Voting
The strategy of allowing multiple players to independently select their moves and then making a decision based on the majority vote of these selections has proven to be an effective method for improving performance.

In contrast to the conventional approach of allocating a single vote to each player, regardless of their skill level, our findings suggest that weighting votes according to factors such as strength may offer a more effective strategy. By incorporating elements beyond strength into the calculation of vote weights, we have demonstrated that weighted voting can enhance performance. 

- Shogo Takeuchi: Weighted Majority Voting with a Heterogeneous System in the Game of Shogi. The 2018 Conference on Technologies and Applications of Artificial Intelligence (TAAI2018), pp. 122--125, Dec. 2018.
  - [Abstract and PDF (IEEE Xplore)](https://ieeexplore.ieee.org/document/10056467)

### Advice from/to Game AI
People can improve their skills through advice, such as finding better moves or avoiding mistakes. Therefore, to improve the performance of game AIs, we focused on advice. The issues to be considered are the definition of advice and mechanism with advice for move selection. 
We propose that “advice” consists of moves selected by an adviser and suggest a mechanism where a player reconsiders theire move when it differs from advice. We performed tournaments among the proposed systems and other methods against a single engine to compare the strength in shogi. We showed the effectiveness of the proposed method from the experimental results and demonstrated that game AIs can improve their strength with advice. In addition, we found that the advice from a weaker game AI is still useful for game AI. 

- Shogo Takeuchi: Advice is useful for game AI: Experiments with alpha-beta search players in Shogi. 16th International Conference (ACG 2019), pp. 1–-10, Aug. 2019.
  - [Abstract and PDF (Springer)](https://link.springer.com/chapter/10.1007%2F978-3-030-65883-0_1)


### Diversity in Game AIs
We are developing methods to measure diversity in game AIs and evaluating their impact on the performance of the diverse game AIs. Groups of game AIs emerge in multiplayer games, majority voting systems, rating systems, and so on. It is thought that the diversity of the group influences the performance of the game AI, however, the measurement of diversity and its effects have not yet been studied. In this project, we will try to develop measurement methods of the diversity in game AIs and methods to generate diverse game AIs.

# For SSP Candidates
## Expected Performance
The successful candidate would be expected to:
- work independently and develop (strong) computer game players
- read related journal and conference papers
- publish research results in international journal papers, and present them at international conferences

## Required Skills and Knowledge
The successful candidate should have the following knowledge and skills:
- Background in computer science
- Strong interest in game informatics
- Programming skill in C++, Java, Python, and similar programming languages
- Ability to communicate and discuss in English
