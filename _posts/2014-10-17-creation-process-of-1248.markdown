---
layout: post
title:  "The design of game <1248>"
date:   2014-10-17 17:50:00
categories: exp
---

Of all the games that I designed and developed, the game named <1248> has the largest number of downloads. Even during recent several months when I had been busy with work and stopped publishing new versions of it, the game enjoyed steady increase in the number of users every day.

The inspiration came from the game called <1024!>, which is a variation of the globally famous game <2048>.

The concept of <2048>'s gameplay is so simple that almost every player can understand it at first glance. The aim is also quite clear : to successfully get a 8192 card. It needs each one of 4096, 2048, 1024, 512, 256, 128, 64, 32, 16, 8, 4, 2 card and another 2 card together to win. All of these cards need 13 slots when totally there are only 16 slots on the board, thus making it rather difficult for average players to win.

The game <1024!> varies from <2048> in that there is a blocker in the middle of the board, preventing cards moving through the whole row or column. The extra blocker brings a brand new feeling to the gameplay and makes it more challenging.

When I started creating my own version of <2048> - <1248>, I kept the following things in mind:

- The basic gameplay resembles <2048>.
- Make it easier to win.
- Add a blocker to make it more challenging.
- The player should be able play and chase for more scores for ever as long as he/she wants.
- Enhance user experience by paying attention to details.

I did these modifications to the original design of <2048>:

- Modification #1 : The newly generated card should not always be of the smallest value. The value should go higher in correspondence with the player's score. For instance if the player has already got a '256' card, the newly generated card can be '4' rather than '2' or '1'.
- Modification #2 : If there are still cards of very small value remain on the board, the value of newly generated cards should not rise otherwise the cards of small value will never get merged.
- Modification #3 : There is no so-called "win" for this game. When the player successfully merges two '8192' cards, the card goes back to '2' with an bonus score, rather than generating a '16384' card. In this way we have generated a 'loop' for the player to play for ever till the board is filled with cards that cannot be merged any more.
- Modification #4 : Add an 'Undo' button. (I implemented this feature in the first version of this game, but have been keeping it hidden because this may be the only effective way for monetization, in addition to game ads.)
- Modification #5 : Save board state upon every move, so the player can continue playing at anytime.

Modification #1 and #2 make the game easier, thus average players will feel better when playing this game. Modification #3 makes the game worth playing more than once. And Modification #4 is an enhancement for user experience. Modification #5 makes the game better adapted to mobile users who prefer to use small time slices to play.

Judging from the reviews on AppStore, these modifications are quite welcomed among players.

[Click here to see game <1248> on AppStore.](https://itunes.apple.com/app/id842015054)