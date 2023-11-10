---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-charmeleon-BookSprite.png
BoxSprite: SRD-charmeleon-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: "It turns aggressive after evolving, it is very hot-headed by nature,\
  \ so it constantly starts fights. When it\u2019s excited, the flame at the tip of\
  \ its tail flares with a bluish white color."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Charmander]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Charizard]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Solar Power
HomeSprite: SRD-charmeleon-HomeSprite.png
Image: charmeleon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 5
ShuffleToken: SRD-charmeleon-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 19.0
  Pounds: 41.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-charmeleon-BookSprite.png|wsmall]]
> ![[SRD-charmeleon-HomeSprite.png]]
> ![[SRD-charmeleon-BoxSprite.png|htiny]]
> ![[SRD-charmeleon-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*It turns aggressive after evolving, it is very hot-headed by nature, so it constantly starts fights. When it’s excited, the flame at the tip of its tail flares with a bluish white color.*

**DexID**:: 0005
**Name**:: Charmeleon
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Solar Power|Solar Power]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 41.9lbs / 19.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Charmander]] | Level  | Medium  |
| To        | [[SRD-Charizard]]  | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Charmeleon.md"
flatten moves as T
where file.path = this.file.path
```
