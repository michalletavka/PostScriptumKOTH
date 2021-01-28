# King of the hill
A community made game mode for Post Scriptum.

Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=2357747214

# How to add KOTH into your map

1. Load the `.uasset` files contained in this repository to your mod
2. Select `BP_PS_GameMode_KOTH` as Game Mode in World Settings
3. Select `BP_PS_HUD_KOTH` as Player HUD in World Settings
4. Drag and drop the `BP_PS_KOTH_Lattice` actor into your map and make sure ther is no other Lattice actor
5. Make sure the Main Base actor is of class `BP_PSCaptureZoneMainNew`
6. Make sure all the objectives are of class `BP_PSCaptureZoneNew`

And that's all!

## Additional settings
Check out the details of the `BP_PS_KOTH_Lattice` actor, you'll find a `Flag Duration` and `Break Duration` variables. Fiddle with these to adjust how long should the flag stay active and how long should the break between flags be.

Adjust the size of your objective by setting the `Scale` property on the instances of `BP_PSCaptureZoneMainNew` placed on your map. Size of the objective sphere in the Steam Workshop **KOTH** mod is set to 4000 and it's scaled up for Classic KOTH by 6 and for Single KOTH by 10.