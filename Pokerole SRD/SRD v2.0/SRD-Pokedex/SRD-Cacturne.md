---
Ability1: Sand Veil
Ability2: ''
BookSprite: SRD-cacturne-BookSprite.png
BoxSprite: SRD-cacturne-BoxSprite.png
DexCategory: Scarecrow Pokemon
DexDescription: They only move during the night. If they spot a traveler, Cacturnes
  will stalk them in groups, waiting for the exhausted creatures to sleep before attacking.
  Their insides are actually sand.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cacnea]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Water Absorb
HomeSprite: SRD-cacturne-HomeSprite.png
Image: cacturne.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Spiky Shield|Spiky Shield]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Revenge|Revenge]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Needle Arm|Needle Arm]]'
- - Ace
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 332
ShuffleToken: SRD-cacturne-ShuffleToken.png
Type1: Grass
Type2: Dark
Weight:
  Kilograms: 77.4
  Pounds: 170.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cacturne-BookSprite.png|wsmall]]
> ![[SRD-cacturne-HomeSprite.png]]
> ![[SRD-cacturne-BoxSprite.png|htiny]]
> ![[SRD-cacturne-ShuffleToken.png|wsmall]]


*Scarecrow Pokemon*
*They only move during the night. If they spot a traveler, Cacturnes will stalk them in groups, waiting for the exhausted creatures to sleep before attacking. Their insides are actually sand.*

**DexID**:: 0332
**Name**:: Cacturne
**Type**:: Grass / Dark
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 170.6lbs / 77.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Cacnea]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cacturne.md"
flatten moves as T
where file.path = this.file.path
```
