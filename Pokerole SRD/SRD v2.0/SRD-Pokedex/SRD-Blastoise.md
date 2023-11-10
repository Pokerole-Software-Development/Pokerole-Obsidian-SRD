---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-blastoise-BookSprite.png
BoxSprite: SRD-blastoise-BoxSprite.png
DexCategory: Shellfish Pokemon
DexDescription: The jets of water it spouts from the rocket cannons on its shell have
  been recorded to punch through steel. It is confident on its great defense and water
  spouts to overcome any obstacle.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wartortle]]'
  Speed: Medium
- Evolves: To
  Item: Blastoisinite
  Kind: Mega
  Pokemon: '[[SRD-Blastoise (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Rain Dish
HomeSprite: SRD-blastoise-HomeSprite.png
Image: blastoise.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Bubble|Bubble]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
Number: 9
ShuffleToken: SRD-blastoise-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 85.5
  Pounds: 188.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blastoise-BookSprite.png|wsmall]]
> ![[SRD-blastoise-HomeSprite.png]]
> ![[SRD-blastoise-BoxSprite.png|htiny]]
> ![[SRD-blastoise-ShuffleToken.png|wsmall]]


*Shellfish Pokemon*
*The jets of water it spouts from the rocket cannons on its shell have been recorded to punch through steel. It is confident on its great defense and water spouts to overcome any obstacle.*

**DexID**:: 0009
**Name**:: Blastoise
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 188.5lbs / 85.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                       | Kind   | Speed   | Item          |
|:----------|:------------------------------|:-------|:--------|:--------------|
| From      | [[SRD-Wartortle]]             | Level  | Medium  |               |
| To        | [[SRD-Blastoise (Mega Form)]] | Mega   |         | Blastoisinite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Blastoise.md"
flatten moves as T
where file.path = this.file.path
```
