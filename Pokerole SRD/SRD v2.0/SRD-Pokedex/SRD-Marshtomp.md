---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-marshtomp-BookSprite.png
BoxSprite: SRD-marshtomp-BoxSprite.png
DexCategory: Mud Fish Pokemon
DexDescription: A sticky film allows them to live out of water. They are seen playing
  in the mud at beaches to rehydrate their dry bodies. They are slow runners and swimmers
  but they can be fast sliding through the mud.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mudkip]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Swampert]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Damp
HomeSprite: SRD-marshtomp-HomeSprite.png
Image: marshtomp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
- - Pro
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
Number: 259
ShuffleToken: SRD-marshtomp-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-marshtomp-BookSprite.png|wsmall]]
> ![[SRD-marshtomp-HomeSprite.png]]
> ![[SRD-marshtomp-BoxSprite.png|htiny]]
> ![[SRD-marshtomp-ShuffleToken.png|wsmall]]


*Mud Fish Pokemon*
*A sticky film allows them to live out of water. They are seen playing in the mud at beaches to rehydrate their dry bodies. They are slow runners and swimmers but they can be fast sliding through the mud.*

**DexID**:: 0259
**Name**:: Marshtomp
**Type**:: Water / Ground
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Damp|Damp]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Mudkip]]   | Level  | Medium  |
| To        | [[SRD-Swampert]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Marshtomp.md"
flatten moves as T
where file.path = this.file.path
```
