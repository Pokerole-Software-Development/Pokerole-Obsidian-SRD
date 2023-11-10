---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-froakie-BookSprite.png
BoxSprite: SRD-froakie-BoxSprite.png
DexCategory: Bubble Frog Pokemon
DexDescription: It protects its skin by covering its body in bubble foam. Beneath
  its happy-go-lucky air, it keeps a watchful eye on its surroundings. It needs good
  discipline or it will be bad mannered with others.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Frogadier]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Protean
HomeSprite: SRD-froakie-HomeSprite.png
Image: froakie.png
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
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - '---------------------------'
  - '---------------------------'
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
Number: 656
ShuffleToken: SRD-froakie-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 7.0
  Pounds: 15.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-froakie-BookSprite.png|wsmall]]
> ![[SRD-froakie-HomeSprite.png]]
> ![[SRD-froakie-BoxSprite.png|htiny]]
> ![[SRD-froakie-ShuffleToken.png|wsmall]]


*Bubble Frog Pokemon*
*It protects its skin by covering its body in bubble foam. Beneath its happy-go-lucky air, it keeps a watchful eye on its surroundings. It needs good discipline or it will be bad mannered with others.*

**DexID**:: 0656
**Name**:: Froakie
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Protean|Protean]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 15.4lbs / 7.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Frogadier]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Froakie.md"
flatten moves as T
where file.path = this.file.path
```
