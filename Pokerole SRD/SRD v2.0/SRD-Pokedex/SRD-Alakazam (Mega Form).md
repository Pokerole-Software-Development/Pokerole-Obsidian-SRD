---
Ability1: Trace
Ability2: ''
BookSprite: SRD-alakazam-mega-form-BookSprite.png
BoxSprite: SRD-alakazam-mega-form-BoxSprite.png
DexCategory: Psi Pokemon
DexDescription: With the power of the Mega Stone it is constantly plagued with visions
  of the future which make it great at evading attacks. Its body is feeble and it
  moves purely through psychic energy.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Alakazite
  Kind: Mega
  Pokemon: '[[SRD-Alakazam]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-alakazam-mega-form-HomeSprite.png
Image: alakazam-mega-form.png
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
Number: 65
ShuffleToken: SRD-alakazam-mega-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 48.0
  Pounds: 105.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-alakazam-mega-form-BookSprite.png|wsmall]]
> ![[SRD-alakazam-mega-form-HomeSprite.png]]
> ![[SRD-alakazam-mega-form-BoxSprite.png|htiny]]
> ![[SRD-alakazam-mega-form-ShuffleToken.png|wsmall]]


*Psi Pokemon*
*With the power of the Mega Stone it is constantly plagued with visions of the future which make it great at evading attacks. Its body is feeble and it moves purely through psychic energy.*

**DexID**:: 0065M1
**Name**:: Alakazam (Mega Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Trace|Trace]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 105.8lbs / 48.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Item      |
|:----------|:-----------------|:-------|:----------|
| From      | [[SRD-Alakazam]] | Mega   | Alakazite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Alakazam (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
