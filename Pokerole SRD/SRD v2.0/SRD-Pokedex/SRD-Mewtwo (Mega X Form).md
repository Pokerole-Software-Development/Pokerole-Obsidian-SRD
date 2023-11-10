---
Ability1: Steadfast
Ability2: ''
BookSprite: SRD-mewtwo-mega-x-form-BookSprite.png
BoxSprite: SRD-mewtwo-mega-x-form-BoxSprite.png
DexCategory: No Data
DexDescription: The power of the Mega Stone was absorbed into its muscles if it grapples
  you and its psychic force does not crack you its strong arms will.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Mewtwonite X
  Kind: Mega
  Pokemon: '[[SRD-Mewtwo]]'
GenderType: N
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: ''
HomeSprite: SRD-mewtwo-mega-x-form-HomeSprite.png
Image: mewtwo-mega-x-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Psywave|Psywave]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Power Swap|Power Swap]]'
- - Master
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Barrier|Barrier]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Me First|Me First]]'
- - Master
  - '[[SRD-Psystrike|Psystrike]]'
- - Master
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
Number: 150
ShuffleToken: SRD-mewtwo-mega-x-form-ShuffleToken.png
Type1: Psychic
Type2: Fighting
Weight:
  Kilograms: 127.0
  Pounds: 280.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mewtwo-mega-x-form-BookSprite.png|wsmall]]
> ![[SRD-mewtwo-mega-x-form-HomeSprite.png]]
> ![[SRD-mewtwo-mega-x-form-BoxSprite.png|htiny]]
> ![[SRD-mewtwo-mega-x-form-ShuffleToken.png|wsmall]]


*No Data*
*The power of the Mega Stone was absorbed into its muscles if it grapples you and its psychic force does not crack you its strong arms will.*

**DexID**:: 0150M1
**Name**:: Mewtwo (Mega X Form)
**Type**:: Psychic / Fighting
**Abilities**:: [[SRD-Steadfast|Steadfast]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 7'5" / 2.3m
**Weight**: 280.0lbs / 127.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Item         |
|:----------|:---------------|:-------|:-------------|
| From      | [[SRD-Mewtwo]] | Mega   | Mewtwonite X |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mewtwo (Mega X Form).md"
flatten moves as T
where file.path = this.file.path
```
