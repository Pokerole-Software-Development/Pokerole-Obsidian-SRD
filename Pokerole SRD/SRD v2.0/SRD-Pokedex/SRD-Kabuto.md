---
Ability1: Swift Swim
Ability2: Battle Armor
BookSprite: SRD-kabuto-BookSprite.png
BoxSprite: SRD-kabuto-BoxSprite.png
DexCategory: Shellfish Pokemon
DexDescription: Kabuto is a Pokemon that has been regenerated from a fossil. However,
  in extremely rare cases, living specimens have been found. The Pokemon has not changed
  at all for 300 million years.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kabutops]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Weak Armor
HomeSprite: SRD-kabuto-HomeSprite.png
Image: kabuto.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 140
ShuffleToken: SRD-kabuto-ShuffleToken.png
Type1: Rock
Type2: Water
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kabuto-BookSprite.png|wsmall]]
> ![[SRD-kabuto-HomeSprite.png]]
> ![[SRD-kabuto-BoxSprite.png|htiny]]
> ![[SRD-kabuto-ShuffleToken.png|wsmall]]


*Shellfish Pokemon*
*Kabuto is a Pokemon that has been regenerated from a fossil. However, in extremely rare cases, living specimens have been found. The Pokemon has not changed at all for 300 million years.*

**DexID**:: 0140
**Name**:: Kabuto
**Type**:: Rock / Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Battle Armor|Battle Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Kabutops]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kabuto.md"
flatten moves as T
where file.path = this.file.path
```
