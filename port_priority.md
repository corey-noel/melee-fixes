## Sudden Death

* Sudden death has been modified. Characters will respawn on one stock at 0%, and no bombs will drop. Sudden death has a 3 minute timer

#### Entering sudden death

* Should a stock match go to time, it will not go to sudden death. The winner will be the character with the most stocks and least percentage (excluding decimal percentage)

  * In the case of a tie in percents the game will go to sudden death with all tied characters/teams

* In the case of a teams match, the winning team will be the team with the most stocks between them when all of their stocks are added together/the least percent between them when all of their percents are added together (excluding decimal percentages)

* Should a stock match end with all characters dieing on the same frame, the game will still go to sudden death with all characters who died on the final frame

* Sudden death will nest as many times as is necessary

## Port Priority

#### Grabs

* Higher port characters no longer get an additional frame of hitstun when throwing

* If a character grabs two other characters on the same frame, they will always grab the one nearest to them

  * In the realistically impossible case of a tie, the grab will bounce

* If two characters grab each other on the same frame, the grab will "bounce" and both characters will go into the animation of having their grab release

* Move verbosely:

  * I'll be calling the state that occurs after a character escapes a grab **defensive release** (**D-R**), and the state that occurs after a character *has* their grab escaped **Offensive Release** (**O-R**).

  * When a character X gets a grab, if the character Y they are grabbing is getting a grab on the same frame, that character X will enter O-R

  * When a character Y gets grabbed, if the character X grabbing them is grabbed on the same frame, that character Y will enter D-R

  * If a character Y is grabbed by both X and Z, X and Z will enter O-R facing Y, and Y will enter D-R in the same direction they were already facing, unless the grab handler has them face a different direction

  * If a character would be put into both O-R and D-R by the grab handler, they will be put into O-R

  * Characters will always be turned to face the character they grabbed/are being grabbed by, with facing the character that they grabbed taking priority

  * In all singles cases not involving ICs, this simply means that both characters grabbed each other on the same frame and will enter O-R

| **When X grabs Y, and ...**  | Y no grab | Y grabs X | Y grabs Z |
| --- | --- | --- | --- |
| **Z no grab** | X grabs Y | X and Y in **O-R**, facing each other | X in **O-R** facing Y, Y in **O-R** facing Z, Z in **D-R** facing Y |
| **Z grabs X** | X in **O-R** facing Y, Y in **D-R** facing X, Z in **O-R** facing X | X in **O-R** facing Y, Y and Z in **O-R** facing X | Each character in **O-R** facing the character they grabbed. Also how? |
| **Z grabs Y** | X and Z in **O-R** facing Y, Y in **D-R** facing original direction | X and Z in **O-R** facing Y, Y in **O-R** facing X | X and Y in **O-R** facing Y, Y in **O-R** facing Z |

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
