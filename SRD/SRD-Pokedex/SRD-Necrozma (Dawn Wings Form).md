---
Ability1: Prism Armor
Ability2: ''
BookSprite: SRD-necrozma-dawn-wings-form-BookSprite.png
BoxSprite: SRD-necrozma-dawn-wings-form-BoxSprite.png
DexCategory: 'Aether Foundation Log #182'
DexDescription: The shadowy creature is in pain, and it hungers for any light it can
  find. I wonder how would it fare on the other side, back in our world. Would the
  moonlight ease its spirit or release a terrible monster?
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Necrozma]]'
GenderType: N
Height:
  Feet: 13.8
  Meters: 4.2
HiddenAbility: ''
HomeSprite: SRD-necrozma-dawn-wings-form-HomeSprite.png
Image: necrozma-dawn-wings-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Moonlight|Moonlight]]'
- - Master
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Master
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Stored Power|Stored Power]]'
- - Master
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Autotomize|Autotomize]]'
- - Master
  - '[[SRD-Photon Geyser (Special)|Photon Geyser (Special)]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Wring Out|Wring Out]]'
- - Master
  - '[[SRD-Prismatic Laser|Prismatic Laser]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Moongeist Beam|Moongeist Beam]]'
Number: 800
ShuffleToken: SRD-necrozma-dawn-wings-form-ShuffleToken.png
Type1: Psychic
Type2: Ghost
Weight:
  Kilograms: 350.0
  Pounds: 771.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-necrozma-dawn-wings-form-BookSprite.png|wsmall]]
> ![[SRD-necrozma-dawn-wings-form-HomeSprite.png]]
> ![[SRD-necrozma-dawn-wings-form-BoxSprite.png|htiny]]
> ![[SRD-necrozma-dawn-wings-form-ShuffleToken.png|wsmall]]


*Aether Foundation Log #182*
*The shadowy creature is in pain, and it hungers for any light it can find. I wonder how would it fare on the other side, back in our world. Would the moonlight ease its spirit or release a terrible monster?*

**DexID**:: 0800F2
**Name**:: Necrozma (Dawn Wings Form)
**Type**:: Psychic / Ghost
**Abilities**:: [[SRD-Prism Armor|Prism Armor]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 13'8" / 4.2m
**Weight**: 771.6lbs / 350.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind    |
|:----------|:-----------------|:--------|
| From      | [[SRD-Necrozma]] | Special |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Necrozma (Dawn Wings Form).md"
flatten moves as T
where file.path = this.file.path
```
