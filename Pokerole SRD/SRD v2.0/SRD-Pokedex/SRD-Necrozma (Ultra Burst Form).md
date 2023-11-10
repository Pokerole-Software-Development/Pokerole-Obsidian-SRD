---
Ability1: Neuroforce
Ability2: ''
BookSprite: SRD-necrozma-ultra-burst-form-BookSprite.png
BoxSprite: SRD-necrozma-ultra-burst-form-BoxSprite.png
DexCategory: Aether Foundation S.O.S Message
DexDescription: Alert to national authorities we had a serious breach of security!
  This is an emergency! Close the port- (White Noise).
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Necrozma]]'
GenderType: N
Height:
  Feet: 24.6
  Meters: 7.5
HiddenAbility: ''
HomeSprite: SRD-necrozma-ultra-burst-form-HomeSprite.png
Image: necrozma-ultra-burst-form.png
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
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Sunsteel Strike|Sunsteel Strike]]'
- - Master
  - '[[SRD-Moongeist Beam|Moongeist Beam]]'
Number: 800
ShuffleToken: SRD-necrozma-ultra-burst-form-ShuffleToken.png
Type1: Psychic
Type2: Dragon
Weight:
  Kilograms: 230.0
  Pounds: 507.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-necrozma-ultra-burst-form-BookSprite.png|wsmall]]
> ![[SRD-necrozma-ultra-burst-form-HomeSprite.png]]
> ![[SRD-necrozma-ultra-burst-form-BoxSprite.png|htiny]]
> ![[SRD-necrozma-ultra-burst-form-ShuffleToken.png|wsmall]]


*Aether Foundation S.O.S Message*
*Alert to national authorities we had a serious breach of security! This is an emergency! Close the port- (White Noise).*

**DexID**:: 0800F3
**Name**:: Necrozma (Ultra Burst Form)
**Type**:: Psychic / Dragon
**Abilities**:: [[SRD-Neuroforce|Neuroforce]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 24'6" / 7.5m
**Weight**: 507.1lbs / 230.0kg
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Necrozma (Ultra Burst Form).md"
flatten moves as T
where file.path = this.file.path
```
