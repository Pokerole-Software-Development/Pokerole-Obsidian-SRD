---
Ability1: Inner Focus
Ability2: Keen Eye
BookSprite: SRD-sneasel-BookSprite.png
BoxSprite: SRD-sneasel-BoxSprite.png
DexCategory: Sharp Claw Pokemon
DexDescription: It drives weaker Pokemon from their homes and eats their eggs. They
  are vicious and cunning. They wait for prey hidden in the darkness and enjoy slashing
  their foes until they get tired or the foe stops moving.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Razor Claw
  Kind: Level
  Pokemon: '[[SRD-Weavile]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Pickpocket
HomeSprite: SRD-sneasel-HomeSprite.png
Image: sneasel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Beat Up|Beat Up]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Snatch|Snatch]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Ice Shard|Ice Shard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
Number: 215
ShuffleToken: SRD-sneasel-ShuffleToken.png
Type1: Dark
Type2: Ice
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sneasel-BookSprite.png|wsmall]]
> ![[SRD-sneasel-HomeSprite.png]]
> ![[SRD-sneasel-BoxSprite.png|htiny]]
> ![[SRD-sneasel-ShuffleToken.png|wsmall]]


*Sharp Claw Pokemon*
*It drives weaker Pokemon from their homes and eats their eggs. They are vicious and cunning. They wait for prey hidden in the darkness and enjoy slashing their foes until they get tired or the foe stops moving.*

**DexID**:: 0215
**Name**:: Sneasel
**Type**:: Dark / Ice
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Keen Eye|Keen Eye]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| To        | [[SRD-Weavile]] | Level  | Razor Claw |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sneasel.md"
flatten moves as T
where file.path = this.file.path
```
