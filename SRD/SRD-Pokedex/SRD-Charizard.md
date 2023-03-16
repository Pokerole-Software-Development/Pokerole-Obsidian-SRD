---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-charizard-BookSprite.png
BoxSprite: SRD-charizard-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: A Charizard flies around looking for strong opponents. It breathes
  intense flames that can melt any material. However, it will never touch a weaker
  foe. Not many trainers are able to handle its bad temper.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Charmeleon]]'
  Speed: Medium
- Evolves: To
  Item: Charizardite Y
  Kind: Mega
  Pokemon: '[[SRD-Charizard (Mega Y Form)]]'
- Evolves: To
  Item: Charizardite X
  Kind: Mega
  Pokemon: '[[SRD-Charizard (Mega X Form)]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Solar Power
HomeSprite: SRD-charizard-HomeSprite.png
Image: charizard.png
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
ShuffleToken: SRD-charizard-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 90.5
  Pounds: 199.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-charizard-BookSprite.png|wsmall]]
> ![[SRD-charizard-HomeSprite.png]]
> ![[SRD-charizard-BoxSprite.png|htiny]]
> ![[SRD-charizard-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*A Charizard flies around looking for strong opponents. It breathes intense flames that can melt any material. However, it will never touch a weaker foe. Not many trainers are able to handle its bad temper.*

**DexID**:: 0006
**Name**:: Charizard
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Solar Power|Solar Power]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 199.5lbs / 90.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                         | Kind   | Speed   | Item           |
|:----------|:--------------------------------|:-------|:--------|:---------------|
| From      | [[SRD-Charmeleon]]              | Level  | Medium  |                |
| To        | [[SRD-Charizard (Mega Y Form)]] | Mega   |         | Charizardite Y |
| To        | [[SRD-Charizard (Mega X Form)]] | Mega   |         | Charizardite X |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Charizard.md"
flatten moves as T
where file.path = this.file.path
```
