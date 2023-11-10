---
Ability1: Innards Out
Ability2: ''
BookSprite: SRD-pyukumuku-BookSprite.png
BoxSprite: SRD-pyukumuku-BoxSprite.png
DexCategory: Sea Cucumber Pokemon
DexDescription: "Once this Pokemon finds a spot it likes it will remain there without\
  \ moving, even if food is out of reach. It can expel its organs through its mouth\
  \ and use them like an arm. It\u2019s slimy and not many people like it."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Unaware
HomeSprite: SRD-pyukumuku-HomeSprite.png
Image: pyukumuku.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Purify|Purify]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bestow|Bestow]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
Number: 771
ShuffleToken: SRD-pyukumuku-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 1.2
  Pounds: 2.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pyukumuku-BookSprite.png|wsmall]]
> ![[SRD-pyukumuku-HomeSprite.png]]
> ![[SRD-pyukumuku-BoxSprite.png|htiny]]
> ![[SRD-pyukumuku-ShuffleToken.png|wsmall]]


*Sea Cucumber Pokemon*
*Once this Pokemon finds a spot it likes it will remain there without moving, even if food is out of reach. It can expel its organs through its mouth and use them like an arm. It’s slimy and not many people like it.*

**DexID**:: 0771
**Name**:: Pyukumuku
**Type**:: Water
**Abilities**:: [[SRD-Innards Out|Innards Out]] ([[SRD-Unaware|Unaware]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::1) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.6lbs / 1.2kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pyukumuku.md"
flatten moves as T
where file.path = this.file.path
```
