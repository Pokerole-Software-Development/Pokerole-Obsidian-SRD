---
Ability1: Poison Point
Ability2: Poison Touch
BookSprite: SRD-skrelp-BookSprite.png
BoxSprite: SRD-skrelp-BoxSprite.png
DexCategory: Mock Kelp Pokemon
DexDescription: Camouflaged as rotten kelp they spray liquid poison on a prey that
  approaches unaware. It needs to store a lot of energy to be able to evolve so it
  takes them a long time. Touching one will give you a fever.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dragalge]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Adaptability
HomeSprite: SRD-skrelp-HomeSprite.png
Image: skrelp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
Number: 690
ShuffleToken: SRD-skrelp-ShuffleToken.png
Type1: Poison
Type2: Water
Weight:
  Kilograms: 7.3
  Pounds: 16.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skrelp-BookSprite.png|wsmall]]
> ![[SRD-skrelp-HomeSprite.png]]
> ![[SRD-skrelp-BoxSprite.png|htiny]]
> ![[SRD-skrelp-ShuffleToken.png|wsmall]]


*Mock Kelp Pokemon*
*Camouflaged as rotten kelp they spray liquid poison on a prey that approaches unaware. It needs to store a lot of energy to be able to evolve so it takes them a long time. Touching one will give you a fever.*

**DexID**:: 0690
**Name**:: Skrelp
**Type**:: Poison / Water
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Poison Touch|Poison Touch]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 16.1lbs / 7.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Dragalge]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Skrelp.md"
flatten moves as T
where file.path = this.file.path
```
