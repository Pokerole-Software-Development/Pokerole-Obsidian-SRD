---
Ability1: Intimidate
Ability2: Shed Skin
BookSprite: SRD-ekans-BookSprite.png
BoxSprite: SRD-ekans-BoxSprite.png
DexCategory: Snake Pokemon
DexDescription: "Lives on grasslands. Preys on Rattatas and Pokemon Eggs it finds.\
  \ It\u2019s jaw can detach itself to swallow any prey whole. It coils and sleeps\
  \ after eating. Ekans grow bigger with age."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Arbok]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Unnerve
HomeSprite: SRD-ekans-HomeSprite.png
Image: ekans.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Glare|Glare]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[SRD-Disable|Disable]]'
Number: 23
ShuffleToken: SRD-ekans-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 6.9
  Pounds: 15.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ekans-BookSprite.png|wsmall]]
> ![[SRD-ekans-HomeSprite.png]]
> ![[SRD-ekans-BoxSprite.png|htiny]]
> ![[SRD-ekans-ShuffleToken.png|wsmall]]


*Snake Pokemon*
*Lives on grasslands. Preys on Rattatas and Pokemon Eggs it finds. It’s jaw can detach itself to swallow any prey whole. It coils and sleeps after eating. Ekans grow bigger with age.*

**DexID**:: 0023
**Name**:: Ekans
**Type**:: Poison
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Shed Skin|Shed Skin]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'6" / 2.0m
**Weight**: 15.2lbs / 6.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| To        | [[SRD-Arbok]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ekans.md"
flatten moves as T
where file.path = this.file.path
```
