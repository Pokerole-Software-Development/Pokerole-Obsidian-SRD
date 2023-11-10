---
Ability1: Sheer Force
Ability2: ''
BookSprite: SRD-camerupt-mega-form-BookSprite.png
BoxSprite: SRD-camerupt-mega-form-BoxSprite.png
DexCategory: Eruption Pokemon
DexDescription: The power of the Mega Stone melts its two humps into a single one.
  The single hump is heavier making it slower, but its newly renewed attitude makes
  the hump erupt in heavy bursts of molten lava.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Cameruptite
  Kind: Mega
  Pokemon: '[[SRD-Camerupt]]'
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: ''
HomeSprite: SRD-camerupt-mega-form-HomeSprite.png
Image: camerupt-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Magnitude|Magnitude]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 323
ShuffleToken: SRD-camerupt-mega-form-ShuffleToken.png
Type1: Fire
Type2: Ground
Weight:
  Kilograms: 320.5
  Pounds: 706.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-camerupt-mega-form-BookSprite.png|wsmall]]
> ![[SRD-camerupt-mega-form-HomeSprite.png]]
> ![[SRD-camerupt-mega-form-BoxSprite.png|htiny]]
> ![[SRD-camerupt-mega-form-ShuffleToken.png|wsmall]]


*Eruption Pokemon*
*The power of the Mega Stone melts its two humps into a single one. The single hump is heavier making it slower, but its newly renewed attitude makes the hump erupt in heavy bursts of molten lava.*

**DexID**:: 0323M1
**Name**:: Camerupt (Mega Form)
**Type**:: Fire / Ground
**Abilities**:: [[SRD-Sheer Force|Sheer Force]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 8'2" / 2.5m
**Weight**: 706.6lbs / 320.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Camerupt]] | Mega   | Cameruptite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Camerupt (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
