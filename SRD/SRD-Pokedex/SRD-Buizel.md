---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-buizel-BookSprite.png
BoxSprite: SRD-buizel-BoxSprite.png
DexCategory: Sea Weasel Pokemon
DexDescription: It is usually seen close to streams and rivers. Buizel swims by rotating
  its two tails like a screw, the sack around its neck swells to help it float or
  deflates to dive underwater and catch prey.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Floatzel]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Water Veil
HomeSprite: SRD-buizel-HomeSprite.png
Image: buizel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Tail Slap|Tail Slap]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
Number: 418
ShuffleToken: SRD-buizel-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 29.5
  Pounds: 65.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-buizel-BookSprite.png|wsmall]]
> ![[SRD-buizel-HomeSprite.png]]
> ![[SRD-buizel-BoxSprite.png|htiny]]
> ![[SRD-buizel-ShuffleToken.png|wsmall]]


*Sea Weasel Pokemon*
*It is usually seen close to streams and rivers. Buizel swims by rotating its two tails like a screw, the sack around its neck swells to help it float or deflates to dive underwater and catch prey.*

**DexID**:: 0418
**Name**:: Buizel
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Water Veil|Water Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 65.0lbs / 29.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Floatzel]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Buizel.md"
flatten moves as T
where file.path = this.file.path
```
