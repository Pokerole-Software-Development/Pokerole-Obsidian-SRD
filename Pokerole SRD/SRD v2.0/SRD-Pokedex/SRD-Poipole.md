---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-poipole-BookSprite.png
BoxSprite: SRD-poipole-BoxSprite.png
DexCategory: 'Aether Foundation Log #162'
DexDescription: "Thanks to the Recon Squad we\u2019ve managed to secure a location\
  \ on the other side. UB- Adhesive have been a great help; their intelligence and\
  \ friendliness would make them very popular in our world."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Move: Dragon Pulse
  Pokemon: '[[SRD-Naganadel]]'
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-poipole-HomeSprite.png
Image: poipole.png
Legendary: 'No'
Moves:
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
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Master
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 803
ShuffleToken: SRD-poipole-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 1.8
  Pounds: 4.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-poipole-BookSprite.png|wsmall]]
> ![[SRD-poipole-HomeSprite.png]]
> ![[SRD-poipole-BoxSprite.png|htiny]]
> ![[SRD-poipole-ShuffleToken.png|wsmall]]


*Aether Foundation Log #162*
*Thanks to the Recon Squad we’ve managed to secure a location on the other side. UB- Adhesive have been a great help; their intelligence and friendliness would make them very popular in our world.*

**DexID**:: 0803
**Name**:: Poipole
**Type**:: Poison
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 4.0lbs / 1.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Move         |
|:----------|:------------------|:-------|:-------------|
| To        | [[SRD-Naganadel]] | Level  | Dragon Pulse |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Poipole.md"
flatten moves as T
where file.path = this.file.path
```
