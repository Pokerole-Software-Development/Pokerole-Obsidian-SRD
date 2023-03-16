---
Ability1: Tough Claws
Ability2: ''
BookSprite: SRD-charizard-mega-x-form-BookSprite.png
BoxSprite: SRD-charizard-mega-x-form-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: The power of the Mega Stone make its inner flames burn so hot that
  its body turns black as coal and blue fire escapes constantly from its mouth. It
  is filled with rage and its demeanor is unpredictable
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Charizardite X
  Kind: Mega
  Pokemon: '[[SRD-Charizard]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-charizard-mega-x-form-HomeSprite.png
Image: charizard-mega-x-form.png
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
ShuffleToken: SRD-charizard-mega-x-form-ShuffleToken.png
Type1: Fire
Type2: Dragon
Weight:
  Kilograms: 110.5
  Pounds: 243.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-charizard-mega-x-form-BookSprite.png|wsmall]]
> ![[SRD-charizard-mega-x-form-HomeSprite.png]]
> ![[SRD-charizard-mega-x-form-BoxSprite.png|htiny]]
> ![[SRD-charizard-mega-x-form-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*The power of the Mega Stone make its inner flames burn so hot that its body turns black as coal and blue fire escapes constantly from its mouth. It is filled with rage and its demeanor is unpredictable*

**DexID**:: 0006M2
**Name**:: Charizard (Mega X Form)
**Type**:: Fire / Dragon
**Abilities**:: [[SRD-Tough Claws|Tough Claws]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 243.6lbs / 110.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   | Item           |
|:----------|:------------------|:-------|:---------------|
| From      | [[SRD-Charizard]] | Mega   | Charizardite X |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Charizard (Mega X Form).md"
flatten moves as T
where file.path = this.file.path
```
