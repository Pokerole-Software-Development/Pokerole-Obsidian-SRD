---
Ability1: Stance Change
Ability2: ''
BookSprite: SRD-aegislash-blade-form-BookSprite.png
BoxSprite: SRD-aegislash-blade-form-BoxSprite.png
DexCategory: Royal Sword Pokemon
DexDescription: Those who wield this sword hear whispers of bloodlust and power. This
  cursed sword has the souls of those who fell by its blade. While in this form it
  can only use Attack moves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Aegislash]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-aegislash-blade-form-HomeSprite.png
Image: aegislash-blade-form.png
Legendary: 'No'
Moves:
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-King''s Shield|King''s Shield]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 681
ShuffleToken: SRD-aegislash-blade-form-ShuffleToken.png
Type1: Steel
Type2: Ghost
Weight:
  Kilograms: 53.0
  Pounds: 116.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aegislash-blade-form-BookSprite.png|wsmall]]
> ![[SRD-aegislash-blade-form-HomeSprite.png]]
> ![[SRD-aegislash-blade-form-BoxSprite.png|htiny]]
> ![[SRD-aegislash-blade-form-ShuffleToken.png|wsmall]]


*Royal Sword Pokemon*
*Those who wield this sword hear whispers of bloodlust and power. This cursed sword has the souls of those who fell by its blade. While in this form it can only use Attack moves.*

**DexID**:: 0681F1
**Name**:: Aegislash (Blade Form)
**Type**:: Steel / Ghost
**Abilities**:: [[SRD-Stance Change|Stance Change]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 116.8lbs / 53.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| From      | [[SRD-Aegislash]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Aegislash (Blade Form).md"
flatten moves as T
where file.path = this.file.path
```
