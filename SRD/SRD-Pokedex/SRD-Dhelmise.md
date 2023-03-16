---
Ability1: Steelworker
Ability2: ''
BookSprite: SRD-dhelmise-BookSprite.png
BoxSprite: SRD-dhelmise-BoxSprite.png
DexCategory: Sea Creeper Pokemon
DexDescription: A spirit adrift in the sea came back to life through this Pokemon
  that rarely leaves the deepest waters of the sea. Through the sea some Wailord carcasses
  have been found covered in seaweed and gashes.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 12.8
  Meters: 3.9
HiddenAbility: ''
HomeSprite: SRD-dhelmise-HomeSprite.png
Image: dhelmise.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growth|Growth]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Wrap|Wrap]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Amateur
  - '[[SRD-Anchor Shot|Anchor Shot]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Shadow Force|Shadow Force]]'
- - Ace
  - '[[SRD-Power Whip|Power Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Surf|Surf]]'
- - Pro
  - '[[SRD-Grass Knot|Grass Knot]]'
- - Pro
  - '[[SRD-Brutal Swing|Brutal Swing]]'
Number: 781
ShuffleToken: SRD-dhelmise-ShuffleToken.png
Type1: Ghost
Type2: Grass
Weight:
  Kilograms: 210.0
  Pounds: 463.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dhelmise-BookSprite.png|wsmall]]
> ![[SRD-dhelmise-HomeSprite.png]]
> ![[SRD-dhelmise-BoxSprite.png|htiny]]
> ![[SRD-dhelmise-ShuffleToken.png|wsmall]]


*Sea Creeper Pokemon*
*A spirit adrift in the sea came back to life through this Pokemon that rarely leaves the deepest waters of the sea. Through the sea some Wailord carcasses have been found covered in seaweed and gashes.*

**DexID**:: 0781
**Name**:: Dhelmise
**Type**:: Ghost / Grass
**Abilities**:: [[SRD-Steelworker|Steelworker]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 12'8" / 3.9m
**Weight**: 463.0lbs / 210.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dhelmise.md"
flatten moves as T
where file.path = this.file.path
```
