---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-torterra-BookSprite.png
BoxSprite: SRD-torterra-BoxSprite.png
DexCategory: Continent Pokemon
DexDescription: Torterras travel in groups, mistaken as moving forests. Many pokemon
  make their nest on its back and live there for their entire lives. Ancient people
  thought that they lived on the back of a giant Torterra.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grotle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Shell Armor
HomeSprite: SRD-torterra-HomeSprite.png
Image: torterra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Frenzy Plant|Frenzy Plant]]'
Number: 389
ShuffleToken: SRD-torterra-ShuffleToken.png
Type1: Grass
Type2: Ground
Weight:
  Kilograms: 310.0
  Pounds: 683.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-torterra-BookSprite.png|wsmall]]
> ![[SRD-torterra-HomeSprite.png]]
> ![[SRD-torterra-BoxSprite.png|htiny]]
> ![[SRD-torterra-ShuffleToken.png|wsmall]]


*Continent Pokemon*
*Torterras travel in groups, mistaken as moving forests. Many pokemon make their nest on its back and live there for their entire lives. Ancient people thought that they lived on the back of a giant Torterra.*

**DexID**:: 0389
**Name**:: Torterra
**Type**:: Grass / Ground
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 683.4lbs / 310.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Grotle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Torterra.md"
flatten moves as T
where file.path = this.file.path
```
