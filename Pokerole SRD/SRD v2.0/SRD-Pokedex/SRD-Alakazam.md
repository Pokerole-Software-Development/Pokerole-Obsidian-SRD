---
Ability1: Synchronize
Ability2: Inner Focus
BookSprite: SRD-alakazam-BookSprite.png
BoxSprite: SRD-alakazam-BoxSprite.png
DexCategory: Psi Pokemon
DexDescription: A Pokemon that can memorize anything and never forgets what it learns.
  Over time it becomes too smart to allow anyone to be its master. Alakazam's psychic
  powers can be terrifying.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Kadabra]]'
- Evolves: To
  Item: Alakazite
  Kind: Mega
  Pokemon: '[[SRD-Alakazam (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Magic Guard
HomeSprite: SRD-alakazam-HomeSprite.png
Image: alakazam.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teleport|Teleport]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Kinesis|Kinesis]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disable|Disable]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Miracle Eye|Miracle Eye]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ally Switch|Ally Switch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reflect|Reflect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Telekinesis|Telekinesis]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Role Play|Role Play]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psycho Cut|Psycho Cut]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recover|Recover]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snatch|Snatch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wonder Room|Wonder Room]]'
Number: 65
ShuffleToken: SRD-alakazam-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 48.0
  Pounds: 105.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-alakazam-BookSprite.png|wsmall]]
> ![[SRD-alakazam-HomeSprite.png]]
> ![[SRD-alakazam-BoxSprite.png|htiny]]
> ![[SRD-alakazam-ShuffleToken.png|wsmall]]


*Psi Pokemon*
*A Pokemon that can memorize anything and never forgets what it learns. Over time it becomes too smart to allow anyone to be its master. Alakazam's psychic powers can be terrifying.*

**DexID**:: 0065
**Name**:: Alakazam
**Type**:: Psychic
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Magic Guard|Magic Guard]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 105.8lbs / 48.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Item      |
|:----------|:-----------------------------|:-------|:----------|
| From      | [[SRD-Kadabra]]              | Trade  |           |
| To        | [[SRD-Alakazam (Mega Form)]] | Mega   | Alakazite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Alakazam.md"
flatten moves as T
where file.path = this.file.path
```
