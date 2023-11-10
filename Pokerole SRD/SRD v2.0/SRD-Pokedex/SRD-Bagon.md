---
Ability1: Rock Head
Ability2: ''
BookSprite: SRD-bagon-BookSprite.png
BoxSprite: SRD-bagon-BoxSprite.png
DexCategory: Rock Head Pokemon
DexDescription: Bagons dream of soaring the sky. This leads to a lot of frustration
  that makes them dive off cliffs in an attempt to fly. Their head is tough enough
  to survive the fall. They are very ill tempered and violent.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Shelgon]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Sheer Force
HomeSprite: SRD-bagon-HomeSprite.png
Image: bagon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Pro
  - '[[SRD-Mimic|Mimic]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 371
ShuffleToken: SRD-bagon-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 42.1
  Pounds: 92.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bagon-BookSprite.png|wsmall]]
> ![[SRD-bagon-HomeSprite.png]]
> ![[SRD-bagon-BoxSprite.png|htiny]]
> ![[SRD-bagon-ShuffleToken.png|wsmall]]


*Rock Head Pokemon*
*Bagons dream of soaring the sky. This leads to a lot of frustration that makes them dive off cliffs in an attempt to fly. Their head is tough enough to survive the fall. They are very ill tempered and violent.*

**DexID**:: 0371
**Name**:: Bagon
**Type**:: Dragon
**Abilities**:: [[SRD-Rock Head|Rock Head]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 92.8lbs / 42.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Shelgon]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bagon.md"
flatten moves as T
where file.path = this.file.path
```
