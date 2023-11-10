---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-nihilego-BookSprite.png
BoxSprite: SRD-nihilego-BoxSprite.png
DexCategory: 'Aether Foundation Log #047'
DexDescription: "We are unable to determine if the creature is sentient or not, it\
  \ adapts its behavior depending on its last host. It hasn\u2019t stopped behaving\
  \ like a little girl since then, it\u2019s both unsettling and fascinating."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-nihilego-HomeSprite.png
Image: nihilego.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Power Split|Power Split]]'
- - Master
  - '[[SRD-Guard Split|Guard Split]]'
- - Master
  - '[[SRD-Tickle|Tickle]]'
- - Master
  - '[[SRD-Acid|Acid]]'
- - Master
  - '[[SRD-Constrict|Constrict]]'
- - Master
  - '[[SRD-Pound|Pound]]'
- - Master
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Master
  - '[[SRD-Psywave|Psywave]]'
- - Master
  - '[[SRD-Headbutt|Headbutt]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Master
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Master
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Head Smash|Head Smash]]'
- - Master
  - '[[SRD-Pain Split|Pain Split]]'
- - Master
  - '[[SRD-Role Play|Role Play]]'
- - Master
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Number: 793
ShuffleToken: SRD-nihilego-ShuffleToken.png
Type1: Rock
Type2: Poison
Weight:
  Kilograms: 55.5
  Pounds: 122.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nihilego-BookSprite.png|wsmall]]
> ![[SRD-nihilego-HomeSprite.png]]
> ![[SRD-nihilego-BoxSprite.png|htiny]]
> ![[SRD-nihilego-ShuffleToken.png|wsmall]]


*Aether Foundation Log #047*
*We are unable to determine if the creature is sentient or not, it adapts its behavior depending on its last host. It hasn’t stopped behaving like a little girl since then, it’s both unsettling and fascinating.*

**DexID**:: 0793
**Name**:: Nihilego
**Type**:: Rock / Poison
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 3'9" / 1.2m
**Weight**: 122.4lbs / 55.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Nihilego.md"
flatten moves as T
where file.path = this.file.path
```
