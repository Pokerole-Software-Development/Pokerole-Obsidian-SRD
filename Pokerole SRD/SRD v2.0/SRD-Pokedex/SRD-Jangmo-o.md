---
Ability1: Bulletproof
Ability2: Soundproof
BookSprite: SRD-jangmo-o-BookSprite.png
BoxSprite: SRD-jangmo-o-BoxSprite.png
DexCategory: Scaly Pokemon
DexDescription: They live in mountains rarely visited by humans. Although they are
  valiant and hard-working Pokemon they retain their independent nature. It uses the
  scale on its head for both attack and defense.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hakamo-o]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Overcoat
HomeSprite: SRD-jangmo-o-HomeSprite.png
Image: jangmo-o.png
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
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Amateur
  - '[[SRD-Noble Roar|Noble Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Reversal|Reversal]]'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
Number: 782
ShuffleToken: SRD-jangmo-o-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 29.7
  Pounds: 65.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jangmo-o-BookSprite.png|wsmall]]
> ![[SRD-jangmo-o-HomeSprite.png]]
> ![[SRD-jangmo-o-BoxSprite.png|htiny]]
> ![[SRD-jangmo-o-ShuffleToken.png|wsmall]]


*Scaly Pokemon*
*They live in mountains rarely visited by humans. Although they are valiant and hard-working Pokemon they retain their independent nature. It uses the scale on its head for both attack and defense.*

**DexID**:: 0782
**Name**:: Jangmo-o
**Type**:: Dragon
**Abilities**:: [[SRD-Bulletproof|Bulletproof]] / [[SRD-Soundproof|Soundproof]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 65.5lbs / 29.7kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Hakamo-o]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jangmo-o.md"
flatten moves as T
where file.path = this.file.path
```
