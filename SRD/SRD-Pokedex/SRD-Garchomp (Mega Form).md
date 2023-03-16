---
Ability1: Sand Force
Ability2: ''
BookSprite: SRD-garchomp-mega-form-BookSprite.png
BoxSprite: SRD-garchomp-mega-form-BoxSprite.png
DexCategory: Mach Pokemon
DexDescription: The excess of power from the Mega Stone melted its fins and claws
  together forming sharp, dangerous scythes. If its disposition was already violent,
  it grows now by a tenfold. They can be vicious and feral.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Garchompite
  Kind: Mega
  Pokemon: '[[SRD-Garchomp]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: ''
HomeSprite: SRD-garchomp-mega-form-HomeSprite.png
Image: garchomp-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 445
ShuffleToken: SRD-garchomp-mega-form-ShuffleToken.png
Type1: Dragon
Type2: Ground
Weight:
  Kilograms: 95.0
  Pounds: 209.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-garchomp-mega-form-BookSprite.png|wsmall]]
> ![[SRD-garchomp-mega-form-HomeSprite.png]]
> ![[SRD-garchomp-mega-form-BoxSprite.png|htiny]]
> ![[SRD-garchomp-mega-form-ShuffleToken.png|wsmall]]


*Mach Pokemon*
*The excess of power from the Mega Stone melted its fins and claws together forming sharp, dangerous scythes. If its disposition was already violent, it grows now by a tenfold. They can be vicious and feral.*

**DexID**:: 0445M1
**Name**:: Garchomp (Mega Form)
**Type**:: Dragon / Ground
**Abilities**:: [[SRD-Sand Force|Sand Force]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'2" / 1.9m
**Weight**: 209.4lbs / 95.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| From      | [[SRD-Garchomp]] | Mega   | Garchompite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Garchomp (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
