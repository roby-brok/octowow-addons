# My OctoWoW Addon Setup

The addons and client mods I run on [OctoWoW](https://octowow.st) (WoW 1.12.1 client).

This repository is **a list, not a mirror.** No addon code is hosted here — every entry links to the
author's own repository, which is where you should download it from. All credit belongs to the
people who wrote these; I just use them and occasionally fix something.

Maintained by **Roby_Brok**.

---

## Client mods (DLLs)

These are loaded by [VanillaFixes](https://github.com/hexblade/VanillaFixes) and are not addons —
several of the addons below depend on them.

| Mod | Version | Source |
|---|---|---|
| SuperWoW | 2.2 | https://github.com/balakethelock/SuperWoW |
| Nampower | 4.6.2 | https://github.com/Emyrk/nampower |
| UnitXP SP3 | — | https://codeberg.org/konaka/UnitXP_SP3 |

---

## Interface

| Addon | Version | Source |
|---|---|---|
| pfUI | 9.0.0 | **[my fork](https://github.com/roby-brok/pfUI)** — original by [Shagu](https://github.com/shagu/pfUI), Turtle edition by me0wg4ming |
| pfUI [Addon Skinner] | 0.4 | https://github.com/jrc13245/pfUI-addonskinner |
| pfUI [Better Totems] | 1.0 | **[my fork](https://github.com/roby-brok/pfUI-bettertotems)** — original by [Bombg](https://github.com/Bombg/pfUI-bettertotems) |
| Modern Map Markers | 2.4 | https://github.com/tilare/ModernMapMarkers *(I run an OctoWoW variant with Atlas + transport-destination support)* |
| LevelRange [Turtle] | 2.2.0 | https://github.com/Spartelfant/LevelRange-Turtle |
| Atlas-TW (Atlas-CFM) | 1.60 | https://github.com/byCFM2/Atlas-TW |
| PizzaSlices | 1.5.2 | *radial action menus, by Pizzahawaii — installed manually* |
| Turtle_General / Turtle_GroupUI | — | *bundled with the client* |

## Quests & world

| Addon | Version | Source |
|---|---|---|
| pfQuest | 8.0.0 | https://github.com/shagu/pfQuest |
| pfQuest [TurtleWoW DB] | — | https://github.com/shagu/pfQuest-turtle |
| pfExtend | 1.0.5 | **[my fork](https://github.com/roby-brok/pfExtend)** — original by [Cliencer](https://github.com/Cliencer/pfExtend) and TinyStick |
| FlightMap | 1.12-1 | *Dhask's FlightMap — installed manually* |

## Combat

| Addon | Version | Source |
|---|---|---|
| BigWigs | 2.0.0 | https://github.com/pepopo978/BigWigs |
| TWThreat | 1.2.3 | https://github.com/CosminPOP/TWThreat |
| ShaguDPS | 3.0.1 | https://github.com/shagu/ShaguDPS |
| Modified Power Auras | 1.5 | https://github.com/tdymel/ModifiedPowerAuras |
| DoiteAuras | 1.8.7 | https://github.com/Player-Doite/DoiteAuras |
| Mik's Scrolling Battle Text | 4.43 | *classic addon by Mik — installed manually* |
| Aegis: RallyPower | 0.15.0 | *by Subtilizer (Torchlite) — installed manually* |
| Aegis: Single Button Rotation | 0.15.5 | *by Mercaius & Subtilizer (Torchlite) — installed manually* |

## Macros & API

| Addon | Version | Source |
|---|---|---|
| SuperCleveRoidMacros | 2.4 | https://github.com/jrc13245/SuperCleveRoidMacros |
| SuperMacro (SuperWoW support) | 3.19 | https://github.com/jrc13245/SuperMacro-turtle-SuperWoW |
| SuperAPI | — | https://github.com/balakethelock/SuperAPI |
| Nampower Settings | — | https://github.com/Dusk-92/NampowerSettings |
| UnitXP SP3 Addon | — | https://github.com/whtmst/UnitXP_SP3_Addon |

## Items, bags & characters

| Addon | Version | Source |
|---|---|---|
| aux-addon | — | https://github.com/OldManAlpha/aux-addon |
| ItemRack | 1.98 | https://github.com/McPewPew/ItemRack |
| SortBags | — | https://github.com/shirsig/SortBags |
| BetterCharacterStats | 1.15.3 | https://github.com/pepopo978/BetterCharacterStats |
| StatCompare | 2.0.0 Beta | *by slashboy, updated by Provocateur@turtlewow — installed manually* |
| TurtleMail | 1.4.5 | https://github.com/sica42/TurtleMail |
| PizzaWorldBuffs | 2.0.0 | https://github.com/acid9000/PizzaWorldBuffs |

---

## Notes

**Entries marked *installed manually* have no source link on purpose.** I could not verify where
those copies came from, and pointing you at a repository I haven't confirmed is worse than saying
nothing. If you know the correct home for one of them, please open an issue.

**Most of these install through the OctoWoW launcher**, which keeps its own catalogue at
`https://octowow.st/api/addons.json`. That is the easiest route and it handles updates for you.

**The three forks** exist only to carry fixes I hit while playing. Each one's README explains what
was changed and why, and none of the changes are OctoWoW-specific. Use the original repositories
unless you specifically want those fixes — and if an upstream author wants a change, it's theirs to
take.

## Thanks

To everyone whose work is listed above, and in particular to **Shagu**, whose pfUI and pfQuest are
the backbone of this setup.
