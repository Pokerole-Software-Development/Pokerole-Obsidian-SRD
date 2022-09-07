---
Species: "[[]]"
StrengthPoints: 0
DexterityPoints: 0
VitalityPoints: 0
SpecialPoints: 0
InsightPoints: 0
Tough: 0
Cool: 0
Beauty: 0
Cute: 0
Clever: 0
---

# `= this.Species.name`

**Species**: `= this.Species`
**DexID**: `= this.Species.DexID`
**Type**: `= this.Species.Type`
**Abilities**: `= this.Species.Abilities`
**HP**: `= this.Species.Vitality + this.VitalityPoints + this.Species.base-hp`
**Will**:: `= this.Species.Insight + this.InsightPoints + 2`
**Rank**: 
**Nature**:
**Gender**: 


|           |                                                                                                                                                                            |                                                                               |        |                                                     |                     |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------ | --------------------------------------------------- | ------------------- |
| Strength  | `= padleft("",this.Species.Strength,"⬤")+padleft("",this.StrengthPoints,"⦿")+padright("",this.Species.MaxStrength - this.StrengthPoints - this.Species.Strength,"⭘")`      | `= this.Species.Strength+this.StrengthPoints`/`= this.Species.MaxStrength`    | Tough  | `= padright(padright("⬤",this.Tough+1,"⦿"),5,"⭘")`  | `= this.Tough+1`/5  |
| Dexterity | `= padleft("",this.Species.Dexterity,"⬤")+padleft("",this.DexterityPoints,"⦿")+padright("",this.Species.MaxDexterity - this.DexterityPoints - this.Species.Dexterity,"⭘")` | `= this.Species.Dexterity+this.DexterityPoints`/`= this.Species.MaxDexterity` | Cool   | `=padright(padright("⬤",this.Cool+1,"⦿"),5,"⭘")`    | `= this.Cool+1`/5   |
| Vitality  | `= padleft("",this.Species.Vitality,"⬤")+padleft("",this.VitalityPoints,"⦿")+padright("",this.Species.MaxVitality - this.VitalityPoints - this.Species.Vitality,"⭘")`      | `= this.Species.Vitality+this.VitalityPoints`/`= this.Species.MaxVitality`    | Beauty | `= padright(padright("⬤",this.Beauty+1,"⦿"),5,"⭘")` | `= this.Beauty+1`/5 |
| Special   | `= padleft("",this.Species.Special,"⬤")+padleft("",this.SpecialPoints,"⦿")+padright("",this.Species.MaxSpecial - this.SpecialPoints - this.Species.Special,"⭘")`           | `= this.Species.Special+this.SpecialPoints`/`= this.Species.MaxSpecial`       | Cute   | `=padright( padright("⬤",this.Cute+1,"⦿"),5,"⭘")`   | `= this.Cute+1`/5   |
| Insight   | `= padleft("",this.Species.Insight,"⬤")+padleft("",this.InsightPoints,"⦿")+padright("",this.Species.MaxInsight - this.InsightPoints - this.Species.Insight,"⭘")`           | `= this.Species.Insight+this.InsightPoints`/`= this.Species.MaxInsight`       | Clever | `= padright(padright("⬤",this.Clever+1,"⦿"),5,"⭘")` | `= this.Clever+1`/5 |


| Fight         | Survival       | Social           |
| ------------- | -------------- | ---------------- |
| [Brawl:: 0]   | [Alert:: 0]    | [Allure:: 0]     |
| [Channel:: 0] | [Athletic:: 0] | [Etiquette:: 0]  |
| [Clash:: 0]   | [Nature:: 0]   | [Intimidate:: 0] |
| [Evasion:: 0] | [Stealth:: 0]  | [Perform:: 0]    |

## `= this.Species.Learnset`

**Moves**:: 

```dataviewjs
for (let i = 0; i < dv.current().Moves.length; i++) { 
    let MovePage = dv.page(dv.current().Moves[i]) 
    let SpeciesPage = dv.page(dv.current().Species)
    
    dv.header(3, MovePage.name)

    let acc = "F";

    if (MovePage.Accuracy1 === "Will")
    {
        acc = SpeciesPage["Insight"] + dv.current()["InsightPoints"] + 2;
    } else
    {
        acc = (
                (SpeciesPage[MovePage.Accuracy1]) ? 
                     SpeciesPage[MovePage.Accuracy1] : 
                     dv.current()[MovePage.Accuracy1]) 
                + ((SpeciesPage[MovePage.Accuracy1]) ? 
                    + dv.current()[MovePage.Accuracy1+"Points"] 
                    : 1) 
                + dv.current()[MovePage.Accuracy2]; 
    }
     
     let dmg = MovePage.Power + ((SpeciesPage[MovePage.Damage1]) ? SpeciesPage[MovePage.Damage1] + dv.current()[MovePage.Damage1+"Points"] : 0) +((SpeciesPage[MovePage.Damage2]) ? SpeciesPage[MovePage.Damage2] + dv.current()[MovePage.Damage2+"Points"] : 0) + ((SpeciesPage.Type.includes(MovePage.Type) )? 1 : 0);
     
     dv.paragraph("**Damage: **" + MovePage.Power + ((MovePage.Damage1) ? " + "+MovePage.Damage1 : "") + ((MovePage.Damage2) ? " + "+MovePage.Damage2 : "") +((SpeciesPage.Type.includes(MovePage.Type) )? " + STAB" : "") +  " = **" + dmg +"**");
     dv.paragraph("**Accuracy: **" + MovePage.Accuracy1 +" + "+MovePage.Accuracy2 + " = **" + acc +"**");
     
 
     dv.paragraph("| Type | Target | Damage Type | Power |\n"+
 "| ------------- | --------------- | ---------------- | -------------- |\n"+
 "| "+MovePage.Type+" | "+MovePage.Target+" | "+MovePage.DmgType+" | "+MovePage.Power+" |")
 
     dv.el('em', MovePage.description)
     
     dv.paragraph(MovePage.effect)
 }
```