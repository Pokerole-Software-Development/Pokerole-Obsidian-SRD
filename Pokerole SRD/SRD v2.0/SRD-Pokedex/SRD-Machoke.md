---
Ability1: Guts
Ability2: No Guard
BookSprite: SRD-machoke-BookSprite.png
BoxSprite: SRD-machoke-BoxSprite.png
DexCategory: Superpower Pokemon
DexDescription: Even with its strong frame and power, it is a humble and helpful Pokemon.
  Many of them work for human companies. On their days off you can see them heading
  to the wild to train together.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Machop]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Machamp]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Steadfast
HomeSprite: SRD-machoke-HomeSprite.png
Image: machoke.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Low Kick|Low Kick]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Low Sweep|Low Sweep]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
- - Pro
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
Number: 67
ShuffleToken: SRD-machoke-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 70.5
  Pounds: 155.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-machoke-BookSprite.png|wsmall]]
> ![[SRD-machoke-HomeSprite.png]]
> ![[SRD-machoke-BoxSprite.png|htiny]]
> ![[SRD-machoke-ShuffleToken.png|wsmall]]


*Superpower Pokemon*
*Even with its strong frame and power, it is a humble and helpful Pokemon. Many of them work for human companies. On their days off you can see them heading to the wild to train together.*

**DexID**:: 0067
**Name**:: Machoke
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-No Guard|No Guard]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 155.4lbs / 70.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Machop]]  | Level  | Medium  |
| To        | [[SRD-Machamp]] | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Machoke.md"
flatten moves as T
where file.path = this.file.path
```
