---
Ability1: Volt Absorb
Ability2: Static
BookSprite: SRD-arctozolt-BookSprite.png
BoxSprite: SRD-arctozolt-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: This DNA hybrid has a hard time walking around. The bottom part is
  from a Pokemon from an arctic region and the upper lived in warm jungles. Poor thing
  is always shivering and sneezing without control.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: Slush Rush
HomeSprite: SRD-arctozolt-HomeSprite.png
Image: arctozolt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Echoed Voice|Echoed Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pluck|Pluck]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Freeze Dry|Freeze Dry]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slam|Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bolt Beak|Bolt Beak]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icicle Crash|Icicle Crash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hail|Hail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomping Tantrum|Stomping Tantrum]]'
Number: 881
ShuffleToken: SRD-arctozolt-ShuffleToken.png
Type1: Electric
Type2: Ice
Weight:
  Kilograms: 150.0
  Pounds: 330.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arctozolt-BookSprite.png|wsmall]]
> ![[SRD-arctozolt-HomeSprite.png]]
> ![[SRD-arctozolt-BoxSprite.png|htiny]]
> ![[SRD-arctozolt-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*This DNA hybrid has a hard time walking around. The bottom part is from a Pokemon from an arctic region and the upper lived in warm jungles. Poor thing is always shivering and sneezing without control.*

**DexID**:: 0881
**Name**:: Arctozolt
**Type**:: Electric / Ice
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]] / [[SRD-Static|Static]] ([[SRD-Slush Rush|Slush Rush]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'5" / 2.3m
**Weight**: 330.7lbs / 150.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arctozolt.md"
flatten moves as T
where file.path = this.file.path
```
