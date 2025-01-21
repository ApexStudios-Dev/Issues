# I am having issues with block lighting and other rendering issues.
Do you have _Optifine_ or a similar mod installed? If so try and reproduce the issue without said mod installed.

If issue is lighting related and still arises, do you have the _Forge Lighting Pipeline_ enabled in forges client config? if not go and enable it.
_Config should hot load, so shouldn't need to reload game or world_

`./config/forge-client.toml` - `experimentalForgeLightPipelineEnabled = true`

# Will you port X mod to Fabric?
Unfortunately no, we have decided to hault all multi-loader development.

It has proven to be much more work than originally anticipated, we are now focusing on NeoForge development only.

# Upon loading the game it says I am missing `Registrator`
Use **ApexCore v1.10.0** (_or newer_) this comes with Registrator pre-packaged into it.

If you get any issues about duplicate mods referring to Registrator delete the old Registrator mod jar.

# Which versions of Minecraft do you currently support?

_We actively support the most recent major Minecraft version_

# How do I enable CTM for your mod?
We do not implement CTM ourselves but make use of CTM provided by other mods.

Install any mod which provides CTM capabilities, if we support that mods CTM, a new resource pack will become available for you to enable.

Currently supported CTM mods:
- CTM
- XyCraft: Core

# The mod is crashing when holding/attempting to place one of your items
Do you have Oculus/Optifine/Shaders installed or any other mod which overhauls the vanilla renderer?

If so this is more than likely the culprit, before reporting a issue please validate if this is the case by attempting to recreate the issue without said mods installed.
