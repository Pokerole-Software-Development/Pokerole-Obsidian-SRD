---
Ability1: Mega Launcher
Ability2: ''
BookSprite: SRD-clawitzer-BookSprite.png
BoxSprite: SRD-clawitzer-BoxSprite.png
DexCategory: Howitzer Pokemon
DexDescription: "They can be seen swimming backwards using their launcher as A propulsor,\
  \ but they usually stay at the bottom of the sea. Their meat is tough and bitter\
  \ so people don\u2019t use them as food anymore."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Clauncher]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: ''
HomeSprite: SRD-clawitzer-HomeSprite.png
Image: clawitzer.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Splash|Splash]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Vice Grip|Vice Grip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flail|Flail]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crabhammer|Crabhammer]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Pulse|Water Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Jet|Aqua Jet]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dark Pulse|Dark Pulse]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
Number: 693
ShuffleToken: SRD-clawitzer-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 35.3
  Pounds: 77.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clawitzer-BookSprite.png|wsmall]]
> ![[SRD-clawitzer-HomeSprite.png]]
> ![[SRD-clawitzer-BoxSprite.png|htiny]]
> ![[SRD-clawitzer-ShuffleToken.png|wsmall]]


*Howitzer Pokemon*
*They can be seen swimming backwards using their launcher as A propulsor, but they usually stay at the bottom of the sea. Their meat is tough and bitter so people don’t use them as food anymore.*

**DexID**:: 0693
**Name**:: Clawitzer
**Type**:: Water
**Abilities**:: [[SRD-Mega Launcher|Mega Launcher]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 77.8lbs / 35.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Clauncher]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Clawitzer.md"
flatten moves as T
where file.path = this.file.path
```
