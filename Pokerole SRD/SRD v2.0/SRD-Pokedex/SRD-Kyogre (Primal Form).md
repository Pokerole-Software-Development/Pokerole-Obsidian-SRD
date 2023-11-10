---
Ability1: Primordial Sea
Ability2: ''
BookSprite: SRD-kyogre-primal-form-BookSprite.png
BoxSprite: SRD-kyogre-primal-form-BoxSprite.png
DexCategory: No Data
DexDescription: Millions of years ago chaos reigned. Neverending typhoons drowning
  all life under unforgiving waters. Who was so sad and hurt in the deep darkness
  of the sea? As its sapphire tears still flood the world.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Kyogre]]'
GenderType: N
Height:
  Feet: 32.2
  Meters: 9.8
HiddenAbility: ''
HomeSprite: SRD-kyogre-primal-form-HomeSprite.png
Image: kyogre-primal-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Origin Pulse|Origin Pulse]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Water Spout|Water Spout]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Splishy Splash|Splishy Splash]]'
- - Master
  - '[[SRD-Steam Eruption|Steam Eruption]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
Number: 382
ShuffleToken: SRD-kyogre-primal-form-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 430.0
  Pounds: 948.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kyogre-primal-form-BookSprite.png|wsmall]]
> ![[SRD-kyogre-primal-form-HomeSprite.png]]
> ![[SRD-kyogre-primal-form-BoxSprite.png|htiny]]
> ![[SRD-kyogre-primal-form-ShuffleToken.png|wsmall]]


*No Data*
*Millions of years ago chaos reigned. Neverending typhoons drowning all life under unforgiving waters. Who was so sad and hurt in the deep darkness of the sea? As its sapphire tears still flood the world.*

**DexID**:: 0382M1
**Name**:: Kyogre (Primal Form)
**Type**:: Water
**Abilities**:: [[SRD-Primordial Sea|Primordial Sea]]
**Base HP**:: 10

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::9)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::8)/(MaxInsight::8)     |

**Height**: 32'2" / 9.8m
**Weight**: 948.0lbs / 430.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Kyogre]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kyogre (Primal Form).md"
flatten moves as T
where file.path = this.file.path
```
