---
Ability1: Bulletproof
Ability2: Soundproof
BookSprite: SRD-hakamo-o-BookSprite.png
BoxSprite: SRD-hakamo-o-BoxSprite.png
DexCategory: Scaly Pokemon
DexDescription: The scales on its body are shed and regrow sharper each time. It is
  a courageous and diligent Pokemon who always lets out a war cry before the battle.
  Any marks on its scale armor is worn with pride.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Jangmo-o]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kommo-o]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Overcoat
HomeSprite: SRD-hakamo-o-HomeSprite.png
Image: hakamo-o.png
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
  - '[[SRD-Autotomize|Autotomize]]'
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
Number: 783
ShuffleToken: SRD-hakamo-o-ShuffleToken.png
Type1: Dragon
Type2: Fighting
Weight:
  Kilograms: 47.0
  Pounds: 103.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hakamo-o-BookSprite.png|wsmall]]
> ![[SRD-hakamo-o-HomeSprite.png]]
> ![[SRD-hakamo-o-BoxSprite.png|htiny]]
> ![[SRD-hakamo-o-ShuffleToken.png|wsmall]]


*Scaly Pokemon*
*The scales on its body are shed and regrow sharper each time. It is a courageous and diligent Pokemon who always lets out a war cry before the battle. Any marks on its scale armor is worn with pride.*

**DexID**:: 0783
**Name**:: Hakamo-o
**Type**:: Dragon / Fighting
**Abilities**:: [[SRD-Bulletproof|Bulletproof]] / [[SRD-Soundproof|Soundproof]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 103.6lbs / 47.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Jangmo-o]] | Level  | Slow    |
| To        | [[SRD-Kommo-o]]  | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hakamo-o.md"
flatten moves as T
where file.path = this.file.path
```
