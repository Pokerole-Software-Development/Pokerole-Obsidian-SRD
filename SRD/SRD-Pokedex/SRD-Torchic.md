---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-torchic-BookSprite.png
BoxSprite: SRD-torchic-BoxSprite.png
DexCategory: Chick Pokemon
DexDescription: They walk clumsily, but follow their trainers wherever they go. Torchics
  have a flame sac in their belly - burning all the time. If you hug them, they feel
  warm, but if you squeeze them, they may spit fire.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Combusken]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Speed Boost
HomeSprite: SRD-torchic-HomeSprite.png
Image: torchic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 255
ShuffleToken: SRD-torchic-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 2.5
  Pounds: 5.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-torchic-BookSprite.png|wsmall]]
> ![[SRD-torchic-HomeSprite.png]]
> ![[SRD-torchic-BoxSprite.png|htiny]]
> ![[SRD-torchic-ShuffleToken.png|wsmall]]


*Chick Pokemon*
*They walk clumsily, but follow their trainers wherever they go. Torchics have a flame sac in their belly - burning all the time. If you hug them, they feel warm, but if you squeeze them, they may spit fire.*

**DexID**:: 0255
**Name**:: Torchic
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 5.5lbs / 2.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Combusken]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Torchic.md"
flatten moves as T
where file.path = this.file.path
```
