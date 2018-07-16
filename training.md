# Training Mode

* Character select in training looks similar to the regular character select. Each port selects a character and whether or not they are an CPU

* At least one port must be set to human to start. Allows multiple players to enter as a human

*\* Indicates a toggle option. If multiple are selected, CPU will choose one at random*

## Damage options

#### CPU DMG
| Options | Notes |
| --- | --- |
| 0-999 | |

#### Player DMG
| Options | Notes |
| --- | --- |
| 0-999 | |

#### DMG reset
| Options | Notes |
| --- | --- |
| Never | Only reset CPU DMG upon reset |
| Fixed DMG | Take no DMG from hits |
| On pause | Reset upon pausing |
| Wait | After 30 grounded frames of being out of hitstun/hitlag/grab (or pause) |

## Display options

#### Input display
| Options | Notes |
| --- | --- |
| Off | |
| Current | Shows what inputs are currently being pressed |
| Tracking | Shows a scrolling list of inputs |

#### Character models
| Options | Notes |
| --- | --- |
| On/Off | Show character models |

#### Simple Overlay
| Options | Notes |
| --- | --- |
| On/Off | Overlays for hitboxes, hurtboxes, invincibility, intangibility |

#### State Overlay
| Options | Notes |
| --- | --- |
| On/Off | Overlays for missed l-cancels, stand still, hitstun, actionablability |

#### Advanced Overlay
| Options | Notes |
| --- | --- |
| On/Off | Overlays for ECB and ledge grab boxes |

#### DI Overlay
| Options | Notes |
| --- | --- |
| On/Off | Overlays for DI/SDI/Shield DI |

#### Frame Data Display
| Options | Notes |
| --- | --- |
| Off | |
| Hitstun Frame Counter | Counter that shows when your opponent left hitstun and for how long |
| Sheildstun Frame Counter | Counter that shows you when your opponent left shieldstun and for how long |

When the opponent is not in hitstun/shieldstun, the counter will start counting up (once per frame). While the opponent is in hitstun/shieldstun, the counter will remain fixed. When the opponent leaves hitstun/shieldstun, the counter will reset to 1

## Replays and save states

#### D-pad function
| Options | Notes |
| --- | --- |
| Functions | D-pad directions perform functions |
| Taunt | D-pad performs taunts |

#### Functions
| D-pad directions | Action | Notes |
| --- | --- | --- |
| Up | Record inputs | Game will record player inputs until down on the d-pad is pressed again, for use with some other features. All empty space before the first change in input and after the last change in input will be trimmed. If buttons are being held when you start recording, these will not count toward "untrimmed" frames |
| Down | Replay inputs | CPU will replay the action once |
| Left | Save state | |
| Right | Load state | |

#### Replay start padding minimum
*(Padding randomly selected between min and max)*

| Options | Notes |
| --- | --- |
| 0-60 | The minimum empty frames to add as a padding to replay start |

#### Replay start padding maximum
*(Padding randomly selected between min and max)*

| Options | Notes |
| --- | --- |
| 0-60 | The maximum empty frames to add as a padding to replay start |

## Training Options

#### Game Speed
| Options | Notes |
| --- | --- |
| 100% | |
| 50% | |
| 25% | |
| 10% | |

#### Camera settings
| Options | Notes |
| --- | --- |
| Regular | |
| Fixed | Fixed full-stage camera |
| Zoom in | Zoom in on first human port |

#### Spawn Items
| Options | Notes |
| --- | --- |
| Item | Scrolls through items, clicking spawns |

## CPU Options
#### CPU Neutral Action
| Options | Notes |
| --- | --- |
| Stand | Do nothing. Recover when put off stage and drop quickly from respawn platform to main platform of stage |
| Shield | |
| Crouch | |
| Short hop | |
| Full hop | |
| Dash dance | Fixed, maximum distance |
| Recorded action | Repeating |

## CPU Punish options
#### CPU Action Out of Hitstun/Tech
| *Options\** | Notes |
| --- | --- |
| Nothing | |
| Shield/airdodge | |
| Buffer spotdodge/airdodge down | |
| Buffer roll/airdodge sideways | |
| Jump | |
| Nair/Jab | |
| Recorded Action | |

#### CPU Drift
| *Options\** | Notes |
| --- | --- |
| None | |
| Toward | |
| Away | |

#### CPU DI
| *Options\** | Notes |
| --- | --- |
| None | |
| Eight directions | Toward, toward up, away, away down, etc |
| Perfect survival | |
| Perfect combo | |

#### CPU SDI Direction
| *Options\** | Notes |
| --- | --- |
| None | |
| Eight directions | Toward, toward up, away, away down, etc |

#### CPU SDI Strength
| *Options\** | Notes |
| --- | --- |
| None | |
| One unit | |
| Two units | |
| Perfect SDI | |

#### CPU ASDI
| *Options\** | Notes |
| --- | --- |
| On/Off | Will ASDI in the same direction as SDI |

#### CPU Tech
| *Options\** | Notes |
| --- | --- |
| Tech in place | |
| Tech in | |
| Tech out | |
| Miss Tech | |

#### CPU Action on Missed Tech
| *Options\** | Notes |
| --- | --- |
| Get up attack | |
| Straight getup | |
| Roll in | |
| Roll out | |
| Wait | Chooses a random wait time, then picks another option |

#### SDI Jab Reset Up
| *Options\** | Notes |
| --- | --- |
| On/Off | |

## CPU Shield Options
#### Shield Regeneration
| Options | Notes |
| --- | --- |
| Normal | |
| Always full | No DMG, depletion, or regen |
| Always half | No DMG, depletion, or regen |
| Instant recovery | Upon breaking, dropping shield, getting poked, or acting out of shield, shield regens to full immediately. Depletes and takes DMG |
| No depletion | Shield will take DMG, but does not deplete while held |
| No depletion + Instant recovery | Shield will take DMG, but does not deplete while held + instant recovery |
| Static | Shield will stay at whatever size it is at when set to static. No depletion, DMG, or regen. Can be used in conjunction with no depletion mode to fix to any shield size |

#### Shield Tilt
| Options | Notes |
| --- | --- |
| Neutral | |
| Always exactly toward | |
| 8 Directions | |

#### Act out of shield chance (upon leaving shieldstun)
| Options | Notes |
| --- | --- |
| Never | |
| Always | |
| Prediction | Crudely predicts the number of frames before shield will be hit again |
| 10-90% | |

#### Action out of shield
| *Options\** | Notes |
| --- | --- |
| None | |
| Grab | |
| Roll forward | |
| Roll backward | |
| Spotdodge | |
| Full hop/double jump away | |
| Up special | |
| Up smash | |
| Neutral air | |
| Up air | |
| Fair air | |
| Down air | |
| Back air | |
| Character specific move | Has a pre-recorded input for each character. Shines for spacies, DJ land down smash for Peach, etc |
| Jump, then recorded action |
| Spotdodge, then recorded action | |
| Drop shield, then recorded action | |
| Auto-powershield, then recorded action | Requires auto-power shield to be enabled |

#### CPU Shield DI
| *Options\** | Notes |
| --- | --- |
| None | |
| Toward | |
| Away | |

#### CPU Shield DI Strength
| *Options\** | Notes |
| --- | --- |
| None | |
| One unit | |
| Two units | |
| Perfect shield DI | |

#### CPU Auto-Shield DI
| *Options\** | Notes |
| --- | --- |
| On/Off | Will auto-shield DI in the same direction as shield DI |

#### Auto-power shield
| Options | Notes |
| --- | --- |
| On/Off | Will always power shield, even if shield has been held for many frames |
