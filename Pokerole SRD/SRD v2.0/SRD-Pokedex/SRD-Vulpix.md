---
Ability1: Flash Fire
Ability2: ''
BookSprite: SRD-vulpix-BookSprite.png
BoxSprite: SRD-vulpix-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: It is born with just one tail. As it grows, its single white tail
  gains color and splits into six. It is quite warm and cuddly - very popular with
  the ladies . It is, however, uncommon to see one in the wild.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Ninetales]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Drought
HomeSprite: SRD-vulpix-HomeSprite.png
Image: vulpix.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Roar|Roar]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 37
ShuffleToken: SRD-vulpix-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 9.9
  Pounds: 21.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vulpix-BookSprite.png|wsmall]]
> ![[SRD-vulpix-HomeSprite.png]]
> ![[SRD-vulpix-BoxSprite.png|htiny]]
> ![[SRD-vulpix-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*It is born with just one tail. As it grows, its single white tail gains color and splits into six. It is quite warm and cuddly - very popular with the ladies . It is, however, uncommon to see one in the wild.*

**DexID**:: 0037
**Name**:: Vulpix
**Type**:: Fire
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] ([[SRD-Drought|Drought]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 21.8lbs / 9.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Item       |
|:----------|:------------------|:-------|:-----------|
| To        | [[SRD-Ninetales]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vulpix.md"
flatten moves as T
where file.path = this.file.path
```
