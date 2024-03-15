# What Could Go Wrong - AV Edition

This repository hosts the files used for the What Could Go Wrong? digital card game. Nikolas Martelaro and Wendy Ju developed and presented the game at a Workshop at AutoUI 2020.

The digital card game can be loaded into and played on PlayingCards.io. Custom cards can be added using the `csv` files for `prompts` and `responses`

## Abstract
While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.

## Game Setup Instructions
1. Download this repository
2. Go to https://playingcards.io/game/standard-deck to start a custom deck
3. Enter the virtual card table
4. Click the `Edit Table` icon in the green toolbard
5. Select `Room Options`
6. Select  `Import From File`
7. Upload `what-could-go-worng-av.pcio`
8. Click `Edit Table` to exit editing mode and go into gameplay mode

## Gameplay Instructions
1. All players draw 5 white cards from their stack 
2. Click the spinner to choose the first player who will be the Card Czar.
3. The Card Czar then pull a black prompt card and reads it to the group.
4. The Card Czar and the players discuss about the content of the black card to make sure everyone understood the subject. If players have different interpretation, the Card Czar can choose the interpretation of the subject for this round. If a player is not informed about the subject, he can tell others, who will explain it to him. 
5. All other players then put 1 white response card face down in their slot.
6. The Card Czar then flips and reads each white card out loud.
7. The Card Czar then picks one of the white cards to further discuss. +1 point goes to the player whose card was chosen.
8. The group then discusses further what else could go wrong based on the chosen card. People can award +1 point anyone who makes a good point in discussion.
9. After the discussion dissipates after a few minutes, the next player becomes the Card Czar and clicks the “Deal” button. Each player then draws a new white card, so that they again have 5 cards in their hand.

### During the game
1. Take notes on ideas that you have not thought about before
2. Some of the cards are causes, others are effects. Don’t worry about what the game designers intended with each card, go where the discussion is best.
3. Some of the cards may be upsetting. (Such as, a person is abused.)
4. It’s fine to take time to have discussion.
5. Try not to get side tracked, though!

### Video Demonstration
[![What could go wrong card game demonstration](https://img.youtube.com/vi/DlqgWnhEqoc/0.jpg)](https://youtu.be/DlqgWnhEqoc)

## Adding new cards
Edit the `prompts.csv` and `responses.csv` to add new cards to the decks. Follow instrcutions for adding new cards here: https://playingcards.io/docs/custom-decks

## Suggested Citation
Nikolas Martelaro and Wendy Ju. 2020. What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles. In *12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications* (*AutomotiveUI '20*). Association for Computing Machinery, New York, NY, USA, 99–101. DOI:https://doi.org/10.1145/3409251.3411734

### Bibtex
@inproceedings{10.1145/3409251.3411734,  
author = {Martelaro, Nikolas and Ju, Wendy},  
title = {What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles},  
year = {2020},  
isbn = {9781450380669},  
publisher = {Association for Computing Machinery},  
address = {New York, NY, USA},  
url = {https://doi.org/10.1145/3409251.3411734},  
doi = {10.1145/3409251.3411734},  
abstract = { While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.},  
booktitle = {12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications},  
pages = {99–101},  
numpages = {3},  
keywords = {game with a purpose, failure modes, autonomous vehicles},  
location = {Virtual Event, DC, USA},  
series = {AutomotiveUI '20}. 
}


