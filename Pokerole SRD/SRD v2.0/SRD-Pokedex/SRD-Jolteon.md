---
Ability1: Volt Absorb
Ability2: ''
BookSprite: SRD-jolteon-BookSprite.png
BoxSprite: SRD-jolteon-BoxSprite.png
DexCategory: Lightning Pokemon
DexDescription: This Pokemon evolved after being affected by electric radiation. Every
  hair on its body starts to stand sharply if it becomes charged with electricity.
  It shoots lightning from all around its body.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Eevee]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Quick Feet
HomeSprite: SRD-jolteon-HomeSprite.png
Image: jolteon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 135
ShuffleToken: SRD-jolteon-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 24.5
  Pounds: 54.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jolteon-BookSprite.png|wsmall]]
> ![[SRD-jolteon-HomeSprite.png]]
> ![[SRD-jolteon-BoxSprite.png|htiny]]
> ![[SRD-jolteon-ShuffleToken.png|wsmall]]


*Lightning Pokemon*
*This Pokemon evolved after being affected by electric radiation. Every hair on its body starts to stand sharply if it becomes charged with electricity. It shoots lightning from all around its body.*

**DexID**:: 0135
**Name**:: Jolteon
**Type**:: Electric
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]] ([[SRD-Quick Feet|Quick Feet]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'6" / 0.8m
**Weight**: 54.0lbs / 24.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item          |
|:----------|:--------------|:-------|:--------------|
| From      | [[SRD-Eevee]] | Stone  | Thunder Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jolteon.md"
flatten moves as T
where file.path = this.file.path
```
