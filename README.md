# RMGK Practice v1.0.0

A practice mod for **Super Mario Galaxy Korea (RMGK01)**, with a Windows permanent patcher and a Dolphin/Riivolution package.

**[Download the release](https://github.com/M3ntallyt/SMG1-Practice-Mod/releases)**

The patcher and distribution documentation are in English. In-game text, audio, layouts and gameplay retain the existing mod's languages and behavior.

## Downloads

| File | Purpose |
| --- | --- |
| `RMGK_Perma_Patcher_v1.0.0_WINDOWS.zip` | Windows 64-bit permanent patcher, with the mod and disc tools included. |
| `RMGK_Practice_v1.0.0_RIIVOLUTION.zip` | Complete Dolphin/Riivolution mod package. |

The source companion is supplied alongside the Windows package. Source code and detailed verification reports are inside the downloadable packages.

## Permanent patcher

1. Extract the **entire Windows ZIP**, keeping `mod` and `tools` beside the executable.
2. Run `RMGK_Perma_Patcher_v1.0.exe` and select a **clean Korean RMGK01 ISO, WBFS or RVZ**.
3. Choose **one output format: ISO, WBFS or RVZ**, then select a new output filename.
4. Wait for **DONE** and launch the resulting image normally in Dolphin.

Only one output format is produced per run. Launch permanently patched images without applying the Riivolution mod again. Python and Go are not required to run the patcher.

## Dolphin / Riivolution

1. Close Dolphin and extract the complete Dolphin ZIP into `Dolphin/Load/Riivolution`.
2. Start the clean Korean game with Riivolution patches and select **IGT v1.0**.
3. Start normally from your game save, rather than an emulator savestate from an older mod build.

Existing game saves, PBs, stored positions and preferences remain compatible.

## Practice features

- In-game timing, PB/result display and input display.
- Practice restart, existing death/transition timing and save improvements.
- Hungry Luma respawn and repeatable power-up/tutorial behavior.
- Persistent position slots and Observatory teleport shortcuts.
- Dome-to-dome timing, route PBs and the black Luma route map.
- Pause-menu star selection and persistent preferences.

## Main controls

Hold a combination for **30 frames**. Each hold triggers once; release before repeating it.

| Combination | Action |
| --- | --- |
| Z + Down | Toggle the level/dome timer display. |
| Z + Left | Toggle the input display. |
| Z + Up | Toggle music. |
| Z + Right | Toggle Luma respawn for the next fresh attempt. |
| C + Up | Toggle power-up explanations and first presentation. |
| C + Right | Toggle Rolling Green / Loopdeeloop tutorials. |
| C + Left | Toggle position controls and Observatory teleports. |
| C + Down | Restart Stage. |

In levels, press **1** to save a position and **2** to restore the current context's slot. A successful position load invalidates that attempt for PBs while timing continues. The complete controls, Observatory shortcuts and save-data details are in each package's English README.

## Version and validation

**v1.0** is the public release version, based on development build v203. Gameplay patch values and resource bytes are preserved, and the permanent patcher's generated DOL matches the preceding working patcher.

Validation passed: **12 Go tests, 10 native PPC checks and all nine single-format input/output pairs**. Container tests use a small synthetic Wii disc. Full gameplay and Windows dialogs were not executed during this packaging update.

## Third-party notices

The patcher includes WIT and DolphinTool. Their notices, licenses and corresponding source archives are supplied with the release. Consult `THIRD_PARTY.txt` and the per-component licenses in the packages.
