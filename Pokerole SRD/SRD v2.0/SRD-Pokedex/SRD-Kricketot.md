---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-kricketot-BookSprite.png
BoxSprite: SRD-kricketot-BoxSprite.png
DexCategory: Cricket Pokemon
DexDescription: If you hear a xilophone-like sound at night it means that this Pokemon
  is roaming close. It communicates by making rhythmic sounds with its antennae. It
  is not aggressive and feeds on honey and tree sap.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kricketune]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Run Away
HomeSprite: SRD-kricketot-HomeSprite.png
Image: kricketot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-String Shot|String Shot]]'
Number: 401
ShuffleToken: SRD-kricketot-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 2.2
  Pounds: 4.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kricketot-BookSprite.png|wsmall]]
> ![[SRD-kricketot-HomeSprite.png]]
> ![[SRD-kricketot-BoxSprite.png|htiny]]
> ![[SRD-kricketot-ShuffleToken.png|wsmall]]


*Cricket Pokemon*
*If you hear a xilophone-like sound at night it means that this Pokemon is roaming close. It communicates by making rhythmic sounds with its antennae. It is not aggressive and feeds on honey and tree sap.*

**DexID**:: 0401
**Name**:: Kricketot
**Type**:: Bug
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.9lbs / 2.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Kricketune]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kricketot.md"
flatten moves as T
where file.path = this.file.path
```
