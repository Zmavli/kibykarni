---
title: It's Good Enough -- A Party Game
layout: post
date: 2021-09-22
description: A party game I came up with about being average at being average.
tags: games
---



I had this idea after a friend and I talked about games and competitiveness. The objective of the game is to be the most average person at being average.

## Rules
The game requires at least three players. 

{% marginnote "Variation: Increase or decrease the range." %} Each player presents an integer from 0 to 100. 

{% marginnote "If there are only a few players, then this can be done orally. However, if there are many, then I suggest using small whiteboards to write on which are then held up. Alternatively, use some sort of electronic method." %} All players must present their number at the same time. 

{% marginnote "Variation: Play continues until the total number of points awarded meets a certain threshold." %} The game lasts for at least three rounds. The number of rounds to be played is set before the game starts.

{% marginnote "Variation: Calculate the arithmetic mean of all numbers presented. The player whose number is closest to the mean gets a point. (However, this is too much calculation to do in a non-electronic interface and will ruin the flow.)" %} The player who presents a number that is the median of all numbers presented is awarded a point. If there are an even number of players, then the two players which are closest to the median are awarded a point.

If two or more players present the same number, they are disqualified from that round and cannot score any points. They are also fully ignored in the finding of the median for scoring.

If all players but two present the same number, the two players who are different score one point each.

If all players but one present the same number, the one player who is different scores a point.

If all players present the same number, no one scores any points.

Repeat until the set number of rounds is reached. All points are tabulated. The winner is the player whose number of points is the median among the numbers of points of all players.

{% marginnote "Otherwise, there would be no winner in games with an even number of players." %} Duplicate scores are considered to only be one score for the purposes of finding the median.

## Sample game one

<br>

| Players |     Round 1 | Round 2 |   Round 3 |      Round 4 |    Round 5 |
|:--------|------------:|--------:|----------:|-------------:|-----------:|
| Alice   |          99 |      50 |        73 |           88 |         97 |
| Bob     |           0 |      50 |        22 |           70 |         78 |
| Carol   |          50 |      50 |         6 |           75 |         39 |
| Dave    |          49 |       1 |        25 |           97 |         27 |
| Winner? | Carol, Dave |    Dave | Bob, Dave | Carol, Alice | Carol, Bob |

## Sample scoring one

<br>

| Players | Scores |
|:--------|-------:|
| Alice   |      1 |
| Bob     |      2 |
| Carol   |      3 |
| Dave    |      3 |
| Winner? |   Bob! |

Bob is the winner as Carol and Dave have the same score -- their scores are treated as one number. In $$\{1, 2, 3\}$$, the median is 2.

## Sample game two

<br>

| Players | Round 1 | Round 2 | Round 3 | Round 4 | Round 5 |
|:--------|--------:|--------:|--------:|--------:|--------:|
| Xander  |       4 |      87 |      55 |      23 |      50 |
| Yvonne  |      22 |      83 |      55 |      66 |      50 |
| Zachary |      89 |      59 |       0 |      50 |      50 |
| Winner? |  Yvonne |  Yvonne | Zachary | Zachary |  No one |

## Sample scoring two

<br>

| Players | Scores |
|:--------|-------:|
| Xander  |      0 |
| Yvonne  |      2 |
| Zachary |      2 |
| Winner? |   Tie. |

There is a tie.

## Ties?

{% marginnote "Simpler variation: Continue play one round at a time until the tie is broken."%} In keeping with the theme of medianness, ties are resolved in the following manner. The first and last rounds are ignored in scoring. If this is enough to resolve the tie, then the winner is declared. Otherwise, remove the second and second-to-last rounds and so on until a winner is found. In this case, the scores now become...

| Players | Round 2 | Round 3 | Round 4 |
|:--------|--------:|--------:|--------:|
| Xander  |      87 |      55 |      23 |
| Yvonne  |      83 |      55 |      66 |
| Zachary |      59 |       0 |      50 |
| Winner? |  Yvonne | Zachary | Zachary |

<br>

| Players |   Scores |
|:--------|---------:|
| Xander  |        0 |
| Yvonne  |        1 |
| Zachary |        2 |
| Winner? |  Yvonne! |

## Other variations

Another idea is to have a stack of n cards labeled 1 to n. Each player is given m+1 cards where m is the number of rounds to be played. To present a number, they present the card. All presented cards are discarded at the end of each round.

Yet another is to have players list down as many numbers as there are rounds, and all of them are presented and scored simultaneously. Their first number is their number for the first round, the second for the second, and so forth. This detracts from the excitement of the progressing game. However, in some instances, it becomes mathematically impossible for certain players to win in the middle-to-late stages of the game. This eliminates that sad possibility. This could even be treated as a single round in and of itself, creating even more super fun added layers of delicious median-ny nesting!
