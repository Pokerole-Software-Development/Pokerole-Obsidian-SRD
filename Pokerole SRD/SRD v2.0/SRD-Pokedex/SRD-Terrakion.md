---
Ability1: Justified
Ability2: ''
BookSprite: SRD-terrakion-BookSprite.png
BoxSprite: SRD-terrakion-BoxSprite.png
DexCategory: No Data
DexDescription: Legends in Unova tell about four Pokemon that rebelled against the
  unfair ruler. One of them trampled through the castle walls, destroying the fortress
  to free the trapped Pokemon inside.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-terrakion-HomeSprite.png
Image: terrakion.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Smack Down|Smack Down]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Retaliate|Retaliate]]'
- - Master
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Work Up|Work Up]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
Number: 639
ShuffleToken: SRD-terrakion-ShuffleToken.png
Type1: Rock
Type2: Fighting
Weight:
  Kilograms: 260.0
  Pounds: 573.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-terrakion-BookSprite.png|wsmall]]
> ![[SRD-terrakion-HomeSprite.png]]
> ![[SRD-terrakion-BoxSprite.png|htiny]]
> ![[SRD-terrakion-ShuffleToken.png|wsmall]]


*No Data*
*Legends in Unova tell about four Pokemon that rebelled against the unfair ruler. One of them trampled through the castle walls, destroying the fortress to free the trapped Pokemon inside.*

**DexID**:: 0639
**Name**:: Terrakion
**Type**:: Rock / Fighting
**Abilities**:: [[SRD-Justified|Justified]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 573.2lbs / 260.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Terrakion.md"
flatten moves as T
where file.path = this.file.path
```
