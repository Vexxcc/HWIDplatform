--[[


Auto-Features:
[+] Anti-Afk



Commands:

.setup [place] - Setup command
Places: admin
coming soon: train, club, bank, and more!

.drop [player] - Starts to drop 10k or below.
.stop [player/all] - Stops dropping.
.block [player] - Starts blocking.
.unblock [player] - Starts unblocking.
.warp [player] - Brings an alt/dropper to the operator.
.reset [player] - Refreshes an alt/droppers character.
.ucdrop on [player] - Hides a dropper/alt.
.ucdrop off [player] - Brings back a dropper/alt from hiding.
.advert on [player] [message] - Starts to advertise a message.
.advert off [player] - Stops advertising.
.freeze [player] - Freezes a player.
.unfreeze [player] - Unfreezes a player.
.airlock [player] - Makes a alt/dropper float.
.gpu [player] - Makes a alt/dropper screen black to reduce GPU power.
.setfps [player] [FPS] - Reduces a alts FPS.

premium commands

]]

getgenv().Prefix = "."
getgenv().Operator = {}
getgenv().Droppers = {}


loadstring(game:HttpGet('https://raw.githubusercontent.com/Vexxcc/altcontrol/main/README.md'))()
