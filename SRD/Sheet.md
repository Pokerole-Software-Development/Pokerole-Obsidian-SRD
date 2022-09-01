---
Species: "[[SRD-Eevee]]"
StrengthPoints: 1
DexterityPoints: 0
VitalityPoints: 1
SpecialPoints: 0
InsightPoints: 0
Move: "[[SRD-Tackle]]"
---

# `= this.Species.name`

![[SRD-BoxSprite-eevee.png|right]]

**DexID::** `= this.Species.DexID`
**Type::** `= choice(length(this.Species.Type2)=0, this.Species.Type1,this.Species.Type1+"/"+this.Species.Type2)`
**Abilities::** `= choice(length(this.Species.Ability2)=0, "[[SRD-"+this.Species.Ability1+"|"+this.Species.Ability1+"]]","[[SRD-"+this.Species.Ability1+"|"+this.Species.Ability1+"]]"+" / "+"[[SRD-"+this.Species.Ability2+"|"+this.Species.Ability2+"]]")` `= choice(length(this.Species.HiddenAbility)=0,"","("+"[[SRD-"+this.Species.HiddenAbility+"|"+this.Species.HiddenAbility+"]]"+")")` `= choice(length(this.Species.EventAbilities)=0,"","\<"+"[[SRD-"+this.Species.EventAbilities+"|"+this.Species.EventAbilities+"]]"+"\>")`
**HP:** `= this.Species.BaseHP+this.VitalityPoints+this.Species.Vitality`

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft("",this.Species.Strength,"⬤")+padleft("",this.StrengthPoints,"⦿")+padright("",this.Species.MaxStrength - this.StrengthPoints - this.Species.Strength,"⭘")`    | `= this.Species.Strength+this.StrengthPoints`/`= this.Species.MaxStrength`   |
| Dexterity | `= padleft("",this.Species.Dexterity,"⬤")+padleft("",this.DexterityPoints,"⦿")+padright("",this.Species.MaxDexterity - this.DexterityPoints - this.Species.Dexterity,"⭘")` | `= this.Species.Dexterity+this.DexterityPoints`/`= this.Species.MaxDexterity` |
| Vitality  | `= padleft("",this.Species.Vitality,"⬤")+padleft("",this.VitalityPoints,"⦿")+padright("",this.Species.MaxVitality - this.VitalityPoints - this.Species.Vitality,"⭘")`    | `= this.Species.Vitality+this.VitalityPoints`/`= this.Species.MaxVitality`   |
| Special   | `= padleft("",this.Species.Special,"⬤")+padleft("",this.SpecialPoints,"⦿")+padright("",this.Species.MaxSpecial - this.SpecialPoints - this.Species.Special,"⭘")`       | `= this.Species.Special+this.SpecialPoints`/`= this.Species.MaxSpecial`     |
| Insight   | `= padleft("",this.Species.Insight,"⬤")+padleft("",this.InsightPoints,"⦿")+padright("",this.Species.MaxInsight - this.InsightPoints - this.Species.Insight,"⭘")`       | `= this.Species.Insight+this.InsightPoints`/`= this.Species.MaxInsight`     |

## [[SRD-Eevee-Learnset]]

### `= this.Move.name` 
*`= this.Move.Description`*

`= this[this.Move.Accuracy1]`

**Accuracy:** `= this.Move.Accuracy1` + `= this.Move.Accuracy2`
**Damage:** `= this.Move.Power` `= choice(length(this.Move.Damage1)=0, "","\+ "+ this.Move.Damage1)` `= choice(length(this.Move.Damage2)=0, "","\+ "+ this.Move.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Move.Type` | `= this.Move.Target` | `= this.Move.DmgType` | `= this.Move.Power` | 

**Effect:** `= this.Move.Effect`