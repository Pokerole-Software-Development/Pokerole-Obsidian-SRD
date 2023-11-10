---
Ability1: Prism Armor
Ability2: ''
BookSprite: SRD-necrozma-BookSprite.png
BoxSprite: SRD-necrozma-BoxSprite.png
DexCategory: 'Aether Foundation Log #179'
DexDescription: First it was just a passing shadow, a shady lurker on the other side
  of the abyss, but then today it made an appearance. the creature attached itself
  to our light sources, depleting them until it was all in darkness.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Necrozma (Dusk Mane Form)]]'
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Necrozma (Dawn Wings Form)]]'
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Necrozma (Ultra Burst Form)]]'
GenderType: N
Height:
  Feet: 7.9
  Meters: 2.4
HiddenAbility: ''
HomeSprite: SRD-necrozma-HomeSprite.png
Image: necrozma.png
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
Number: 800
ShuffleToken: SRD-necrozma-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 230.0
  Pounds: 507.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-necrozma-BookSprite.png|wsmall]]
> ![[SRD-necrozma-HomeSprite.png]]
> ![[SRD-necrozma-BoxSprite.png|htiny]]
> ![[SRD-necrozma-ShuffleToken.png|wsmall]]


*Aether Foundation Log #179*
*First it was just a passing shadow, a shady lurker on the other side of the abyss, but then today it made an appearance. the creature attached itself to our light sources, depleting them until it was all in darkness.*

**DexID**:: 0800
**Name**:: Necrozma
**Type**:: Psychic
**Abilities**:: [[SRD-Prism Armor|Prism Armor]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 7'9" / 2.4m
**Weight**: 507.1lbs / 230.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                             | Kind    |
|:----------|:------------------------------------|:--------|
| To        | [[SRD-Necrozma (Dusk Mane Form)]]   | Special |
| To        | [[SRD-Necrozma (Dawn Wings Form)]]  | Special |
| To        | [[SRD-Necrozma (Ultra Burst Form)]] | Special |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Necrozma.md"
flatten moves as T
where file.path = this.file.path
```
