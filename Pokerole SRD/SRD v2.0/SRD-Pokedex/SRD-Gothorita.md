---
Ability1: Frisk
Ability2: Competitive
BookSprite: SRD-gothorita-BookSprite.png
BoxSprite: SRD-gothorita-BoxSprite.png
DexCategory: Manipulate Pokemon
DexDescription: Starlight is the source of their power. At night, they mark star positions
  by using floating stones. According to many old tales, it creates friends for itself
  by controlling sleeping children on starry nights.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gothita]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gothitelle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Shadow Tag
HomeSprite: SRD-gothorita-HomeSprite.png
Image: gothorita.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tickle|Tickle]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Ace
  - '[[SRD-Charm|Charm]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
Number: 575
ShuffleToken: SRD-gothorita-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 18.0
  Pounds: 39.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gothorita-BookSprite.png|wsmall]]
> ![[SRD-gothorita-HomeSprite.png]]
> ![[SRD-gothorita-BoxSprite.png|htiny]]
> ![[SRD-gothorita-ShuffleToken.png|wsmall]]


*Manipulate Pokemon*
*Starlight is the source of their power. At night, they mark star positions by using floating stones. According to many old tales, it creates friends for itself by controlling sleeping children on starry nights.*

**DexID**:: 0575
**Name**:: Gothorita
**Type**:: Psychic
**Abilities**:: [[SRD-Frisk|Frisk]] / [[SRD-Competitive|Competitive]] ([[SRD-Shadow Tag|Shadow Tag]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 39.7lbs / 18.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Gothita]]    | Level  | Medium  |
| To        | [[SRD-Gothitelle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gothorita.md"
flatten moves as T
where file.path = this.file.path
```
