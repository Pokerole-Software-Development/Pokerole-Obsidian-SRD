---
Ability1: Shed Skin
Ability2: ''
BookSprite: SRD-dragonair-BookSprite.png
BoxSprite: SRD-dragonair-BoxSprite.png
DexCategory: Dragon Pokemon
DexDescription: It is said to live in seas and lakes. Even though it has no wings,
  it has been depicted flying. There were legends of this Pokemon controlling the
  weather and ending the storms to leave a rainbow behind.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dratini]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dragonite]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 13.1
  Meters: 4.0
HiddenAbility: Marvel Scale
HomeSprite: SRD-dragonair-HomeSprite.png
Image: dragonair.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Mist|Mist]]'
Number: 148
ShuffleToken: SRD-dragonair-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 16.5
  Pounds: 36.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dragonair-BookSprite.png|wsmall]]
> ![[SRD-dragonair-HomeSprite.png]]
> ![[SRD-dragonair-BoxSprite.png|htiny]]
> ![[SRD-dragonair-ShuffleToken.png|wsmall]]


*Dragon Pokemon*
*It is said to live in seas and lakes. Even though it has no wings, it has been depicted flying. There were legends of this Pokemon controlling the weather and ending the storms to leave a rainbow behind.*

**DexID**:: 0148
**Name**:: Dragonair
**Type**:: Dragon
**Abilities**:: [[SRD-Shed Skin|Shed Skin]] ([[SRD-Marvel Scale|Marvel Scale]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 13'1" / 4.0m
**Weight**: 36.4lbs / 16.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Dratini]]   | Level  | Slow    |
| To        | [[SRD-Dragonite]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dragonair.md"
flatten moves as T
where file.path = this.file.path
```
