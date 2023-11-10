---
Ability1: Shed Skin
Ability2: Moxie
BookSprite: SRD-scraggy-BookSprite.png
BoxSprite: SRD-scraggy-BoxSprite.png
DexCategory: Shedding Pokemon
DexDescription: It sheds skin constantly, but keeps wearing it since the old skin
  has a rubber-like texture and it can pull it all the way up to its head. It bashes
  foes with headbutts and is known for making dirty moves on fights.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Scrafty]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Intimidate
HomeSprite: SRD-scraggy-HomeSprite.png
Image: scraggy.png
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
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
Number: 559
ShuffleToken: SRD-scraggy-ShuffleToken.png
Type1: Dark
Type2: Fighting
Weight:
  Kilograms: 11.8
  Pounds: 26.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scraggy-BookSprite.png|wsmall]]
> ![[SRD-scraggy-HomeSprite.png]]
> ![[SRD-scraggy-BoxSprite.png|htiny]]
> ![[SRD-scraggy-ShuffleToken.png|wsmall]]


*Shedding Pokemon*
*It sheds skin constantly, but keeps wearing it since the old skin has a rubber-like texture and it can pull it all the way up to its head. It bashes foes with headbutts and is known for making dirty moves on fights.*

**DexID**:: 0559
**Name**:: Scraggy
**Type**:: Dark / Fighting
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] / [[SRD-Moxie|Moxie]] ([[SRD-Intimidate|Intimidate]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 26.0lbs / 11.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Scrafty]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Scraggy.md"
flatten moves as T
where file.path = this.file.path
```
