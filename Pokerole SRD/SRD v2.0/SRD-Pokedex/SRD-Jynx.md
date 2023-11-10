---
Ability1: Oblivious
Ability2: Forewarn
BookSprite: SRD-jynx-BookSprite.png
BoxSprite: SRD-jynx-BoxSprite.png
DexCategory: Humanshape Pokemon
DexDescription: It is not common outside cold areas. This Pokemon is female only.
  Its cries sound like human speech. However, it is impossible to tell what it is
  trying to say. The way it moves and talks induce others to dance.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Smoochum]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Dry Skin
HomeSprite: SRD-jynx-HomeSprite.png
Image: jynx.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lovely Kiss|Lovely Kiss]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Heart Stamp|Heart Stamp]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Avalanche|Avalanche]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Number: 124
ShuffleToken: SRD-jynx-ShuffleToken.png
Type1: Ice
Type2: Psychic
Weight:
  Kilograms: 40.6
  Pounds: 89.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jynx-BookSprite.png|wsmall]]
> ![[SRD-jynx-HomeSprite.png]]
> ![[SRD-jynx-BoxSprite.png|htiny]]
> ![[SRD-jynx-ShuffleToken.png|wsmall]]


*Humanshape Pokemon*
*It is not common outside cold areas. This Pokemon is female only. Its cries sound like human speech. However, it is impossible to tell what it is trying to say. The way it moves and talks induce others to dance.*

**DexID**:: 0124
**Name**:: Jynx
**Type**:: Ice / Psychic
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Forewarn|Forewarn]] ([[SRD-Dry Skin|Dry Skin]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 89.5lbs / 40.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Smoochum]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jynx.md"
flatten moves as T
where file.path = this.file.path
```
