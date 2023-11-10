---
Ability1: Synchronize
Ability2: Inner Focus
BookSprite: SRD-kadabra-BookSprite.png
BoxSprite: SRD-kadabra-BoxSprite.png
DexCategory: Psi Pokemon
DexDescription: "Kadabra holds a silver spoon in its hand. The spoon is used to amplify\
  \ the alpha waves of its brain. When this Pokemon walks in, objects near to it go\
  \ crazy, moving in ways they shouldn\u2019t."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Abra]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Alakazam]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Magic Guard
HomeSprite: SRD-kadabra-HomeSprite.png
Image: kadabra.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Teleport|Teleport]]'
- - Starter
  - '[[SRD-Kinesis|Kinesis]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 64
ShuffleToken: SRD-kadabra-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 56.5
  Pounds: 124.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kadabra-BookSprite.png|wsmall]]
> ![[SRD-kadabra-HomeSprite.png]]
> ![[SRD-kadabra-BoxSprite.png|htiny]]
> ![[SRD-kadabra-ShuffleToken.png|wsmall]]


*Psi Pokemon*
*Kadabra holds a silver spoon in its hand. The spoon is used to amplify the alpha waves of its brain. When this Pokemon walks in, objects near to it go crazy, moving in ways they shouldn’t.*

**DexID**:: 0064
**Name**:: Kadabra
**Type**:: Psychic
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Magic Guard|Magic Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 124.6lbs / 56.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Abra]]     | Level  | Medium  |
| To        | [[SRD-Alakazam]] | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kadabra.md"
flatten moves as T
where file.path = this.file.path
```
