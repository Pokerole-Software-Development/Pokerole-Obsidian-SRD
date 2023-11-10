---
Ability1: Compound Eyes
Ability2: ''
BookSprite: SRD-butterfree-BookSprite.png
BoxSprite: SRD-butterfree-BoxSprite.png
DexCategory: Butterfly Pokemon
DexDescription: "It can be found in forests and plains. It loves the honey in some\
  \ flowers even with tiny amounts of pollen. Its wings are covered by dust that allows\
  \ it to fly even when it\u2019s raining."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Metapod]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Tinted Lens
HomeSprite: SRD-butterfree-HomeSprite.png
Image: butterfree.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Electroweb|Electroweb]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nightmare|Nightmare]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Bug Buzz|Bug Buzz]]'
Number: 12
ShuffleToken: SRD-butterfree-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 32.0
  Pounds: 70.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-butterfree-BookSprite.png|wsmall]]
> ![[SRD-butterfree-HomeSprite.png]]
> ![[SRD-butterfree-BoxSprite.png|htiny]]
> ![[SRD-butterfree-ShuffleToken.png|wsmall]]


*Butterfly Pokemon*
*It can be found in forests and plains. It loves the honey in some flowers even with tiny amounts of pollen. Its wings are covered by dust that allows it to fly even when it’s raining.*

**DexID**:: 0012
**Name**:: Butterfree
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Tinted Lens|Tinted Lens]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 70.5lbs / 32.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Metapod]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Butterfree.md"
flatten moves as T
where file.path = this.file.path
```
