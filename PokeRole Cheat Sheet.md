# Types

![[Pasted image 20210818192148.png]]

# Skills

| Strength | Dexterity | Vitality | Special | Insight |
| -------- | --------- | -------- | ------- | ------- |

| Fight       | Survival     | Social         | Knowledge    | Pokemon     |
| ----------- | ------------ | -------------- | ------------ | ----------- |
| **Brawl**   | **Alert**    | **Empathy**    | **Crafts**   | **Channel** |
| **Evasion** | **Athletic** | **Etiquette**  | **Lore**     | **Clash**   |
| **Throw**   | **Nature**   | **Intimidate** | **Medicine** |             |
| **Weapons** | **Stealth**  | **Perform**    | **Science**  |             |

| Tough | Cool | Clever | Beauty | Cute |
| ----- | ---- | ------ | ------ | ---- |
# Will Points

**Spend**
- 1 to ignore one Pain Penalty for the rest of the Scene
- 1 to reroll one failure from each roll for the rest of the round 

**Recovery**
-  Rest for a few days
-  feel accomplished by having achieved something great
-  follow their nature
-  get them as a reward for good role-play.

# Combat

**Pre Combat**

- Everyone rolls Initiative! `1d6+Dex+Alert`
- GM Declares any Weather Effects in Play
- Choose Abilities

## Combat Loop

1. Round Starts
    1. *Pokemon using Priority Moves jump to top of Initiative, Order Multiple Pokemon via Move Priority Number, then Dex.*
    2. Each Pokemon takes a Turn or Passes in Initiative Order 
    3. Repeat until all Pokemon Pass
    4. Trainer Actions
        1. Search for Cover `Insight+Alert`
        2. Enter the Fray, *cannot give Orders to Pokemon*
        3. Run Away `Dex+Athletic` vs Foe's `Dex+Athletic`
2. Repeat from 2 until Combat Ends

## A Pokemon's Turn

1. Choose a Move to use *that you have not used this Round!*
    1. If the move is "All Foes in Range" or "User and Allies in Range", select up to the [[PokeRole Cheat Sheet#Max Targets in Range by Rank|max number of targets]] allowed for your rank.
2. Make an Accuracy Roll `See Move for Dice Pool`
    1. Apply [[PokeRole Cheat Sheet#Pain Penalty All rolls EXCEPT ones with VIT or Will|Pain Penalty]]
    2. Apply Other Modifiers
3. Number of Successes Required met: **Attack Hits!**
    1. Three or more successes than needed? **Critical Hit, add 2d6 to Damage!**
4. Target can Evade or Clash the attack *if the attack doesn't use a social attribute!*
    * Evade
        1. Roll `Dex+Evade`
        2. Apply [[PokeRole Cheat Sheet#Pain Penalty All rolls EXCEPT ones with VIT or Will|Pain Penalty]]
        3. Equal to or Greater than Accuracy Roll: **Attack Evaded, no Damage, End of Turn**
    * Clash
        1. Chose a Damaging Move to use to clash with. *This counts as using the move for the Round!*
        2. Roll `Clash+Strength` if attacker used a Physical Move, `Clash+Special` if they used a Special move.
        3. Apply [[PokeRole Cheat Sheet#Pain Penalty All rolls EXCEPT ones with VIT or Will|Pain Penalty]]
        4. Equal to or Greater than Accuracy Roll: **Attack Clashed, Each take One Damage, End of Turn.**
5. Roll Damage
    1. `See Move for base Dice Pool`
    2. Add STAB, `1d6` if Move is same type at User.
    3. Add Critical Hit bonus Damage if Applicable
    4. *Subtract* Target's `Def/SpDef` from dice pool
    5. Apply any other Modifiers
6. Apply Damage
    1. If Target's type is immune to move's type: **No Damage, end of Turn!**
    2. No Successes on Damage roll: **1 Damage, end of Turn!**
    3. If Target's type resists move's type: **-1 from Damage for each resistant type!**
    4. If Target's type is weak to move's type: **+1 Damage! for each weak type!**
    5. Then: **Deal # of Successes as Damage, End of Turn!**

### Max Targets in Range by Rank

| Rank          | Targets |
| ------------- | ------- |
| Starter       | 2       |
| Beginner      | 2       |
| Amateur       | 3       |
| Ace           | 5       |
| Professional+ | 6       |

### Successes Required 

| Action # in Round | Required Successes |
| ----------------- | ------------------ |
| 1                 | 1                  |
| 2                 | 2                  |
| 3                 | 3                  |
| 4                 | 4                  |
| 5                 | 5                  |

### Pain Penalty (All rolls EXCEPT ones with VIT or Will)

| HP     | Reduce Successes by |
| ------ | ------------------- |
| Full   | 0                   |
| >=Half | 1                   |
| 1 HP   | 2                   |

# Dynamax

While a Pokémon is in Dynamax form it will obtain the following benefits:

| Dynamax       | Gigantamax      |
| ------------- | --------------- |
| Base Hp + 6   | Base Hp + 12    |
| Use Max Moves | Use G-Max Moves |

- Dynamax/Gigantamax lasts 3 Rounds
- Dynamax/Gigantamax Pokémon are immune to:
    - Flinch
    - Moves based on weight
    - OHKO Moves
    - Destiny Bond
    - Being removed from combat
    - having ther Ability Changed or Removed.
    - Other Pokémon cannot transform into them
- Max and G-Max Moves cannot be copied.

# Status

| Status         | Effect                                           | Resist                                                                    | Duration                            |
| -------------- | ------------------------------------------------ | ------------------------------------------------------------------------- | ----------------------------------- |
| Burn 1         | 1 Damage end/round                               | `Dex+Athletic` as action: 4 Cumulative Successes, Cured                   | End of Scene                        |
| Burn 2         | 2 Damage end/round (Lethal if Attack was)        | `Dex+Athletic` as action: 4 Cumulative Successes, Cured                   | End of Scene                        |
| Burn 3         | 3 Damage end/round (Lethal if Attack was)        | `Dex+Athletic` as action: 4 Cumulative Successes, Cured                   | End of Scene                        |
| Paralysis      | -2 Dex, moves 1/2 speed                          | N/A                                                                       | 24 Hours                            |
| Frozen         | No Actions                                       | Use Moves against Ice(HP 5, Def 2), Super Effective Moves break instantly | Until ice melts, Pokemon Faints     |
| Poison         | 1 Damage end/round                               | Subject remains immobile: Damage per hour instead                         | Until Faint & wake up 8 hours later |
| Badly Poisoned | Like Poison, but +1 Damage each Round            | Subject remains immobile: Damage per hour instead                         | Until Faint & wake up 8 hours later |
| Sleep          | No Actions                                       | `Insight`/action: 5 Cumulative Successes, wakes up.                       | 5 Minutes                           |
| Confused       | -1 Success from Actions, Failed Action: 1 Damage | `Insight` @ round start, 2+ successes ignore this effect for the round    | 5 Rounds or Switched Out            |
| Disabled       | Cannot used Disabled Move                        | N/A                                                                       | 5 Rounds to Scene                   |
| Flinched       | Lose Next Action                                 | N/A                                                                       | 1 Action                            |
| In Love        | 1/2 Damage against Foe and foe's allies          | `Insight` @ round start, 2+ successes ignore this effect for the round    | 1 Scene or Switched Out             |

# Weather

- **Sunny  **
    - +1 to Fire Move Power 
    - -1 Damage from Water Moves
    - Cannot be Frozen
- **Harsh Sun**
    - +1 to Fire Move Power
    - Water Type Moves cannot be used
    - +2d6 to Chance rolls for Burn Status
    - Cannot be Frozen
    - Sunny/Rain/Sandstorm/Hail Weather effects fail
- **Rain**
    - +1 to Water Move Power
    - -1 Damage from Fire Moves
    - Only 1 Success required to Cure Burn Status
    - Moves that Complete Heal in Sunny Weather only restore 1 HP
- **Typhoon**
    - +1 to Water Move Power
    - Fire Type Moves cannot be Used
    - Cannot be Burned
    - Moves that Complete Heal in Sunny Weather restore no HP
    - Sunny/Rain/Sandstorm/Hail Weather effects fail
- **Sandstorm**
    - 1 Damage to Non Rock, Ground, or Steel Types at end of Round
    - +1 Special Defense to Rock types
    - Moves that Complete Heal in Sunny Weather only restore 1 HP
- **Strong Winds**
    - +1 to Flying Type Move Damage
    - Electric, Ice, and Rock types moves are Neutral to Flying Types
    - Entry Hazards (Spikes) & Barriers (Light Screen) & Block Moves Fail
    - Sunny/Rain/Sandstorm/Hail Weather effects fail
- **Hail**
    - 1 Damage to Non Ice Types at end of round
    - +1 Defense to Ice Types in the field
    - Moves that Complete Heal in Sunny Weather only restore 1 HP
- **Fog**
    - -1 Success from Accuracy
- **Muddy**
    - Mobility reduced to 1/2
    - Cannot get out of range
- **On Fire!**
    - 3 Chance Dice to Burn Pokemon at end of Round
- **Electric Poles**
    - +1 to Electric Move Power
    - Pokemon don't need to Recharge. 

# Catching

Catch rolls are: `Seal Potency` + `Bonus Successes`

![[Pasted image 20211020210141.png]]

![[Pasted image 20211020210205.png]]

![[Pasted image 20211020210218.png]]

# Training

Training rolls are `<Relevant Attribute/Social> + Lore`.

**Rank Up**

![[Pasted image 20211020205852.png]]

**Retrain** 
3 Successes to:

- Redistribute all Attributes and Social Attributes awarded by Rank.  
- Redistribute all Skill Points awarded by Rank. Assign all Skill Points from a Rank, before assigning all Skill Points from the next Rank.
- Pokémon may forget Moves and learn new Moves from available Ranks. *Forgotten Moves exclusive to previous Evolutions are lost forever.*

# Crit stats

https://anydice.com/program/28362