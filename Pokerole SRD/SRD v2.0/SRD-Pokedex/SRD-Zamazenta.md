---
Ability1: Dauntless Shield
Ability2: ''
BookSprite: SRD-zamazenta-BookSprite.png
BoxSprite: SRD-zamazenta-BoxSprite.png
DexCategory: No Data
DexDescription: There is a legend of a hero who through sheer might wielded the shield
  of heroes to protect the people from the greatest evil.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Zamazenta (Crown Form)]]'
GenderType: N
Height:
  Feet: 9.5
  Meters: 2.9
HiddenAbility: ''
HomeSprite: SRD-zamazenta-HomeSprite.png
Image: zamazenta.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Howl|Howl]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
Number: 889
ShuffleToken: SRD-zamazenta-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 210.0
  Pounds: 463.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zamazenta-BookSprite.png|wsmall]]
> ![[SRD-zamazenta-HomeSprite.png]]
> ![[SRD-zamazenta-BoxSprite.png|htiny]]
> ![[SRD-zamazenta-ShuffleToken.png|wsmall]]


*No Data*
*There is a legend of a hero who through sheer might wielded the shield of heroes to protect the people from the greatest evil.*

**DexID**:: 0889
**Name**:: Zamazenta
**Type**:: Fighting
**Abilities**:: [[SRD-Dauntless Shield|Dauntless Shield]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 9'5" / 2.9m
**Weight**: 463.0lbs / 210.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                        | Kind   |
|:----------|:-------------------------------|:-------|
| To        | [[SRD-Zamazenta (Crown Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zamazenta.md"
flatten moves as T
where file.path = this.file.path
```
