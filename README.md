# The Custom Run

Cheat Engine table for Need for Speed: The Run (PC) that rebuilds the campaign around Tier 6. You drive Tier 6 hypercars from the first stage, every opponent runs Tier 6 performance while keeping its original model, and the game is locked to its hardest AI settings. Toggles only, no hotkeys.

Built on The Supercar Run Reworked, with systems from _mRally2's The Supercar Run, Master Table and TOD Randomizer.

## What the master switch does

Ticking Tier 6 Custom Run enables everything at once:

- Garages, gas stations and the junkyard offer only Tier 6 cars, all unlocked.
- Custom start and checkpoint times for the 6 timed events, the same on every difficulty.
- Every opponent receives Tier 6 performance, as mapped below.
- AI difficulty is forced to Expert with difficulty scalar 0.
- Drafting is disabled for everyone on track.

## How opponents get Tier 6 performance

Opponents keep their original looks. Cars that exist in Tier 6 run their own Tier 6 edition. The rest receive the performance of a Tier 6 donor, picked by realism first (brand, engine, era), then by performance tier:

| Donor | Opponents |
|---|---|
| Aston Martin One-77 "Marcus" | One-77, V12 Vantage |
| Porsche 918 RSR | 911 Carrera S, 911 GT2 (993), 911 GT3 RS 4.0 |
| Corvette Z06 Carbon LE | Camaro SS '67, Camaro ZL1, El Camino SS, Challenger R/T, Mustang Boss 302 '69, Mustang Boss 302, Mustang RTR, Mustang RTR-X, Firebird Formula |
| Skyline GT-R (R32) | 1M Coupe, M3 Sport Evolution, Focus RS, 370Z, Megane RS, Impreza WRX STI, Scirocco R, Supra |
| Hennessey Venom GT | Exige Cup 260, GT500 Super Snake, the mob's Challenger SRT8s, Cesar's El Caminos |
| Pagani Zonda Cinque | SLS AMG, Calvin Garret's included |
| McLaren MP4-12C | M3 GTS, Evora |
| McLaren F1 | Ford GT, Cobra Daytona |
| Nissan GT-R SpecV | Lancer Evolution X |
| Skyline 2000GT-R | 200SX (S14) |
| Fairlady 240ZG | Corolla AE86, Golf GTI Mk1 |
| Mazda RX-7 RZ | MX-5 |
| Audi R8 V10 | Quattro 20V |
| Murcielago SV | Gallardo Valentino Balboni |
| Aventador | Miura SV |

Every donor can be changed live, per opponent, in the AI PERFORMANCE section.

## Sections

- **Tier 6 Custom Run** - the master switch described above.
- **RACE TIMES** - start and checkpoint seconds for the 6 timed events, editable per checkpoint, plus an optional timer pause. Defaults:

| Event | Start | CP1 | CP2 | CP3 | CP4 | CP5 |
|---|---|---|---|---|---|---|
| Altamont Pass | 28 | 21 | 32 | 21 | 21 | |
| Yosemite Approach | 22 | 27 | 22 | 20 | 18 | |
| Desert Valley | 24 | 27 | 27 | 18 | | |
| Independence Pass | 23 | 22 | 24 | 23 | 23 | 20 |
| Buffalo Gap | 40 | 30 | 23 | 24 | 30 | |
| Smoky Mountain | 35 | 20 | 18 | 18 | 25 | |

- **GARAGE CARS** - Model and Skin for all 15 story garage slots. Car 1 is the pre-selected car.
- **GAS STATION CARS** - 22 on/off toggles, or MODE 1 (default): gas stations offer only your current car's garage set.
- **AI PERFORMANCE** - the Tier 6 donor of each of the 37 opponents, with a live readout of active overrides.
- **AI DIFFICULTY** - AI Level and Difficulty Scalar. The master sets Expert and 0; change them here, applies live.
- **RACE RULES** - Disable Nitrous and Disable Drafting, for everyone on track, player included. The master ticks Disable Drafting.
- **NIGHT** - night on every level, free roam: no out-of-bounds reset, no wrong-way respawn, no rival getting away.
- **CURRENT CAR SKIN** - change your car's variant, applies on restart.
- **CURRENT CAR (showroom)** - shows which car is on screen in View Cars.

## Requirements

- NFS: The Run, PC, patch 1.1
- Cheat Engine 7.3+

## Use

1. Launch the game, open the table in Cheat Engine, attach.
2. Tick **Tier 6 Custom Run**. Once per session, a short freeze is normal.
3. Set up what you want. RACE TIMES, GARAGE CARS, GAS STATION CARS and AI PERFORMANCE need the master on, the rest work on their own.

## Notes

- Don't untick the master mid-session. To start over, reload the table.
- Pick garage cars before the garage loads.
- The gas station list wraps around, by design.
- Edits reset to defaults when the table is reloaded.
- Changing an AI donor causes a short freeze, so do it between races.

## Credits

The Supercar Run Reworked by its author, on which this table is built. All original mods and research by _mRally2 (https://paypal.me/mRally2). Need for Speed: The Run is property of Electronic Arts.
