# Arcade Mode

* Arcade Mode allows players to apply upgrade power-ups to each character

* Each character has three distinct upgrades that may be toggled on and off

## Sheik/Zelda
#### Upgrade A
* Transform is 4 frames long
#### Upgrade B
* Both needles and Din's Fire send toward the player

## Marth
#### Upgrade A
* Tipper forward smash and down air both put opponents into a hitlag-like stun state
* Only players who have not been stunned in the past 60 frames can be stunned
* Stun length is a fixed value for each move
* Stunned players are frozen in space and cannot SDI during stun
* If stunned players are hit again they are not launched immediately (they stay in stun)
* Instead, upon leaving stun, they are sent with the knockback of the most recent move to hit them
* Stunned players cannot be grabbed

## Peach
#### Upgrade A
* Down special can pull any item
* "Use" items will activate immediately upon being pulled (like food & warp stars)
* There is a distribution of likelihood of item pulls, with more powerful items being rarer

## Donkey Kong
#### Upgrade A
* All aerials are active on frame 4

#### Upgrade B
* Aerial down special is now a slow command grab that goes directly into cargo throw

#### Upgrade C
* Giant punch fully charges in two winds

## Ice Climbers
#### Upgrade A
* 3 of them.

## Young Link
#### Upgrade A
* Down air comes out faster
* Down air bounce is interruptible with any action
* Down air knockback growth massively reduced

## Link
#### Upgrade A
* Arrow charge can be stored like any other charge projectile

## Captain Falcon
#### Upgrade A
* Both hard and soft knee give CF his double jump back

#### Upgrade B
* All moves other than up air aerials are interruptible with jump after hitting

## Ness
#### Upgrade A
* If Ness holds down special for 3 seconds, he will drop a trap hitbox

#### Upgrade B
* Neutral special is completely maneuverable, can be slowly drifted in every direction without gravity
* After a short startup animation, the projectile is released and Ness becomes fully actionable. Ness can move, perform normal attacks, shield, and grab, all while the projectile is out and being steered
* The projectile will burst upon releasing the B button with 8 frames of lag
* If Ness gets hit before releasing the B button, the projectile will fizzle without bursting

## Bowser
#### Upgrade A
* As Bowser deals damage or is damaged, he builds rage. Taking damage builds at half the rate of the damage taken, while dealing damage builds at a rate equal to the damage taken.
* Once rage is at 80, it is considered to be full. This will be shown by a visual fire effect.
* Rage carries between stocks
* Down special replaced with Koopa Rage, which can only be used when rage is full.
  * Creates a large explosion that drains rage to zero, and Bowser gain 5 seconds of the following effects
    * Projectile invincibility
    * Fire effects on all moves
    * Subtractive armor, slightly stronger than Yoshi's
    * 1.5 damage dealt
    * Increased run speed and weight
    * Neutral special travels much further and knocks down
    * Side special grabs both kill at low percents
