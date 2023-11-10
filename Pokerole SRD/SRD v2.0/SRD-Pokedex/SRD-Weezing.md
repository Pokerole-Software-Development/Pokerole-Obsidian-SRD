---
Ability1: Levitate
Ability2: Neutralizing Gas
BookSprite: SRD-weezing-BookSprite.png
BoxSprite: SRD-weezing-BoxSprite.png
DexCategory: Poison Gas Pokemon
DexDescription: They are considered a pest in urban areas. They wait until night to
  roam and eat from the trash cans in the neighborhood. If it finds a filthy and unkempt
  house it will make its nest in there.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Koffing]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Stench
HomeSprite: SRD-weezing-HomeSprite.png
Image: weezing.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Clear Smog|Clear Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Sludge|Sludge]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
Number: 110
ShuffleToken: SRD-weezing-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 9.5
  Pounds: 20.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-weezing-BookSprite.png|wsmall]]
> ![[SRD-weezing-HomeSprite.png]]
> ![[SRD-weezing-BoxSprite.png|htiny]]
> ![[SRD-weezing-ShuffleToken.png|wsmall]]


*Poison Gas Pokemon*
*They are considered a pest in urban areas. They wait until night to roam and eat from the trash cans in the neighborhood. If it finds a filthy and unkempt house it will make its nest in there.*

**DexID**:: 0110
**Name**:: Weezing
**Type**:: Poison
**Abilities**:: [[SRD-Levitate|Levitate]] / [[SRD-Neutralizing Gas|Neutralizing Gas]] ([[SRD-Stench|Stench]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 20.9lbs / 9.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Koffing]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Weezing.md"
flatten moves as T
where file.path = this.file.path
```
