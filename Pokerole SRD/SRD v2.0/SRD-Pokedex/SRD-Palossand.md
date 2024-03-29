---
Ability1: Water Compaction
Ability2: ''
BookSprite: SRD-palossand-BookSprite.png
BoxSprite: SRD-palossand-BoxSprite.png
DexCategory: Sand Castle Pokemon
DexDescription: The possessed people shaped this Pokemon into a castle, buried beneath
  the sand where it stands are the remains of all its victims. Some say these unmarked
  graves will give birth to a new Sandygast.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sandygast]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Sand Veil
HomeSprite: SRD-palossand-HomeSprite.png
Image: palossand.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Harden|Harden]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Tomb|Sand Tomb]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shore Up|Shore Up]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Polish|Rock Polish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
Number: 770
ShuffleToken: SRD-palossand-ShuffleToken.png
Type1: Ghost
Type2: Ground
Weight:
  Kilograms: 250.0
  Pounds: 551.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-palossand-BookSprite.png|wsmall]]
> ![[SRD-palossand-HomeSprite.png]]
> ![[SRD-palossand-BoxSprite.png|htiny]]
> ![[SRD-palossand-ShuffleToken.png|wsmall]]


*Sand Castle Pokemon*
*The possessed people shaped this Pokemon into a castle, buried beneath the sand where it stands are the remains of all its victims. Some say these unmarked graves will give birth to a new Sandygast.*

**DexID**:: 0770
**Name**:: Palossand
**Type**:: Ghost / Ground
**Abilities**:: [[SRD-Water Compaction|Water Compaction]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 551.2lbs / 250.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Sandygast]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Palossand.md"
flatten moves as T
where file.path = this.file.path
```
