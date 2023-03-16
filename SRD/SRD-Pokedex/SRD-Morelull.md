---
Ability1: Illuminate
Ability2: Effect Spore
BookSprite: SRD-morelull-BookSprite.png
BoxSprite: SRD-morelull-BoxSprite.png
DexCategory: Illuminating Pokemon
DexDescription: Morellul are nocturnal Pokemon whose headbulbs emit a faint glow.
  They root into a tree and use its nutrients to power their light, when the tree
  is all dried up they are ready to evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Shiinotic]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Rain Dish
HomeSprite: SRD-morelull-HomeSprite.png
Image: morelull.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Flash|Flash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Moonlight|Moonlight]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Strength Sap|Strength Sap]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Spotlight|Spotlight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
Number: 755
ShuffleToken: SRD-morelull-ShuffleToken.png
Type1: Grass
Type2: Fairy
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-morelull-BookSprite.png|wsmall]]
> ![[SRD-morelull-HomeSprite.png]]
> ![[SRD-morelull-BoxSprite.png|htiny]]
> ![[SRD-morelull-ShuffleToken.png|wsmall]]


*Illuminating Pokemon*
*Morellul are nocturnal Pokemon whose headbulbs emit a faint glow. They root into a tree and use its nutrients to power their light, when the tree is all dried up they are ready to evolve.*

**DexID**:: 0755
**Name**:: Morelull
**Type**:: Grass / Fairy
**Abilities**:: [[SRD-Illuminate|Illuminate]] / [[SRD-Effect Spore|Effect Spore]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 0'7" / 0.2m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Shiinotic]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Morelull.md"
flatten moves as T
where file.path = this.file.path
```
