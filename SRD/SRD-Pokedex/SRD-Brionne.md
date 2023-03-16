---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-brionne-BookSprite.png
BoxSprite: SRD-brionne-BoxSprite.png
DexCategory: Pop Star Pokemon
DexDescription: In the wild, each pack has their own songs and dances, Brionne practice
  them in the moonlight. It is cheerful and not timid at all, it forms friendships
  easily through dance movements.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Popplio]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Primarina]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Liquid Voice
HomeSprite: SRD-brionne-HomeSprite.png
Image: brionne.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 729
ShuffleToken: SRD-brionne-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 17.5
  Pounds: 38.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-brionne-BookSprite.png|wsmall]]
> ![[SRD-brionne-HomeSprite.png]]
> ![[SRD-brionne-BoxSprite.png|htiny]]
> ![[SRD-brionne-ShuffleToken.png|wsmall]]


*Pop Star Pokemon*
*In the wild, each pack has their own songs and dances, Brionne practice them in the moonlight. It is cheerful and not timid at all, it forms friendships easily through dance movements.*

**DexID**:: 0729
**Name**:: Brionne
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Liquid Voice|Liquid Voice]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 38.6lbs / 17.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Popplio]]   | Level  | Medium  |
| To        | [[SRD-Primarina]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Brionne.md"
flatten moves as T
where file.path = this.file.path
```
