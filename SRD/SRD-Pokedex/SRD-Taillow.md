---
Ability1: Guts
Ability2: ''
BookSprite: SRD-taillow-BookSprite.png
BoxSprite: SRD-taillow-BoxSprite.png
DexCategory: Tiny Swallow Pokemon
DexDescription: They are brave and noble, facing bigger foes whoever they might be.
  However, being just a child, it usually feels lonely and cries at night. They can
  be seen migrating south in the winter.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Swellow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Scrappy
HomeSprite: SRD-taillow-HomeSprite.png
Image: taillow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Rage|Rage]]'
Number: 276
ShuffleToken: SRD-taillow-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 2.3
  Pounds: 5.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-taillow-BookSprite.png|wsmall]]
> ![[SRD-taillow-HomeSprite.png]]
> ![[SRD-taillow-BoxSprite.png|htiny]]
> ![[SRD-taillow-ShuffleToken.png|wsmall]]


*Tiny Swallow Pokemon*
*They are brave and noble, facing bigger foes whoever they might be. However, being just a child, it usually feels lonely and cries at night. They can be seen migrating south in the winter.*

**DexID**:: 0276
**Name**:: Taillow
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Guts|Guts]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 5.1lbs / 2.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Swellow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Taillow.md"
flatten moves as T
where file.path = this.file.path
```
