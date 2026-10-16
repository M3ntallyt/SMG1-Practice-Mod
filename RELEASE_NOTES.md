# RMGK Practice v1.0

RMGK Practice v1.0 for **Super Mario Galaxy Korea (RMGK01)**.

This release provides English documentation and an English permanent patcher. The mod's gameplay code, game text, audio and resources retain the existing v203 behavior.

- **Windows Perma Patcher:** accepts a clean Korean ISO, WBFS or RVZ and produces exactly one selected ISO, WBFS or RVZ. Extract the entire ZIP before running the executable.
- **Dolphin/Riivolution package:** extract into `Dolphin/Load/Riivolution` and select **IGT v1.0**. Start normally from a game save rather than an older emulator savestate.
- **Source companion:** patcher and mod development sources, verification reports, licenses and corresponding third-party source archives. Distribute alongside the Windows package.

Existing game saves, PBs, stored positions and preferences remain compatible. Permanently patched images should be launched normally, without applying the Riivolution mod again.

Validation: 12 Go tests, 10 native PPC checks and all nine single-format input/output pairs passed. Container checks use a small synthetic test disc. The patched DOL is identical to the preceding working patcher; full gameplay and Windows dialogs were not executed during this packaging update.
