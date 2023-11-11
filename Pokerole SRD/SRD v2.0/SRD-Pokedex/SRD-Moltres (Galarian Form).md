---
Ability1: Berserk
Ability2: ''
BookSprite: SRD-moltres-galarian-form-BookSprite.png
BoxSprite: SRD-moltres-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-moltres-galarian-form-HomeSprite.png
Image: moltres-galarian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Payback|Payback]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wing Attack|Wing Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-After You|After You]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fiery Wrath|Fiery Wrath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hurricane|Hurricane]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Memento|Memento]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hex|Hex]]'
Number: 146
ShuffleToken: SRD-moltres-galarian-form-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 66.0
  Pounds: 145.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-moltres-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-moltres-galarian-form-HomeSprite.png]]
> ![[SRD-moltres-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-moltres-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0146G
**Name**:: Moltres (Galarian Form)
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Berserk|Berserk]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 6'6" / 2.0m
**Weight**: 145.5lbs / 66.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Moltres (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
