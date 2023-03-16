---
Ability1: Speed Boost
Ability2: ''
BookSprite: SRD-blaziken-mega-form-BookSprite.png
BoxSprite: SRD-blaziken-mega-form-BoxSprite.png
DexCategory: Blaze Pokemon
DexDescription: The power of the Mega Stone makes its inner fire burn so strong that
  it sets its limbs ablaze. This allows it to move faster than ever but it also takes
  a toll on its feathers as they burn to black cinders.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Blazikenite
  Kind: Mega
  Pokemon: '[[SRD-Blaziken]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-blaziken-mega-form-HomeSprite.png
Image: blaziken-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Peck|Peck]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 257
ShuffleToken: SRD-blaziken-mega-form-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 52.0
  Pounds: 114.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blaziken-mega-form-BookSprite.png|wsmall]]
> ![[SRD-blaziken-mega-form-HomeSprite.png]]
> ![[SRD-blaziken-mega-form-BoxSprite.png|htiny]]
> ![[SRD-blaziken-mega-form-ShuffleToken.png|wsmall]]


*Blaze Pokemon*
*The power of the Mega Stone makes its inner fire burn so strong that it sets its limbs ablaze. This allows it to move faster than ever but it also takes a toll on its feathers as they burn to black cinders.*

**DexID**:: 0257M1
**Name**:: Blaziken (Mega Form)
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Speed Boost|Speed Boost]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 114.6lbs / 52.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Blaziken]] | Mega   | Blazikenite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Blaziken (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
