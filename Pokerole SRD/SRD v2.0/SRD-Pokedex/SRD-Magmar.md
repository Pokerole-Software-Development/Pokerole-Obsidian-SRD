---
Ability1: Flame Body
Ability2: ''
BookSprite: SRD-magmar-BookSprite.png
BoxSprite: SRD-magmar-BoxSprite.png
DexCategory: Spitfire Pokemon
DexDescription: It can be found living in volcanic areas. In battle, Magmar blows
  out intense flames all over its body to intimidate the opponent. This creates heat
  waves that ignite grass and trees in the surroundings.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Magby]]'
  Speed: Medium
- Evolves: To
  Item: Magmarizer
  Kind: Trade
  Pokemon: '[[SRD-Magmortar]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Vital Spirit
HomeSprite: SRD-magmar-HomeSprite.png
Image: magmar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smog|Smog]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Blast|Fire Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Karate Chop|Karate Chop]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dual Chop|Dual Chop]]'
Number: 126
ShuffleToken: SRD-magmar-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 44.5
  Pounds: 98.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magmar-BookSprite.png|wsmall]]
> ![[SRD-magmar-HomeSprite.png]]
> ![[SRD-magmar-BoxSprite.png|htiny]]
> ![[SRD-magmar-ShuffleToken.png|wsmall]]


*Spitfire Pokemon*
*It can be found living in volcanic areas. In battle, Magmar blows out intense flames all over its body to intimidate the opponent. This creates heat waves that ignite grass and trees in the surroundings.*

**DexID**:: 0126
**Name**:: Magmar
**Type**:: Fire
**Abilities**:: [[SRD-Flame Body|Flame Body]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 98.1lbs / 44.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item       |
|:----------|:------------------|:-------|:--------|:-----------|
| From      | [[SRD-Magby]]     | Level  | Medium  |            |
| To        | [[SRD-Magmortar]] | Trade  |         | Magmarizer |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Magmar.md"
flatten moves as T
where file.path = this.file.path
```
