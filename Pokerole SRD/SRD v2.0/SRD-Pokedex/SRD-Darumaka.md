---
Ability1: Hustle
Ability2: ''
BookSprite: SRD-darumaka-BookSprite.png
BoxSprite: SRD-darumaka-BoxSprite.png
DexCategory: Zen Charm Pokemon
DexDescription: Lives on deserts and arid terrains. It has a flame inside its body.
  When the flame burns brightly it becomes very active running around, when the flame
  is low it falls asleep. Their droppings double as a bonfire.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Darmanitan]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Inner Focus
HomeSprite: SRD-darumaka-HomeSprite.png
Image: darumaka.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Incinerate|Incinerate]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Fire Fang|Fire Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Facade|Facade]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Belly Drum|Belly Drum]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 554
ShuffleToken: SRD-darumaka-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 37.5
  Pounds: 82.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darumaka-BookSprite.png|wsmall]]
> ![[SRD-darumaka-HomeSprite.png]]
> ![[SRD-darumaka-BoxSprite.png|htiny]]
> ![[SRD-darumaka-ShuffleToken.png|wsmall]]


*Zen Charm Pokemon*
*Lives on deserts and arid terrains. It has a flame inside its body. When the flame burns brightly it becomes very active running around, when the flame is low it falls asleep. Their droppings double as a bonfire.*

**DexID**:: 0554
**Name**:: Darumaka
**Type**:: Fire
**Abilities**:: [[SRD-Hustle|Hustle]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 82.7lbs / 37.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Darmanitan]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Darumaka.md"
flatten moves as T
where file.path = this.file.path
```
