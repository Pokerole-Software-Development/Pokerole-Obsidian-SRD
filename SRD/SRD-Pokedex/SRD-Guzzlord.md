---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-guzzlord-BookSprite.png
BoxSprite: SRD-guzzlord-BoxSprite.png
DexCategory: 'Aether Foundation Log #074'
DexDescription: One disaster after another. This time we lost an entire facility,
  UB-05 is a monster, there is no other way to call it, it swallowed documents, vehicles
  and even an entire building, there is no end to its hunger.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 18.0
  Meters: 5.5
HiddenAbility: ''
HomeSprite: SRD-guzzlord-HomeSprite.png
Image: guzzlord.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Belch|Belch]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Swallow|Swallow]]'
- - Master
  - '[[SRD-Stockpile|Stockpile]]'
- - Master
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Master
  - '[[SRD-Steamroller|Steamroller]]'
- - Master
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Master
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Thrash|Thrash]]'
- - Master
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Master
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Master
  - '[[SRD-Wring Out|Wring Out]]'
- - Master
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 799
ShuffleToken: SRD-guzzlord-ShuffleToken.png
Type1: Dark
Type2: Dragon
Weight:
  Kilograms: 888.0
  Pounds: 1957.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-guzzlord-BookSprite.png|wsmall]]
> ![[SRD-guzzlord-HomeSprite.png]]
> ![[SRD-guzzlord-BoxSprite.png|htiny]]
> ![[SRD-guzzlord-ShuffleToken.png|wsmall]]


*Aether Foundation Log #074*
*One disaster after another. This time we lost an entire facility, UB-05 is a monster, there is no other way to call it, it swallowed documents, vehicles and even an entire building, there is no end to its hunger.*

**DexID**:: 0799
**Name**:: Guzzlord
**Type**:: Dark / Dragon
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 11

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::4)/(MaxInsight::4)     |

**Height**: 18'0" / 5.5m
**Weight**: 1957.7lbs / 888.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Guzzlord.md"
flatten moves as T
where file.path = this.file.path
```
