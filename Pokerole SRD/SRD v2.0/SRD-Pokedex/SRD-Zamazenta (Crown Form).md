---
Ability1: Dauntless Shield
Ability2: ''
BookSprite: SRD-zamazenta-crown-form-BookSprite.png
BoxSprite: SRD-zamazenta-crown-form-BoxSprite.png
DexCategory: No Data
DexDescription: "There is a legend about a mighty shield able to deflect any attack,\
  \ it became known as the Fighting Master\u2019s Shield, not even the largest creatures\
  \ could go through it."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Zamazenta]]'
GenderType: N
Height:
  Feet: 9.5
  Meters: 2.9
HiddenAbility: ''
HomeSprite: SRD-zamazenta-crown-form-HomeSprite.png
Image: zamazenta-crown-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Howl|Howl]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonblast|Moonblast]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reflect|Reflect]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Safeguard|Safeguard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Steel Beam|Steel Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Behemoth Bash|Behemoth Bash]]'
Number: 889
ShuffleToken: SRD-zamazenta-crown-form-ShuffleToken.png
Type1: Fighting
Type2: Steel
Weight:
  Kilograms: 785.0
  Pounds: 1730.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zamazenta-crown-form-BookSprite.png|wsmall]]
> ![[SRD-zamazenta-crown-form-HomeSprite.png]]
> ![[SRD-zamazenta-crown-form-BoxSprite.png|htiny]]
> ![[SRD-zamazenta-crown-form-ShuffleToken.png|wsmall]]


*No Data*
*There is a legend about a mighty shield able to deflect any attack, it became known as the Fighting Master’s Shield, not even the largest creatures could go through it.*

**DexID**:: 0889F1
**Name**:: Zamazenta (Crown Form)
**Type**:: Fighting / Steel
**Abilities**:: [[SRD-Dauntless Shield|Dauntless Shield]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::8)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::8)/(MaxInsight::8)     |

**Height**: 9'5" / 2.9m
**Weight**: 1730.6lbs / 785.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| From      | [[SRD-Zamazenta]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zamazenta (Crown Form).md"
flatten moves as T
where file.path = this.file.path
```
