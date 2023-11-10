---
Ability1: Shield Dust
Ability2: Tinted Lens
BookSprite: SRD-venomoth-BookSprite.png
BoxSprite: SRD-venomoth-BoxSprite.png
DexCategory: Poison Moth Pokemon
DexDescription: They are plentiful in forests but only come out at night. They possess
  an incredible eyesight and are attracted to light sources. Their wings scatter a
  toxic powder which they use to immobilize their prey.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Venonat]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Wonder Skin
HomeSprite: SRD-venomoth-HomeSprite.png
Image: venomoth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Amateur
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Ace
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Defog|Defog]]'
Number: 49
ShuffleToken: SRD-venomoth-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-venomoth-BookSprite.png|wsmall]]
> ![[SRD-venomoth-HomeSprite.png]]
> ![[SRD-venomoth-BoxSprite.png|htiny]]
> ![[SRD-venomoth-ShuffleToken.png|wsmall]]


*Poison Moth Pokemon*
*They are plentiful in forests but only come out at night. They possess an incredible eyesight and are attracted to light sources. Their wings scatter a toxic powder which they use to immobilize their prey.*

**DexID**:: 0049
**Name**:: Venomoth
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] / [[SRD-Tinted Lens|Tinted Lens]] ([[SRD-Wonder Skin|Wonder Skin]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Venonat]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Venomoth.md"
flatten moves as T
where file.path = this.file.path
```
