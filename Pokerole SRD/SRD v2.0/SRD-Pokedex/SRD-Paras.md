---
Ability1: Effect Spore
Ability2: Dry Skin
BookSprite: SRD-paras-BookSprite.png
BoxSprite: SRD-paras-BoxSprite.png
DexCategory: Mushroom Pokemon
DexDescription: Paras has two parasitic mushrooms growing on its back. They grow large
  by drawing nutrients from this Bug Pokemon. They are valued as a medicine for prolonging
  life. Paras can be found in humid areas.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Parasect]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Damp
HomeSprite: SRD-paras-HomeSprite.png
Image: paras.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scratch|Scratch]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Powder|Poison Powder]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spore|Spore]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rototiller|Rototiller]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
Number: 46
ShuffleToken: SRD-paras-ShuffleToken.png
Type1: Bug
Type2: Grass
Weight:
  Kilograms: 5.4
  Pounds: 11.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-paras-BookSprite.png|wsmall]]
> ![[SRD-paras-HomeSprite.png]]
> ![[SRD-paras-BoxSprite.png|htiny]]
> ![[SRD-paras-ShuffleToken.png|wsmall]]


*Mushroom Pokemon*
*Paras has two parasitic mushrooms growing on its back. They grow large by drawing nutrients from this Bug Pokemon. They are valued as a medicine for prolonging life. Paras can be found in humid areas.*

**DexID**:: 0046
**Name**:: Paras
**Type**:: Bug / Grass
**Abilities**:: [[SRD-Effect Spore|Effect Spore]] / [[SRD-Dry Skin|Dry Skin]] ([[SRD-Damp|Damp]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 11.9lbs / 5.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Parasect]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Paras.md"
flatten moves as T
where file.path = this.file.path
```
