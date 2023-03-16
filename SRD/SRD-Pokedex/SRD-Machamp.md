---
Ability1: Guts
Ability2: No Guard
BookSprite: SRD-machamp-BookSprite.png
BoxSprite: SRD-machamp-BoxSprite.png
DexCategory: Superpower Pokemon
DexDescription: There are a few roaming in the mountains. Machamp has the power to
  hurl anything aside. However, trying to do any work that requires care and dexterity
  may cause its arms to get tangled.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Machoke]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Steadfast
HomeSprite: SRD-machamp-HomeSprite.png
Image: machamp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Low Kick|Low Kick]]'
- - Starter
  - '[[SRD-Strength|Strength]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - Beginner
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Low Sweep|Low Sweep]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
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
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
Number: 68
ShuffleToken: SRD-machamp-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 130.0
  Pounds: 286.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-machamp-BookSprite.png|wsmall]]
> ![[SRD-machamp-HomeSprite.png]]
> ![[SRD-machamp-BoxSprite.png|htiny]]
> ![[SRD-machamp-ShuffleToken.png|wsmall]]


*Superpower Pokemon*
*There are a few roaming in the mountains. Machamp has the power to hurl anything aside. However, trying to do any work that requires care and dexterity may cause its arms to get tangled.*

**DexID**:: 0068
**Name**:: Machamp
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-No Guard|No Guard]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 286.6lbs / 130.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   |
|:----------|:----------------|:-------|
| From      | [[SRD-Machoke]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Machamp.md"
flatten moves as T
where file.path = this.file.path
```
