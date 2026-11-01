# 🇫🇷 8-0 Paris-Nice Draft — Can You Win the Maillot Jaune?

Draft legendary Paris-Nice cyclists across 6 eras and try to win every stage in an 8-stage Paris-Nice ("Course au Soleil"). 84 legends. 6 eras. 8 stages. 1 goal: 8-0.

## The Race

**Paris-Nice** (officially "Paris-Nice, Course au Soleil" — Race to the Sun) is one of cycling's most prestigious stage races, first held in 1933. Each March, the world's best cyclists race from the chill of Paris to the sunshine of the Côte d'Azur over 8 days, crossing some of France's most iconic terrain.

## How to Play

1. **Pick 5 legends** from 6 eras (1933-2026)
2. **Era synergy**: +1.5 OVR per additional rider from the same era
3. **Race 8 stages** (no rest days): ITT + flat + hills + mountain
4. **Goal**: Win every stage → 8-0 (Course au Soleil complete!)

## Dataset (84 legends)

| Era | Years | Key Cyclists |
|-----|-------|--------------|
| 1 | 1933-1959 | Bobet, Coppi, Bartali, Anquetil, Poulidor |
| 2 | 1960-1979 | **Merckx (99)**, Hinault (97), Zoetemelk, Gimondi, Kelly |
| 3 | 1980-1999 | Indurain (95), Pantani (94), Roche, Rominger, Virenque |
| 4 | 2000-2009 | Armstrong, Ullrich, Nibali, Contador (foundation era) |
| 5 | 2010-2019 | Froome (95), Sagan (96), Cancellara, Cavendish |
| 6 | 2020-now | **Pogačar (99)**, Vingegaard (97), Evenepoel (96), van der Poel (96), van Aert (95) |

## Position System

5 cyclist archetypes:
- **GC**: General Classification / all-rounder
- **CLIM**: Climbing specialist (mountain stages)
- **HILL**: Punchy / classics specialist (hilly stages)
- **SPR**: Sprinter (flat stages)
- **TT**: Time trial specialist (ITT stages)

## Difficulty Curve (Monte Carlo 200 sims)

| OVR | Avg Wins/8 | Perfect 8-0 | Experience |
|-----|------------|-------------|------------|
| 70-90 | 0 | 0% | Struggling backmarker |
| 93 | 0.32 | 0% | Top-10 contender |
| 95 | 1.27 | 0% | Race winner |
| 97 | 3.22 | 0% | Multi-stage star |
| 99 | 4.63 | 0.5% | ELITE (Merckx/Pogačar) |

## Tech

- Single HTML file (38KB), no dependencies, no build
- Vanilla JS + CSS3
- Position × Stage-type matrix (subtle bonuses)
- Era synergy system
- 21-1 GC points
- Maillot Jaune as leader's jersey (Paris-Nice also wears yellow!)

## Color Theme

- 🇫🇷 French Tricolore: blue + white + red accents
- Yellow Maillot Jaune (leader's jersey)
- Alpine mountain gradient background

## Cross-link Matrix (16 → 17 X-0 Sports Drafts)

| # | Variant | URL |
|---|---------|-----|
| 1 | NFL 38-0 🏈 | https://github.com/TeapoyY/squad-draft-football |
| 2 | NASCAR Cup 36-0 | https://github.com/TeapoyY/nascar-36-draft |
| 3 | Tour de France 21-0 🚴 | https://github.com/TeapoyY/tour-de-france-21-draft |
| 4 | Tour de Suisse 8-0 🇨🇭 | https://github.com/TeapoyY/tour-de-suisse-8-draft |
| 5 | Crit. du Dauphiné 8-0 🇫🇷 | https://github.com/TeapoyY/criterium-du-dauphine-8-draft |
| 6 | Vuelta a España 21-0 🔴 | https://github.com/TeapoyY/vuelta-21-draft |
| 7 | IndyCar 17-0 🏎&#xfe0f; | https://github.com/TeapoyY/indycar-17-draft |
| 8 | Formula E 17-0 ⚡ | https://github.com/TeapoyY/formulae-17-draft |
| 9 | MotoGP 20-0 🏍&#xfe0f; | https://github.com/TeapoyY/motogp-20-draft |
| 10 | Endurance 24-0 🏁 | https://github.com/TeapoyY/endurance-24-draft |
| 11 | WRC 13-0 🏔&#xfe0f; | https://github.com/TeapoyY/wrc-13-draft |
| 12 | Giro d'Italia 23-0 🌹 | https://github.com/TeapoyY/giro-23-draft |
| 13 | NASCAR Truck 24-0 | https://github.com/TeapoyY/nascar-truck-24-draft |
| 14 | Cycling Monuments 5-0 🏆 | https://github.com/TeapoyY/monuments-5-draft |
| 15 | Tirreno-Adriatico 7-0 🇮🇹 | https://github.com/TeapoyY/tirreno-adriatico-7-draft |
| 16 | Paris-Nice 8-0 🇫🇷 | (this repo) |

## Credits

Forked from Critérium du Dauphiné 8-0 (9/10). Same architecture, French stage-race tradition. 🇫🇷

## License

MIT
