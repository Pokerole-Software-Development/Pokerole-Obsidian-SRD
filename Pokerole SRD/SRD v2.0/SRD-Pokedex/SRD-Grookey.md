---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-grookey-BookSprite.png
BoxSprite: SRD-grookey-BoxSprite.png
DexCategory: Chimp Pokemon
DexDescription: They spend their early days looking for a stick with a certain sound,
  it then uses the stick to create rhythmic beats that makes plan glow and grow. Grookey
  are enthusiastic and kind creatures that love music.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Thwackey]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Grassy Surge
HomeSprite: SRD-grookey-HomeSprite.png
Image: grookey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Branch Poke|Branch Poke]]'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Grass Pledge|Grass Pledge]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
Number: 810
ShuffleToken: SRD-grookey-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grookey-BookSprite.png|wsmall]]
> ![[SRD-grookey-HomeSprite.png]]
> ![[SRD-grookey-BoxSprite.png|htiny]]
> ![[SRD-grookey-ShuffleToken.png|wsmall]]


*Chimp Pokemon*
*They spend their early days looking for a stick with a certain sound, it then uses the stick to create rhythmic beats that makes plan glow and grow. Grookey are enthusiastic and kind creatures that love music.*

**DexID**:: 0810
**Name**:: Grookey
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Grassy Surge|Grassy Surge]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Thwackey]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Grookey.md"
flatten moves as T
where file.path = this.file.path
```
