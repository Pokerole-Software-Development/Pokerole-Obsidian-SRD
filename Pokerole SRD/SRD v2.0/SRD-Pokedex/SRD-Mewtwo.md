---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-mewtwo-BookSprite.png
BoxSprite: SRD-mewtwo-BoxSprite.png
DexCategory: No Data
DexDescription: An article in a science magazine talked about how much cloning research
  was progressing, but... could it be?
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Mewtwonite Y
  Kind: Mega
  Pokemon: '[[SRD-Mewtwo (Mega Y Form)]]'
- Evolves: To
  Item: Mewtwonite X
  Kind: Mega
  Pokemon: '[[SRD-Mewtwo (Mega X Form)]]'
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Unnerve
HomeSprite: SRD-mewtwo-HomeSprite.png
Image: mewtwo.png
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
ShuffleToken: SRD-mewtwo-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 122.0
  Pounds: 269.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mewtwo-BookSprite.png|wsmall]]
> ![[SRD-mewtwo-HomeSprite.png]]
> ![[SRD-mewtwo-BoxSprite.png|htiny]]
> ![[SRD-mewtwo-ShuffleToken.png|wsmall]]


*No Data*
*An article in a science magazine talked about how much cloning research was progressing, but... could it be?*

**DexID**:: 0150
**Name**:: Mewtwo
**Type**:: Psychic
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 269.0lbs / 122.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                      | Kind   | Item         |
|:----------|:-----------------------------|:-------|:-------------|
| To        | [[SRD-Mewtwo (Mega Y Form)]] | Mega   | Mewtwonite Y |
| To        | [[SRD-Mewtwo (Mega X Form)]] | Mega   | Mewtwonite X |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mewtwo.md"
flatten moves as T
where file.path = this.file.path
```
