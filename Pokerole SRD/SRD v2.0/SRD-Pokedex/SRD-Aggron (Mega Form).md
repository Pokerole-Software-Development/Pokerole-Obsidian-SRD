---
Ability1: Filter
Ability2: ''
BookSprite: SRD-aggron-mega-form-BookSprite.png
BoxSprite: SRD-aggron-mega-form-BoxSprite.png
DexCategory: Iron Armor Pokemon
DexDescription: The power of the Mega Stone makes their already-small caring nature
  disappear. They become relentless and more machine-like, trampling their way around
  as nothing can penetrate their armor.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Aggronite
  Kind: Mega
  Pokemon: '[[SRD-Aggron]]'
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: ''
HomeSprite: SRD-aggron-mega-form-HomeSprite.png
Image: aggron-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Autotomize|Autotomize]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 306
ShuffleToken: SRD-aggron-mega-form-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 395.0
  Pounds: 870.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aggron-mega-form-BookSprite.png|wsmall]]
> ![[SRD-aggron-mega-form-HomeSprite.png]]
> ![[SRD-aggron-mega-form-BoxSprite.png|htiny]]
> ![[SRD-aggron-mega-form-ShuffleToken.png|wsmall]]


*Iron Armor Pokemon*
*The power of the Mega Stone makes their already-small caring nature disappear. They become relentless and more machine-like, trampling their way around as nothing can penetrate their armor.*

**DexID**:: 0306M1
**Name**:: Aggron (Mega Form)
**Type**:: Steel
**Abilities**:: [[SRD-Filter|Filter]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::11)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 870.8lbs / 395.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Aggron]] | Mega   | Aggronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aggron (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
