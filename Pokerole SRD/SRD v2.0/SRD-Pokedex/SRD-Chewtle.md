---
Ability1: Strong Jaw
Ability2: Shell Armor
BookSprite: SRD-chewtle-BookSprite.png
BoxSprite: SRD-chewtle-BoxSprite.png
DexCategory: Snapping Pokemon
DexDescription: It uses its horn as its primary weapon, but it has a reputation as
  a biter. Apparently its gums are itchy and the only way to soothe them is biting
  and chewing on stuff. It is kinda cranky but relatively harmless.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Drednaw]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Swift Swim
HomeSprite: SRD-chewtle-HomeSprite.png
Image: chewtle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Jaw Lock|Jaw Lock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Dragon Tail|Dragon Tail]]'
Number: 833
ShuffleToken: SRD-chewtle-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chewtle-BookSprite.png|wsmall]]
> ![[SRD-chewtle-HomeSprite.png]]
> ![[SRD-chewtle-BoxSprite.png|htiny]]
> ![[SRD-chewtle-ShuffleToken.png|wsmall]]


*Snapping Pokemon*
*It uses its horn as its primary weapon, but it has a reputation as a biter. Apparently its gums are itchy and the only way to soothe them is biting and chewing on stuff. It is kinda cranky but relatively harmless.*

**DexID**:: 0833
**Name**:: Chewtle
**Type**:: Water
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Drednaw]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chewtle.md"
flatten moves as T
where file.path = this.file.path
```
