---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-raboot-BookSprite.png
BoxSprite: SRD-raboot-BoxSprite.png
DexCategory: Rabbit Pokemon
DexDescription: This Pokemon loves to kick and trains each day to get better at it.
  Its fur is now very thick, some debate it is to protect it from the cold weather
  others say it is to produce hotter flames.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Scorbunny]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cinderace]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Libero
HomeSprite: SRD-raboot-HomeSprite.png
Image: raboot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Work Up|Work Up]]'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 814
ShuffleToken: SRD-raboot-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 9.0
  Pounds: 19.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-raboot-BookSprite.png|wsmall]]
> ![[SRD-raboot-HomeSprite.png]]
> ![[SRD-raboot-BoxSprite.png|htiny]]
> ![[SRD-raboot-ShuffleToken.png|wsmall]]


*Rabbit Pokemon*
*This Pokemon loves to kick and trains each day to get better at it. Its fur is now very thick, some debate it is to protect it from the cold weather others say it is to produce hotter flames.*

**DexID**:: 0814
**Name**:: Raboot
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Libero|Libero]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 19.8lbs / 9.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Scorbunny]] | Level  | Medium  |
| To        | [[SRD-Cinderace]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Raboot.md"
flatten moves as T
where file.path = this.file.path
```
