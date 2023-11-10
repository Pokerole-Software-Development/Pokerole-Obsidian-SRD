---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-thwackey-BookSprite.png
BoxSprite: SRD-thwackey-BoxSprite.png
DexCategory: Beat Pokemon
DexDescription: "Thwakeys are passionate about their drumming, they can get so caught\
  \ up in their music that they don\u2019t notice the battle is already over. The\
  \ faster they can beat their drums, the stronger they are."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Grookey]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Rillaboom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Grassy Surge
HomeSprite: SRD-thwackey-HomeSprite.png
Image: thwackey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Double Hit|Double Hit]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Branch Poke|Branch Poke]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Uproar|Uproar]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
Number: 811
ShuffleToken: SRD-thwackey-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 14.0
  Pounds: 30.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-thwackey-BookSprite.png|wsmall]]
> ![[SRD-thwackey-HomeSprite.png]]
> ![[SRD-thwackey-BoxSprite.png|htiny]]
> ![[SRD-thwackey-ShuffleToken.png|wsmall]]


*Beat Pokemon*
*Thwakeys are passionate about their drumming, they can get so caught up in their music that they don’t notice the battle is already over. The faster they can beat their drums, the stronger they are.*

**DexID**:: 0811
**Name**:: Thwackey
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Grassy Surge|Grassy Surge]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 30.9lbs / 14.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Grookey]]   | Level  | Medium  |
| To        | [[SRD-Rillaboom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Thwackey.md"
flatten moves as T
where file.path = this.file.path
```
