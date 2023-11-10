---
Ability1: Tough Claws
Ability2: ''
BookSprite: SRD-aerodactyl-mega-form-BookSprite.png
BoxSprite: SRD-aerodactyl-mega-form-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: With the power of the Mega Stone it restores the original appearance
  it had millions of years ago with its body covered in sharp rocks. It is very aggressive
  and will attack anything that moves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Aerodactylite
  Kind: Mega
  Pokemon: '[[SRD-Aerodactyl]]'
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: ''
HomeSprite: SRD-aerodactyl-mega-form-HomeSprite.png
Image: aerodactyl-mega-form.png
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
ShuffleToken: SRD-aerodactyl-mega-form-ShuffleToken.png
Type1: Rock
Type2: Flying
Weight:
  Kilograms: 79.0
  Pounds: 174.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aerodactyl-mega-form-BookSprite.png|wsmall]]
> ![[SRD-aerodactyl-mega-form-HomeSprite.png]]
> ![[SRD-aerodactyl-mega-form-BoxSprite.png|htiny]]
> ![[SRD-aerodactyl-mega-form-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*With the power of the Mega Stone it restores the original appearance it had millions of years ago with its body covered in sharp rocks. It is very aggressive and will attack anything that moves.*

**DexID**:: 0142M1
**Name**:: Aerodactyl (Mega Form)
**Type**:: Rock / Flying
**Abilities**:: [[SRD-Tough Claws|Tough Claws]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'9" / 2.1m
**Weight**: 174.2lbs / 79.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon            | Kind   | Item          |
|:----------|:-------------------|:-------|:--------------|
| From      | [[SRD-Aerodactyl]] | Mega   | Aerodactylite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aerodactyl (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
