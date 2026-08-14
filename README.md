# My OctoWoW Addon Setup

The addons and client mods I run on [OctoWoW](https://octowow.st) (WoW 1.12.1 client).

This repository is **a list, not a mirror.** No addon code is hosted here — every entry links to the
author's own repository, which is where you should download it from. All credit belongs to the
people who wrote these; I just use them and occasionally fix something.

Maintained by **Roby_Brok**.

> ### Two setups — which list is for you?
>
> This page is the **classic setup**: shipped data tables, only the client mods the
> launcher already provides, no extra steps. It keeps working and nothing here is going
> away.
>
> Since August 2026 my own install is the
> **[ClassicAPI setup](https://github.com/roby-brok/octowow-addons-classicAPI)** — rebuilt
> around [brues-code's ClassicAPI](https://github.com/brues-code/ClassicAPI) DLL, with the
> smoother event-driven pfUI. It asks one extra step of you: installing that DLL by hand,
> because **the Octo client does not ship it**. Happy to do that → start there. Want zero
> extra steps → stay here.

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
| pfUI | 9.0.8 | **[my fork](https://github.com/roby-brok/pfUI)** — original by [Shagu](https://github.com/shagu/pfUI), Turtle edition by me0wg4ming |
| pfUI [Addon Skinner] | 0.5 | **[my fork](https://github.com/roby-brok/pfUI-addonskinner)** of [jrc13245's](https://github.com/jrc13245/pfUI-addonskinner) — originals by [dein0s](https://gitlab.com/dein0s_wow_vanilla/pfUI-addonskinner) and [RoadBlock](https://github.com/Road-block/). Adds a skin for Mik's Scrolling Battle Text's options window |
| pfUI [Better Totems] | 1.0 | **[my fork](https://github.com/roby-brok/pfUI-bettertotems)** — original by [Bombg](https://github.com/Bombg/pfUI-bettertotems) |
| Modern Map Markers [Octo] | 2.4 | https://github.com/paokkerkir/ModernMapMarkers-octo — an OctoWoW fork of [tilare's original](https://github.com/tilare/ModernMapMarkers), adding Atlas map links and transport destinations |
| LevelRange [Turtle] | 2.2.0 | https://github.com/Spartelfant/LevelRange-Turtle |
| Atlas-TW (Atlas-CFM) | 1.60 | https://github.com/byCFM2/Atlas-TW |
| PizzaSlices | 1.5.2 | by Pizzahawaii — [mirror](https://github.com/roby-brok/octowow-addon-mirrors) |
| Turtle_General / Turtle_GroupUI | — | *bundled with the client* |

## Quests & world

| Addon | Version | Source |
|---|---|---|
| pfQuest | 8.0.1 | **[my fork](https://github.com/roby-brok/pfQuest)** — adds map icon scaling, a fix for the map detaching from the quest log, a repair for the [Translate] button (it never worked), hand-verified objective corrections, and `/db checkdb` — which tells delivery/talk-to quests (whose map pin is their turn-in marker) apart from real data gaps; built on [The Kludge Bureau's](https://github.com/The-Kludge-Bureau/pfQuest) continuation of [Shagu's original](https://github.com/shagu/pfQuest) |
| pfQuest [Octo DB] | 1.0.13 | **[my pack](https://github.com/roby-brok/pfQuest-octo)** — [The Kludge Bureau's](https://github.com/The-Kludge-Bureau/pfQuest-turtle) TurtleWoW database with [paokkerkir's](https://github.com/paokkerkir/pfQuest-octo) Octo pack folded in, so you do not have to pick one, plus a long run of corrections verified against the server's own database. Replaces both — do not install them alongside it. |
| pfExtend | 1.0.8 | **[my fork](https://github.com/roby-brok/pfExtend)** — original by [Cliencer](https://github.com/Cliencer/pfExtend) and TinyStick. ⚠️ While its QuestHelper browser is open it resets pfQuest's tracker and route on every refresh — close it when done |
| FlightMap | 1.12-1 | by Dhask — [mirror](https://github.com/roby-brok/octowow-addon-mirrors) |

## Combat

| Addon | Version | Source |
|---|---|---|
| BigWigs | 2.0.0 | https://github.com/pepopo978/BigWigs |
| OWThreat | 1.4.0 | **[my fork](https://github.com/roby-brok/OWThreat)** — original ([TWThreat](https://github.com/MarcelineVQ/TWThreat)) by Xerron/Er. Renamed, with ~15 bug fixes and the dead code stripped out. Speaks the same threat API, so it still works with raiders running stock TWThreat — but do not install both |
| ShaguDPS | 3.0.1 | https://github.com/shagu/ShaguDPS |
| Modified Power Auras | 1.5 | https://github.com/tdymel/ModifiedPowerAuras |
| DoiteAuras | 1.8.7 | https://github.com/Player-Doite/DoiteAuras |
| Mik's Scrolling Battle Text | v5.0-octo | **[my fork](https://github.com/roby-brok/MikScrollingBattleText)** — original by Mik, now rebased onto [brues-code's continuation](https://github.com/brues-code/Vanilla_MikScrollingBattleText) (the living branch of the family). My fixes ride on top: it no longer silently switches combat logging to disk on (269 MB found), the combat-log parser gets a literal-prefix reject, and the icon cache is honoured. None of it needs ClassicAPI. Keep the stock `MikScrollingBattleTextOptions` alongside it, unmodified |
| Aegis: RallyPower | 1.1.0 | https://github.com/Torchlite-bit/Aegis_RallyPower |
| Aegis: Single Button Rotation | 1.1.4 | https://github.com/Torchlite-bit/Aegis_SBR |

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
| StatCompare | 2.0.0 Beta | by slashboy, updated by Provocateur@turtlewow — [mirror](https://github.com/roby-brok/octowow-addon-mirrors) |
| OctoMail | 1.5.0 | **[my fork](https://github.com/roby-brok/OctoMail)** of [TurtleMail](https://github.com/sica42/TurtleMail) by [shirsig](https://github.com/shirsig) and [sica42](https://github.com/sica42) — fixes an autocomplete list and a mail log that both grew forever. Imports your TurtleMail data on first run |
| PizzaWorldBuffs | 2.0.0 | https://github.com/acid9000/PizzaWorldBuffs |

---

## Notes

**Entries marked *mirror* have no live upstream I could find.** Rather than leave people with no
way to get them, I re-uploaded those copies unmodified to
[octowow-addon-mirrors](https://github.com/roby-brok/octowow-addon-mirrors) — that repository makes
very clear they are not my work and lists each author. If you know the real home for one of them,
please open an issue and I will link it and delete the copy.

**Most of these install through the OctoWoW launcher**, which keeps its own catalogue at
`https://octowow.st/api/addons.json`. That is the easiest route and it handles updates for you.

**Installing from a GitHub ZIP:** the green *Code → Download ZIP* button unpacks as
`Name-main` or `Name-master`. The game (and pfUI's addon integrations) only recognize the
addon if the folder inside `Interface\AddOns` is named **exactly** the addon's own name
(`pfUI`, `OWThreat`, …) — rename it after unzipping, or use the launcher or `git clone`
instead.

**The forks** exist only to carry fixes I hit while playing. Each one's README explains what
was changed and why, and none of the changes are OctoWoW-specific. Use the original repositories
unless you specifically want those fixes — and if an upstream author wants a change, it's theirs to
take.

## Thanks

To everyone whose work is listed above, and in particular to **Shagu**, whose pfUI and pfQuest are
the backbone of this setup.
