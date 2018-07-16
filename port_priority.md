## Sudden Death

* Sudden death has been modified. Characters will respawn on one stock at 0%, and no bombs will drop. Sudden death has a 2 minute timer

#### Entering sudden death

* Should a stock match go to time, it will not go to sudden death. The winner will be the character with the most stocks.

  * In the case of a tie in number of stocks, the winner will be the character with the least percent (including decimal percentages).

  * In the case of a tie in percents the game will go to sudden death with all tied characters/teams

* In the case of a teams match, the winning team will be the team with the most stocks between them when all of their stocks are added together/the least percent between them when all of their percents are added together (including decimal percentages)

* Should a stock match end with all characters dieing on the same frame, the game will still go to sudden death with all characters who died on the final frame

* Sudden death will nest as many times as is necessary

## Port Priority

#### Grabs

* If two characters grab each other on the same frame, the grab will "bounce" and both characters will go into the animation of having their grab release

  * When a character X gets a grab, if the character Y they are grabbing is getting a grab on the same frame, that character X will enter their animation of having their grab release

  * When a character X gets grabbed, if the character Y grabbing them is grabbed on the same frame, that character X will enter their animation of being released from a grab

  * The animation of a character having their grab released takes priority

  * Characters will always be turned to face the character they grabbed/are being grabbed by, with facing the character that they grabbed taking priority

  * In 99% of cases (including all singles cases) this simply means that both characters grabbed each other on the same frame and will enter the animation of having their grab release

* If a character grabs two other characters on the same frame, they will always grab the one nearest to them

  * In the realistically impossible case of a tie, the grab will bounce

* Higher port characters no longer get an additional frame of hitstun when throwing

#### Ledge Grabs

* If multiple characters grab an edge on the same frame, those characters will gain a full second of invincibility and immediately enter their regular getup

#### Other

* If a character is hit by two attacks on the same frame, knockback will stack via vector addition rather than replacement

* All ports now spawn airborne on the first stock, rather than just ports 3 and 4

* All ports spawn at the same time on the first stock

* On all stages, all ports respawn above the center of the stage

## Neutral starts

* In 1v1's, spawns are on platforms (if they exist) on either side

* In 2v2's, teams spawn around a platform (one on, and one under)

* On FD, teams spawn left and right

* Left/right determined by port

  * Lower port gets leftmost spawn

  * In the case of teams, the team with the player with the lowest port gets the leftmost spawn

  * Within teams, the team member with the lower port gets the leftmost or upper most spawn for that team

* In non-competitive matches (3 players, 4 players (not teams), uneven teams) spawns are just by port
