---
Ability1: Inner Focus
Ability2: Regenerator
BaseHP: 4
BoxSprite: SRD-BoxSprite-mienshao.png
DexID: '0620'
Dexterity: 3
EventAbilities: ''
GenderType: ''
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: Reckless
HomeSprite: SRD-HomeSprite-mienshao.png
Insight: 2
Legendary: 'No'
MaxDexterity: 6
MaxInsight: 4
MaxSpecial: 6
MaxStrength: 7
MaxVitality: 4
Name: Mienshao
Number: 620
RecommendedRank: Amateur
Special: 3
Sprite: mienshao.png
Strength: 3
Type1: Fighting
Type2: ''
Unevolved: 'No'
Vitality: 2
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-mienshao.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-mienshao.png|right]]

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

![[SRD-Mienshao-Learnset]]