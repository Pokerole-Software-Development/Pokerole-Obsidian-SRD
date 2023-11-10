---
Ability1: Sand Force
Ability2: ''
BookSprite: SRD-steelix-mega-form-BookSprite.png
BoxSprite: SRD-steelix-mega-form-BoxSprite.png
DexCategory: Iron Snake Pokemon
DexDescription: "With the power of the Mega Stone its body goes through so much pressure\
  \ that part of it becomes diamond crystals. Its defense is almost unbreakable but\
  \ its temper is short and it\u2019s easily angered."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Steelixite
  Kind: Mega
  Pokemon: '[[SRD-Steelix]]'
GenderType: ''
Height:
  Feet: 34.4
  Meters: 10.5
HiddenAbility: ''
HomeSprite: SRD-steelix-mega-form-HomeSprite.png
Image: steelix-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bind|Bind]]'
- - Starter
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 208
ShuffleToken: SRD-steelix-mega-form-ShuffleToken.png
Type1: Steel
Type2: Ground
Weight:
  Kilograms: 740.0
  Pounds: 1631.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-steelix-mega-form-BookSprite.png|wsmall]]
> ![[SRD-steelix-mega-form-HomeSprite.png]]
> ![[SRD-steelix-mega-form-BoxSprite.png|htiny]]
> ![[SRD-steelix-mega-form-ShuffleToken.png|wsmall]]


*Iron Snake Pokemon*
*With the power of the Mega Stone its body goes through so much pressure that part of it becomes diamond crystals. Its defense is almost unbreakable but its temper is short and it’s easily angered.*

**DexID**:: 0208M1
**Name**:: Steelix (Mega Form)
**Type**:: Steel / Ground
**Abilities**:: [[SRD-Sand Force|Sand Force]]
**Base HP**:: 10

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::11)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 34'4" / 10.5m
**Weight**: 1631.4lbs / 740.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Steelix]] | Mega   | Steelixite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Steelix (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
