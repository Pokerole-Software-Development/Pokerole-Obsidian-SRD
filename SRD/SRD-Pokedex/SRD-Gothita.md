---
Ability1: Frisk
Ability2: Competitive
BookSprite: SRD-gothita-BookSprite.png
BoxSprite: SRD-gothita-BoxSprite.png
DexCategory: Fixation Pokemon
DexDescription: They continuously observe both Trainers and Pokemon. Apparently, they
  are looking at something that only they can see. The ribbon-like feelers on their
  body increase their psychic power.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gothorita]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Shadow Tag
HomeSprite: SRD-gothita-HomeSprite.png
Image: gothita.png
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
Number: 574
ShuffleToken: SRD-gothita-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 5.8
  Pounds: 12.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gothita-BookSprite.png|wsmall]]
> ![[SRD-gothita-HomeSprite.png]]
> ![[SRD-gothita-BoxSprite.png|htiny]]
> ![[SRD-gothita-ShuffleToken.png|wsmall]]


*Fixation Pokemon*
*They continuously observe both Trainers and Pokemon. Apparently, they are looking at something that only they can see. The ribbon-like feelers on their body increase their psychic power.*

**DexID**:: 0574
**Name**:: Gothita
**Type**:: Psychic
**Abilities**:: [[SRD-Frisk|Frisk]] / [[SRD-Competitive|Competitive]] ([[SRD-Shadow Tag|Shadow Tag]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.8lbs / 5.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Gothorita]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Gothita.md"
flatten moves as T
where file.path = this.file.path
```
