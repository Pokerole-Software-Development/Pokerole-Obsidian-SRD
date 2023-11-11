---
Ability1: Light Metal
Ability2: Heavy Metal
BookSprite: SRD-duraludon-BookSprite.png
BoxSprite: SRD-duraludon-BoxSprite.png
DexCategory: Alloy Pokemon
DexDescription: "Its body resembles a shiny polished metal and it\u2019s both lightweight\
  \ and strong. The only drawback is that it rusts easily. It lives on dry climates\
  \ and deep inside caves because rain and moisture make it cranky."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Stalwart
HomeSprite: SRD-duraludon-HomeSprite.png
Image: duraludon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Breaking Swipe|Breaking Swipe]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Laser Focus|Laser Focus]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Burst|Metal Burst]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Steel Beam|Steel Beam]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Coat|Mirror Coat]]'
Number: 884
ShuffleToken: SRD-duraludon-ShuffleToken.png
Type1: Steel
Type2: Dragon
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-duraludon-BookSprite.png|wsmall]]
> ![[SRD-duraludon-HomeSprite.png]]
> ![[SRD-duraludon-BoxSprite.png|htiny]]
> ![[SRD-duraludon-ShuffleToken.png|wsmall]]


*Alloy Pokemon*
*Its body resembles a shiny polished metal and it’s both lightweight and strong. The only drawback is that it rusts easily. It lives on dry climates and deep inside caves because rain and moisture make it cranky.*

**DexID**:: 0884
**Name**:: Duraludon
**Type**:: Steel / Dragon
**Abilities**:: [[SRD-Light Metal|Light Metal]] / [[SRD-Heavy Metal|Heavy Metal]] ([[SRD-Stalwart|Stalwart]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'9" / 1.8m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Duraludon.md"
flatten moves as T
where file.path = this.file.path
```
