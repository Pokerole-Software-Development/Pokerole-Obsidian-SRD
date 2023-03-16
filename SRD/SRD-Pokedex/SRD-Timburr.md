---
Ability1: Guts
Ability2: Sheer Force
BookSprite: SRD-timburr-BookSprite.png
BoxSprite: SRD-timburr-BoxSprite.png
DexCategory: Muscular Pokemon
DexDescription: They carry a big log as a tool and as a weapon. You may see them helping
  with construction work as they strive to challenge their strength. When it can swing
  the log without problems it is close to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gurdurr]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Iron Fist
HomeSprite: SRD-timburr-HomeSprite.png
Image: timburr.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Low Kick|Low Kick]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Foresight|Foresight]]'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 532
ShuffleToken: SRD-timburr-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-timburr-BookSprite.png|wsmall]]
> ![[SRD-timburr-HomeSprite.png]]
> ![[SRD-timburr-BoxSprite.png|htiny]]
> ![[SRD-timburr-ShuffleToken.png|wsmall]]


*Muscular Pokemon*
*They carry a big log as a tool and as a weapon. You may see them helping with construction work as they strive to challenge their strength. When it can swing the log without problems it is close to evolve.*

**DexID**:: 0532
**Name**:: Timburr
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Gurdurr]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Timburr.md"
flatten moves as T
where file.path = this.file.path
```
