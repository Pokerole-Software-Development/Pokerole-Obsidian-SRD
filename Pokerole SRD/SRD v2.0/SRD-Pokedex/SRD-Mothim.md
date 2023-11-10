---
Ability1: Swarm
Ability2: ''
BookSprite: SRD-mothim-BookSprite.png
BoxSprite: SRD-mothim-BoxSprite.png
DexCategory: Moth Pokemon
DexDescription: "It flies near the mountains in search of honey. It is an opportunist\
  \ and won\u2019t gather any honey by itself, instead Mothim steals from Combee hives\
  \ and other Pokemon. This Pokemon is male only."
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Male
  Kind: Level
  Pokemon: '[[SRD-Burmy]]'
  Speed: Fast
GenderType: M
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Tinted Lens
HomeSprite: SRD-mothim-HomeSprite.png
Image: mothim.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Gust|Gust]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Lunge|Lunge]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 414
ShuffleToken: SRD-mothim-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 23.3
  Pounds: 51.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mothim-BookSprite.png|wsmall]]
> ![[SRD-mothim-HomeSprite.png]]
> ![[SRD-mothim-BoxSprite.png|htiny]]
> ![[SRD-mothim-ShuffleToken.png|wsmall]]


*Moth Pokemon*
*It flies near the mountains in search of honey. It is an opportunist and won’t gather any honey by itself, instead Mothim steals from Combee hives and other Pokemon. This Pokemon is male only.*

**DexID**:: 0414
**Name**:: Mothim
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Swarm|Swarm]] ([[SRD-Tinted Lens|Tinted Lens]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 51.4lbs / 23.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   | Gender   |
|:----------|:--------------|:-------|:--------|:---------|
| From      | [[SRD-Burmy]] | Level  | Fast    | Male     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mothim.md"
flatten moves as T
where file.path = this.file.path
```
