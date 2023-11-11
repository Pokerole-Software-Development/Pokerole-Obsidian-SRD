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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Kick|Double Kick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smack Down|Smack Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Retaliate|Retaliate]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Work Up|Work Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
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
