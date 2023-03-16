---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-spewpa-BookSprite.png
BoxSprite: SRD-spewpa-BoxSprite.png
DexCategory: Scatterdust Pokemon
DexDescription: It remains hidden inside old logs. When predators attack, it quickly
  bristles the fur covering its body to scare them. Bird Pokemon have a hard time
  trying to eat it with all the dust it releases as protection.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Scatterbug]]'
  Speed: Fast
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vivillon]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Friend Guard
HomeSprite: SRD-spewpa-HomeSprite.png
Image: spewpa.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
Number: 665
ShuffleToken: SRD-spewpa-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 8.4
  Pounds: 18.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spewpa-BookSprite.png|wsmall]]
> ![[SRD-spewpa-HomeSprite.png]]
> ![[SRD-spewpa-BoxSprite.png|htiny]]
> ![[SRD-spewpa-ShuffleToken.png|wsmall]]


*Scatterdust Pokemon*
*It remains hidden inside old logs. When predators attack, it quickly bristles the fur covering its body to scare them. Bird Pokemon have a hard time trying to eat it with all the dust it releases as protection.*

**DexID**:: 0665
**Name**:: Spewpa
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 18.5lbs / 8.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Scatterbug]] | Level  | Fast    |
| To        | [[SRD-Vivillon]]   | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Spewpa.md"
flatten moves as T
where file.path = this.file.path
```
