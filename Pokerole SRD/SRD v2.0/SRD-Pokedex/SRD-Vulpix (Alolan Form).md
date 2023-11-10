---
Ability1: Snow Cloak
Ability2: ''
BookSprite: SRD-vulpix-alolan-form-BookSprite.png
BoxSprite: SRD-vulpix-alolan-form-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: "The Vulpix who became stranded in Alola had to change type in order\
  \ to survive. Alola\u2019s local name for this Pokemon is Keokeo. They use their\
  \ tails as a fan to cool themselves in hot climates."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Ninetales (Alolan Form)]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Snow Warning
HomeSprite: SRD-vulpix-alolan-form-HomeSprite.png
Image: vulpix-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Roar|Roar]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Moonblast|Moonblast]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hex|Hex]]'
Number: 37
ShuffleToken: SRD-vulpix-alolan-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 9.9
  Pounds: 21.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vulpix-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-vulpix-alolan-form-HomeSprite.png]]
> ![[SRD-vulpix-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-vulpix-alolan-form-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*The Vulpix who became stranded in Alola had to change type in order to survive. Alola’s local name for this Pokemon is Keokeo. They use their tails as a fan to cool themselves in hot climates.*

**DexID**:: 0037A
**Name**:: Vulpix (Alolan Form)
**Type**:: Ice
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Snow Warning|Snow Warning]])
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

| Evolves   | Pokemon                         | Kind   | Item      |
|:----------|:--------------------------------|:-------|:----------|
| To        | [[SRD-Ninetales (Alolan Form)]] | Stone  | Ice Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vulpix (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
