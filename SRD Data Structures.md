# SRD Data Structures

## Dex Ids

DexID matches the following pattern `\d{4}([GAHPXY]|F\d)` which in simple terms is the four digit pokedex number plus an indicator of variant. DexID is used in the Pokedex and Learnset data structures. 

- **Variants**: 
    - **G**alar, 
    - **A**lolan, 
    - **H**isuian, 
    - **P**aldean, 
    - **X** Mega, 
    - **Y** Mega Variant, 
    - **F#** Form (with Number to id multiple forms)

## Pokedex

| Field            | Type   | Notes                                                                | When Querying Use: |
| ---------------- | ------ | -------------------------------------------------------------------- | ------------------ |
| Ability1         | String | Ability Name                                                         | -                  |
| Ability2         | String | Ability Name or empty string if none                                 | -                  |
| BoxSprite        | String | Filename of the Boxsprite for the mon                                | -                  |
| EventAbilities   | String | Ability Name or empty string if none                                 | -                  |
| GenderType       | String | Empty String unless Species has unique gender forms, then "M" or "F" | -                  |
| HasAForm?        | String | "Yes" or Empty String                                                | hasaform           |
| HiddenAbility    | String | Ability Name or empty string if none                                 | -                  |
| HomeSprite       | String | Filename of the Pokemon Home Sprite for the Mon                      | -                  |
| Learnset         | String | Obsidian link to Learnset document for the Pokemon                   | -                  |
| Legendary        | String | "Yes" or "No"                                                        | -                  |
| Name             | String | Pokemon Species name                                                 | -                  |
| Number           | int    | Pokedex Number of Species                                                                     |                    |
| Sprite           | String | Basename for this pokemon's sprites                                  | -                  |
| Type1            | String | Type                                                                 | -                  |
| Type2            | String | Type or empty string                                                 | -                  |
| DexID            | String | Pokedex Number + variant flags, if any                                 | -                  |
| Species          | String | Pokemon Species name (same as Name)                                  | -                  |
| Types             | String | Combined Type1 and Type2, " / " separated if both                    | -                  |
| Abilities        | String | Combined Abilities in format "#1 / #2 (Hidden) \<Event\>"            | -                  |
| Base HP          | int    | Base HP value                                                        | base-hp            |
| Strength         | int    | Base Strength score for the Species                                  | -                  |
| Dexterity        | int    | Base Dexterity score for the Species                                 | -                  |
| Vitality         | int    | Base Vitality score for the Species                                  | -                  |
| Special          | int    | Base Special score for the Species                                   | -                  |
| Insight          | int    | Base Insight score for the Species                                   | -                  |
| MaxStrength      | int    | Max Strength score for the Species                                   | -                  |
| MaxDexterity     | int    | Max Dexterity score for the Species                                  | -                  |
| MaxVitality      | int    | Max Vitality score for the Species                                   | -                  |
| MaxSpecial       | int    | Max Special score for the Species                                    | -                  |
| MaxInsight       | int    | Max Insight score for the Species                                    | -                  |
| Recommended Rank | String | Rank the Species MIGHT be found in the wild                          | recommended-rank   |
| Good Starter     | String | "Yes" or "No"                                                        | good-starter       |
| Can Evolve       | String | "Yes" or "No"                                                        | can-evolve         |

*Note: The last column "When Querying Use:" is only relevant for the columns that don't have dashes. This column is for fields that have names that can't be indexed via . notation normally due to the characters in the field name. The simplifications you see there (dashes instead of space, lower case, dropping special characters) can be used on any Dataview field, you just don't need to.*

## Learnsets

| Field   | Type   | Notes                                                                                                                      |
| ------- | ------ | -------------------------------------------------------------------------------------------------------------------------- |
| Name    | String | Name of Mon                                                                                                                |
| Species | String | Obsidian Link to Species entry in Pokedex                                                                                  |
| DexID   | String | Pokedex Number + variant flags, if any                                                                                       |
| Moves   | list   | List of Lists. Internal Lists have two values, Rank move is learned at (string), and the string obsidian link to the move. |

*Note: Working with the Moves list is a little funky, but not hard once you understand how Flatten works. Look at [[Mons with Move]] to get an example of how Flatten can be used.*

## Moves

| Field       | Type   | Notes                                     |
| ----------- | ------ | ----------------------------------------- |
| Accuracy1   | String | Attribute Name                            |
| Accuracy2   | String | Skill Name                                |
| Damage1     | String | Attribute Name or Empty String            |
| Damage2     | String | Second Damage Pool source or Empty String |
| Description | String | Description text for move                 |
| DmgType     | String | "Physical" or "Special"                   |
| Effect      | String | Move's effect text                        |
| Name        | String | Name of the Move                          |
| Power       | int    | Power value of the move                   |
| Target      | String | What is targeted by Move                  |
| Type        | String | Type of the Move                          |

## Abilities

| Field       | Type   | Notes                              |
| ----------- | ------ | ---------------------------------- |
| Description | String | Flavor Text description of Ability |
| Effect      | String | Effect text of Ability             |
| Name        | String | Name of Ability                    |


## Natures

| Field       | Type   | Notes                                             |
| ----------- | ------ | ------------------------------------------------- |
| Confidence  | int    | Confidence score of the Nature                    |
| Description | String | Text Description of Nature                        |
| Keywords    | String | Comma separated keywords for the Nature           |
| Name        | String | Name of Nature                                    |
| Nature      | String | Name and Confidence in format "Name (confidence)" |

