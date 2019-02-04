# ShadowMemoryWatchList
Memory Watch List for Dolphin Memory Engine running Shadow the Hedgehog

This is repo is really just ment for backing up my personal memory list for my personal projects. So I don't plan to include minor addresses that dont help with that goal.  If something is incorrect or there's something missing that you think should be here, feel free to let me know.

The list currently contains the following:

| Label | Description |
|---|---|
| Meter Score and Values | This is for tracking the score and chaos power meter values during gameplay |
| Stats | Stats for Ammo, Lives, Rings, and the current Timer value |
| Position | X, Y, Z position values for Shadow (Not his acutal position, it's something else, but it matches his position values exactly.  Can be used to find his current position values in memory.) |
| Stage Variables | Currently loaded Stage ID and Expert Flag. (If locked will force the a stage load to enter the locked values. Known issue is that The Last Way from Stage Select requires Final Haunt to be selected, so there's more to it than it seems.) |
| Player Controls | Values for controller input. (Currently only P1 Buttons.  Would like to have all 4 players with analog signals eventually.) |
| MemoryCard-Stages | Seems to be the values for all missions and bosses that are saved to the Memory Card. Unused are empty sections that are formated like the rest of the sections, but no values are been written to it.  Maybe useful to know for extra levels in a ROM hack? (I recall seeing an extra set of these values somewhere else in memory, so assume this isn't complete for now.) |
| Option Menu Variables | Values for tracking the position and selection of items in the Options Menu. (I have more values in a different list that I forgot about before the current commit.  I'll add them here later.)|
| Time Stop Enabled | If on, it turns Shadow's Chaos Control into the Chaos Control Time Stop seen in boss battles. |
| Speed Multiplier | Values that changes Shadow's speed. (Stolen from the default Dolphin Gecko Codes.  Not sure what it truely does.) |
| Stop Time and Shadow | I believe it's used by Pause and Mission Complete to prevent player commands.  Can be used to trigger events based on completing a stage. |
| Last Story Unlocked | Allows access to Last Story |
| Expert Mode Unlocked | Allows access to Expert Mode |
| Library 1-32 | Part 1 of Library Entries Flags (as you will see this is what I ment by "something missing") |
| Number of A Ranks | Seems to be the number used in the stage select to show A rank progress.  Not sure if it does more than that. |
| Library End | Just a note to keep track of the area that Library flags take up. Will clean this up later. |
| ???? | ???? (I think I was testing something, but I'm not sure what.) |
| Weapons Unlocked | Flags for determining which weapons are currently unlocked. Uses Hero and Dark flags to determine if Lv 1 or Lv 2 is to be used, except for Shadow Rifle. |
