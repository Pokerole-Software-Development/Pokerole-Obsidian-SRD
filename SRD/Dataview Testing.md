- [x] sprites and home images
- [ ] Make displayed, derived values in the templates into keys
- [ ] Use a support page for the character sheet that does longer queries
- [ ] Capitalization is a problem 



```dataview
TABLE 
Number, Name
FROM #PokeroleSRD/Pokedex 
WHERE GoodStarter = "Yes"
SORT Number ASC
```

```
TABLE
Name
FROM #PokeroleSRD/Pokedex 
WHERE 
Type1 = "Fairy" OR Type2 = "Fairy"
```

```
TABLE
Name
FROM #PokeroleSRD/Pokedex 
WHERE 
(MaxStrength = Strength
OR MaxDexterity = Dexterity
OR MaxVitality = Vitality
OR MaxSpecial = Special
OR MaxInsight = Insight)
AND 
!(MaxStrength != Strength
OR MaxDexterity != Dexterity
OR MaxVitality != Vitality
OR MaxSpecial != Special
OR MaxInsight != Insight)

```

``` 
TABLE
Name
FROM #PokeroleSRD/Pokedex 
WHERE 
( 5 <= Strength
OR 5 <= Dexterity
OR 5 <= Vitality
OR 5 <= Special
OR 6 <= Insight)
AND
(MaxStrength != Strength
OR MaxDexterity != Dexterity
OR MaxVitality != Vitality
OR MaxSpecial != Special
OR MaxInsight != Insight)
```

