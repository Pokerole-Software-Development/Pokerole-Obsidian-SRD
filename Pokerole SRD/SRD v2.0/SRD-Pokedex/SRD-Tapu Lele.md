---
Ability1: Psychic Surge
Ability2: ''
BookSprite: SRD-tapu-lele-BookSprite.png
BoxSprite: SRD-tapu-lele-BoxSprite.png
DexCategory: No Data
DexDescription: It is said that an innocent but cruel spirit guards Akala island.
  When the spirit is feeling benevolent it scatters some of its scales around, these
  scales have healing powers.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Telepathy
HomeSprite: SRD-tapu-lele-HomeSprite.png
Image: tapu-lele.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - Master
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Master
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Psywave|Psywave]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Master
  - '[[SRD-Psyshock|Psyshock]]'
- - Master
  - '[[SRD-Tickle|Tickle]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Flatter|Flatter]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Magic Room|Magic Room]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
Number: 786
ShuffleToken: SRD-tapu-lele-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 18.6
  Pounds: 41.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tapu-lele-BookSprite.png|wsmall]]
> ![[SRD-tapu-lele-HomeSprite.png]]
> ![[SRD-tapu-lele-BoxSprite.png|htiny]]
> ![[SRD-tapu-lele-ShuffleToken.png|wsmall]]


*No Data*
*It is said that an innocent but cruel spirit guards Akala island. When the spirit is feeling benevolent it scatters some of its scales around, these scales have healing powers.*

**DexID**:: 0786
**Name**:: Tapu Lele
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Psychic Surge|Psychic Surge]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 41.0lbs / 18.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tapu Lele.md"
flatten moves as T
where file.path = this.file.path
```
