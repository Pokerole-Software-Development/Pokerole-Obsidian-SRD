---
Ability1: Poison Point
Ability2: Rivalry
BookSprite: SRD-nidoran-f-BookSprite.png
BoxSprite: SRD-nidoran-f-BoxSprite.png
DexCategory: Poison Pin Pokemon
DexDescription: A female only species. It lives close to meadows and forests. They
  are mellow Pokemon. To protect herself, she secretes a powerful toxin through her
  body. Her horn is small but venomous to the touch.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Nidorina]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Hustle
HomeSprite: SRD-nidoran-f-HomeSprite.png
Image: nidoran-f.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flatter|Flatter]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lovely Kiss|Lovely Kiss]]'
- - Pro
  - '[[SRD-Moonlight|Moonlight]]'
- - Pro
  - '[[SRD-Charm|Charm]]'
Number: 29
ShuffleToken: SRD-nidoran-f-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 7.0
  Pounds: 15.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nidoran-f-BookSprite.png|wsmall]]
> ![[SRD-nidoran-f-HomeSprite.png]]
> ![[SRD-nidoran-f-BoxSprite.png|htiny]]
> ![[SRD-nidoran-f-ShuffleToken.png|wsmall]]


*Poison Pin Pokemon*
*A female only species. It lives close to meadows and forests. They are mellow Pokemon. To protect herself, she secretes a powerful toxin through her body. Her horn is small but venomous to the touch.*

**DexID**:: 0029
**Name**:: Nidoran F
**Type**:: Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Rivalry|Rivalry]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 15.4lbs / 7.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Nidorina]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Nidoran F.md"
flatten moves as T
where file.path = this.file.path
```
