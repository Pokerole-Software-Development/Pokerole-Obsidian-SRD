---
Ability1: Swift Swim
Ability2: Oblivious
BookSprite: SRD-feebas-BookSprite.png
BoxSprite: SRD-feebas-BoxSprite.png
DexCategory: Fish Pokemon
DexDescription: "This Pokemon tastes awful, it is incredibly ugly, smelly, kind of\
  \ dumb and a terrible fighter. To make things worse, it is actually extremely rare.\
  \ For those reasons, people tend to avoid it and it\u2019s usually ignored"
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Milotic]]'
  Stat: Beauty
  Value: 5
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Adaptability
HomeSprite: SRD-feebas-HomeSprite.png
Image: feebas.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brine|Brine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dive|Dive]]'
Number: 349
ShuffleToken: SRD-feebas-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 7.4
  Pounds: 16.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-feebas-BookSprite.png|wsmall]]
> ![[SRD-feebas-HomeSprite.png]]
> ![[SRD-feebas-BoxSprite.png|htiny]]
> ![[SRD-feebas-ShuffleToken.png|wsmall]]


*Fish Pokemon*
*This Pokemon tastes awful, it is incredibly ugly, smelly, kind of dumb and a terrible fighter. To make things worse, it is actually extremely rare. For those reasons, people tend to avoid it and it’s usually ignored*

**DexID**:: 0349
**Name**:: Feebas
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::2)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 16.3lbs / 7.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Stat   |   Value |
|:----------|:----------------|:-------|:-------|--------:|
| To        | [[SRD-Milotic]] | Stat   | Beauty |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Feebas.md"
flatten moves as T
where file.path = this.file.path
```
