---
Ability1: Bulletproof
Ability2: Soundproof
BookSprite: SRD-kommo-o-BookSprite.png
BoxSprite: SRD-kommo-o-BoxSprite.png
DexCategory: Scaly Pokemon
DexDescription: It completed its harsh training and returns to the mountain where
  it was born to look after the young Jangmo-o, watching them from afar. It is constantly
  looking for strong opponents.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Hakamo-o]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Overcoat
HomeSprite: SRD-kommo-o-HomeSprite.png
Image: kommo-o.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Clanging Scales|Clanging Scales]]'
- - Ace
  - '[[SRD-Autotomize|Autotomize]]'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Focus Blast|Focus Blast]]'
- - Pro
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 784
ShuffleToken: SRD-kommo-o-ShuffleToken.png
Type1: Dragon
Type2: Fighting
Weight:
  Kilograms: 78.2
  Pounds: 172.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-kommo-o-BookSprite.png|wsmall]]
> ![[SRD-kommo-o-HomeSprite.png]]
> ![[SRD-kommo-o-BoxSprite.png|htiny]]
> ![[SRD-kommo-o-ShuffleToken.png|wsmall]]


*Scaly Pokemon*
*It completed its harsh training and returns to the mountain where it was born to look after the young Jangmo-o, watching them from afar. It is constantly looking for strong opponents.*

**DexID**:: 0784
**Name**:: Kommo-o
**Type**:: Dragon / Fighting
**Abilities**:: [[SRD-Bulletproof|Bulletproof]] / [[SRD-Soundproof|Soundproof]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 172.4lbs / 78.2kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Hakamo-o]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Kommo-o.md"
flatten moves as T
where file.path = this.file.path
```
