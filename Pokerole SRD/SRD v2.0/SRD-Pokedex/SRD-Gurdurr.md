---
Ability1: Guts
Ability2: Sheer Force
BookSprite: SRD-gurdurr-BookSprite.png
BoxSprite: SRD-gurdurr-BoxSprite.png
DexCategory: Muscular Pokemon
DexDescription: "This Pokemon is very muscular and strongly built. It likes to show\
  \ off it\u2019s strength and muscles. Some years back a famous wrestler got defeated\
  \ in just a few seconds by one of these Pokemon."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Timburr]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Conkeldurr]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Iron Fist
HomeSprite: SRD-gurdurr-HomeSprite.png
Image: gurdurr.png
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
Number: 533
ShuffleToken: SRD-gurdurr-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gurdurr-BookSprite.png|wsmall]]
> ![[SRD-gurdurr-HomeSprite.png]]
> ![[SRD-gurdurr-BoxSprite.png|htiny]]
> ![[SRD-gurdurr-ShuffleToken.png|wsmall]]


*Muscular Pokemon*
*This Pokemon is very muscular and strongly built. It likes to show off it’s strength and muscles. Some years back a famous wrestler got defeated in just a few seconds by one of these Pokemon.*

**DexID**:: 0533
**Name**:: Gurdurr
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Timburr]]    | Level  | Medium  |
| To        | [[SRD-Conkeldurr]] | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gurdurr.md"
flatten moves as T
where file.path = this.file.path
```
