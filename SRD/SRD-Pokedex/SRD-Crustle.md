---
Ability1: Sturdy
Ability2: Shell Armor
BookSprite: SRD-crustle-BookSprite.png
BoxSprite: SRD-crustle-BoxSprite.png
DexCategory: Stone Home Pokemon
DexDescription: They carry enormous boulders as a protective shell. When competing
  for territory, Crustle fight viciously. The one whose boulder is broken is the loser
  of the battle. They feed on the moss that grows in their rock.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dwebble]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Weak Armor
HomeSprite: SRD-crustle-HomeSprite.png
Image: crustle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Starter
  - '[[SRD-Rock Blast|Rock Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Rock Wrecker|Rock Wrecker]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Number: 558
ShuffleToken: SRD-crustle-ShuffleToken.png
Type1: Bug
Type2: Rock
Weight:
  Kilograms: 200.0
  Pounds: 440.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-crustle-BookSprite.png|wsmall]]
> ![[SRD-crustle-HomeSprite.png]]
> ![[SRD-crustle-BoxSprite.png|htiny]]
> ![[SRD-crustle-ShuffleToken.png|wsmall]]


*Stone Home Pokemon*
*They carry enormous boulders as a protective shell. When competing for territory, Crustle fight viciously. The one whose boulder is broken is the loser of the battle. They feed on the moss that grows in their rock.*

**DexID**:: 0558
**Name**:: Crustle
**Type**:: Bug / Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 440.9lbs / 200.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Dwebble]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Crustle.md"
flatten moves as T
where file.path = this.file.path
```
