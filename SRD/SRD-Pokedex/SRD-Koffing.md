---
Ability1: Levitate
Ability2: Neutralizing Gas
BookSprite: SRD-koffing-BookSprite.png
BoxSprite: SRD-koffing-BoxSprite.png
DexCategory: Poison Gas Pokemon
DexDescription: It is drawn to the smog and fumes of the cities. It fills its body
  with toxic gases to float like a balloon. When it gets nervous it releases a sickly
  green gas. Breathing this gas will give you a bad case of sniffles.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Weezing]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Weezing (Galarian Form)]]'
  Region: Galar
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Stench
HomeSprite: SRD-koffing-HomeSprite.png
Image: koffing.png
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
  - '[[SRD-Gyro Ball|Gyro Ball]]'
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
  - '[[SRD-Rollout|Rollout]]'
Number: 109
ShuffleToken: SRD-koffing-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-koffing-BookSprite.png|wsmall]]
> ![[SRD-koffing-HomeSprite.png]]
> ![[SRD-koffing-BoxSprite.png|htiny]]
> ![[SRD-koffing-ShuffleToken.png|wsmall]]


*Poison Gas Pokemon*
*It is drawn to the smog and fumes of the cities. It fills its body with toxic gases to float like a balloon. When it gets nervous it releases a sickly green gas. Breathing this gas will give you a bad case of sniffles.*

**DexID**:: 0109
**Name**:: Koffing
**Type**:: Poison
**Abilities**:: [[SRD-Levitate|Levitate]] / [[SRD-Neutralizing Gas|Neutralizing Gas]] ([[SRD-Stench|Stench]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   | Speed   | Region   |
|:----------|:--------------------------------|:-------|:--------|:---------|
| To        | [[SRD-Weezing]]                 | Level  | Slow    |          |
| To        | [[SRD-Weezing (Galarian Form)]] | Level  | Slow    | Galar    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Koffing.md"
flatten moves as T
where file.path = this.file.path
```
