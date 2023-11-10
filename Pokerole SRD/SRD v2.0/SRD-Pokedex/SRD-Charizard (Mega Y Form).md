---
Ability1: Drought
Ability2: ''
BookSprite: SRD-charizard-mega-y-form-BookSprite.png
BoxSprite: SRD-charizard-mega-y-form-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: With the power of the Mega Stone It becomes bold and confident. Its
  flying skills get better and t boasts speed and maneuverability. When it flies you
  cannot see it directly as its flames burn as bright as the sun.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Charizardite Y
  Kind: Mega
  Pokemon: '[[SRD-Charizard]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-charizard-mega-y-form-HomeSprite.png
Image: charizard-mega-y-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Heat Wave|Heat Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Inferno|Inferno]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 6
ShuffleToken: SRD-charizard-mega-y-form-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 100.5
  Pounds: 221.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-charizard-mega-y-form-BookSprite.png|wsmall]]
> ![[SRD-charizard-mega-y-form-HomeSprite.png]]
> ![[SRD-charizard-mega-y-form-BoxSprite.png|htiny]]
> ![[SRD-charizard-mega-y-form-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*With the power of the Mega Stone It becomes bold and confident. Its flying skills get better and t boasts speed and maneuverability. When it flies you cannot see it directly as its flames burn as bright as the sun.*

**DexID**:: 0006M1
**Name**:: Charizard (Mega Y Form)
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Drought|Drought]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 221.6lbs / 100.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   | Item           |
|:----------|:------------------|:-------|:---------------|
| From      | [[SRD-Charizard]] | Mega   | Charizardite Y |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Charizard (Mega Y Form).md"
flatten moves as T
where file.path = this.file.path
```
