---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-larvesta-BookSprite.png
BoxSprite: SRD-larvesta-BoxSprite.png
DexCategory: Torch Pokemon
DexDescription: Very Rare. The base of volcanoes is where they make their homes. They
  shoot fire from their horns to repel attacks from enemies. It becomes a flaming
  cocoon for months before it finally evolves.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Volcarona]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Swarm
HomeSprite: SRD-larvesta-HomeSprite.png
Image: larvesta.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thrash|Thrash]]'
- - Pro
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Pro
  - '[[SRD-Harden|Harden]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Number: 636
ShuffleToken: SRD-larvesta-ShuffleToken.png
Type1: Bug
Type2: Fire
Weight:
  Kilograms: 28.8
  Pounds: 63.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-larvesta-BookSprite.png|wsmall]]
> ![[SRD-larvesta-HomeSprite.png]]
> ![[SRD-larvesta-BoxSprite.png|htiny]]
> ![[SRD-larvesta-ShuffleToken.png|wsmall]]


*Torch Pokemon*
*Very Rare. The base of volcanoes is where they make their homes. They shoot fire from their horns to repel attacks from enemies. It becomes a flaming cocoon for months before it finally evolves.*

**DexID**:: 0636
**Name**:: Larvesta
**Type**:: Bug / Fire
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Swarm|Swarm]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 63.5lbs / 28.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Volcarona]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Larvesta.md"
flatten moves as T
where file.path = this.file.path
```
