---
Ability1: Honey Gather
Ability2: ''
BookSprite: SRD-combee-BookSprite.png
BoxSprite: SRD-combee-BoxSprite.png
DexCategory: Tiny Bee Pokemon
DexDescription: It forms hives around trees. It flies all day sipping the nectar from
  flowers to make honey. It is usually born a male. If a female is born, it will grow
  into a Vespiqueen and start its own Hive.
EventAbilities: ''
Evolutions:
- Evolves: To
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Vespiquen]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Hustle
HomeSprite: SRD-combee-HomeSprite.png
Image: combee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endeavor|Endeavor]]'
Number: 415
ShuffleToken: SRD-combee-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-combee-BookSprite.png|wsmall]]
> ![[SRD-combee-HomeSprite.png]]
> ![[SRD-combee-BoxSprite.png|htiny]]
> ![[SRD-combee-ShuffleToken.png|wsmall]]


*Tiny Bee Pokemon*
*It forms hives around trees. It flies all day sipping the nectar from flowers to make honey. It is usually born a male. If a female is born, it will grow into a Vespiqueen and start its own Hive.*

**DexID**:: 0415
**Name**:: Combee
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Honey Gather|Honey Gather]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   | Gender   |
|:----------|:------------------|:-------|:--------|:---------|
| To        | [[SRD-Vespiquen]] | Level  | Slow    | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Combee.md"
flatten moves as T
where file.path = this.file.path
```
