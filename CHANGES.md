
# Progression: Apparel & Armour (Title TBC)
It always bother me when I install mods like Medieval Overhaul or one of the old-timey Vanilla Factions Expanded that all of the medieval clothing appears in the same research projects as more modern clothing. This mod aims to correct that.

On its own, this mod doesn’t do a whole lot - it creates a new research project to unlock the hand tailor bench. It is intended that this mod be used with other mods that add medieval apparel and armour to the game.

* Added new research: Rustic clothing (400)
    * Rustic clothing > Complex clothing
* Moved hand tailoring bench to Rustic clothing research
* Moved the following to Rustic clothing:
    * Robe
    * Hood
    * Cape (if Royalty or Biotech installed)
* Flak armor requires Machining and Complex clothing - Modern combat armour doesn't have much in common with medieval plate armour
* Plate armor requires Rustic clothing and Smithing
* Steel simple helmet now requires Complex clothing

# Integrations
## Royalty
* Modified research chains:
    * Rustic clothing > Noble apparel > Royal apparel
* Beret, Corset, Formal shirt, Formal vest, Ladies hat, and Top hat require Complex clothing + Noble apparel
* Royal apparel only requires Nobel apparel research
* Crown and Cornet also require Smithing

## Ideology
* Moved the following to Rustic clothing:
    * Flophat
    * Headwrap
    * Broadwrap
    * Slicecap
    * Tailcap
    * Visage mask
    * Burka
    * Slave Body Strap
* Added the following to Complex clothing:
    * Authority cap
* Shadecone and Slave collar added to Crafting spot for Tribal crafting

## Biotech
* Moved the following to Rustic clothing:
    * Kid romper
    * Sash

## Anomaly
TBA

## Odyssey
TBA

## Medieval Overhaul
* Fixed random name capitalisations for recipes
* Rustic clothing renamed to Rustic tailoring, added to Medieval tab in place of Tailoring
* Renamed Tailoring to Complex tailoring and moved back to Main tab
* Moved most apparel items to Rustic tailoring research:
    * Arming cap
    * Braies
    * Coif
    * Full arming cap
    * Gambeson
    * Hood
    * Padded surcoat
    * Quiver
    * Red bandana
    * Trousers
    * Vest
* New research Rugs:
    * Textile spinning > Rugs, Silk
    * Moved cloth and leather rugs to Rugs research
    * TODO: Will likely make leather and hide rugs neolithic tech for tribals to craft
    * Royal rugs moved to Royal architecture research and requires Rugs research
    * Silk rugs moved to Silk research and requires Rugs research
* Protective clothing now requires Rustic tailoring as a prerequisite
### Fixes
* Fixed assorted naming capitalisations and consistencies
### Stat Rebalances
Clothes and armour costs and stats are pretty out of whack with the vanilla game. I aim to make these more aligned to vanilla values to provide a proper sense of progression.

Generally, fewer clothes count for nudity - hats, helmets, gloves, boots, etc no longer count as clothing.

Clothing and armour has been balanced to align more closely with vanilla stats.

Armour and headgear has been balanced using Plate armor from vanilla and various medieval armors from the Vanilla Expanded mods.

Protective clothing provides additional warmth and is fast and cheap to make, but does not provide much in the way of protection. The kettle helm is more range-focussed, while the flat-top and nasal helms are melee focused.

Chain armour is lighter and more maneauverable than plate armour, but provides slightly less protection and takes a long time to craft. 

The Hauberk makes up the base for the armour on the middle layer as follows:
    * Light Plate Armour has been nerfed, now provides 0.85 armour multiplier and -0.4 movespeed.
    * Hauberk + Heavy Hauberk < VE Light Plate Armour
    * Hauberk + Breast Plate ~= VE Light Plate Armour, provides slightly more armour but is slightly less maneauverable
    * Hauberk + Brigandine ~= Plate Armour
    * Hauberk + Full Plate ~= VE Heavy Plate Armour

Plate armours have been rebalanced, but the various helmets are mostly equivalent and are there to provide flavour to your armies.

Adorned gear takes slightly longer to make and has a small social impact buff, as well as the existing cold resistance.
Gilded gear takes longer to make, but has a greater social impact buff.

Lindwurm armour is rare and quite difficult to make, however it is very protective, insulating and light. It offers the protection of full plate armour, but the weight and maneuverability of light plate armor.

Shields have been balanced and now require more research. Round shield is unlocked with Protective clothing, Heater shield with Chain armour, and Kite shield with Plate armor.

## Medieval Overhaul + Biotech
* Nerfed MO Quiver so that Biotech’s Heavy bandolier is a direct upgrade
    * TODO: Change to layer torso without destroying textures and equip sets
    * Covers: Torso
    * Ranged Cooldown Multiplier: -5% (also modified to use Vanilla system instead of VE)
    * Provides no armor or insulation

## TODO: Medieval Overhaul + Royalty
* Added Noble apparel requirement to the following:
    * Zweihander's hat
    * Zweihander's helm
    * Zweihander's cuirass
    * Zweihander's cuirass (puffy)
* Added Royal apparel requirement to the following:
    * Gilded full plate
    * Gilded arnet

## Vanilla Factions Expanded - Medieval 2
* Added new research: Leather armor (500)
    * Rustic clothing > Leather armor
    * New research appears in Vanilla Expanded tab
    * TODO: Maybe Heavy leather armor should also require smithing research?
* Moved the following to Rustic clothing
    * Padded helmet
    * Padded armor
    * Cap
    * Mantle
    * Jester hat
    * Jester outfit
    * Dame hat
    * Dame dress
    * King’s crown
    * King’s robe
    * Plague mask
    * Chaperon
* Round shield and Heater shield stay in Smithing and Plate armor respectively

## Vanilla Factions Expanded - Medieval 2 + Royalty
* Moved the following to Noble Apparel:
    * Jester hat
    * Jester outfit
    * Dame dress
    * Dame hat
* Moved the following to Royal apparel
    * King’s robes
    * King’s crown

## TODO: Vanilla Factions Expanded - Medieval 2 + Medieval Overhaul
* Integrated research chain
    * Rustic clothing > Protective clothing > Leather armor, Chainmail armor
    * VE Leather Armor is less protective than Hauberk but has no speed malus and requires Leather armor research
    * VE Heavy leather armor is less protective than Breast plate but has smaller speed penalty and requires Leather armor research
* Renamed VE Padded armor to Light padded armor to avoid overlap, added crafting level requirement
* Renamed VE Padded helmet to Light padded helmet, increased work amount required, reduced crafting level requirement
* Rebalanced Leather armor and helmet
* Rebalanced Heavy leather armor and helmet
* Increased level requirement for Heavy Plate Armor and Helmet to 10
* TODO: Shields
* TODO: Figure out Cap MO overlap

## TODO: Vanilla Apparel Expanded
* Moved the following to Rustic clothing:
    * Tunic
    * Blouse
    * Apron
    * Cape (Removed from 1.6?)
    * Trapper hat (Removed from 1.6?)
    * Summer hat (Removed from 1.6?)
    * Gloves
* Changed tech level of the following:
    * Boots: Medieval > Industrial (OP stats for medieval tech level)
    * Shoes: Medieval > Industrial (OP stats for medieval tech level)
* TODO: Nerfs
    * Apron is OP for tech level and materials required

## TODO: Vanilla Apparel Expanded + Royalty
* Rename Royalty cape to Shoulder cape to differentiate from VE Cape

## TODO: Vanilla Apparel Expanded + Biotech
* Rename Biotech cape to Shoulder cape to differentiate from VE Cape

## TODO: Vanilla Apparel Expanded + Anomaly
* Combine effects of VE and Anomaly Lab coat and nerf slightly to compensate

## TODO: Vanilla Apparel Expanded + Medieval Overhaul
* Renamed VE Gloves to Mittens to differentiate from MO Gloves
* Rename MO Boots to Jackboots to differentiate from VE Boots. Also slightly increase material cost
* Rename VE Trousers to Suit trousers to distinguish from MO Trousers

## TODO: Vanilla Armour Expanded
* Leather tanning research now required Rustic clothing prerequisite

## TODO: Vanilla Armour Expanded + Medieval Overhaul
* Rebalanced the following:
    * Light Plate Armor
    * Chainmail, also moved to MO Chain armor research and renamed Light Hauberk
    * Plate Helmet
    * Plate Shoulderpads, MO Breast plate and Brigandine no longer provide shoulder coverage and have their movement speed malus reduced to compensate
* Removed VE Chestplate in favour of MO Breast Plate
* Removed Plate Gloves and Plate Boots in favour of MO
* TODO: Figure out overlap for Gambeson and Quilted vest

# Bug Fixes
* Fixed name capitalisations for a bunch of items in both VE and MO
* Fixed MO rugs appearing as bills without prior research research
