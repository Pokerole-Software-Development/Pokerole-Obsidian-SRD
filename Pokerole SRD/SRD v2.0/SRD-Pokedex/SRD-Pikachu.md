---
Ability1: Static
Ability2: ''
BookSprite: SRD-pikachu-BookSprite.png
BoxSprite: SRD-pikachu-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: Lives in small groups in forests but they tend to stay hidden. It
  stores electricity in the electric sacs on its cheeks and uses its tail to ground
  the excess charge. They can be stubborn and wary of strangers.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Pichu]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Raichu]]'
- Evolves: To
  Item: Thunder Stone
  Kind: Stone
  Pokemon: '[[SRD-Raichu (Alolan Form)]]'
  Region: Alola
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Lightning Rod
HomeSprite: SRD-pikachu-HomeSprite.png
Image: pikachu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Surf|Surf]]'
- - Pro
  - '[[SRD-Volt Tackle|Volt Tackle]]'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
Number: 25
ShuffleToken: SRD-pikachu-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pikachu-BookSprite.png|wsmall]]
> ![[SRD-pikachu-HomeSprite.png]]
> ![[SRD-pikachu-BoxSprite.png|htiny]]
> ![[SRD-pikachu-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*Lives in small groups in forests but they tend to stay hidden. It stores electricity in the electric sacs on its cheeks and uses its tail to ground the excess charge. They can be stubborn and wary of strangers.*

**DexID**:: 0025
**Name**:: Pikachu
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                      | Kind   | Stat      | Value   | Item          | Region   |
|:----------|:-----------------------------|:-------|:----------|:--------|:--------------|:---------|
| From      | [[SRD-Pichu]]                | Stat   | Happiness | 4.0     |               |          |
| To        | [[SRD-Raichu]]               | Stone  |           |         | Thunder Stone |          |
| To        | [[SRD-Raichu (Alolan Form)]] | Stone  |           |         | Thunder Stone | Alola    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pikachu.md"
flatten moves as T
where file.path = this.file.path
```
