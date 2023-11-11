---
Ability1: Strong Jaw
Ability2: Shell Armor
BookSprite: SRD-drednaw-BookSprite.png
BoxSprite: SRD-drednaw-BoxSprite.png
DexCategory: Bite Pokemon
DexDescription: It stays immobile near rivers and lakes, disguised as a rock until
  it snaps at an unsuspecting prey. Once something is trapped by its sharp teeth there
  is no way to take it out as it is incredibly stubborn.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Chewtle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Swift Swim
HomeSprite: SRD-drednaw-HomeSprite.png
Image: drednaw.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Shell|Razor Shell]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Jaw Lock|Jaw Lock]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dive|Dive]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Tail|Dragon Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Skull Bash|Skull Bash]]'
Number: 834
ShuffleToken: SRD-drednaw-ShuffleToken.png
Type1: Water
Type2: Rock
Weight:
  Kilograms: 115.5
  Pounds: 254.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drednaw-BookSprite.png|wsmall]]
> ![[SRD-drednaw-HomeSprite.png]]
> ![[SRD-drednaw-BoxSprite.png|htiny]]
> ![[SRD-drednaw-ShuffleToken.png|wsmall]]


*Bite Pokemon*
*It stays immobile near rivers and lakes, disguised as a rock until it snaps at an unsuspecting prey. Once something is trapped by its sharp teeth there is no way to take it out as it is incredibly stubborn.*

**DexID**:: 0834
**Name**:: Drednaw
**Type**:: Water / Rock
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 254.6lbs / 115.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Chewtle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drednaw.md"
flatten moves as T
where file.path = this.file.path
```
