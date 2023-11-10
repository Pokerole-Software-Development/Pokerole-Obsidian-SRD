---
Ability1: Prism Armor
Ability2: ''
BookSprite: SRD-necrozma-dusk-mane-form-BookSprite.png
BoxSprite: SRD-necrozma-dusk-mane-form-BoxSprite.png
DexCategory: 'Aether Foundation Log #182'
DexDescription: The shadowy creature is in pain, and it hungers for any light it can
  find. I wonder how would it fare on the other side, back in our world. Would the
  sunlight ease its spirit or release a terrible monster?
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Necrozma]]'
GenderType: N
Height:
  Feet: 12.5
  Meters: 3.8
HiddenAbility: ''
HomeSprite: SRD-necrozma-dusk-mane-form-HomeSprite.png
Image: necrozma-dusk-mane-form.png
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
  - '[[SRD-Sunsteel Strike|Sunsteel Strike]]'
Number: 800
ShuffleToken: SRD-necrozma-dusk-mane-form-ShuffleToken.png
Type1: Psychic
Type2: Steel
Weight:
  Kilograms: 460.0
  Pounds: 1014.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-necrozma-dusk-mane-form-BookSprite.png|wsmall]]
> ![[SRD-necrozma-dusk-mane-form-HomeSprite.png]]
> ![[SRD-necrozma-dusk-mane-form-BoxSprite.png|htiny]]
> ![[SRD-necrozma-dusk-mane-form-ShuffleToken.png|wsmall]]


*Aether Foundation Log #182*
*The shadowy creature is in pain, and it hungers for any light it can find. I wonder how would it fare on the other side, back in our world. Would the sunlight ease its spirit or release a terrible monster?*

**DexID**:: 0800F1
**Name**:: Necrozma (Dusk Mane Form)
**Type**:: Psychic / Steel
**Abilities**:: [[SRD-Prism Armor|Prism Armor]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 12'5" / 3.8m
**Weight**: 1014.1lbs / 460.0kg
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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Necrozma (Dusk Mane Form).md"
flatten moves as T
where file.path = this.file.path
```
