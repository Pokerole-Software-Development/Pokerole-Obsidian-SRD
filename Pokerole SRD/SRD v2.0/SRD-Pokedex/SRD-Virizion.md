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
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Retaliate|Retaliate]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Work Up|Work Up]]'
- - Master
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Attract|Attract]]'
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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Virizion.md"
flatten moves as T
where file.path = this.file.path
```
