## Engine Changes

* Based off of version 1.02

* "Tournament Winner" (Jump from edge) made a few frames more interruptible

* All throw directions can be buffered

* Hitting with early hits of a multi hit move will no longer stale the later hits of the same attack

* Phantom hits removed. In a setup that would have caused a move to phantom hit, the attack now regular hits instead

* Hitstun does not prevent mashing out of grabs

* Invisible ceiling removed

* Walljump/walljump tech horizontal movement has been reduced for many characters, especially lighter characters

* Camera KOs made longer to match the length of Star KOs

* All non-item projectiles are now absorbable

* Many non-item wielding characters (not Link, YL, or Peach) have had their item throws redone or buffed

* No hitstun knockback (characters not going into hitstun when hit by vertically launching moves that deal less than 7% during knockdown) removed for moves that hit stronger than the knockdown/tumble threshold. Maintained for moves that hit weaker than this threshold, allowing for jab resets to still be escaped

* Threshold for breaking crouch cancel unchanged, but the amount it reduces hitstun by decreased

* Items being knocked out of hands are no longer random. They will drop guaranteed if the character holding the item has taken 60 DMG since starting to hold it, and will not drop before this

#### Throw SDI

* There is a 3 frame window immediately before a throw releases, during which players can input Throw SDI (TDI), which will translate the release point of the throw

  * Throw SDI cannot be performed with the C stick or ASDI'd, and is read the on the 3 frames before regular DI is read for throws

  * TDI cannot be done down. Only up, to either side, or to any of the intermediate angles

  * Throw SDI has half of the effectiveness of regular SDI

  * A small circular visual indicator has been added to the release point of all throws, which will translate with TDI

    * This has implications for all "small" chaingrabs (not on fast fallers). By implementing TDI Yoshi, Roy, and Pichu players will be able to have a level of influence over Sheik/Ganondorf down throw chaingrabs. It is unlikely that this will completely neuter the possibility of these chaingrabs, but rather make escaping them feasible with good tech and good mixups. Slight translations in release will not allow for escaping of all followups, merely regrabs at certain percents with perfect inputs. Expect to get down throw f tilted or down throw faired even with perfect TDI, but down throw to regrab could possibly be escapable if you win mixups, do research on how to get out at what percents, and execute perfectly

    * Chaingrabs on fastfallers will not be affected as much. TDI to either side will be easy to cover with a dash regrab, while TDI up might possibly need to be covered with an up tilt or up air in some cases.

    * Additionally, it will become possible to mix up the timing of some faster throws to avoid the possibility of Throw SDI entirely

    * This is to avoid the potential unfortunate reality of a meta where characters with excessive amounts of chaingrabs are all relevant and dominant: Sheik, Ganondorf, Plumbers, Pikachu/Pichu, G&W, and others. While their throws will still be punishing, heavy hitting, and allow for many followups, they will not be guaranteed damage from x to y percent into a kill move if the opponent knows how to get out and reads their timing mixups. Very easily chain grabbed characters have some hope of getting out of grabs if they can win interactions during chaingrabs and have good tech.

## Inputs

* Made dashing back one frame more lenient

* C-stick performs smash attacks/aerials/buffered shield options/buffered throws in single player

* Angling inputs for forward smashes can be performed by holding up or down on the control stick and pressing straight forward on the c-stick

* Made shorthops one frame more lenient

* Made L-cancelling 3 frames more lenient

* Made shield dropping more lenient, so as to make it no longer controller dependent

* Input polling issue fixed. Is now tied to processing frames, making inputs feel cleaner and more consistent, especially when playing at slow speeds (such as in training mode)

## Aesthetics

* There is a visual and audio indicator for when a player is mashing out of a grab/sleep/stun/bury/shield break

* A noise plays when an invincible character is attacked

* Tags and other effects become invisible when the player becomes invisible

## Effects

* Characters can now be knocked out of bury by hits that deal more than 16%

* Buried characters do not get invincibility when they leave bury

* Opponents hit with an ice effect move will always be frozen if the knockback exceeds the knockdown threshold and they have not been frozen in the last 100 frames, instead of being dependent on RNG

## Game Options

* Handicap now controls starting stocks/score/coins instead (also useful for crew battles)

* Pause options redone

  * On

  * Off

  * Hold (one second)

##### Default Options

* Rules = Stock

* Stocks = 4

* Time Limit = 4 minutes

* Stock Match Time Limit = 6 minutes

* Friendly Fire = On

* Pause = Hold
