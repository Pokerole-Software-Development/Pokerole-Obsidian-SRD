---
Ability1: Mega Launcher
Ability2: ''
BookSprite: SRD-clauncher-BookSprite.png
BoxSprite: SRD-clauncher-BoxSprite.png
DexCategory: Water Gun Pokemon
DexDescription: They live in beaches and shallow waters. They can knock down a flying
  prey by shooting water from their massive claws. Their shell is very though but
  their meat is delicious.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Clawitzer]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-clauncher-HomeSprite.png
Image: clauncher.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Vice Grip|Vice Grip]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Crabhammer|Crabhammer]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Ace
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Ace
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 692
ShuffleToken: SRD-clauncher-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 8.3
  Pounds: 18.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clauncher-BookSprite.png|wsmall]]
> ![[SRD-clauncher-HomeSprite.png]]
> ![[SRD-clauncher-BoxSprite.png|htiny]]
> ![[SRD-clauncher-ShuffleToken.png|wsmall]]


*Water Gun Pokemon*
*They live in beaches and shallow waters. They can knock down a flying prey by shooting water from their massive claws. Their shell is very though but their meat is delicious.*

**DexID**:: 0692
**Name**:: Clauncher
**Type**:: Water
**Abilities**:: [[SRD-Mega Launcher|Mega Launcher]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 18.3lbs / 8.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Clawitzer]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Clauncher.md"
flatten moves as T
where file.path = this.file.path
```
