---
Ability1: Shed Skin
Ability2: Moxie
BookSprite: SRD-scrafty-BookSprite.png
BoxSprite: SRD-scrafty-BoxSprite.png
DexCategory: Hoodlum Pokemon
DexDescription: They form gangs and beat anyone who trespasses their territory. The
  one with the biggest crest is the leader. They throw powerful kicks and their skin
  is an excellent shield. Be careful around them.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Scraggy]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Intimidate
HomeSprite: SRD-scrafty-HomeSprite.png
Image: scrafty.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Low Kick|Low Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Facade|Facade]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 560
ShuffleToken: SRD-scrafty-ShuffleToken.png
Type1: Dark
Type2: Fighting
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scrafty-BookSprite.png|wsmall]]
> ![[SRD-scrafty-HomeSprite.png]]
> ![[SRD-scrafty-BoxSprite.png|htiny]]
> ![[SRD-scrafty-ShuffleToken.png|wsmall]]


*Hoodlum Pokemon*
*They form gangs and beat anyone who trespasses their territory. The one with the biggest crest is the leader. They throw powerful kicks and their skin is an excellent shield. Be careful around them.*

**DexID**:: 0560
**Name**:: Scrafty
**Type**:: Dark / Fighting
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] / [[SRD-Moxie|Moxie]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Scraggy]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Scrafty.md"
flatten moves as T
where file.path = this.file.path
```
