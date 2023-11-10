---
Ability1: Early Bird
Ability2: Scrappy
BookSprite: SRD-kangaskhan-BookSprite.png
BoxSprite: SRD-kangaskhan-BoxSprite.png
DexCategory: Parent Pokemon
DexDescription: A female only species. It raises its offspring in its belly pouch.
  The young leaves once it learns to find its own food. In the wild, mothers and daughters
  fiercely defend each other.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Kangaskhanite
  Kind: Mega
  Pokemon: '[[SRD-Kangaskhan (Mega Form)]]'
GenderType: F
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Inner Focus
HomeSprite: SRD-kangaskhan-HomeSprite.png
Image: kangaskhan.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 115
ShuffleToken: SRD-kangaskhan-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 80.0
  Pounds: 176.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kangaskhan-BookSprite.png|wsmall]]
> ![[SRD-kangaskhan-HomeSprite.png]]
> ![[SRD-kangaskhan-BoxSprite.png|htiny]]
> ![[SRD-kangaskhan-ShuffleToken.png|wsmall]]


*Parent Pokemon*
*A female only species. It raises its offspring in its belly pouch. The young leaves once it learns to find its own food. In the wild, mothers and daughters fiercely defend each other.*

**DexID**:: 0115
**Name**:: Kangaskhan
**Type**:: Normal
**Abilities**:: [[SRD-Early Bird|Early Bird]] / [[SRD-Scrappy|Scrappy]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 176.4lbs / 80.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                        | Kind   | Item          |
|:----------|:-------------------------------|:-------|:--------------|
| To        | [[SRD-Kangaskhan (Mega Form)]] | Mega   | Kangaskhanite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kangaskhan.md"
flatten moves as T
where file.path = this.file.path
```
