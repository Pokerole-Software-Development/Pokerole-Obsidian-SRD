---
Ability1: Hyper Cutter
Ability2: Shell Armor
BookSprite: SRD-crawdaunt-BookSprite.png
BoxSprite: SRD-crawdaunt-BoxSprite.png
DexCategory: Rogue Pokemon
DexDescription: Crawdaunt is extremely violent and territorial. The ponds where it
  lives look like desolated places due to them attacking anything that comes close.
  It sheds its shell once a year, this weakens it for a few days.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Corphish]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Adaptability
HomeSprite: SRD-crawdaunt-HomeSprite.png
Image: crawdaunt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Crabhammer|Crabhammer]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Razor Shell|Razor Shell]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
Number: 342
ShuffleToken: SRD-crawdaunt-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 32.8
  Pounds: 72.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-crawdaunt-BookSprite.png|wsmall]]
> ![[SRD-crawdaunt-HomeSprite.png]]
> ![[SRD-crawdaunt-BoxSprite.png|htiny]]
> ![[SRD-crawdaunt-ShuffleToken.png|wsmall]]


*Rogue Pokemon*
*Crawdaunt is extremely violent and territorial. The ponds where it lives look like desolated places due to them attacking anything that comes close. It sheds its shell once a year, this weakens it for a few days.*

**DexID**:: 0342
**Name**:: Crawdaunt
**Type**:: Water / Dark
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 72.3lbs / 32.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Corphish]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Crawdaunt.md"
flatten moves as T
where file.path = this.file.path
```
