---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-dusknoir-BookSprite.png
BoxSprite: SRD-dusknoir-BoxSprite.png
DexCategory: Gripper Pokemon
DexDescription: "This feared Pokemon is said to travel to the other world. Some even\
  \ believe that it takes lost spirits along with it. It uses the antenna on it\u2019\
  s head to receive messages from the deceased."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Reaper Cloth
  Kind: Trade
  Pokemon: '[[SRD-Dusclops]]'
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Frisk
HomeSprite: SRD-dusknoir-HomeSprite.png
Image: dusknoir.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bind|Bind]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Shadow Punch|Shadow Punch]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gravity|Gravity]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Mean Look|Mean Look]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
- - Pro
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 477
ShuffleToken: SRD-dusknoir-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 106.6
  Pounds: 235.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dusknoir-BookSprite.png|wsmall]]
> ![[SRD-dusknoir-HomeSprite.png]]
> ![[SRD-dusknoir-BoxSprite.png|htiny]]
> ![[SRD-dusknoir-ShuffleToken.png|wsmall]]


*Gripper Pokemon*
*This feared Pokemon is said to travel to the other world. Some even believe that it takes lost spirits along with it. It uses the antenna on it’s head to receive messages from the deceased.*

**DexID**:: 0477
**Name**:: Dusknoir
**Type**:: Ghost
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Frisk|Frisk]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 7'2" / 2.2m
**Weight**: 235.0lbs / 106.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item         |
|:----------|:-----------------|:-------|:-------------|
| From      | [[SRD-Dusclops]] | Trade  | Reaper Cloth |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dusknoir.md"
flatten moves as T
where file.path = this.file.path
```
