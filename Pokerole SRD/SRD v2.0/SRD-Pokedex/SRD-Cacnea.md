---
Ability1: Sand Veil
Ability2: ''
BookSprite: SRD-cacnea-BookSprite.png
BoxSprite: SRD-cacnea-BoxSprite.png
DexCategory: Cactus Pokemon
DexDescription: They release a strong and sweet aroma to attract prey, if they get
  closer, Cacneas shoot sharp thorns to bring them down. They resemble cactuses and
  hide among them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cacturne]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Water Absorb
HomeSprite: SRD-cacnea-HomeSprite.png
Image: cacnea.png
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
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Acid|Acid]]'
- - Pro
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 331
ShuffleToken: SRD-cacnea-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 51.3
  Pounds: 113.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cacnea-BookSprite.png|wsmall]]
> ![[SRD-cacnea-HomeSprite.png]]
> ![[SRD-cacnea-BoxSprite.png|htiny]]
> ![[SRD-cacnea-ShuffleToken.png|wsmall]]


*Cactus Pokemon*
*They release a strong and sweet aroma to attract prey, if they get closer, Cacneas shoot sharp thorns to bring them down. They resemble cactuses and hide among them.*

**DexID**:: 0331
**Name**:: Cacnea
**Type**:: Grass
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 113.1lbs / 51.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Cacturne]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cacnea.md"
flatten moves as T
where file.path = this.file.path
```
