---
Ability1: Rock Head
Ability2: Pressure
BookSprite: SRD-aerodactyl-BookSprite.png
BoxSprite: SRD-aerodactyl-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: "A vicious Pokemon from the distant past. It appears to have flown\
  \ by spreading its wings and gliding. One has been revived from a fossil. It\u2019\
  s very dangerous; it attacks with the intent to tear apart its victims."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Aerodactylite
  Kind: Mega
  Pokemon: '[[SRD-Aerodactyl (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Unnerve
HomeSprite: SRD-aerodactyl-HomeSprite.png
Image: aerodactyl.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Sky Drop|Sky Drop]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Number: 142
ShuffleToken: SRD-aerodactyl-ShuffleToken.png
Type1: Rock
Type2: Flying
Weight:
  Kilograms: 59.0
  Pounds: 130.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aerodactyl-BookSprite.png|wsmall]]
> ![[SRD-aerodactyl-HomeSprite.png]]
> ![[SRD-aerodactyl-BoxSprite.png|htiny]]
> ![[SRD-aerodactyl-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*A vicious Pokemon from the distant past. It appears to have flown by spreading its wings and gliding. One has been revived from a fossil. It’s very dangerous; it attacks with the intent to tear apart its victims.*

**DexID**:: 0142
**Name**:: Aerodactyl
**Type**:: Rock / Flying
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Pressure|Pressure]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 130.1lbs / 59.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                        | Kind   | Item          |
|:----------|:-------------------------------|:-------|:--------------|
| To        | [[SRD-Aerodactyl (Mega Form)]] | Mega   | Aerodactylite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aerodactyl.md"
flatten moves as T
where file.path = this.file.path
```
