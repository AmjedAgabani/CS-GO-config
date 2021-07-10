#  CS-GO-config

*Last Updated 20/03/21*
## How to install

Put files in  C:\Program Files (x86)\Steam\userdata\#######\730\local\cfg

## How to use

### serv.cfg -> configured for servers with [PracticeMode (by splewis)](https://github.com/splewis/csgo-practice-mode "PracticeMode (by splewis)") installed

Launch by opening console and typing `exec serv`

Return config to match-ready default config by typin `exec unload` in console.

#### Keybinds

|Key|Function   |
| ------------ | ------------ |
|  INS | say ".bot" (adds bot at location) |
| HOME  | say ".boost" (adds bot to boost player) |
| DEL | say ".nobot" (deletes bot that you are looking at) |
| PGUP | say ".dry" (starts dryrun)  |
| PGDN | say ".noflash" (removes flashes) |
| END | say ".stop" (stops active event) |
| n | say ".throw" (throws last nade) |
| / | say ".ff" (fast forwards server by 20 secs) |
| ALT | `noclip` (toggle noclip) |
------------
### demoview.cfg

Launch by opening console and typing `exec demoview`

#### Keybinds

|Key|Function   |
| ------------ | ------------ |
|  PGDN | Slowmo (Hold to play demo at 50% speed) |
| PGUP  | Fastforward (Hold to play demo at 500% speed) |
| END | Super Fastforward (Hold to play demo at 1500% speed) |
| HOME | Toggle demo pause (Press to pause & play demo) |
| INS | Toggle xray (press to toggle xray) // *Note: MUST TOGGLE OF CASTER XRAY CONTROL* |
| UPARROW | Foward 5 seconds (on 128 tick demo) |
| DOWNARROW | Back 5 seconds (on 128 tick demo) |
------------
### prac.cfg

Launch by opening console whilst in locally hosted server and typing `exec prac`

#### Keybinds

|Key|Function   |
| ------------ | ------------ |
| n | `sv_rethrow_last_grenade` (throws last thrown grenade) |
