---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-blaziken-BookSprite.png
BoxSprite: SRD-blaziken-BoxSprite.png
DexCategory: Blaze Pokemon
DexDescription: "They can jump incredible heights. As they grow older, their feathers\
  \ combust as new feathers grow back. They are courageous fighters and expert martial\
  \ artists. Their wrists light in flames when it\u2019s about to attack."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Combusken]]'
  Speed: Medium
- Evolves: To
  Item: Blazikenite
  Kind: Mega
  Pokemon: '[[SRD-Blaziken (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Speed Boost
HomeSprite: SRD-blaziken-HomeSprite.png
Image: blaziken.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Peck|Peck]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 257
ShuffleToken: SRD-blaziken-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 52.0
  Pounds: 114.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blaziken-BookSprite.png|wsmall]]
> ![[SRD-blaziken-HomeSprite.png]]
> ![[SRD-blaziken-BoxSprite.png|htiny]]
> ![[SRD-blaziken-ShuffleToken.png|wsmall]]


*Blaze Pokemon*
*They can jump incredible heights. As they grow older, their feathers combust as new feathers grow back. They are courageous fighters and expert martial artists. Their wrists light in flames when it’s about to attack.*

**DexID**:: 0257
**Name**:: Blaziken
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'2" / 1.9m
**Weight**: 114.6lbs / 52.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Combusken]]            | Level  | Medium  |             |
| To        | [[SRD-Blaziken (Mega Form)]] | Mega   |         | Blazikenite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Blaziken.md"
flatten moves as T
where file.path = this.file.path
```
