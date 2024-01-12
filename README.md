# Greys-Incense-Expanded

Welcome to the repository for my first mod: an expansion on the lovely Epochs - Incense mod by DetVisor. This mod also currently utilizes some edited assets from the Vanilla Expanded series of mods where placeholders are needed. Currently, this mod directly uses the resources from the Epoch's mod, but I'm working on a patch. As such, this isn't ready for release into the Steam Workshop just yet, and **this release is just for testing purposes.**

I've always felt that RimWorld lacks commodities outside of food and drugs when it comes to luxuries. The aesthetics of Epochs - Incense, and the associated environmental mood boost seemed overpowered for how little material investment there was, but I enjoyed it immensely. Thus the idea for this mod was born, before I realized that fuel implementation requires more processing power. Oh dear.

This first implementation of the mod was in order to accomplish two things: a production chain that makes sense, and a framework for growable aromatics. This will be expanded to include its own categories for aromatic plants in the future. The production chain is based on how incense works today. You need combustibles, oxidizers, binders and aromatics to make incense -- conveniently things that have one implementation in every biome, except for the most remote. Ice sheets may eventually even utilize an Ambergris resource.

Additions:

- Several trees and plants with harvestable aromatic materials, including:
    - Boswellia
    - Sandalwood
    - Tabinoki
    - Monarda (Wild Bergamont)
    - White Sage
    - Patchouli
- A simple production chain for making primitive and more advanced incense sticks.
    - Incense has two forms: indirect vs direct burning. The mod currently only has direct-burning types.
    - Process raw aromatics into powders, essential oils and pastes.
    - Utilize gum tragacanth for stickless incense in wood-poor environments.
    - Two qualities of incense from various ingredients (Sandalwood is going to be nerfed in price, but takes a long time to grow to offset)
- Existing incense burners are patched (poorly I should add, no judgements please) to utilize appropriate fuels.
- Rudimentary "Speshul" incense burners for better quality incense and increased boon radius and quality.

Roadmap:

Current workload -->
- Heavily tweaking balance for harvest, crafting value add, usage of incense, etc:
    - <del>Recipe errors were found and fixed.</del>
    - <del>Will probably adjust ratios for regrowing plants, due to ease of sowing and repeatable harvests (gum tragacanth, patchouli, etc.)</del>
    - [2024-01-01] From playtesting determined that growth period for plants might be too long, looking at reducing them by 25-30% after more extensive testing.
    - [2024-01-12] From playtesting realized bug in the aromatics recipe with the custom ThingCategory GI_AromaticPlant recipe for paste, now troubleshooting fix.
- Making incense crafting a viable stream for selling to factions:
    - <del>Shaman merchants and exotic wares merchants in particular.</del>
    - Exotic goods dealers now deal with raw incense materials, but need to deal with manufactured and finished incense products.
- Better art for trees.
- <del>Better art for sage bundles.</del>
- Better art for essential oils [2024-01-01] and Monarda
- [2024-01-01] Some sort of internal error. For testing purposes I've decided to remove mentions of IncenseTable from the recipes and the textures for now (boo, I did pretty well on those...) Still going to troubleshoot it<del>Fixing the incense table, because I cannot seem to get it to work no matter how hard I try.</del>
- Patching for utilization of Epoch's art (to prevent redundancy errors)

Next up -->
- Incense art review and improvement.
- Better implementation of patches.
    - <del>[2024-01-12] Added ReGrowth: Aspen patch for Monarda.</del>
- Integration of current plants with popular biome mods.
    - ReGrowth partially complete. Unsure about integration with the rather complex Ashlands.
- Implementation of braziers that utilize raw aromatics (Frankincense chips, sandalwood, sage, etc)
- Less recipe clutter.
- Integration with Ideology:
    - Rituals.
    - Incense desire.
    - Make incense platforms actually require incense.
- Mod specific incenser art based off of historical/cultural designs.

Future/Potential Implementations and Goals -->
- Better def manipulation through some custom C# coding:
    - Heat mapping incense spread for tiered benefit depending on distance (if computationally viable)
    - Allowing incense of both types to be used by a single type of burner
    - Providing psychic/meditation boons for certain incenses.
- More plants and biome utilization for wild aromatics.
- Anima/Gauranlen tree materials.
- Custom gene that secretes incense making materials (ew)
- Ambergris or other animal based incenses.
