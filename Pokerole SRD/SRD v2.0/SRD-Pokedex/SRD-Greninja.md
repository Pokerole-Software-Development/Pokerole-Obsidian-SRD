---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-greninja-BookSprite.png
BoxSprite: SRD-greninja-BoxSprite.png
DexCategory: Ninja Pokemon
DexDescription: "It appears and vanishes with a ninja\u2019s grace. It toys with its\
  \ enemies using swift movements, then slices them with throwing sharp water stars.\
  \ If it was not properly disciplined, it will never listen any master."
EventAbilities: Battle Bond
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Frogadier]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Protean
HomeSprite: SRD-greninja-HomeSprite.png
Image: greninja.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Water Shuriken|Water Shuriken]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Substitute|Substitute]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Double Team|Double Team]]'
- - Ace
  - '[[SRD-Mat Block|Mat Block]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
Number: 658
ShuffleToken: SRD-greninja-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-greninja-BookSprite.png|wsmall]]
> ![[SRD-greninja-HomeSprite.png]]
> ![[SRD-greninja-BoxSprite.png|htiny]]
> ![[SRD-greninja-ShuffleToken.png|wsmall]]


*Ninja Pokemon*
*It appears and vanishes with a ninja’s grace. It toys with its enemies using swift movements, then slices them with throwing sharp water stars. If it was not properly disciplined, it will never listen any master.*

**DexID**:: 0658
**Name**:: Greninja
**Type**:: Water / Dark
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Protean|Protean]]) <[[SRD-Battle Bond|Battle Bond]]>
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Frogadier]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Greninja.md"
flatten moves as T
where file.path = this.file.path
```
