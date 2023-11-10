---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-dusclops-BookSprite.png
BoxSprite: SRD-dusclops-BoxSprite.png
DexCategory: Beckon Pokemon
DexDescription: "Its body is hollow. Some paranormal experts say there is a spectral\
  \ energy ball inside them but it is not confirmed. If it absorbs an object or a\
  \ creature there\u2019s the risk that nothing will come back out."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Duskull]]'
  Speed: Medium
- Evolves: To
  Item: Reaper Cloth
  Kind: Trade
  Pokemon: '[[SRD-Dusknoir]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Frisk
HomeSprite: SRD-dusclops-HomeSprite.png
Image: dusclops.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Night Shade|Night Shade]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Shadow Punch|Shadow Punch]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gravity|Gravity]]'
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
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
Number: 356
ShuffleToken: SRD-dusclops-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 30.6
  Pounds: 67.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dusclops-BookSprite.png|wsmall]]
> ![[SRD-dusclops-HomeSprite.png]]
> ![[SRD-dusclops-BoxSprite.png|htiny]]
> ![[SRD-dusclops-ShuffleToken.png|wsmall]]


*Beckon Pokemon*
*Its body is hollow. Some paranormal experts say there is a spectral energy ball inside them but it is not confirmed. If it absorbs an object or a creature there’s the risk that nothing will come back out.*

**DexID**:: 0356
**Name**:: Dusclops
**Type**:: Ghost
**Abilities**:: [[SRD-Levitate|Levitate]] ([[SRD-Frisk|Frisk]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 5'2" / 1.6m
**Weight**: 67.5lbs / 30.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   | Item         |
|:----------|:-----------------|:-------|:--------|:-------------|
| From      | [[SRD-Duskull]]  | Level  | Medium  |              |
| To        | [[SRD-Dusknoir]] | Trade  |         | Reaper Cloth |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dusclops.md"
flatten moves as T
where file.path = this.file.path
```
