# PF-WOTR-mod-archive
archive for created mods which use WOTR's own mod system

NOTE:
For mods to work, there MUST be "Assemblies" and "Bundles" folder inside the same folder as "Blueprints". However, due to how github works, empty folders cannot be uploaded. Please make them manually.

Please remember to update OwlcatModificationManagerSettings.json for mods to be recognized!

**Alignment:**
All Mythic Paths are any Alignment. Doesn't exactly work due to 'fix alignment' mythic quests.

**Legend:**
Modifies Legend EXP table to be 2 to 1 compared to normal exp table.

**MythicReworked:**
Rework of the below mod. Major changes include: All requirements for Mythic Paths have been removed. All Mythic Paths are now available for selection on Drezen rooftop, with features moved to accomodate the 5 remaining Mythic Levels.

**Mythic:**
Allows faster and more front-loaded mythic levels, also allows Legend to be picked on Drezen rooftop.
**2 Mythic Levels in prologue** (upon gaining light power and upon defeating maze boss).
List of changes to accomodate:

Drezen rooftop exit node (does not normally allow Legend to exit).

Intro section during C3 changed to recognize Legend (does not give proper etudes otherwise).

Areelu's Lab changed to be discoverable even without Mythic Quests.

Goddess Summit edited (can choose between original game Legend or new Secret Ending Legend which does not give certain etudes).

Note: Areelu dialogue directly checks if you are Legend etude, so the following have been edited to compensate with the above:

Areelu's secret lab dialogue

Threshold dialogue

Additional changes:

Month/day requirement for secret ending removed.

Ch2 UndeadLair (Ruins of Ashberry Hamlet in EN localization) perception dc check set to 0.

Includes bug fix for Seelah companion quest (Meet Elan in Drezen etude -> Meet Elan in Barracks etude).

Following has been fixed, so these changes are deprecated:


Due to game being slightly buggy (I don't know if its because of the mod or just the game being the game, certain quests/companion quests seem to not trigger due to not having Mythic Quest in Legend.

Current changes because of the above:

Molten Scar is now findable without quest.

Update: Played through Legend secret ending. Had some issues in chapter 3 with some quest chains not starting. Wintersun can be found manually, and Molten Scar has been edited to be findable without any conditions. Secret ending works as normal. Areelu/other reactions sometimes revert to Legend, but all conversations that give etudes should be fine. 6/7 of soft requirements are achievable. (7th unachievable one is the reach rank 10 in certain mythic classes that areelu favors).
Update update: Updated chapter 3, proper etudes are now given. Companion quests have been tested to be working through time requirement.

**Paladin:**
Buffs Paladin class and Radiance sword.

**SpeedyExhaustion:**
Removes character speed slow effect on Exhaustion debuff.

**RemoveExhaustion:**
Changes Fatigue and Exhaustion to have no effect, and will no longer show in UI.

**BugfixDLC**
DLC 6 modified: Opening cutscene that shows portal has been removed due to sometimes bugging out. Sithud reborn cutscene has been changed to the victory cutscene.

**KineticRod**
Adds Kinetic Rod and Greater Kinetic Rod to the game, which can be bought at the tavern in act 3 and the Storyteller in act 4, respectively.

Adds CrownOfElements (from Kingmaker), obtainable by defeating Sarzaksys in Act 4 (Fleshmarkets).

Adds Quicken Kinetic Metamagic rod, obtainable by defeating Vellexia (obtained in post-combat dialogue). Due to swift actions not interacting very well with gather power, I made them incompatible, so you can only have one group active at a time. To compensate, the rod gives -1 burn.

Adds Ultimate Kinetic Rod and Ultimate Kinetic Diadem to the game, buyable from the Storyteller in act 5. (Dialog and vendor have been updated to accomdate this change).

**Skilled Azata**
Changes Azata's 'All Skilled' feature to make all skills class skills, and gives an additional +6 bonus for having a rank (original is +3, so 1 rank = 10 total).

**MonkAlignment**
Simple mod that removes monk alignment requirement.

**BiggerGoldenDragon**
Changes Golden Dragon size modifier from 0.16 to 1.00. Because why not?

Modding Notes:
Components with the same name generally are unable to stack. For example, copy pasting a component three times means the game only recognizes it once.

For adding items to units, use Upgraders, as those are runtime-friendly. Otherwise, it only changes when the unit is first created.

Vendor shared tables are added through Etudes when the chapter is updated.
