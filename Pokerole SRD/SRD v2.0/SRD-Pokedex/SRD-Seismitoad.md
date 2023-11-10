---
Ability1: Swift Swim
Ability2: Poison Touch
BookSprite: SRD-seismitoad-BookSprite.png
BoxSprite: SRD-seismitoad-BoxSprite.png
DexCategory: Vibration Pokemon
DexDescription: It is only found in a few marshes, and rarely seen on clean water.
  They shoot a paralyzing liquid from their head bumps and use the vibrations on their
  bumps to harm their foes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Palpitoad]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Water Absorb
HomeSprite: SRD-seismitoad-HomeSprite.png
Image: seismitoad.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Round|Round]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
Number: 537
ShuffleToken: SRD-seismitoad-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 62.0
  Pounds: 136.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-seismitoad-BookSprite.png|wsmall]]
> ![[SRD-seismitoad-HomeSprite.png]]
> ![[SRD-seismitoad-BoxSprite.png|htiny]]
> ![[SRD-seismitoad-ShuffleToken.png|wsmall]]


*Vibration Pokemon*
*It is only found in a few marshes, and rarely seen on clean water. They shoot a paralyzing liquid from their head bumps and use the vibrations on their bumps to harm their foes.*

**DexID**:: 0537
**Name**:: Seismitoad
**Type**:: Water / Ground
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Poison Touch|Poison Touch]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 136.7lbs / 62.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Palpitoad]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Seismitoad.md"
flatten moves as T
where file.path = this.file.path
```
