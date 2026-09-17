# AtlasLootClassic

This mod is distributed under Version 2 of the GPL.  A copy of the GPL is included in this zip file with links to non-english translations.

[Changelog history](https://github.com/Hoizame/AtlasLootClassic/blob/master/AtlasLootClassic/Documentation/Release_Notes.md)

## v3.2.0-fix3 (September 17, 2026)

- Fixed infinite recursive script timeouts ("script ran too long") caused by UI layout thrashing and dropdown menu cascades in modern Classic Era clients.
- Added a debounced `GET_ITEM_INFO_RECEIVED` and `ITEM_DATA_LOAD_RESULT` event listener to safely auto-refresh the UI when bulk item cache data arrives from the server.
- Excluded the incompatible TBC `AtlasLootClassic_BiS` module from the Classic Era build to prevent dead queries and blank items.
- Updated deprecated globals and `LE_ITEM` Enums to restore compatibility with the modern Classic Era client.

## v3.2.0 (Oct. 22, 2023)

- update .toc version
- fix lua error with companions
- Hallow's End update PR #416
- Fix epic blue gem id, add Ashen Verdict engineering PR #413
- Add Defiler Scourgestone Vendor
- Update Dalaran Vendor
- #397, #388 Update to use new Mount API
- #396 Added "Maiden of Grief" Missing items in Titan Rune Beta - Halls of Stone
- #395 Fixed "King Dred" Wrong loot in Titan Rune Beta - Drak'Tharon Keep
- #394 Fixed "The Prophet Tharon'ja" Wrong loot in Titan Rune Beta - Drak'Tharon Keep
- #393 Added Missing Leatherworking Fur Linings
- #391 Added Enchanting Cloak Resistances (Arcane, Fire, Frost, Nature, Shadow), Removed Duplicates
- #387 Fixed Incorrect Set Links for Death Knight Season 7 PvP Set
- #381 Added "Six Shared Loot Bosses" Missing items in Titan Rune Beta - Violet Hold
