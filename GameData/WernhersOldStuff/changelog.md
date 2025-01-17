# Changelog  
  
| modName    | Wernher's Old Stuff (WOS) by TiktaalikDreaming                    |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0+ARR                                                  |
| author     | TiktaalikDreaming and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207233-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/WernhersOldStuff)       |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/WernhersOldStuff)     |
| spacedock  | (https://spacedock.info/mod/42)                                   |
| ckan       | WernhersOldStuff                                                  |

## Version 1.9.99.5-prerelease `<Sixth First Steps>` edition

* Released
  * 08 Jun 2023
  * for Kerbal Space Program KSP 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * This release is in a series of updates to this addon. Each update will update some of the parts and  patches so that this addon can be updated in a more manageable manner instead of one massive update.
  * Now can search `wos`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `A9`, `A10`, `A11`, `A12` in editors
  * ghostparts.cfg has been updated and temporarily added to compensate for parts that were renamed

### Change Summary 1.9.99.5

* 49/47 parts included
  * two parts split out into own files
  * 2 Custom IVA's
  * 16 Custom props
  * 12 Custom FX
  * Agency
  * 2 Custom flags
  * parts are fully localized (English) included actions
  * Phase I,II,III passes completed
    * parts pass started (see 1.9.99.0 for more details)
    * DRAG_CUBES, cargo, and node pass yet to complete
* .craft
  * A4 (experimental)

### Changes 1.9.99.5

#### Parts 1.9.99.5

* Parts included in this update (final parts)
  * Aggregat3n5
    * wos-A3-tank
    * wos-A3-wing
    * wos-A5-gyro-nose
    * wos-A5-wing
    * wos-A3-base
    * wos-A3-eng
    * wos-A3-gyro-nose
  * Aggregat4
    * wos-A4-gyro
    * wos-A4-nose
    * wos-A4-tank
    * wos-A4-wing-a
    * wos-A4-wing-fin
    * wos-A4-eng
* Update
  * all parts to include [oldName = ] for ghostparts v2
  * localized
  * linted
  * organized
  * reformat
* Remove extraneous quotes
  * [toggleText = "#autoLOC_236032"]
  * [enableText = "#autoLOC_236028"]
  * [disableText = "#autoLOC_236030"]
* closes #31 - Rename
* closes #57 - [Bug] Part costs
* closes #67 - [BUG] part cost

### Asset 1.9.99.5

* upscale (512x320) and convert flags
* update model texture pointers from .mbm/tga/png to .dds
* closes #32 - Assets move and organization 🎨 📁
* closes #69 - [BUG] Model load err
* updates #68 - [BUG] Texture 'WernhersOldStuff/Props/VintageDials/BlankBMP' not found!

### Localization 1.9.99.5

* Add
  * [readme-ru.md] v1.0.1.0
  * [quickstart-ru.md] v1.0.0.0
  * translations by: (Spasibo) [evanisrael](https://github.com/evanisrael)
* Update
  * [en-us.cfg] v1.0.5.0
    * add
      * action strings
      * final missing part strings added
    * linting
    * organizing
    * standardizing strings
* closes #13 - English <us-en.cfg>
* closes #30 - Part Localization
* updates #12 - Localization - Master

### docs/

* Update
  * [changelog.md]
  * [readme]
  * Hero.png
  * move thumbs to docs
  * release notes
  * /docs/
    * [`_config.yml`] v1.0.3.0
    * [404.md] v1.0.3.2
    * [Attribution.md] v1.0.5.0
    * [Flags.md] v1.0.0.0
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.0.5.0
    * [ManualInstallation.md] v1.1.8.0
    * [Marketing.md] v1.0.1.2
    * [Notices.md] v1.0.2.0
    * [PartsCatalog.md] v1.0.5.0
    * [Why.md] v1.0.5.0
* closes #36 - Add part thumbs

### Configs 1.9.99.5

* Update
  * <WernhersOldStuff.cfg> v1.0.5.0
    * add missing tags catch
  * <GhostParts.cfg> v1.0.5.0
    * update to v2.0.2.0 template
    * easily can be adjusted to allow old parts to show in editor
    * or can also be adjusted to just use old part names and hide new (if needed)

### Status 1.9.99.5

* Issues
  * closes #65 - Wernher's Old Stuff (WOS) 1.9.99.5-prerelease `<Sixth First Steps>` edition
  * closes #66 - 1.9.99.5 Additional Tasks
  * closes #64 - Duplicate
  * updates #51 - Agency Description

---

## Version 1.9.99.4-prerelease `<Fifth First Steps>` edition

* Released
  * on: 17 Feb 2023
  * for: Kerbal Space Program KSP 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

This release is in a series of updates to this addon. Each update will update some of the parts and patches so that this addon can be updated in a more manageable manner instead of one massive update.

### Summary 1.9.99.4

* This is next in a series of updates with each (pre)release updating some of the forty-eight (47+1) parts and patches so this addon can be updated in a more manageable way.
* Found another part hiding in another part's house
* All parts have been localized
  * some part tags need to be added yet and using placeholders
* This update pass (47+1 parts total)
  * seven (7) parts updated
  * reduced release size by 2.1mb (culmative 8.8mb less png-dds conversion)
  * twelve (12) parts left to update
* Now can search `wos`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `A9`, `A10`, `A11`, `A12` in editors
* ghostparts.cfg has been updated and temporarily added to compensate for parts that were renamed
* parts updated this release include:
  * A1-gyro
  * A1-tank
  * A2-base
  * A2-base-guide (split out into own part.cfg)
  * A2-engine
  * A2-tank-nitrogen
  * A2-tank-oxygen
* split out RealFuels.cfg v1.0.0.0

### Localization 1.9.99.4

* Update
  * [en-us.cfg] v1.0.1.0
    * linting
    * organizing
    * standardizing strings
* updates #12 - Localization - Master
* updates #13 - English <us-en.cfg>
* updates #30 - Part Localization

### Asset 1.9.99.4

* converted .png to .dds
  * props
    * png --> bc3 dds
    * 25.9mb --> 13.9mb
* Eliminated duplicates
  * A-2_NRM.dds 342kb
  * A-2.dds 342kb
  * 684kb total

### Configs 1.9.99.4

* Update
  * <WernhersOldStuff.cfg> v1.9.99.4
    * add series specific tags
  * <GhostParts.cfg> v1.9.99.4

### Compatibility 1.9.99.4

* Add
  * RealFuels.cfg v1.0.0.0
    * pull from part configs

### Parts 1.9.99.4

* Updated
  * localized
  * linted
  * organized
  Parts included in this update
    * A1-gyro
    * A1-tank
    * A2-base
    * A2-base-guide (split out into own part.cfg)
    * A2-engine
    * A2-tank-nitrogen
    * A2-tank-oxygen
* updates #57 - [Bug] Part costs

### Status 1.9.99.4

* Issues
  * closes #61 - Wernher's Old Stuff (WOS) 1.9.99.4-prerelease `<Fifth First Steps>` edition
  * closes #62 - 1.9.99.4 Additional Tasks
  * updates #32 - Assets move and organization 🎨 📁
  * updates #31 - Rename
  * updates #36 - Add part thumbs
  * updates #57 - [Bug] Part costs

---

## Version 1.9.99.3-prerelease `<Fourth First Steps>` edition

* Released
  * on: 11 Dec 2022
  * for: Kerbal Space Program KSP 1.12.4
  * by: zer0Kerbal

### Summary 1.9.99.3

* This is next in a series of updates with each (pre)release updating some of the forty-seven (47) parts and patches so this addon can be updated in a more manageable way.
* All parts have been localized, some part tags need to be added yet, placeholders are in place
* This update pass (47 parts total)
  * seven (7) parts updated
  * reduced release size by 1.44mb (culmative 3.3mb less png-dds conversion)
  * eighteen (18) parts left to update
* Now can search `wos`, `A2`, `A3`, `A4`, `A5`, `A6`, `A9`, `A10`, `A11`, `A12` in editors
* ghostparts.cfg has been updated and temporarily addedto compensate for parts that were renamed
* parts updated this release include:
  * A6 engine shroud
  * A6 winglet
  * A10 shell
  * A10 wing
  * A11 shell
  * A11 wing
  * A12 shell
  * A9 cockpit nose
    * add weak reaction wheel (request)

### Localization 1.9.99.3

* Update
  * [en-us.cfg] v1.0.1.0
    * linting
    * organizing
* updates #12 - Localization - Master
* updates #13 - English <us-en.cfg>
* updates #30 - Part Localization

### Asset 1.9.99.3

* converted .png to .dds
* Eliminated duplicates
  * 2x <blotchydark.dds> 22kb {44kb}
  * 3x <RedstoneA6-NAA75-110Turbine.dds> 1.33mb {3.99mb}
  * 3x <GreenContrlFin.dds> 22kb {66kb}
* Rename
  * Parts
    * Wing4Redstone --> wos-A6-winglet
    * Wing4A10 --> wos-A10-wing
    * Wing4A11 --> wos-A11-wing
    * RedstoneEngineShroud --> wos-A6-engine-shroud
    * A10_Shell --> wos-A10-shell
    * A11_Shell --> wos-A11-shell
    * A12_Shell --> wos-A12-shell
  * Part config
    * <A6wing.cfg> --> <wos-A6-winglet.cfg>
    * <A10wing.cfg> --> <wos-A10-wing.cfg>
    * <A11wing.cfg> --> <wos-A11-wing.cfg>
    * <RedstoneEngineShroud.cfg> --> <wos-A6-engine-shroud.cfg>
    * <Cover.cfg> --> <wos-A10-shell.cfg>
    * <A11_Shell.cfg> --> <wos-A11-shell.cfg>
    * <Cover.cfg> --> <wos-A12-shell.cfg>
  * Models
    * <NewModel.mu> --> <A6-winglet.mu>
    * <NewModel.mu> --> <A10-wing.mu>
    * <NewModel.mu> --> <A11-wing.mu>
    * <NewModel.mu> --> <A6-engine-shroud.mu>
    * <NewModel.mu> --> <A10-shell.mu>
    * <NewModel.mu> --> <A11-shell.mu>
    * <NewModel.mu> --> <A12-shell.mu>

### Configs 1.9.99.3

* Update
  * <WernhersOldStuff.cfg> v1.1.0.0
    * add series specific tags
  * <VariantThemes.cfg> v1.0.1.0
    * finish localizing

### Compatibility 1.9.99.3

* Add
  * <RealSolarSystem.cfg> v1.0.0.0
    * pull from part configs

### Parts 1.9.99.3

* Updated
  * localized
  * linted
  * organized
  * correct cost of A12-tank-dual
  * Add
    * weak reaction wheel to A9 cockpit (request)
    * thank you to [claustro](https://forum.kerbalspaceprogram.com/index.php?/profile/193094-*/) for the suggestion
  * Rename
    * Parts
      * Wing4Redstone --> wos-A6-winglet
      * Wing4A10 --> wos-A10-wing
      * Wing4A11 --> wos-A11-wing
      * RedstoneEngineShroud --> wos-A6-engine-shroud
      * A10_Shell --> wos-A10-shell
      * A11_Shell --> wos-A11-shell
      * A12_Shell --> wos-A12-shell
    * Part config
      * <A6wing.cfg> --> <wos-A6-winglet.cfg>
      * <A10wing.cfg> --> <wos-A10-wing.cfg>
      * <A11wing.cfg> --> <wos-A11-wing.cfg>
      * <RedstoneEngineShroud.cfg> --> <wos-A6-engine-shroud.cfg>
      * <Cover.cfg> --> <wos-A10-shell.cfg>
      * <A11_Shell.cfg> --> <wos-A11-shell.cfg>
      * <Cover.cfg> --> <wos-A12-shell.cfg>
* closes #58 - [BUG] wos-A12-tank-dual: part cost (13000.0) is less than the cost of its resources (190391.1)
* closes #52 - [Request]: add reaction wheels to command noses (weak to match period)
* updates #57 - [Bug] Part costs

### Status 1.9.99.3

* Issues
  * closes #55 - Wernher's Old Stuff (WOS) 1.9.99.3-prerelease `<Fourth First Steps>` edition
  * closes #56 - 1.9.99.3 Additional Tasks
  * updates #32 - Assets move and organization 🎨 📁
  * updates #31 - Rename
  * updates #36 - Add part thumbs

---

## Version 1.9.99.2-prerelease `<Third First Steps>` edition

* Released
  * on: 02 Nov 2022
  * for: Kerbal Space Program KSP 1.12.4
  * by: zer0Kerbal

### Summary 1.9.99.2

This is next in a series of updates to this addon.
Each (pre)release will update some of the parts and patches so this addon can be updated in a more manageable way.
All parts have been localized, some part tags need to be added yet, placeholders are in place
Now can search `wos` in editors to find all Wernher's Old Stuff parts
Initial update pass completed on twenty-two parts; with twenty-five (25) parts left to update (47 parts total)
ghostparts.cfg has been updated and temporarily added to this addon to compensate for parts that were renamed.

This Release has been reduced by 1.0mb  (cumulatively 1.86mb) by removing duplicate files and texture conversions.

### Localization 1.9.99.2

* localize parts
* Create
  * Agency
  * Localization/
    * [en-us.cfg]
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Add
  * <WernhersOldStuff.cfg> v1.0.0.0
    * adds localized tags to parts
* closes #13 - English <us-en.cfg>
* closes #30 - Part Localization
* updates #12 - Localization - Master

### Spaces 1.9.99.2

* Updated
  * wos-iva-A9
  * wos-iva-A9-rpm
  * Prop-Seat-A9
  * Aggregat4Extras\internal.cfg
  * Aggregat4Extras\internal-rpm.cfg
  * Aggregat4Extras\Prop_Seat_A9.cfg

### Configs 1.9.99.2

* <VariantThemes.cfg> v1.0.0.0
* closes #44 - [BUG] Unable to find theme

### Parts 1.9.99.2

* Updated
  * <A9Cockpit.cfg> --> <wos-A9-cockpit-nose.cfg>
  * <Skids.cfg> --> <wos-aggregate-skid.cfg>
  * <A9Wing.cfg> --> <wos-A9-wing.cfg>
  * <A6Ramjet.cfg> --> <wos-A6-Ramjet-two.cfg>
  * <A-6wing.cfg> --> <wos-A6-wing.cfg>
  * <A-4bWing.cfg> --> <wos-A4-wing-b.cfg>

### Status 1.9.99.2

* Issues
  * updates #32 - Assets move and organization 🎨 📁
  * updates #31 - Rename
  * closes #47 - Wernher's Old Stuff (WOS) 1.9.99.2-prerelease `<Third First Steps>`
  * closes #48 - 1.9.99.2 Verify Legal Mumbo Jumbo
  * closes #49 - 1.9.99.2 Update Documentation
  * closes #50 - 1.9.99.2 Update Social Media
  * updates -  #36 - Add part thumbs

---

## Version 1.9.99.1-prerelease `<2nd First Steps>` edition

* 12 Aug 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary 1.9.99.1

This is next in a series of updates to this addon.
Each (pre)release will update some of the parts and patches so this addon can be updated in a more manageable way.

ghostparts.cfg has been updated and temporarily added to this addon to compensate for parts that were renamed.

This Release has been reduced by 1.0mb  (cumulatively 1.86mb) by removing duplicate files and texture conversions.

### Parts 1.9.99.1

* NEW
  * <wos-A9-wing.cfg> v1.0.0.0
    * EXPERIMENTAL
    * was only missing part.cfg
    * textures and model files for the wing part already present in the addon.
    * NEEDS updating
* Update
  * File and Part names
    * replace `WernhersOldStuff/p` with `WernhersOldStuff/P` 146 times in 30 files
    * <Wing4A12.cfg> --> <wos-A12-wing.cfg> v1.0.0.0
      * Wing4A12 --> wos-A12-wing
    * <part.cfg> --> <wos-decoupler-A12toA10.cfg> v1.0.0.0
      * A12toA10Decoupler --> wos-decoupler-A12toA10
    * <part.cfg> --> <wos-redstone-tank.cfg> v1.0.0.0
      * RedstoneFuelTank --> wos-redstone-tank
    * <part.cfg> --> <wos-A11-tank.cfg> v1.0.0.0
      * A-11FuelTank --> wos-A11-tank
    * <EngineA-6.cfg> --> <wos-A6-engine.cfg> v1.0.0.0
      * a6arocketengine --> wos-A6-engine
    * <wos-A10-engine-nv.cfg> --> <Aggregat10\EngineA-10NV.cfg> v1.0.0.0
      * a10rocketengineNV  --> wos-A10-engine-nv
    * <wos-A10-engine.cfg> --> <Aggregat10\EngineA-10.cfg> v1.0.0.0
      * a10rocketengine --> wos-A10-engine
  * Categories
  * [breakingForce] was 3400 is now 200/400
  * [breakingTorque] was 3400 is now 200/400
  * [ModuleDecouple]
    * remove "" hitch-hikers
    * [fxGroupName] = "decouple"
* Add
  * [DRAG_CUBE]
  * @thumbs/
* updates #31 - Rename
* updates #36 - Add part thumbs
* closes #43 - fix `WernhersOldStuff/p`

### Assets 1.9.99.1

* Move and Organization 🎨 📁
  * change mesh = to MODEL
  * relocate models and textures to /Assets/
    * internal pointers
    * naming
      * <NewModel.mu> --> <A12-wing.mu>
      * <NewModel.mu> --> <A9-wing.mu>
      * <NewModel.mu> --> <A12toA10Decoupler.mu>
      * <NewModel.mu> --> <redstone-tank.mu>
      * <NewModel.mu> --> <A11-tank.mu>
      * <NewModel.mu> --> <A6-engine.mu>
* Convert textures
  * .tga/.mbm --> .png
    * <Aggregat10\A10EngDiff.tga> --> <Aggregat10\A10EngDiff.png>
      * 12mb --> 4.33mb
    * <Aggregat10\A10EngSPEC.tga> --> <Aggregat10\A10EngSPEC.png>
      * 12mb --> 4.33mb
* Remove duplicate textures
  * [A4EngFrame.dds]
    * removed duplicate (21.4kb)
  * [GreenContrlFin.dds]
    * removed duplicate (21.4kb)
    * removed duplicate (21.4kb)
  * [RedstoneA6-NAA75-110Turbine.dds]
    * removed duplicate (1.33mb)
  * [RedstoneA6-NAA75-110Frame.dds]
    * removed duplicate (1.33mb)
  * [RedstoneA6-NAA75-110Nozzle.dds]
    * removed duplicate (1.33mb)
  * [RedstoneA6-NAA75-110SteamExhaust.dds]
    * removed duplicate (1.33mb)
* updates #32 - Assets move and organization 🎨 📁

### Configs 1.9.99.1

* <WernhersOldStuff.cfg> v1.0.0.0
  * updates parts with localization strings

### Status 1.9.99.1

* Issues
  * closes #39 - Wernher's Old Stuff (WOS) 1.9.99.1-prerelease `<2nd First Steps>`
  * closes #40 - 1.9.99.1 Verify Legal Mumbo Jumbo
  * closes #41 - 1.9.99.1 Update Documentation
  * closes #42 - 1.9.99.1 Update Social Media

---

## Version 1.9.99.0-adoption `<First Steps>` edition

* 19 Jul 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary 1.9.99.0

This is the first in a series of updates to this addon.
Each (pre)release will update some of the parts and patches so this addon can be updated in a more manageable way.

ghostparts.cfg has been temporarily added to this addon to compensate for parts that were renamed.

This Release has been reduced by 0.86mb by removing duplicate files.

### Parts 1.9.99.0

* Update
  * File and Part names
    * [A4parachute.cfg] -> [wos-parachute-A4.cfg] v1.0.0.0
    * [AgSrfparachute.cfg] -> [wos-parachute-srf.cfg]v1.0.0.0
    * [A10toA4Decoupler.cfg] -> [wos-decoupler-A10toA4.cfg] v1.0.0.0
    * [A10toA6Decoupler.cfg] -> [wos-decoupler-A10toA6.cfg] v1.0.0.0
    * [A11toA10Decoupler.cfg] -> [wos-decoupler-A11toA10.cfg] v1.0.0.0
    * [A10-FuelTanks.cfg] -> [wos-A10-tank-dual] v1.0.0.0
    * [A-10StarterTank] -> [wos-A10-tank-starter] v1.0.0.0
    * [A-12FuelTank.cfg] -> [wos-A12-tank-dual.cfg] v1.0.0.0
  * Categories
* Add
  * [DRAG_CUBE]
  * @thumbs/
* updates #31 - Rename
* updates #36 - Add part thumbs

### Assets 1.9.99.0

* Move and Organization 🎨 📁
  * change mesh = to MODEL
  * relocate models and textures to /Assets/
    * internal pointers
    * naming
* Remove duplicate textures
  * [MonoEngineNozzle.dds]
    * removed duplicate (341kb)
  * [RedstoneA6-NAA75-110Turbine.dds]
    * removed duplicate (1.33mb)
    * removed duplicate (1.33mb)
  * [A-4Chute.dds]
    * removed duplicate (1.33mb)
  * [A-10EngineVaneFrame.dds]
    * removed duplicate (1.33mb)
* FX
  * Removed duplicates
    * [Circular.tga] (7.6kb)
    * [particles.tga] (11.5kb)
* Category Icons
  * move to SimpleIcons/
* updates #32 - Assets move and organization 🎨 📁

### Configs 1.9.99.0

* Create
  * Resources/[ResourcesGeneric.cfg] v1.0.0.0
* Move
  * [bulkheads.cfg] v1.0.0.0 to Configs/

### Compatibility 1.9.99.0

* Create
  * [AdvancedJetEngine.cfg] v1.0.0.0
* Rename
  * [RealismOverhaulWernhers.cfg] to [RealismOverhaul.cfg]
  * move to Compatiblity/
* [RealismOverhaul.cfg] v1.1.0.0
  * Split
    * to Resources/[ResourcesGeneric.cfg]
    * to Compatibility/[AdvancedJetEngine.cfg]
  * Add
    * FOR[WernhersOldStuff]
  * Update
    * @PART[Wing4A10]:NEEDS[RealismOverhaul]
      * missing {}
      * !MODULE[ModuleRCS] {}

* @PART[a2rocketengine]:NEEDS[RealSolarSystem&!RealFuels]
  * @MODULE[ModuleEngines]
    * missing closing brace `}`

### Props 1.9.99.0

* [CamScreen.cfg] WOS_Cam
  * missing closing brace `}`

### Agents 1.9.99.0

* add description to [WernhersOldStuff.agent]

### Flags 1.9.99.0

* relocate flags from Agencies/ to Flags/
* resize
  * from 256x160
  * to 512x320

### docs/ 1.9.99.0

* Add
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
  * [404.md] v1.0.3.1
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [Part-Catalog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]
* closes #34 - docs/

### Localization 1.9.99.0

* Create
  * Localization/
    * [en-us.cfg]
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #12 - Localization Master
* updates #13 - Localization - English [en-us.cfg]
* updates #30 - Part Localization

### Documentation 1.9.99.0

* Update
  * [Readme.md]
* [WernherOldStuff.version]
  * remove
    * [KSP_VERSION_MAX]

### Status 1.9.99.0

* Issues
  * closes #8 - Wernher's Old Stuff (WOS) 1.9.99.0-adoption `<First Steps>` edition
  * closes #9 - 1.9.99.0 Verify Legal Mumbo Jumbo
  * closes #10 - 1.9.99.0 Update Documentation
  * closes #11 - 1.9.99.0 Social Media

---

## Version 0.19.210115 for Kerbal Space Program 1.11.0

Released on 2021-01-14

Starhelperdude helpfully noticed the releases were a bit odd, turns out I'd forgotten to release any of the updates I'd been working on. This I think is the complete revamp of all the Aggregate-4 oddities. So the wings, the ramjet and the self-cremation-unit (aka cockpit). I blame the cockpit. I got bogged down doing the IVA. New optional dependency of RPM core for nice happy looking cockpit.

[ Download (54.41 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.210115)

---

## Version 0.19.2 for Kerbal Space Program 1.10.0

Released on 2020-02-20

Cleaned up the rather randomized pricing.

[ Download (44.52 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.2)

---

## Version 0.19.1 for Kerbal Space Program 1.8.1

Released on 2018-10-23

Removed old model files that interfered with the surface parachute. Untested because I noticed just before going to work and fixed it while on the bus. Not even sure if I changed the zip file to be honest.

[ Download (34.08 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.1)

---

## Version 0.19 for Kerbal Space Program 1.5.1

Released on 2018-10-22

Finally got around to fixing the RCS on the A-10 wing. Which is a feature I'm not even sure was planned, but seemed suggested by some of the diagrams. Tested in 1.5.1, should work fine in 1.4+ A-11 and A-12 still somewhat dependent on KJR, esp the 12. But, the "stock effect" of it having spontaneous unplanned disassembly on the launch pad probably isn't too far from what would really happen. Plus major part revamps, now includes A2-A5

[ Download (35.19 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19)

---

## Version 0.16b for Kerbal Space Program 1.3.1

Released on 2017-06-21

Switching from bzip2 to deflate method for zip file

[ Download (36.49 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.16b)

---

## Version 0.16 for Kerbal Space Program 1.3.0

Released on 2017-06-04

Made all the main parts as start (some were erroneously in weird tech nodes). Fixed a few descriptions and titles. Moved decouplers to coupling category (only one major version late).

[ Download (30.52 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.16)

---

## Version 0.15b for Kerbal Space Program 1.3.0

Released on 2017-05-29

Zip method now zip

[ Download (34.55 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.15b)

---

## Version 0.15 for Kerbal Space Program 1.3.0

Released on 2017-05-28

Updated config for manufacturer for 1.3

[ Download (24.18 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.15)

---

## Version 0.14 for Kerbal Space Program 1.2.2

Released on 2016-09-10

Major update for Realism Overhaul config. Rework of the A-12 fuel tank to add volume so it can take enough fuel to enable the multistage A-12 to get something into orbit. I split the A-10 engine into the standard and a variant without vectoring vanes. With the A-12's 50 A-10 engines, there's just no need for all the engines to gimbal. Feel free to mix and match or just ignore the new engine. I'm still working on the ramjet, it's not really working properly just yet. It should basically function if you're running RO without AJE. But I need more time tweaking the AJE config.

[ Download (34.84 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.14)

---

## Version 0.13 for Kerbal Space Program 1.1.3

Released on 2016-09-01

Added the fins for the A-11 and A-12 plus decouplers suited to the various stages.
A bit more work on the meshes for the various bits and pieces.
Added A-4b style fins for the A-4.
Added A-6 ramjet.
Fixed up A-4 nose chute, and re-used the chute to make a surface attachable chute for stage recovery.

[ Download (26.40 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.13)

---

## Version 0.12 for Kerbal Space Program 1.1.3

Released on 2016-08-18

Added A-11 and A-12 stages. There's no fins yet for them.
Removed ability to surface attach to the A-10 engine, that was just there for before I'd built the A-10 fins, for testing. But I've added surface attach to the A-10 and A-4 fins.

None of the new parts have Real-Fuel or RSS config, so basically this update is stock only.

[ Download (24.31 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.12)

---

## Version 0.11 for Kerbal Space Program 1.1.3

Released on 2016-05-28

Added in the A-10 and some A-4 variants (A-4b, A-6, A-9) including the manned A-4/9 cockpit.
Resized the non-RSS versions to 64% rather than 50% on advice from NathanKell.
Significantly fixed up most of the centres, mass, lift, and drag.

[ Download (22.71 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.11)

---

## Version 0.10 for Kerbal Space Program 1.1.2

Released on 2016-05-15

Added first stage of the Redstone A-6 NAA-75-110 as four parts. Fuel tank; should be self explanatory Engine; again, fairly obvious Engine Shroud; This connects over the engine. I kept this independent of the engine as with it, the engine is basically a cylinder, which is boring as. Fins; There's four of these on a historical Redstone rocket, and stack nodes let you attach four easily enough. The fins are also surface attachable, for any other fin needs you might have. They include the visual mesh for the control vanes that are more correctly part of the engine, but on the actual A-6 and A-7s was part of the fin mechanism. There's no animation for the vanes, but once the engine's running, you can't really see them anyway. BUT, the engine's thrust is actually split into 8, 4 of which correspond to a control vane and are "gimballed". The other four are central. This way, some (half) of the thrust is gimballed and the other half isn't. And, by gimballing four points radially around the centre, gimballing can actually rotate, something normal gimballed engines can't do. On the other hand, they stuck carbon vanes into the exhaust to achieve this, so it comes at the cost of less thrust, and fairly silly gimballing. At some stage, I'll convert the A-4 to use this system of multi-gimbal, multi-thrust as well.

[ Download (16.56 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.10)

---

## Version 0.9 for Kerbal Space Program 1.1.2

Released on 2016-05-14

Fixed fuel oxidizer ratios. Added extra colour schemes for those with firespitter core.

[ Download (10.69 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.9)

---

## Version 0.8 for Kerbal Space Program 1.1.2

Released on 2016-02-20

Updated and fixed the A-10 engine, specifically because I noticed it was overwriting A-4 engine details if community resource pack was installed, but RealFuels wasn't. Engine is also my updated mesh and so on. Also, logo for EMW changed to proto VonBraun logo interruptus

[ Download (13.04 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.8)

---

## Version 0.7 for Kerbal Space Program 1.0.5

* Released on 2016-02-17

* *No changelog provided*

---
