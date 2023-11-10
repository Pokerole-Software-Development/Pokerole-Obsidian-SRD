---
Ability1: Prankster
Ability2: ''
BookSprite: SRD-tornadus-BookSprite.png
BoxSprite: SRD-tornadus-BoxSprite.png
DexCategory: No Data
DexDescription: Unova suffers from terrible tornadoes and devastating wind currents
  that leave houses and buildings in ruins. Some people claim a Pokemon riding the
  winds is responsible for all the devastation.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Tornadus (Therian Form)]]'
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Defiant
HomeSprite: SRD-tornadus-HomeSprite.png
Image: tornadus.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Thrash|Thrash]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Number: 641
ShuffleToken: SRD-tornadus-ShuffleToken.png
Type1: Flying
Type2: ''
Weight:
  Kilograms: 63.0
  Pounds: 138.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tornadus-BookSprite.png|wsmall]]
> ![[SRD-tornadus-HomeSprite.png]]
> ![[SRD-tornadus-BoxSprite.png|htiny]]
> ![[SRD-tornadus-ShuffleToken.png|wsmall]]


*No Data*
*Unova suffers from terrible tornadoes and devastating wind currents that leave houses and buildings in ruins. Some people claim a Pokemon riding the winds is responsible for all the devastation.*

**DexID**:: 0641
**Name**:: Tornadus
**Type**:: Flying
**Abilities**:: [[SRD-Prankster|Prankster]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 138.9lbs / 63.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                         | Kind   |
|:----------|:--------------------------------|:-------|
| To        | [[SRD-Tornadus (Therian Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tornadus.md"
flatten moves as T
where file.path = this.file.path
```
