---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-piplup-BookSprite.png
BoxSprite: SRD-piplup-BoxSprite.png
DexCategory: Penguin Pokemon
DexDescription: "Piplups are extremely proud. They won\u2019t take anything from anyone\
  \ nor accept being taken care of. It lives along shores in northern countries. It\
  \ is a good swimmer but terrible at walking, it trips over often."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Prinplup]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Defiant
HomeSprite: SRD-piplup-HomeSprite.png
Image: piplup.png
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
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Peck|Peck]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mist|Mist]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Flail|Flail]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 393
ShuffleToken: SRD-piplup-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 5.2
  Pounds: 11.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-piplup-BookSprite.png|wsmall]]
> ![[SRD-piplup-HomeSprite.png]]
> ![[SRD-piplup-BoxSprite.png|htiny]]
> ![[SRD-piplup-ShuffleToken.png|wsmall]]


*Penguin Pokemon*
*Piplups are extremely proud. They won’t take anything from anyone nor accept being taken care of. It lives along shores in northern countries. It is a good swimmer but terrible at walking, it trips over often.*

**DexID**:: 0393
**Name**:: Piplup
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 11.5lbs / 5.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Prinplup]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Piplup.md"
flatten moves as T
where file.path = this.file.path
```
