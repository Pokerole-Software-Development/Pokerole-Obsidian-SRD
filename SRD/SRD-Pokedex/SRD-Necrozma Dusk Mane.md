---
Ability1: Prism Armor
Ability2: ''
BaseHP: 4
BoxSprite: SRD-BoxSprite-necrozma-dusk.png
DexID: 0800F1
Dexterity: 5
EventAbilities: ''
GenderType: N
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-necrozma-dusk.png
Insight: 6
Legendary: 'Yes'
MaxDexterity: 5
MaxInsight: 6
MaxSpecial: 6
MaxStrength: 8
MaxVitality: 7
Name: Necrozma Dusk Mane
Number: 800
RecommendedRank: Master
Special: 6
Sprite: necrozma-dusk.png
Strength: 8
Type1: Psychic
Type2: Steel
Unevolved: 'No'
Vitality: 7
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-necrozma-dusk.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-necrozma-dusk.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | `= this.Strength`/`= this.MaxStrength`   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | `= this.Dexterity`/`= this.MaxDexterity` |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | `= this.Vitality`/`= this.MaxVitality`   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | `= this.Special`/`= this.MaxSpecial`     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | `= this.Insight`/`= this.MaxInsight`     |

**Recommended Rank:** `= this.RecommendedRank`
**Good Starting Pokemon?** `= this.GoodStarter`
**Can Evolve?** `= this.Unevolved`

![[SRD-Necrozma Dusk Mane-Learnset]]