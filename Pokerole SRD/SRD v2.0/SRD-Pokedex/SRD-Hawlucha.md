---
Ability1: Limber
Ability2: Unburden
BookSprite: SRD-hawlucha-BookSprite.png
BoxSprite: SRD-hawlucha-BoxSprite.png
DexCategory: Wrestling Pokemon
DexDescription: Although small in size, its proficient fighting skills enable it to
  keep up with big bruisers like Machamp and Hariyama. Using its wings to attack from
  above allows it to gain an edge in battle.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Mold Breaker
HomeSprite: SRD-hawlucha-HomeSprite.png
Image: hawlucha.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Detect|Detect]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Flying Press|Flying Press]]'
- - Amateur
  - '[[SRD-Bounce|Bounce]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Ace
  - '[[SRD-Sky Drop|Sky Drop]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
Number: 701
ShuffleToken: SRD-hawlucha-ShuffleToken.png
Type1: Fighting
Type2: Flying
Weight:
  Kilograms: 21.5
  Pounds: 47.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hawlucha-BookSprite.png|wsmall]]
> ![[SRD-hawlucha-HomeSprite.png]]
> ![[SRD-hawlucha-BoxSprite.png|htiny]]
> ![[SRD-hawlucha-ShuffleToken.png|wsmall]]


*Wrestling Pokemon*
*Although small in size, its proficient fighting skills enable it to keep up with big bruisers like Machamp and Hariyama. Using its wings to attack from above allows it to gain an edge in battle.*

**DexID**:: 0701
**Name**:: Hawlucha
**Type**:: Fighting / Flying
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Unburden|Unburden]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 47.4lbs / 21.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hawlucha.md"
flatten moves as T
where file.path = this.file.path
```
