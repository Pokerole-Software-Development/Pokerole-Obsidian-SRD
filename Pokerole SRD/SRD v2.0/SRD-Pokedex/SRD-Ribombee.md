---
Ability1: Honey Gather
Ability2: Shield Dust
BookSprite: SRD-ribombee-BookSprite.png
BoxSprite: SRD-ribombee-BoxSprite.png
DexCategory: Bee Fly Pokemon
DexDescription: The pollen puff of a happy Ribombee are very nutritious and valuable
  supplements in Alola. It dislikes rain, for it wets its hair and makes it unable
  to fly, so if you see a Ribombee you know the weather will be nice.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cutiefly]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Sweet Veil
HomeSprite: SRD-ribombee-HomeSprite.png
Image: ribombee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Beginner
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pollen Puff|Pollen Puff]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Moonblast|Moonblast]]'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
Number: 743
ShuffleToken: SRD-ribombee-ShuffleToken.png
Type1: Bug
Type2: Fairy
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ribombee-BookSprite.png|wsmall]]
> ![[SRD-ribombee-HomeSprite.png]]
> ![[SRD-ribombee-BoxSprite.png|htiny]]
> ![[SRD-ribombee-ShuffleToken.png|wsmall]]


*Bee Fly Pokemon*
*The pollen puff of a happy Ribombee are very nutritious and valuable supplements in Alola. It dislikes rain, for it wets its hair and makes it unable to fly, so if you see a Ribombee you know the weather will be nice.*

**DexID**:: 0743
**Name**:: Ribombee
**Type**:: Bug / Fairy
**Abilities**:: [[SRD-Honey Gather|Honey Gather]] / [[SRD-Shield Dust|Shield Dust]] ([[SRD-Sweet Veil|Sweet Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 0'7" / 0.2m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Cutiefly]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ribombee.md"
flatten moves as T
where file.path = this.file.path
```
