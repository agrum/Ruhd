# Ruhd

Rules of the card game

## Overview 

Ruhd is a card game. Each card is a square tile where each side has a color and a number. There are 4 different colors and the numbers go from 1 to 4. One at a time, players place a tile from their hand beside an already placed tile on the board. After placing a tile, the player scores points following the rules. The game ends when the deck is empty and each player has played their remaining tiles. The winner is the player who has scored the most points.

## Setup

1. Shuffle the deck
2. Place 3 tiles in an "L" shape on the table, this will be the starting board
3. Give 2 tiles to each player
4. Set the drawing deck face down, the number of tiles in it depends on the number of players
    - 2-4 players: 12 tiles
    - 5+ players: 2 tiles per player
5. Set aside the remaining tiles, they will not be played during this game
6. Select a starting player, however you prefer

## Taking turns

1. Place a tile from your hand beside at least 1 tile on the board
2. Score your points
3. Draw a tile from the deck, if the deck is not empty

## Scoring points

1. One-side rule: If you placed your tile beside no-more than 1 tile on the board, you score 1 point
2. Diff-diff rule: If a side from the tile you placed touches a side of a different color, you score the difference between the 2 facing numbers, the higest number minus the smallest number
3. Same-same rule: If a side from the tile you placed touches a side of the same color and number, you score that number
4. Pattern rule: If you created a pattern of 3 identical colors or numbers in the same axis of the tile you placed against, you score 2 points. Extending an existing pattern doesn't grant points

All the rules are cummulative:
- When placing a tile beside more than 1 tile on the board, each side can trigger the Diff-diff or Same-same rule
- The pattern rule triggers as many times as there were patterns created
- When placing a tile beside more than 1 tile on the board, each side can trigger pattern rule on their own axis 

After scoring, if you drew your new tile, or if the next player already placed their tile, you cannot claim points that you might have forgotten or missed.

Ruhd doesn't come with scoring tokens, so use a pen and paper, or a scoring app.

### Pattern rule

Here are some examples of what triggers the pattern rule, and what doesn't. The highlighted tile is the tile placed by the player.

Below is a single pattern of 4s on the left side being created.

![Pattern1](https://user-images.githubusercontent.com/2688838/224567089-0c6e3348-efb9-4959-8fca-e60d8afda83f.png)

Below is a triple pattern being created. The left side has both 4 and blue triplets, and the right side has a yellow triplet. The patterns alone would grant 6 points.

![Pattern2](https://user-images.githubusercontent.com/2688838/224567079-96817a15-1e79-432a-b085-10e5181a44ba.png)

Below are two patterns. The left side has a blue triplet while the right side has a yellow triplet. The patterns alone would grant 4 points.

![Pattern3](https://user-images.githubusercontent.com/2688838/224567071-0f3b02ce-d76d-4523-94ae-645d8abb8137.png)

Below is an odd example, but valid nonetheless. Because the pattern didn't exist yet, creating the pattern of 5 yellows on the right grants 2 points. A pattern is only considered already existing if at least 3 tiles were connected. 

![Pattern5](https://user-images.githubusercontent.com/2688838/224566532-00f5341c-c7e2-4292-8584-a58ad78a2543.png)

#### Invalid patterns

Below, the blue pattern already existed, placing this tile will not grant any pattern creation points.

![Pattern4](https://user-images.githubusercontent.com/2688838/224567064-7cab0ebd-b125-4fff-88e5-2649c042e747.png)

Below, the tile is placed on the right side of an existing one. When placing a tile on the right or left of an existing tile, only horizontal patterns - pointing left or right - can be counted on that axis. The 3 yellows facing down do not count as a pattern. Similarly, if a tile is placed above or below an existing tile, only vertical patterns - pointing up or down - can be counted on that axis.

![Pattern6](https://user-images.githubusercontent.com/2688838/224571677-5ff43be9-d049-4597-a748-84ed37f64bff.png)


### Scoring example

![Scoring1](https://user-images.githubusercontent.com/2688838/224573145-b95c2367-41f2-4572-ac21-7d37baeed347.png)

1. The one-side rule doesn't apply since the tile is palced against 2 tiles
2. The left side of the placed tile uses the Diff-diff rule, which equates to 2 minus 1, thus 1 point
3. The bottom side of the placed tile uses the Same-same rule, which equates to 3 points because the facing numbers are 3s
4. A pattern of reds facing left is created on the left, granting 2 points
5. A pattern of 1s facing left is also created on the left side, granting 2 more points
5. A pattern of greens facing up is also created on the bottom side, granting 2 more points
The total for this tile placement is 10 points.

## Special thanks
Thanks to my friends who helped iterating the game to what it is now.
