# The Custom Run

Cheat Engine table for Need for Speed: The Run on PC that rebuilds the campaign around Tier 6. You drive Tier 6 cars from the first stage, every opponent in the game runs Tier 6 performance while keeping the car the story gave it, and the AI is set to Expert. Toggles and dropdowns only, no hotkeys.

Version 1.1. Built on glonce's The Supercar Run Reworked, with systems from _mRally2's The Supercar Run, Master Table and TOD Randomizer.

Nothing is installed into the game folder and nothing on disk is modified. Close Cheat Engine and the game is back to normal. Your save file is not touched either: cars are unlocked by patching the check that compares your driver level against a car's requirement.

## What the master switch does

The top row of the table is `The Custom Run (Tier 6)`. Ticking it turns on everything at once:

Garages, gas stations and the junkyard offer Tier 6 cars only, all unlocked. The 6 timed events use the table's own start and checkpoint seconds, identical on every difficulty. Every opponent record in the game receives Tier 6 performance. AI difficulty is forced to Expert with the difficulty scalar at 0.25. Drafting is turned off for everyone on track, you included.

## How opponents get Tier 6

Opponents keep their original models. A car that has a Tier 6 edition of its own runs it. The rest take the performance of a Tier 6 donor, chosen by brand, engine, chassis or era first, then by pace.

Donors are listed fastest first, so the table doubles as the pace order.

| Donor | bhp | Opponents |
|---|---|---|
| Hennessey Venom GT | 1200 | Cesar DeLeon and his two bodyguards, Eddie Cooke's Mustang, Challenger R/T, Challenger SRT8, Exige Cup 260, GT500 Super Snake |
| Koenigsegg Agera R | 1115 | Ford GT |
| Audi R8 V10 | 992 | Quattro 20V |
| Nissan GT-R SpecV | 957 | Mila Belova, Focus RS, Lancer Evolution X, the other 370Zs, Impreza WRX STI |
| Mazda RX-7 RZ | 956 | MX-5, Supra |
| Porsche 918 RSR | 949 | 911 Carrera S (991), 911 GT2 (993), 911 GT3 RS 4.0 (997) |
| Aston Martin One-77 | 937 | V12 Vantage |
| Lamborghini Murcielago SV | 909 | Gallardo Valentino Balboni |
| Chevrolet Corvette Z06 Carbon LE | 907 | Camaro SS '67, Camaro ZL1, El Camino SS, Mustang Boss 302, Mustang Boss 302 '69, Mustang RTR, Mustang RTR-X, Firebird Formula, Cobra Daytona |
| Pagani Huayra | 898 | Calvin Garret's SLS AMG |
| Lamborghini Aventador | 881 | Miura SV |
| McLaren MP4-12C | 822 | M3 GTS, Evora |
| Nissan Skyline GT-R (R32) | 811 | Nikki Blake, 1M Coupe, M3 Sport Evolution, Megane RS, Scirocco R |
| Nissan Skyline 2000GT-R | 797 | 200SX (S14) |
| Nissan Fairlady 240ZG | 774 | Corolla AE86, Golf GTI Mk1 |

Cars that already have a usable Tier 6 edition are not in that table. They run their own, which the master sets for them, the Sesto Elemento at 787 and the Zonda Cinque at 880 among them. Two Tier 6 cars are not used as a donor for anything: the Bugatti Veyron 16.4 Super Sport at 1183 bhp, because nothing in the opponent roster resembles a quad turbo W16, and the McLaren F1 at 627, because it is the slowest Tier 6 there is.

Five cars have a Tier 6 edition listed in the game files that the game cannot load, so they take a donor like the rest: V12 Vantage, Challenger R/T, Lancer Evolution X, 911 GT2 and GT500 Super Snake. Three of the five crash the game if their own edition is forced on them.

Rivals are matched the same way. Mila takes the GT-R SpecV, the closest Nissan to a 370Z there is, and Nikki the Skyline GT-R R32. Calvin takes the Huayra, which Pagani builds around an AMG V12. Cesar and Eddie take the Venom GT, an American V8 from a tuner whose trade is American V8s. Marcus keeps the One-77's own Signature Edition, so the table writes him nothing it did not already have.

Nikki runs at two speeds and the game decides which. In the one race where both 370Z rivals appear she comes off her own record at 811. Everywhere else she comes off the ordinary 370Z records, which are on the GT-R SpecV, so she runs 957. Put her entry on the GT-R SpecV if you want the two to agree.

Every donor can be changed per opponent, live, in the AI PERFORMANCE section.

## Body kits

Four cars offer their body kits in the Model list alongside their paints. Bugatti Veyron 16.4 Super Sport, Hennessey Venom GT and Koenigsegg Agera R carry Style Pack 1 in eight colours each. The McLaren F1 carries Style Pack 1 and Aero Pack, eight colours each. Forty variants, and none of them costs performance.

No other car offers kits, and that is deliberate. On a car whose Tier 6 is an edition above stock, a kit carries the stock tune instead, which would quietly drop the car to Tier 4 or Tier 5. Those four are Tier 6 at stock, so a kit is free.

Gas stations keep track of your car after a kit change, so MODE 1 goes on offering your own garage set rather than falling back to the whole Tier 6 list.

## Sections

| Section | What it does |
|---|---|
| The Custom Run (Tier 6) | The master switch described above. |
| RACE TIMES | Start and checkpoint seconds for the 6 timed events, editable per checkpoint, plus an optional timer pause. |
| GARAGE CARS | Model and Skin for all 15 story garage slots: the junkyard car, San Francisco (5), Las Vegas (3), Chicago Downtown (3), Uri's car shop (3). The first San Francisco slot is the car you start in. |
| GAS STATION CARS | 22 on/off toggles, or MODE 1, the default, where gas stations offer only your current car's garage set. |
| AI PERFORMANCE | The Tier 6 donor of every opponent in the game, 69 entries in five groups, with a live readout of what you have changed. |
| AI DIFFICULTY | AI Level and Difficulty Scalar. The master sets Expert and 0.25. Applies live. |
| RACE RULES | Disable Nitrous and Disable Drafting, for everyone on track including you. The master ticks Disable Drafting. |
| NIGHT | Night on every level and free roam: no out of bounds reset, no wrong way respawn, no rival getting away. |
| CURRENT CAR (showroom) | Shows which model and skin is on screen in View Cars. |
| CURRENT CAR SKIN | Changes your car's variant. Applies on restart. |

Rows marked "(auto)" are the table's internal machinery. The master ticks them for you.

AI PERFORMANCE is split into RIVALS, five of the six named story rivals in the order you meet them; OPPONENTS on a donor, 39 entries; OPPONENTS already Tier 6, 16 entries the master sets automatically; POLICE, 7 entries; and MOB, 2. Police and mob are left exactly as the game has them and only change if you pick a donor yourself. Every entry also offers Default, which undoes Tier 6 for that one opponent and puts back the performance the game shipped, record by record.

Race time defaults, in seconds granted at the start and at each checkpoint:

| Event | Start | CP1 | CP2 | CP3 | CP4 | CP5 |
|---|---|---|---|---|---|---|
| Altamont Pass | 27 | 21 | 33 | 21 | 21 | |
| Yosemite Approach | 22 | 27 | 22 | 20 | 18 | |
| Desert Valley | 24 | 27 | 27 | 18 | | |
| Independence Pass | 23 | 22 | 24 | 23 | 23 | 20 |
| Buffalo Gap | 40 | 30 | 23 | 24 | 30 | |
| Smoky Mountain | 33 | 22 | 18 | 18 | 26 | |

## Requirements

Need for Speed: The Run on PC, patched to 1.1. The EA App and Steam copies are both 1.1. Cheat Engine 7.3 or newer, from cheatengine.org.

Your antivirus will probably flag Cheat Engine, and may flag the .CT file. That happens to every Cheat Engine table because of how Cheat Engine writes into another program's memory. If you are not comfortable with that, do not use this.

## Use

Launch the game first and let it reach the main menu. Attach Cheat Engine only once the main menu is on screen, not during the intro videos or a loading screen, and open the table after that. Then tick `The Custom Run (Tier 6)`. The game freezes for a few seconds while the table scans memory and rewrites the opponent templates, once per session. Then set up what you want and play.

RACE TIMES, GARAGE CARS, GAS STATION CARS and AI PERFORMANCE need the master on. The rest work on their own.

## If something goes wrong

Nothing happens when you tick the master. Cheat Engine is probably not attached to the game, attached to a stale process from an earlier launch, or attached before the game reached the main menu. Get to the main menu, reattach, and reload the table.

The freeze never ends. Give it 30 seconds. If it is still frozen the AOB scan is failing, which usually means the game is not patch 1.1.

Cheat Engine says it cannot open the process. Run Cheat Engine as administrator.

Opponents are still slow. Check the LIVE READOUT under AI PERFORMANCE for NOT FOUND lines, and check that you ticked the master before the race loaded rather than during it. Set a NOT FOUND dropdown to something else and back again to retry the scan.

The game crashes when the table is ticked. Confirm the game is patch 1.1 and Cheat Engine is 7.3 or newer. Older Cheat Engine versions handle the Lua in this table badly.

## Notes

Do not untick the master mid session. To start over, reload the table.

Pick garage and gas station cars before the screen loads. The game reads its list once.

The gas station list wraps around when you enable fewer cars than the screen has slots. That is intended.

Changing an opponent's donor triggers a memory scan, so the game pauses briefly. Do it between races.

Edits reset to defaults when the table is reloaded.

## Credits

The Supercar Run Reworked by glonce, on which this table is built. All original mods and research by _mRally2 (https://paypal.me/mRally2). Need for Speed: The Run is property of Electronic Arts.
