---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-frogadier-BookSprite.png
BoxSprite: SRD-frogadier-BoxSprite.png
DexCategory: Bubble Frog Pokemon
DexDescription: It is incredibly hard to catch. It starts practicing its skills by
  throwing foam covered pebbles at foes. Many trainers find this rebellious stage
  very challenging to handle and end up being its targets of practice.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Froakie]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Greninja]]'
  Speed: Medium
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Greninja (BBF Form)]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Protean
HomeSprite: SRD-frogadier-HomeSprite.png
Image: frogadier.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Substitute|Substitute]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double Team|Double Team]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 657
ShuffleToken: SRD-frogadier-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 10.9
  Pounds: 24.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-frogadier-BookSprite.png|wsmall]]
> ![[SRD-frogadier-HomeSprite.png]]
> ![[SRD-frogadier-BoxSprite.png|htiny]]
> ![[SRD-frogadier-ShuffleToken.png|wsmall]]


*Bubble Frog Pokemon*
*It is incredibly hard to catch. It starts practicing its skills by throwing foam covered pebbles at foes. Many trainers find this rebellious stage very challenging to handle and end up being its targets of practice.*

**DexID**:: 0657
**Name**:: Frogadier
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Protean|Protean]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 24.0lbs / 10.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                     | Kind   | Speed   |
|:----------|:----------------------------|:-------|:--------|
| From      | [[SRD-Froakie]]             | Level  | Medium  |
| To        | [[SRD-Greninja]]            | Level  | Medium  |
| To        | [[SRD-Greninja (BBF Form)]] | Form   |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Frogadier.md"
flatten moves as T
where file.path = this.file.path
```
