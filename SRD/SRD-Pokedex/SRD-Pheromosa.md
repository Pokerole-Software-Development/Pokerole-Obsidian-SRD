---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-pheromosa-BookSprite.png
BoxSprite: SRD-pheromosa-BoxSprite.png
DexCategory: 'Aether Foundation Log #012'
DexDescription: "This one also appears to be unable to enter a Pokeball, the rays\
  \ just won\u2019t surround them. This one has refused to touch anything we give\
  \ to it and appears displeased by my mere presence."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-pheromosa-HomeSprite.png
Image: pheromosa.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Low Kick|Low Kick]]'
- - Master
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Feint|Feint]]'
- - Master
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Master
  - '[[SRD-Bounce|Bounce]]'
- - Master
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Triple Kick|Triple Kick]]'
- - Master
  - '[[SRD-Lunge|Lunge]]'
- - Master
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Master
  - '[[SRD-Me First|Me First]]'
- - Master
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Master
  - '[[SRD-Speed Swap|Speed Swap]]'
- - Master
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
Number: 795
ShuffleToken: SRD-pheromosa-ShuffleToken.png
Type1: Bug
Type2: Fighting
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pheromosa-BookSprite.png|wsmall]]
> ![[SRD-pheromosa-HomeSprite.png]]
> ![[SRD-pheromosa-BoxSprite.png|htiny]]
> ![[SRD-pheromosa-ShuffleToken.png|wsmall]]


*Aether Foundation Log #012*
*This one also appears to be unable to enter a Pokeball, the rays just won’t surround them. This one has refused to touch anything we give to it and appears displeased by my mere presence.*

**DexID**:: 0795
**Name**:: Pheromosa
**Type**:: Bug / Fighting
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 8)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::3)     |

**Height**: 5'9" / 1.8m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pheromosa.md"
flatten moves as T
where file.path = this.file.path
```
