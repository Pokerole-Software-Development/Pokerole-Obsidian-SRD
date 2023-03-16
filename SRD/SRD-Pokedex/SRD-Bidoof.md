---
Ability1: Simple
Ability2: Unaware
BookSprite: SRD-bidoof-BookSprite.png
BoxSprite: SRD-bidoof-BoxSprite.png
DexCategory: Plump Mouse Pokemon
DexDescription: Steady as a mountain, Bidoof has nerves of steel so nothing can disturb
  its focus. It is agile, active and a great team worker. They live in huge packs
  alongside rivers; the dams they build are incredibly sturdy.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Bibarel]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Moody
HomeSprite: SRD-bidoof-HomeSprite.png
Image: bidoof.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Sport|Water Sport]]'
- - Pro
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Number: 399
ShuffleToken: SRD-bidoof-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 20.0
  Pounds: 44.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bidoof-BookSprite.png|wsmall]]
> ![[SRD-bidoof-HomeSprite.png]]
> ![[SRD-bidoof-BoxSprite.png|htiny]]
> ![[SRD-bidoof-ShuffleToken.png|wsmall]]


*Plump Mouse Pokemon*
*Steady as a mountain, Bidoof has nerves of steel so nothing can disturb its focus. It is agile, active and a great team worker. They live in huge packs alongside rivers; the dams they build are incredibly sturdy.*

**DexID**:: 0399
**Name**:: Bidoof
**Type**:: Normal
**Abilities**:: [[SRD-Simple|Simple]] / [[SRD-Unaware|Unaware]] ([[SRD-Moody|Moody]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 44.1lbs / 20.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Bibarel]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bidoof.md"
flatten moves as T
where file.path = this.file.path
```
