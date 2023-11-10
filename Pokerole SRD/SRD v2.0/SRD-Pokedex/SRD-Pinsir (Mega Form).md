---
Ability1: Aerilate
Ability2: ''
BookSprite: SRD-pinsir-mega-form-BookSprite.png
BoxSprite: SRD-pinsir-mega-form-BoxSprite.png
DexCategory: Stagbeetle Pokemon
DexDescription: With the power of the Mega Stone it develops wings and inhuman strength.
  It can lift foes heavier than itself and still fly with ease. Its mind is in a constant
  state of excitement and it cannot stay still.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Pinsirite
  Kind: Mega
  Pokemon: '[[SRD-Pinsir]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-pinsir-mega-form-HomeSprite.png
Image: pinsir-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Storm Throw|Storm Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
Number: 127
ShuffleToken: SRD-pinsir-mega-form-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 59.0
  Pounds: 130.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pinsir-mega-form-BookSprite.png|wsmall]]
> ![[SRD-pinsir-mega-form-HomeSprite.png]]
> ![[SRD-pinsir-mega-form-BoxSprite.png|htiny]]
> ![[SRD-pinsir-mega-form-ShuffleToken.png|wsmall]]


*Stagbeetle Pokemon*
*With the power of the Mega Stone it develops wings and inhuman strength. It can lift foes heavier than itself and still fly with ease. Its mind is in a constant state of excitement and it cannot stay still.*

**DexID**:: 0127M1
**Name**:: Pinsir (Mega Form)
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Aerilate|Aerilate]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 130.1lbs / 59.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Pinsir]] | Mega   | Pinsirite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pinsir (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
