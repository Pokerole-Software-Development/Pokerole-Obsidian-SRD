---
Ability1: Oblivious
Ability2: Own Tempo
BookSprite: SRD-slowbro-BookSprite.png
BoxSprite: SRD-slowbro-BoxSprite.png
DexCategory: Hermit Crab Pokemon
DexDescription: "This Pokemon fused with a Shellder that bit into its tail. It\u2019\
  s a slow swimmer and doesn\u2019t react to pain but Shellder tends to keep it out\
  \ of trouble."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Slowpoke]]'
  Speed: Slow
- Evolves: To
  Item: Slowbronite
  Kind: Mega
  Pokemon: '[[SRD-Slowbro (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Regenerator
HomeSprite: SRD-slowbro-HomeSprite.png
Image: slowbro.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - Amateur
  - '[[SRD-Withdraw|Withdraw]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
Number: 80
ShuffleToken: SRD-slowbro-ShuffleToken.png
Type1: Water
Type2: Psychic
Weight:
  Kilograms: 78.5
  Pounds: 173.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slowbro-BookSprite.png|wsmall]]
> ![[SRD-slowbro-HomeSprite.png]]
> ![[SRD-slowbro-BoxSprite.png|htiny]]
> ![[SRD-slowbro-ShuffleToken.png|wsmall]]


*Hermit Crab Pokemon*
*This Pokemon fused with a Shellder that bit into its tail. It’s a slow swimmer and doesn’t react to pain but Shellder tends to keep it out of trouble.*

**DexID**:: 0080
**Name**:: Slowbro
**Type**:: Water / Psychic
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 173.1lbs / 78.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                     | Kind   | Speed   | Item        |
|:----------|:----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Slowpoke]]            | Level  | Slow    |             |
| To        | [[SRD-Slowbro (Mega Form)]] | Mega   |         | Slowbronite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Slowbro.md"
flatten moves as T
where file.path = this.file.path
```
