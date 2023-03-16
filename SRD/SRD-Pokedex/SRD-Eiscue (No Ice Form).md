---
Ability1: Ice Face
Ability2: ''
BookSprite: SRD-eiscue-no-ice-form-BookSprite.png
BoxSprite: SRD-eiscue-no-ice-form-BoxSprite.png
DexCategory: Penguin Pokemon
DexDescription: "Eiscue \u201CNo-Ice\u201D Form is actually its true Form. Without\
  \ the ice to protect it you can see its worried expression, it\u2019s actually quite\
  \ endearing. It can now move faster but you can see it feels anxious."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Eiscue]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-eiscue-no-ice-form-HomeSprite.png
Image: eiscue-no-ice-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Ace
  - '[[SRD-Surf|Surf]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
Number: 875
ShuffleToken: SRD-eiscue-no-ice-form-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 89.0
  Pounds: 196.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-eiscue-no-ice-form-BookSprite.png|wsmall]]
> ![[SRD-eiscue-no-ice-form-HomeSprite.png]]
> ![[SRD-eiscue-no-ice-form-BoxSprite.png|htiny]]
> ![[SRD-eiscue-no-ice-form-ShuffleToken.png|wsmall]]


*Penguin Pokemon*
*Eiscue “No-Ice” Form is actually its true Form. Without the ice to protect it you can see its worried expression, it’s actually quite endearing. It can now move faster but you can see it feels anxious.*

**DexID**:: 0875F1
**Name**:: Eiscue (No Ice Form)
**Type**:: Ice
**Abilities**:: [[SRD-Ice Face|Ice Face]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 196.2lbs / 89.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Eiscue]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Eiscue (No Ice Form).md"
flatten moves as T
where file.path = this.file.path
```
