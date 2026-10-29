# Changelog

## 1.7.5

- Reduced the FPS drop while inventory is open by skipping unchanged backpack slot, panel, and crafting-search visuals.
- Stopped repeated backpack cell and tooltip writes when their state is unchanged.
- Stopped periodic Equipment and Quick Slots row resizing when inventory height has not changed.
- Kept Deeper Pockets row growth, backpack panel following, Alt-drag, cargo positions, and existing configuration behavior.

## 1.7.4

- Fixed the player inventory background remaining at four rows after Haldor's Deeper Pockets upgrades when Equipment and Quick Slots is installed.
- Sized the native board to ordinary player rows, excluding backpack and reserved equipment rows.
- Prevented duplicate EQS extra-row expansion of the board, shadow, and gamepad selection frame.
- Preserved backpack follow/Alt-drag behavior, item positions, and configuration settings.

## 1.7.3

- Added the BepInEx dependency and GitHub website link to Thunderstore metadata.
- Added five original loadout and equipment photos using public image links.
- Corrected installation wording for Thunderstore.
- Added OpenAI Codex assistance disclosure to the README, project metadata, and compiled assembly metadata.
- Retained existing gameplay, models, textures, sounds, recipes, and configuration defaults.

## 1.7.2

- Added fitted, saved ground contacts for dropped-pack lantern arms and lantern housings.
- Kept dropped arm and lantern visuals in the same packed pose as their collision geometry.
- Shared saved contact profiles with other clients and headless servers.
- Added one-time contact metadata repair for older dropped packs.
- Retained existing cargo, artwork, sound, worn motion, and armor-stand behavior.

## 1.7.1

- Dropped packs fall from their worn position and settle using body and rounded-bedroll collision.
- Added portable-pack display for equipped quivers, arrows, and the optional Camping travel kit.
- Enabled core portable-pack physics on dedicated servers using the same DLL.

## 1.7.0

- Added persistent backpack cargo and saved item positions when removing or dropping packs.
- Added Shift+R dropping and direct re-equipping when a dropped pack is picked up.
- Retained selected lantern and arm attachments with portable packs.
- Added armor-stand backpack display and cargo preservation.
- Prevented filled backpacks from entering ordinary inventory cells or other backpacks.

## 1.6.50

- Added optional Path of Valheiman integration for inventory rows, gear placement, and grave previews.

## 1.6.49

- Reduced repeated inventory and grave recovery work around death and respawn.

## 1.6.48

- Improved equipped accessory recovery from graves.
- Added Alt-drag positioning for the backpack panel and pack slot while retaining automatic panel following until moved.
