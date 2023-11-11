---
Ability1: Justified
Ability2: ''
BookSprite: SRD-virizion-BookSprite.png
BoxSprite: SRD-virizion-BoxSprite.png
DexCategory: No Data
DexDescription: An old tale in Unova mentions four Pokemon that fought against an
  evil army. The most beautiful of them was also the most swift and graceful in combat,
  it created an army of trees that won the battle.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-virizion-HomeSprite.png
Image: virizion.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Kick|Double Kick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Retaliate|Retaliate]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Work Up|Work Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Blade|Leaf Blade]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Attract|Attract]]'
Number: 640
ShuffleToken: SRD-virizion-ShuffleToken.png
Type1: Grass
Type2: Fighting
Weight:
  Kilograms: 200.0
  Pounds: 440.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-virizion-BookSprite.png|wsmall]]
> ![[SRD-virizion-HomeSprite.png]]
> ![[SRD-virizion-BoxSprite.png|htiny]]
> ![[SRD-virizion-ShuffleToken.png|wsmall]]


*No Data*
*An old tale in Unova mentions four Pokemon that fought against an evil army. The most beautiful of them was also the most swift and graceful in combat, it created an army of trees that won the battle.*

**DexID**:: 0640
**Name**:: Virizion
**Type**:: Grass / Fighting
**Abilities**:: [[SRD-Justified|Justified]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 440.9lbs / 200.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Virizion.md"
flatten moves as T
where file.path = this.file.path
```
