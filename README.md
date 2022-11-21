# Catse's BlenderToHolo Blender Plugin
Catse's (https://steamcommunity.com/id/catse) Blender to Garry's Mod Expression 2 plugin

steam community page: https://steamcommunity.com/groups/blendertoholo/

this is an experimental version of Catse's plugin, exploring animation possibilities

All E2 holo meshes can be added in Blender from Add > Mesh > Garry's Mod E2 Holo Shapes

You can tweak the Garry's Mod in-engine material path in the mesh creator loadout.

The Blender viewport changes color settings to be closer to vanilla Garry's mod by default when adding a holo shape. This can be disabled in the loadout menu.

Sound events can be added by selecting the holo object to emit the sound in Blender, then selecting a sound to play at the current frame from Marker > Add Garry's Mod E2 Sound Marker in the top menu of the Blender timeline. This adds a marker and uses the comma separated name to work out the holo object and sound path for that frame.

The holos in the current scene, sound events and the animation timeline/action can be exported to Garry's Mod E2 .txt with File > Export > Garry's Mod E2 Holograms.

A keyframe for a holo will only be added to the E2 script if the Blender holo object has a keyframe for that frame.
