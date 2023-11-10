---
Ability1: Prankster
Ability2: ''
BookSprite: SRD-klefki-BookSprite.png
BoxSprite: SRD-klefki-BoxSprite.png
DexCategory: Key Ring Pokemon
DexDescription: It adapted well to live with humans. Klefki jingle the objects they
  collect when they are distressed. People trust them with their keys to vaults and
  safes because they are very careful with their collection.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Magician
HomeSprite: SRD-klefki-HomeSprite.png
Image: klefki.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fairy Lock|Fairy Lock]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Amateur
  - '[[SRD-Foul Play|Foul Play]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
Number: 707
ShuffleToken: SRD-klefki-ShuffleToken.png
Type1: Steel
Type2: Fairy
Weight:
  Kilograms: 3.0
  Pounds: 6.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-klefki-BookSprite.png|wsmall]]
> ![[SRD-klefki-HomeSprite.png]]
> ![[SRD-klefki-BoxSprite.png|htiny]]
> ![[SRD-klefki-ShuffleToken.png|wsmall]]


*Key Ring Pokemon*
*It adapted well to live with humans. Klefki jingle the objects they collect when they are distressed. People trust them with their keys to vaults and safes because they are very careful with their collection.*

**DexID**:: 0707
**Name**:: Klefki
**Type**:: Steel / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] ([[SRD-Magician|Magician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 0'7" / 0.2m
**Weight**: 6.6lbs / 3.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Klefki.md"
flatten moves as T
where file.path = this.file.path
```
