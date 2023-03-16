---
Ability1: Insomnia
Ability2: ''
BookSprite: SRD-mewtwo-mega-y-form-BookSprite.png
BoxSprite: SRD-mewtwo-mega-y-form-BoxSprite.png
DexCategory: No Data
DexDescription: With the power of the Mega Stone its body got smaller but its power
  grew immensely. It can blow up even a skyscraper with just its thoughts
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Mewtwonite Y
  Kind: Mega
  Pokemon: '[[SRD-Mewtwo]]'
GenderType: N
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-mewtwo-mega-y-form-HomeSprite.png
Image: mewtwo-mega-y-form.png
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
ShuffleToken: SRD-mewtwo-mega-y-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mewtwo-mega-y-form-BookSprite.png|wsmall]]
> ![[SRD-mewtwo-mega-y-form-HomeSprite.png]]
> ![[SRD-mewtwo-mega-y-form-BoxSprite.png|htiny]]
> ![[SRD-mewtwo-mega-y-form-ShuffleToken.png|wsmall]]


*No Data*
*With the power of the Mega Stone its body got smaller but its power grew immensely. It can blow up even a skyscraper with just its thoughts*

**DexID**:: 0150M2
**Name**:: Mewtwo (Mega Y Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Insomnia|Insomnia]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::10)/(MaxSpecial::10)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 4'9" / 1.5m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Item         |
|:----------|:---------------|:-------|:-------------|
| From      | [[SRD-Mewtwo]] | Mega   | Mewtwonite Y |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mewtwo (Mega Y Form).md"
flatten moves as T
where file.path = this.file.path
```
