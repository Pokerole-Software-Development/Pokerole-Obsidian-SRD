---
Ability1: Chlorophyll
Ability2: Solar Power
BookSprite: SRD-tropius-BookSprite.png
BoxSprite: SRD-tropius-BoxSprite.png
DexCategory: Fruit Pokemon
DexDescription: It is very common in humid and hot regions. It can grow back the fruit
  it has eaten. Mothers prefer Tropius fruits to feed their children as it is more
  nutritive and sweet. They are mellow and friendly Pokemon.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Harvest
HomeSprite: SRD-tropius-HomeSprite.png
Image: tropius.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bestow|Bestow]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Tornado|Leaf Tornado]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
Number: 357
ShuffleToken: SRD-tropius-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 100.0
  Pounds: 220.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tropius-BookSprite.png|wsmall]]
> ![[SRD-tropius-HomeSprite.png]]
> ![[SRD-tropius-BoxSprite.png|htiny]]
> ![[SRD-tropius-ShuffleToken.png|wsmall]]


*Fruit Pokemon*
*It is very common in humid and hot regions. It can grow back the fruit it has eaten. Mothers prefer Tropius fruits to feed their children as it is more nutritive and sweet. They are mellow and friendly Pokemon.*

**DexID**:: 0357
**Name**:: Tropius
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Solar Power|Solar Power]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 220.5lbs / 100.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tropius.md"
flatten moves as T
where file.path = this.file.path
```
