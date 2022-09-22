# Pokerole Obsidian SRD

![](https://i.imgur.com/4ZpTthC.png)

*TLDR:* This is a System Reference Document (SRD) for Pokerole 2.0. 

[Obsidian](https://help.obsidian.md/Obsidian/Index) is a note taking application with a wide variety of community plugins and features markdown notes with wiki style document linking. If you've never used Markdown before, Obsidian has [a guide on the syntax here.](https://help.obsidian.md/How+to/Format+your+notes) (Tip: Ctrl/Cmd+O is the quick switcher, an easy way to search for a document by name.)

[Pokerole](https://www.pokeroleproject.com/) is a Pokemon tabletop roleplaying game. The books are available on the linked homepage and the [Discord Community](https://discord.gg/95DFpdMVcC) is also available to answer questions about the system. 

## Right, But What is This?

A System Reference Document is a reference for a roleplaying game's mechanics. Given Pokerole supports the entire Pokedex, there's a lot of content to be searched and referenced and this vault makes doing so easier. 

The document is divided into the following sections: *Abilities, Learnsets, Moves, Natures, and Pokedex*. The content of each should be self explanatory. Two additional SRD folders exist, *Home and Sprites* which contain Pokemon Home sprites and Box Sprites respectively. 

If you would like more information on what fields are available in each of the Document types, you can check out the [[SRD Data Structures]] document in the root of the Repository. 

Some highlights of the SRD's features: 

- **Links** When an SRD document references another document in the SRD, it will be rendered as a clickable link you can follow. For example, each Pokemon's abilities can be clicked on to get the details of that ability. (Tip: you can press Ctrl/Cmd over a link to open a preview!)
- **Tags** Obsidian supports adding \#tags to documents to group them. Each of the different document types in the SRD are tags according to their type. 
- **[Dataview](https://blacksmithgu.github.io/obsidian-dataview/)** is a very powerful query language that can be run against your notes. It can, for example, select all Pokedex entries where the Pokemon's Maximum Strength are greater than 5 and present them for you in a table. Dataview powers a large portion of the SRD, and I've included a *Dataview Queries* folder in the Vault with some sample queries. 
- **Templates** are documents you can insert into other documents with a command. You can create your own or use some of the ones I've included in the *Templates* folder.
- **Multiplatform** Obsidian can be used on any operating system, include mobile devices. You can set up your Vault to synchronize across all of those devices as well. 

I've also included a *Campaign* folder. This folder is an empty framework based off the one I use for my own Pokerole campaign. 

## Sounds Great, How Do I Start?

1. Download this Obsidian Vault. You can do this via Git if you're familiar, or you can download a [zip](https://github.com/Willowlark/PokeroleObsidianSRD/archive/refs/heads/master.zip) from Github page (you're on it).
2. Install [Obsidian](https://obsidian.md/). (Tip: you may want to look into the requirements for setting up sync before you get started.)
3. Open the Pokerole SRD folder you downloaded in step one by selecting "Open Folder as Vault". 
4. You'll be prompted if you trust the owner of the vault before enabling plugins (they are required). 

## Is There a Character Sheet?

[[Pokemon Character Sheet Template]] is a template you can use to have dynamic Pokemon sheet that references the SRD for moves, abilities, base stats, etc. BE AWARE, this is not the most user friendly character sheet. 

This is designed more for reference (like a Rival's Pokemon), less for on the fly editing like a player would need to do (Hp tracking, etc). Due to the scripting that powers the template, you'll need to be very careful when modifying the template. Below are some usage tips.

1. First thing you have to do is in the *frontmatter* (the list of values before the document itself starts), complete the Species link. If you want a pikachu, Species should read `"[[SRD-Pikachu]]"`. This populates the vast majority of the sheet.
2. Base stats and maximums are calculated from the SRD. To add points to your stats, find the appropriate name in the frontmatter (IE, for Dexterity, add to DexterityPoints). This will increase the stat.
3. DO NOT modify anything in code blocks. It's not worth the effort unless you have a good understanding of Dataview
4. Add to your skills by changing the number in the table. Skills are nice simple.
5. Add moves by putting links to the SRD moves after the `**Moves**::` label. Multiple moves are comma separated. An example would be:
> **Moves**:: [[SRD-Thunderbolt]], [[SRD-Iron Tail]], [[SRD-Electroweb]], [[SRD-Quick Attack]]

# Credits and Contacts

- This SRD was put together by myself, I can be contacted through Github (here) or Discord where my username is Willowlark#2359. 
- The data that was used to generate the SRD was compiled out of the book by Shadeslayer into this [repository](https://github.com/XShadeSlayerXx/PokeRole-Discord.py-Base). 
- Box sprites were compiled from this [repository](https://github.com/msikma/pokesprite).
- Home sprites were ripped from [the spriter's resource](https://www.spriters-resource.com/nintendo_switch/pokemonhome/).
- [Pokerole](https://www.pokeroleproject.com/) was written by it's own team, check them out.
- Needless to say, Pokemon is owned by Nintendo