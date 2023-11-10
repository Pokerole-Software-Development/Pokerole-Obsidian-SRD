---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-naganadel-BookSprite.png
BoxSprite: SRD-naganadel-BoxSprite.png
DexCategory: 'Aether Foundation Log #164'
DexDescription: One specimen of UB- Adhesive has apparently evolved. Its friendly
  demeanor is gone. The large streams of corrosive poison it shot seriously damaged
  our equipment, I must take a sample to study it
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Move: Dragon Pulse
  Pokemon: '[[SRD-Poipole]]'
GenderType: N
Height:
  Feet: 11.8
  Meters: 3.6
HiddenAbility: ''
HomeSprite: SRD-naganadel-HomeSprite.png
Image: naganadel.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Growl|Growl]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Acid|Acid]]'
- - Master
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
Number: 804
ShuffleToken: SRD-naganadel-ShuffleToken.png
Type1: Poison
Type2: Dragon
Weight:
  Kilograms: 150.0
  Pounds: 330.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-naganadel-BookSprite.png|wsmall]]
> ![[SRD-naganadel-HomeSprite.png]]
> ![[SRD-naganadel-BoxSprite.png|htiny]]
> ![[SRD-naganadel-ShuffleToken.png|wsmall]]


*Aether Foundation Log #164*
*One specimen of UB- Adhesive has apparently evolved. Its friendly demeanor is gone. The large streams of corrosive poison it shot seriously damaged our equipment, I must take a sample to study it*

**DexID**:: 0804
**Name**:: Naganadel
**Type**:: Poison / Dragon
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 11'8" / 3.6m
**Weight**: 330.7lbs / 150.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Move         |
|:----------|:----------------|:-------|:-------------|
| From      | [[SRD-Poipole]] | Level  | Dragon Pulse |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Naganadel.md"
flatten moves as T
where file.path = this.file.path
```
