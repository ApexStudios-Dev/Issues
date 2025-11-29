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
- [CTM](https://www.curseforge.com/minecraft/mc-mods/ctm)
- [XyCraft: Core](https://www.curseforge.com/minecraft/mc-mods/xycraft)
- [Athena](https://www.curseforge.com/minecraft/mc-mods/athena)
- [Fusion](https://www.curseforge.com/minecraft/mc-mods/fusion-connected-textures)

# The mod is crashing when holding/attempting to place one of your items

Do you have Oculus/Optifine/Shaders installed or any other mod which overhauls the vanilla renderer?

If so this is more than likely the culprit, before reporting a issue please validate if this is the case by attempting to recreate the issue without said mods installed.

# Will you downport to X version?

We try to keep as up-to-date as possible with our mods, always updating to latest version possible, and we do not actively downport or update any older versions.

With that said we will update older versions if major issues/bugs are found, we sadly just do not have the time to keep every version updated and feature complete.

# Will you downport to / update 21.1 or older?

Same answer as [_`Will you downport to X version?`_](#will-you-downport-to-x-version) but also these versions are very legacy and fully unsupported now.

Due to the major overhaul/rewrite we did in 21.4+ and moving to NeoForge there are unfortunatly too many breaking changes for us to downport to or update these versions.
