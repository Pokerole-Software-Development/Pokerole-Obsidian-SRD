---
Ability1: Keen Eye
Ability2: Big Pecks
BookSprite: SRD-ducklett-BookSprite.png
BoxSprite: SRD-ducklett-BoxSprite.png
DexCategory: Water Bird Pokemon
DexDescription: These bird Pokemon are excellent divers. They swim around in the water
  eating their favorite food, peat moss. They can shoot a spray mist with their feathers
  to protect from any predator that comes.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Swanna]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Hydration
HomeSprite: SRD-ducklett-HomeSprite.png
Image: ducklett.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defog|Defog]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Number: 580
ShuffleToken: SRD-ducklett-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ducklett-BookSprite.png|wsmall]]
> ![[SRD-ducklett-HomeSprite.png]]
> ![[SRD-ducklett-BoxSprite.png|htiny]]
> ![[SRD-ducklett-ShuffleToken.png|wsmall]]


*Water Bird Pokemon*
*These bird Pokemon are excellent divers. They swim around in the water eating their favorite food, peat moss. They can shoot a spray mist with their feathers to protect from any predator that comes.*

**DexID**:: 0580
**Name**:: Ducklett
**Type**:: Water / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Big Pecks|Big Pecks]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Swanna]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ducklett.md"
flatten moves as T
where file.path = this.file.path
```
