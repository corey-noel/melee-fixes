## Ice Climbers
## WIP I guess

* AI
    * AI can pivot/dashdance, removing dash dance desynchs but improving movement
    * AI will always prioritize dashing back to partner when desynched and not under the sphere of influence. Will never choose to attack or taunt. If partner is unreachable (offstage), they will wait for them to get back at their current location
    * AI will use squall hammer to recover when alone
    * Will always DI in and up at 45 degrees
    * Upon getting a grab, will always pummel once and then throw
    * Will always throw toward an edge if near one, up if not near an edge
    * Will always miss tech, then regular getup as soon as possible
    * Will always immediately regular get up from edge if not synced
    * Cannot be controlled while either climber is grabbed, in hitstun, in hitlag, buried, stunned, asleep, or shield broken
* Spawning airborne will not cause the follower climber to become detached
* Both climbers can grab the edge at once
* As a note, Ice Climbers can no longer wobble due to the fact that hitstun does not prevent players from mashing out of grabs (hitlag still does, however)

### Moves
| Move | Changes | Notes |
| --- | --- | --- |
| Nair | BKB increased <br>Range increased | |
| Up air | Range increased | |
| Forward air | Meteor hitbox can hit grounded opponents | |
| Dash attack | Hitbox comes out sooner and stays out longer | |
| Up special | Solo belay gains slightly more height and can be turned around in the air| Pressing a shield button on an early frame (3-6) will cancel Belay after teleporting the AI to the lead climber <br> The AI will be completely actionable and can be controlled <br>The lead climber will be in lag for the normal duration of the move (just like if you had used solo grounded belay) | |
| Side special | Squall can grab edge much sooner | |
