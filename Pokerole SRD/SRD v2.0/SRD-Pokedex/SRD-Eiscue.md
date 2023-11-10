---
Ability1: Ice Face
Ability2: ''
BookSprite: SRD-eiscue-BookSprite.png
BoxSprite: SRD-eiscue-BoxSprite.png
DexCategory: Penguin Pokemon
DexDescription: This Pokemon keeps its head cool with ice. It fishes for its food
  by dangling its single hair into the sea to lure in prey. When they tire of swimming
  they simply let their ice hear be drifted away by the sea.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Eiscue (No Ice Form)]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-eiscue-HomeSprite.png
Image: eiscue.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Ace
  - '[[SRD-Surf|Surf]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
Number: 875
ShuffleToken: SRD-eiscue-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 89.0
  Pounds: 196.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eiscue-BookSprite.png|wsmall]]
> ![[SRD-eiscue-HomeSprite.png]]
> ![[SRD-eiscue-BoxSprite.png|htiny]]
> ![[SRD-eiscue-ShuffleToken.png|wsmall]]


*Penguin Pokemon*
*This Pokemon keeps its head cool with ice. It fishes for its food by dangling its single hair into the sea to lure in prey. When they tire of swimming they simply let their ice hear be drifted away by the sea.*

**DexID**:: 0875
**Name**:: Eiscue
**Type**:: Ice
**Abilities**:: [[SRD-Ice Face|Ice Face]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 196.2lbs / 89.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   |
|:----------|:-----------------------------|:-------|
| To        | [[SRD-Eiscue (No Ice Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Eiscue.md"
flatten moves as T
where file.path = this.file.path
```
