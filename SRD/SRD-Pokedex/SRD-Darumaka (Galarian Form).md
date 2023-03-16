---
Ability1: Hustle
Ability2: Inner Focus
BookSprite: SRD-darumaka-galarian-form-BookSprite.png
BoxSprite: SRD-darumaka-galarian-form-BoxSprite.png
DexCategory: Zen Charm Pokemon
DexDescription: When forced to live on snow, its fire sac froze and now it generates
  cold. Darumaka uses low temperatures as energy, making it very energetic on winter.
  It is playful and likes to throw Snowballs.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Darmanitan (Galarian Form)]]'
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-darumaka-galarian-form-HomeSprite.png
Image: darumaka-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fling|Fling]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 554
ShuffleToken: SRD-darumaka-galarian-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darumaka-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-darumaka-galarian-form-HomeSprite.png]]
> ![[SRD-darumaka-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-darumaka-galarian-form-ShuffleToken.png|wsmall]]


*Zen Charm Pokemon*
*When forced to live on snow, its fire sac froze and now it generates cold. Darumaka uses low temperatures as energy, making it very energetic on winter. It is playful and likes to throw Snowballs.*

**DexID**:: 0554G
**Name**:: Darumaka (Galarian Form)
**Type**:: Ice
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Inner Focus|Inner Focus]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                            | Kind   | Item      |
|:----------|:-----------------------------------|:-------|:----------|
| To        | [[SRD-Darmanitan (Galarian Form)]] | Stone  | Ice Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Darumaka (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
