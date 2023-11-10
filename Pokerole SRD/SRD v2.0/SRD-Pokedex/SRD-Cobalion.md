---
Ability1: Justified
Ability2: ''
BookSprite: SRD-cobalion-BookSprite.png
BoxSprite: SRD-cobalion-BoxSprite.png
DexCategory: No Data
DexDescription: There is a story in Unova about four Pokemon that brought justice
  to the wrongdoers. Their Leader was calm and composed but unforgiving. Its cold
  stare forced you to obey its law.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: ''
HomeSprite: SRD-cobalion-HomeSprite.png
Image: cobalion.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Retaliate|Retaliate]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Work Up|Work Up]]'
- - Master
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
Number: 638
ShuffleToken: SRD-cobalion-ShuffleToken.png
Type1: Steel
Type2: Fighting
Weight:
  Kilograms: 250.0
  Pounds: 551.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cobalion-BookSprite.png|wsmall]]
> ![[SRD-cobalion-HomeSprite.png]]
> ![[SRD-cobalion-BoxSprite.png|htiny]]
> ![[SRD-cobalion-ShuffleToken.png|wsmall]]


*No Data*
*There is a story in Unova about four Pokemon that brought justice to the wrongdoers. Their Leader was calm and composed but unforgiving. Its cold stare forced you to obey its law.*

**DexID**:: 0638
**Name**:: Cobalion
**Type**:: Steel / Fighting
**Abilities**:: [[SRD-Justified|Justified]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 551.2lbs / 250.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cobalion.md"
flatten moves as T
where file.path = this.file.path
```
