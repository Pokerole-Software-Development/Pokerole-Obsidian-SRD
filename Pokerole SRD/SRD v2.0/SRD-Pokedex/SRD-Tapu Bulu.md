---
Ability1: Grassy Surge
Ability2: ''
BookSprite: SRD-tapu-bulu-BookSprite.png
BoxSprite: SRD-tapu-bulu-BoxSprite.png
DexCategory: No Data
DexDescription: Through Ula'ula island runs the legend of a lazy guardian spirit who
  lives among the trees, which it commands to restrain its foes before beating them.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Telepathy
HomeSprite: SRD-tapu-bulu-HomeSprite.png
Image: tapu-bulu.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Master
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Leafage|Leafage]]'
- - Master
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Master
  - '[[SRD-Rototiller|Rototiller]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Megahorn|Megahorn]]'
- - Master
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Master
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
Number: 787
ShuffleToken: SRD-tapu-bulu-ShuffleToken.png
Type1: Grass
Type2: Fairy
Weight:
  Kilograms: 45.5
  Pounds: 100.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tapu-bulu-BookSprite.png|wsmall]]
> ![[SRD-tapu-bulu-HomeSprite.png]]
> ![[SRD-tapu-bulu-BoxSprite.png|htiny]]
> ![[SRD-tapu-bulu-ShuffleToken.png|wsmall]]


*No Data*
*Through Ula'ula island runs the legend of a lazy guardian spirit who lives among the trees, which it commands to restrain its foes before beating them.*

**DexID**:: 0787
**Name**:: Tapu Bulu
**Type**:: Grass / Fairy
**Abilities**:: [[SRD-Grassy Surge|Grassy Surge]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 6'2" / 1.9m
**Weight**: 100.3lbs / 45.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tapu Bulu.md"
flatten moves as T
where file.path = this.file.path
```
