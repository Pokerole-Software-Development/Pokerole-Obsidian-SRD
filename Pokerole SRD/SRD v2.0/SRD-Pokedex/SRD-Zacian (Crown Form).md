---
Ability1: Intrepid Sword
Ability2: ''
BookSprite: SRD-zacian-crown-form-BookSprite.png
BoxSprite: SRD-zacian-crown-form-BoxSprite.png
DexCategory: No Data
DexDescription: "There is a legend about a mighty sword able to cut down anything\
  \ with a single strike, it became known as the Fairy King\u2019s Sword, and it inspired\
  \ awe in friend and foe alike."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Zacian]]'
GenderType: N
Height:
  Feet: 9.2
  Meters: 2.8
HiddenAbility: ''
HomeSprite: SRD-zacian-crown-form-HomeSprite.png
Image: zacian-crown-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Steel Beam|Steel Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Behemoth Blade|Behemoth Blade]]'
Number: 888
ShuffleToken: SRD-zacian-crown-form-ShuffleToken.png
Type1: Fairy
Type2: Steel
Weight:
  Kilograms: 355.0
  Pounds: 782.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zacian-crown-form-BookSprite.png|wsmall]]
> ![[SRD-zacian-crown-form-HomeSprite.png]]
> ![[SRD-zacian-crown-form-BoxSprite.png|htiny]]
> ![[SRD-zacian-crown-form-ShuffleToken.png|wsmall]]


*No Data*
*There is a legend about a mighty sword able to cut down anything with a single strike, it became known as the Fairy King’s Sword, and it inspired awe in friend and foe alike.*

**DexID**:: 0888F1
**Name**:: Zacian (Crown Form)
**Type**:: Fairy / Steel
**Abilities**:: [[SRD-Intrepid Sword|Intrepid Sword]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 8)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 9'2" / 2.8m
**Weight**: 782.6lbs / 355.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Zacian]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zacian (Crown Form).md"
flatten moves as T
where file.path = this.file.path
```
