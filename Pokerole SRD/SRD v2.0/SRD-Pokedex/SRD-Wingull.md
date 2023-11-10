---
Ability1: Keen Eye
Ability2: Hydration
BookSprite: SRD-wingull-BookSprite.png
BoxSprite: SRD-wingull-BoxSprite.png
DexCategory: Seagull Pokemon
DexDescription: "They carry prey and precious items in their beaks, hiding them in\
  \ strange locations. They nest in sheer cliffs at the sea\u2019s edge. They often\
  \ harass fishing boats to steal an easy meal for themselves."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pelipper]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Rain Dish
HomeSprite: SRD-wingull-HomeSprite.png
Image: wingull.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
Number: 278
ShuffleToken: SRD-wingull-ShuffleToken.png
Type1: Water
Type2: Flying
Weight:
  Kilograms: 9.5
  Pounds: 20.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wingull-BookSprite.png|wsmall]]
> ![[SRD-wingull-HomeSprite.png]]
> ![[SRD-wingull-BoxSprite.png|htiny]]
> ![[SRD-wingull-ShuffleToken.png|wsmall]]


*Seagull Pokemon*
*They carry prey and precious items in their beaks, hiding them in strange locations. They nest in sheer cliffs at the sea’s edge. They often harass fishing boats to steal an easy meal for themselves.*

**DexID**:: 0278
**Name**:: Wingull
**Type**:: Water / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Hydration|Hydration]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 20.9lbs / 9.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Pelipper]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wingull.md"
flatten moves as T
where file.path = this.file.path
```
