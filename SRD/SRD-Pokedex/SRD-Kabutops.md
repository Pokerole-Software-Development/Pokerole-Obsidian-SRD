---
Ability1: Swift Swim
Ability2: Battle Armor
BookSprite: SRD-kabutops-BookSprite.png
BoxSprite: SRD-kabutops-BoxSprite.png
DexCategory: Shellfish Pokemon
DexDescription: "Kabutops swarmed underwater to hunt for prey. It was apparently evolving\
  \ from being a water dweller to living on land. It\u2019s evident from the changes\
  \ in its gills and legs. Its fossils suggests it was aggressive."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Kabuto]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Weak Armor
HomeSprite: SRD-kabutops-HomeSprite.png
Image: kabutops.png
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
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
Number: 141
ShuffleToken: SRD-kabutops-ShuffleToken.png
Type1: Rock
Type2: Water
Weight:
  Kilograms: 40.5
  Pounds: 89.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kabutops-BookSprite.png|wsmall]]
> ![[SRD-kabutops-HomeSprite.png]]
> ![[SRD-kabutops-BoxSprite.png|htiny]]
> ![[SRD-kabutops-ShuffleToken.png|wsmall]]


*Shellfish Pokemon*
*Kabutops swarmed underwater to hunt for prey. It was apparently evolving from being a water dweller to living on land. It’s evident from the changes in its gills and legs. Its fossils suggests it was aggressive.*

**DexID**:: 0141
**Name**:: Kabutops
**Type**:: Rock / Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Battle Armor|Battle Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 89.3lbs / 40.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Kabuto]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Kabutops.md"
flatten moves as T
where file.path = this.file.path
```
