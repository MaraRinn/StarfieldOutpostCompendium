# Advanced Reactor Assembly Line

- [Advanced Reactor Assembly Line](#advanced-reactor-assembly-line)
  - [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Reactor Production](#reactor-production)
    - [Andraphon (He3 Infrastructure)](#andraphon-he3-infrastructure)
    - [Procyon III (copper/Isotopic Coolant/Antimicrobial)](#procyon-iii-copperisotopic-coolantantimicrobial)
    - [Shoza III-a (He3, Nd)](#shoza-iii-a-he3-nd)
    - [Zeta Ophiuchi I (polymer, silver exports)](#zeta-ophiuchi-i-polymer-silver-exports)
    - [Cruth (Semimetal Wafer, Paramagnon Conductor)](#cruth-semimetal-wafer-paramagnon-conductor)
    - [Codos (Solvent)](#codos-solvent)
    - [Serpentis V-d (He3/SupColMag)](#serpentis-v-d-he3supcolmag)
    - [Schrodinger VIII-e (control rod)](#schrodinger-viii-e-control-rod)
    - [Grimsey (Iridium, Plutonium, Uranium, Vanadium)](#grimsey-iridium-plutonium-uranium-vanadium)
    - [Operation](#operation)
  - [Industrial Liquid Extractors and Greenhouses](#industrial-liquid-extractors-and-greenhouses)
    - [Molecular Sieve](#molecular-sieve)
      - [Home Base (Austenitic Manifold, Mag Pressure Tank)](#home-base-austenitic-manifold-mag-pressure-tank)
      - [Serpentis IV (membrane, molecular sieve)](#serpentis-iv-membrane-molecular-sieve)
    - [Sterile Nanotubes](#sterile-nanotubes)
      - [Serpentis IV (sterile nanotubes)](#serpentis-iv-sterile-nanotubes)
    - [Substrate Molecule Sieve](#substrate-molecule-sieve)
      - [Alpha Andraste III (biosuppressant, Chlorosilanes, Cl, Xe)](#alpha-andraste-iii-biosuppressant-chlorosilanes-cl-xe)
      - [Serpentis IV (fibre and water expansion)](#serpentis-iv-fibre-and-water-expansion)
      - [Fermi VII-a (Memory Substrate)](#fermi-vii-a-memory-substrate)
      - [Serpentis IV (substrate molecule sieve)](#serpentis-iv-substrate-molecule-sieve)
    - [Veryl-Treated Manifold](#veryl-treated-manifold)
      - [Verne I (neon, veryl)](#verne-i-neon-veryl)
      - [Alpha Tirna VIII-c (Lubricant expansion)](#alpha-tirna-viii-c-lubricant-expansion)
      - [Serpentis IV (veryl-treated manifold)](#serpentis-iv-veryl-treated-manifold)
  - [Industrial Solid Extractors](#industrial-solid-extractors)
    - [Schrodinger II (aldumite)](#schrodinger-ii-aldumite)
    - [Bessel III-b (aldumite drilling rig)](#bessel-iii-b-aldumite-drilling-rig)
    - [Andraphon (He3/Be/Eu)](#andraphon-he3beeu)
  - [Advanced Reactor Production](#advanced-reactor-production)
    - [Operation](#operation-1)
    - [Experience grinding](#experience-grinding)
    - [Shoza VII-c (palladium)](#shoza-vii-c-palladium)
    - [Maal IX-b (positron battery)](#maal-ix-b-positron-battery)
    - [Shoza VIII-b (Power Circuit)](#shoza-viii-b-power-circuit)
    - [Katydid III (Indicite)](#katydid-iii-indicite)
    - [Dalvik (Caesium)](#dalvik-caesium)
    - [Decaran VII-b (Vytinium)](#decaran-vii-b-vytinium)
    - [Carinae III-a (Rothicite)](#carinae-iii-a-rothicite)
    - [Huygens VII-a (Tasine)](#huygens-vii-a-tasine)
    - [Shoza VIII-b (tasine superconductor)](#shoza-viii-b-tasine-superconductor)
    - [Grimsey (Vytinium Fuel Rod)](#grimsey-vytinium-fuel-rod)
    - [Grimsey (storage expansion)](#grimsey-storage-expansion)
  - [Mass Production Upgrades](#mass-production-upgrades)
    - [Cruth: Production Rates and Passage of Time Walkthrough](#cruth-production-rates-and-passage-of-time-walkthrough)
      - [Real Time to UT Ratio](#real-time-to-ut-ratio)
      - [Assay Lab - Observing Production over Time](#assay-lab---observing-production-over-time)
    - [Passage of Time Tutorial](#passage-of-time-tutorial)
      - [Extractor Speed](#extractor-speed)
    - [Decaran (extraction upgrade)](#decaran-extraction-upgrade)
    - [Codos (production upgrade)](#codos-production-upgrade)
  - [Restocking Quick Reference](#restocking-quick-reference)
  - [Other Sites](#other-sites)
    - [Leviathan II (He3/Be/Eu/Nd)](#leviathan-ii-he3beeund)
  - [References](#references)

## Overview

In this document you'll build upon the [Industry From Scratch](Industry%20From%20Scratch.md) infrastructure to:

- Build Reactors using manual logistics
- Build Advanced Reactors using manual logistics
- Add better production capacity through Industrial extractors, greenhouses and animal husbandry facilities
- Add cargo links to automate most of the logistics
- Scale up production to be able to produce 700 Vytinium Fuel Rods every two days for the XP grind

## Reactor Production

As a stepping stone to the Advanced Reactor Production chain, having the capacity to build normal reactors is useful. They produce a fixed 30 power which is great for those worlds where wind turbines and solar arrays are especially weak (airless worlds with dim light).

This manufacturing system is automated simply because schlepping around the starfield to pick up some parts here and other parts there is annoying enough without having to pick up feed stock from one planet and ship it to another.

Recipe for Reactors:

- Adaptive Frame: 6
- Control Rod: 3
  - Austenitic Manifold: 1
  - Dysprosium: 3
  - Isotopic Coolant: 1
- Lead: 10
- Nuclear Fuel Rod: 8
  - Semimetal Wafer: 1
  - Solvent: 2
  - Uranium: 3
- Paramagnon Conductor: 4
  - Gold: 1
  - Neodymium: 1
  - Zero Wire: 3
- Supercooled Magnet: 5
  - Isocentered Magnet: 1
  - Isotopic Coolant: 1
  - Neodymium: 3
- Tau Grade Rheostat: 3

### Andraphon (He3 Infrastructure)

Andraphon is going to supply He3 for Schrodinger (2 inter-system cargo links) and Grimsey (1 cargo link), which in hand-wavy terms requires three helium extractors.

Design:

- Landing Pad - Small
- Cargo Link (He3 to Grimsey)
- Cargo Link - Intersystem (He3 to Schrodinger VIII-e)
- 3 Extractor - Gas (he3)
- Storage - Gas - Large (he3)
- 3 Extractor - Solid (aluminum, europium, iron)
- 3 Storage - Solid - Large (aluminum, europium, iron)
- Industrial Workbench
- 3 Solar Dome (12 power)

Materials:

- Manufactured
  - Adaptive Frame: 40
  - Tau Grade Rheostat: 6
  - Zero Wire: 2
- Solid
  - Aluminum: 111
  - Beryllium: 2
  - Copper: 29
  - Iron: 118
  - Nickel: 12
  - Tungsten: 22

### Procyon III (copper/Isotopic Coolant/Antimicrobial)

Upgrading Procyon III which was already established in *Industry From Scratch*. In this upgrade, add production of Ionic Liquids and produce Isotopic Coolant locally. The antimicrobial production might already be present if you have followed the *Pharmaceutical Lab* path.

Design:

- 2 Wind Turbine - Advanced (25 power)
- Extractor - Gas (tetrafluoride)
- Storage - Gas - Large (tetrafluoride)
- 6 Extractor - Liquid (4 Ionic Liquid, 2 water)
- 2 Storage - Liquid - Large (ionic liquid, water)
- Greenhouse (antimicrobial)
- Extractor - Solid (copper)
- 2 Storage - Solid - Large (copper, antimicrobial)
- Simple Fabricator (isotopic coolant)
- Warehouse - Large (isotopic coolant)
- 3 Cargo Link - Inter-system (copper to Bessel III-b, isotopic coolant to Serpentis V-d, isotopic coolant to Schrodinger VIII-e)

Bill of Materials:

- Manufactured
  - Adaptive Frame: 108
  - Comm Relay: 3
  - Isocentered Magnet: 4
  - Reactive Gauge: 15
  - Zero Wire: 5
- Solid
  - Aluminum: 211
  - Beryllium: 2
  - Copper: 46
  - Iron: 173
  - Nickel: 64
  - Sealant: 8
  - Titanium: 16
  - Tungsten: 38
- Gas
  - Fluorine: 8

### Shoza III-a (He3, Nd)

This expansion is all about Helium-3, with a side of Neodymium for the semimetal wafers on Cruth and supercooled magnets on Serpentis V-d. The outpost was previously established in *Industry From Scratch*.

Design:

- 4 Solar Dome (12 power)
- 6 Extractor - Gas (helium-3)
- 2 Extractor - Solid (neodymium)
- Cargo Link - Inter-system (He3 to Maal IX-b)
- Cargo Link - Inter-system (He3 to Schrodinger VIII-e)
- Cargo Link - Inter-system (He3 to Zeta Ophiuchi I)
- Cargo Link - Inter-system (Nd to Serpentis V-d)
- Cargo Link - Inter-system (Nd to Cruth)

Materials:

- Manufactured
  - Comm Relay: 5
  - Reactive Gauge: 15
  - Tau Grade Rheostat: 8
- Solid
  - Aluminum: 114
  - Copper: 18
  - Iron: 110
  - Nickel: 24
  - Tungsten: 4

Location:

![Shoza III-a resource map showing location of outpost](images/shoza-iii-a-location-map.jpg)

There's a (darker) pixel of aluminum between the He3 and Neodymium regions, if you squint you can see it's like a bulge in the middle of an hourglass.

![Shoza III-a surface map showing location of outpost](images/shoza-iii-a-location-surface.jpg)

On the surface you'll see that there are three distinct terrain tiles: sand dunes, heavy craters, and relatively flat with scattered rock. Near the cave in the centre of a nearby flat rocky tile is a location with two He3 patches and a large stretch of neodymium. Each He3 patch can hold 8 gas extractors, making it ideal for this outpost.

### Zeta Ophiuchi I (polymer, silver exports)

This is a cargo link expansion for the outpost built in the *Industry From Scratch* guide.

Design:

- 3 Cargo Link - Inter-system (silver to Cruth, polymer to Shoza VIII-b, He3 from Shoza III-a)
- Storage - Gas - Large (He3)

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Comm Relay: 3
  - Reactive Gauge: 9
- Solid
  - Aluminum: 36
  - Copper: 20
  - Iron: 60
  - Tungsten: 16

### Cruth (Semimetal Wafer, Paramagnon Conductor)

Note how many solar domes are required to produce the power required just for the startup phase of this outpost.

This starter outpost will be upgraded later, look for sites with large accessible patches of antimony since the extractors will require lots of separation and will extract antimony slowly.

Design:

- Landing Pad - Small
- 11 Solar Dome (4 power)
- 3 Extractor - Solid (antimony, gold, copper)
- 5 Storage - Solid - Large (antimony, copper, gold, neodymium, silver)
- 1 Extractor - Gas (fluorine)
- Storage - Gas - Large (fluorine)
- Simple Fabricator (zero wire)
- 3 Warehouse - Large (zero wire, semimetal wafers, paramagnon conductor)
- 2 Compound Fabricator (semimetal wafer, paramagnon conductor)
- 1 Cargo Link (semimetal wafer to Grimsey)
- 4 Cargo Link - Inter-system (silver from Zeta Ophiuchi I, neodymium from Shoza III-a, paramagnon to Shoza VIII-b, semimetal wafer to Schrodinger VIII-e)

Materials:

- Manufactured
  - Adaptive Frame: 90
  - Comm Relay: 4
  - Isotopic Coolant: 4
  - Reactive Gauge: 12
  - Tau Grade Rheostat: 22
  - Zero Wire: 15
- Solid
  - Adhesive: 8
  - Aluminum: 277
  - Beryllium: 2
  - Copper: 23
  - Iron: 235
  - Nickel: 4
  - Sealant: 2
  - Titanium: 48
  - Tungsten: 42

Location:

Location of Cruth outpost isn't important, just plonk it down on a large yellow patch (Gold, Antimony, Copper). All the resources this outpost needs are in a single biome. The hard part is finding a patch of land that doesn't have POIs nearby.

### Codos (Solvent)

[Codos](https://inara.cz/starfield/starsystem/10/#area1158) is a nice place for a **solvent**-producing outpost, being the only domesticable plant-based solvent supply. It should be possible to find a location that also produces Carboxylic Acids (R-COOH) which are useful for research and weapon mods.

Design:

- Landing Pad with Shipbuilder
- Wind Turbine - Advanced (14 power)
- Extractor - Liquid (water)
- Storage - Liquid - Large (water)
- Greenhouse (solvent)
- 1 Storage - Solid - Large (solvent)
- 1 Cargo Link - Inter-system (Solvent to Grimsey)

Materials:

- Manufactured
  - Adaptive Frame: 43
  - Comm Relay: 1
  - Isocentered Magnet: 2
  - Reactive Gauge: 6
  - Zero Wire: 2
- Solid
  - Aluminum: 58
  - Beryllium: 2
  - Iron: 73
  - Nickel: 20
  - Sealant: 3
- Gas
  - Fluorine: 4

### Serpentis V-d (He3/SupColMag)

Design:

- Industrial Workbench
- 4 Solar Dome (8 power)
- Extractor - Gas (helium-3)
- Storage - Gas - Large (He3)
- 2 Extractor - Solid (Nickel, Cobalt)
- 4 Storage - Solid - Large (Co, Ni, Nd)
- 3 Warehouse - Large (Isotopic Coolant, Isocentered Magnet, Supercooled Magnet)
- Simple Fabricator (isocentered magnet)
- Compound Fabricator (supercooled magnet)
- 3 Cargo Link - Inter-system (Neodymium from Shoza III-a, Isotopic Coolant from Procyon III, Supercooled Magnets to Schrodinger VIII-e)

Materials:

- Manufactured
  - Adaptive Frame: 80
  - Comm Relay: 3
  - Isotopic Coolant: 2
  - Reactive Gauge: 9
  - Tau Grade Rheostat: 8
  - Zero Wire: 8
- Solid
  - Adhesive: 4
  - Aluminum: 201
  - Copper: 23
  - Iron: 153
  - Nickel: 4
  - Sealant: 2
  - Titanium: 48
  - Tungsten: 32

Location:

The resources needed for this outpost are Co/Ni and He3. You'll find Co/Ni in the Hills biome, He3 in the craters biome. In the surface map you'll find a confluence of craters, hills and mountains along the left edge of the litte green nubbin, craters down the centre, hills south (down) from that, mountains west (left) of the craters. The landing site is on the mountains side of craters/mountains border. This outpost has He3, Ni, Co, Al, Be.

This site has sometimes failed to deliver Co, Ni and He - proceed further south along the mountains/craters border and you should find another site. I've even found sites with Al/Be/Co/He3/Ni (not that the Al/Be are of use in this plan).

<img src="images/serpentis-v-d-location-map.jpg" alt="Map of Serpentis V-d with resources shown" width="40%">
<img src="images/serpentis-v-d-landscape-landing.jpg" alt="Landscape at the landing site" width="40%">
<img src="images/serpentis-v-d-surface-map.jpg" alt="Surface map showing landing site and outpost location" width="40%">
<img src="images/serpentis-v-d-landscape-outpost.jpg" alt="Landscape at outpost location" width="40%">

### Schrodinger VIII-e (control rod)

This is a manual production site as part of the XP grind. Produce Control Rods using Dysprosium. The lithium will be used for Rothicite Magnets later.

If you haven't skipped ahead and set up the lubricant production on Alpha Tirna VIII-c as part of the Veryl-Treated Manifold production chain, you should be able to get lubricant from Sieghart in Neon or any Trade Authority. If you have Shattered Space DLC you can get lubricant from Pendentleaf which are common around the Dazra outskirts.

Design:

- Landing Pad - Small
- 6 Wind Turbine - Advanced (6 power)
- 6 Cargo Link - Inter-system (austenitic manifold from Bessel III-b, isotopic coolant from Procyon III, semimetal wafer from Cruth, supercooled magnet from Serpentis V-d, rothicite from Carinae III-a, he3 from Shoza III-a)
- 3 Extractor - Solid (lead, lithium, dysprosium)
- 4 Storage - Solid - Large (dysprosium, lead, lithium, rothicite)
- 1 Storage - Gas - Large (he3)
- 6 Warehouse - Large (austenitic manifold, control rod, isotopic coolant, semimetal wafer, supercooled magnet, rothicite magnet)
- 1 Compound Fabricator (control rod)
- 1 Multiplex Fabricator (rothicite magnet)

Materials:

- Manufactured
  - Adaptive Frame: 110
  - Comm Relay: 6
  - Isocentered Magnet: 12
  - Isotopic Coolant: 2
  - Positron Battery: 3
  - Reactive Gauge: 18
  - Zero Wire: 5
- Solid
  - Adhesive: 4
  - Aluminum: 306
  - Copper: 20
  - Iron: 235
  - Lubricant: 6
  - Polymer: 8
  - Titanium: 104
  - Tungsten: 30

Cargo links:

- He3 from Shoza III-a He3/Nd
- Austenitic Manifold from Bessel III-b Manifolds
- Isotopic Coolant from Procyon III
- Semimetal Wafer from Cruth
- Supercooled Magnet from Serpentis V-d He3/Supcolmag
- Rothicite from Carinae III-a Rothicite

Location:

In the southern hemisphere, find this region. The landing spot is on the **rocky desert** side of the mountains/rocky desert/frozen hills biome border. When you land the ship should be on dirt close to the snowline, the landscape should be predominantly flat with stone pillars and a small mound in the middle distance in the snow-covered region. Opposite from the snowline will be a hot springs geographic feature which you should have seen during the landing animation.

From the landing site, follow the snowline north for about 3km. Half way there (1.6km) you'll pass a large dysprosium patch that crosses the snowline, then eventually come to a snow-covered region that is relatively void of stone pillars. One last stone pillar on the snow side of the border (left, in the direction of travel), and there will be a large slab of rock perched on the hillside.

The final image shows a view from the top of that large rock back towards the ship. At this location you can place an outpost and have access to Dysprosium, Lead and Lithium. The lithium and dysprosium are at opposite edges of the outpost building range, you may have to finesse the location a little to get comfortable access to both.

This is a low-grav world, you'll find it much easier driving on the dirt than the snow. Of course if power sliding is your thing, there's plenty of snow to play in.

<p>
<img src="images/schrodinger-viii-e-location-map.jpg" alt="Map of Schrodinger VIII-e with resources shown. There is a marker for the location of the outpost." width="40%">
<img src="images/schrodinger-viii-e-location-landing.jpg" alt="The landscape at the landing site on Schrodinger VIII-e intended to help players find the location of this outpost" width="40%">
<img src="images/schrodinger-viii-e-location-landscape.jpg" alt="The landscape approaching the outpost on Schrodinger VIII-e intended to help players find the location once they have landed." width="40%">
<img src="images/schrodinger-viii-e-location-outpost.jpg" alt="The landscape around the outpost beacon looking back towards the landing site." width="40%">
</p>

### Grimsey (Iridium, Plutonium, Uranium, Vanadium)

Set Grimsey up as a location for manually producing Nuclear Fuel Rod.

Design:

- Landing Pad - Small
- Industrial Workbench
- 4 Solar Dome (6 power)
- 4 Extractor - Solid (iridium, plutonium, uranium, vanadium)
- 6 Storage - Solid - Large (iridium, lead, plutonium, solvent, uranium, vanadium)
- Storage - Gas - Large (he3)
- 3 Warehouse - Large (control rod, paramagnon conductor, semimetal wafer)
- 2 Cargo Link (semimetal wafer from cruth, he3 from Andraphon)
- Cargo Link - Inter-system (solvent from Codos)

Materials:

- Manufactured
  - Adaptive Frame: 100
  - Comm Relay: 1
  - Reactive Gauge: 3
  - Tau Grade Rheostat: 8
  - Zero Wire: 4
- Solid
  - Aluminum: 236
  - Beryllium: 4
  - Copper: 20
  - Iron: 223
  - Titanium: 48
  - Tungsten: 24

Location:

All the resources we need from Grimsey are in one biome. Land in a plutonium-rich area then find somewhere relatively flat in an area with accessible iridium, plutonium, uranium and vanadium deposits.

### Operation

Run a route to pick up materials and manufacture components on the way:

- Collect 10 Lead, 3 Control Rods, 5 Supercooled Magnet from Schrodinger VIII-e
- Collect 6 Adaptive Frame, 3 Tau Grade Rheostat from Bessel III-b
- Collect 4 Paramagnon Conductor from Cruth
- Craft 8 Nuclear Fuel Rods at Grimsey
- Build reactor, then demolish it (ensures you have all the parts, leaves materials in your ship)
- Head to site to build reactor

## Industrial Liquid Extractors and Greenhouses

The larger project ahead is mass producing Vytinium Fuel Rods (an XP and money grind). For that project it would be nice to have better extraction technology. This industrial extractor project is oriented towards producing Veryl-Treated Manifold and Substrate Molecule Sieve. These components allow construction of industrial liquid and gas extractors, and industrial greenhouses. These will be useful for materials such as Solvent.

Note that for the quantities required in any playthrough it might be easier just buying the Substrate Molecule Sieve and Veryl-Treated Manifold from the stores that stock them. Contrast the labour of setting up or expanding a half dozen new outposts with collecting a few dozen infrequently stocked components.

Stores that sometimes stock rarer parts:

- Clint's, Gagarin Landing
- Outland, New Atlantis
- UC Exchange, Cydonia
- Sieghart's, Neon
- Shepherd's, Akila City
- The Trader

To establish the infrastructure to build these parts, let's start with the end in mind and work backwards from the final product. Materials for Liquid Extractor - Industrial:

- 5 Adaptive Frame (1.6kg)
- 2 Substrate Molecule Sieve (4.5kg)
  - Biosuppressant
  - Memory Substrate
  - Molecular Sieve
  - Sterile Nanotube
- 6 Titanium (0.5kg)
- 3 Veryl-Treated Manifold (5.4kg)
  - Austenitic Manifold
  - Lubricant
  - 2 Veryl
  - Ytterbium

### Molecular Sieve

Molecular Sieve requires the following components:

- 2 Ionic Liquid
- 1 Mag Pressure Tank
  - 2 Aluminium
  - 1 Nickel
- 2 Membrane

#### Home Base (Austenitic Manifold, Mag Pressure Tank)

Design:

- Reactor
- 2 Simple Fabricator (Austenitic Manifold, Mag Pressure Tank)
- 2 Warehouse - Large (Austenitic Manifold, Mag Pressure Tank)

Materials:

- Adaptive Frame: 16
- Aluminum: 28
- Control Rod: 3
- Lead: 10
- Nuclear Fuel Rod: 8
- Paramagnon Conductor: 4
- Sealant: 2
- Supercooled Magnet: 5
- Tau Grade Rheostat: 3
- Titanium: 16
- Tungsten: 4
- Zero Wire: 3

#### Serpentis IV (membrane, molecular sieve)

[Serpentis IV](https://inara.cz/starfield/starsystem/47/#area1892) has a domesticable animal that produces **Membrane**. Water is available locally. This base can be expanded over time to produce water, fiber, metabolic agent, sealant, toxin, analgesic, argon, lithium. In most playthroughs I'll end up building a pharamceutical lab here.

Import mag pressure tank by hand from Bessel, fill up the warehouse and that should last most of a playthrough.

Design:

- 3 Wind Turbine - Advanced (25 power)
- 5 Extractor - Liquid (water)
- 1 Storage - Liquid - Large (water)
- 2 Greenhouse (fiber)
- 2 Animal Husbandry Facility (membrane, sealant)
- 4 Storage - Solid - Large (2 fiber, membrane, sealant)
- Storage - Liquid - Large (ionic liquids)
- Compound Fabricator (molecular sieve)
- 2 Warehouse - Small (mag pressure tank, molecular sieve)

Materials:

- Manufactured
  - Adaptive Frame: 111
  - Isocentered Magnet: 6
  - Isotopic Coolant: 2
  - Reactive Gauge: 15
  - Zero Wire: 5
- Solid
  - Adhesive: 4
  - Aluminum: 210
  - Copper: 26
  - Iron: 140
  - Nickel: 60
  - Sealant: 15
  - Titanium: 10
  - Tungsten: 26
- Gas
  - Fluorine: 12

Location:

My favoured spots are along the "frozen crevasses" side of the frozen crevasse/savanna borders. When you land you should see both savanna and frozen crevasse landscape. With a bit of hunting you'll find a spot with Argon, Benzene and Lithium. With a bit more luck you'll find Chlorosilanes too, though they're not needed for much.

<p>
<img src="images/serpentis-iv-location-map.jpg" alt="Map of Serpentis IV with resources shown. There is a marker for the location of the outpost." width="40%">
<img src="images/serpentis-iv-location-landscape.jpg" alt="The landscape around the outpost on Serpentis IV intended to help players find the location once they have landed." width="40%">
<img src="images/serpentis-iv-location-map-2.jpg" alt="Map of Serpentis IV with resources shown. There is a marker for the alternative outpost location" width="40%">
<img src="images/serpentis-iv-location-outpost-2.jpg" alt="The landscape around the landing site for the alternative outpost location on Serpentis IV." width="40%">
<img src="images/serpentis-iv-location-outpost-2.jpg" alt="The landscape around the alternative outpost location on Serpentis IV" width="40%">
</p>

### Sterile Nanotubes

To produce Sterile Nanotubes we need:

- 1 Molecular Sieve
- 2 Solvent
- 2 Vanadium

#### Serpentis IV (sterile nanotubes)

Import solvent from Codos, Vanadium from Grimsey.

Design:

- Wind Turbine - Advanced (25 power)
- 2 Storage - Solid - Large (solvent, vanadium)
- Compound Fabricator (sterile nanotubes)
- Warehouse - small (sterile nanotubes)

Materials:

- Manufactured
  - Adaptive Frame: 20
  - Isocentered Magnet: 2
  - Isotopic Coolant: 2
  - Zero Wire: 5
- Solid
  - Adhesive: 4
  - Aluminum: 37
  - Iron: 40
  - Tungsten: 8

### Substrate Molecule Sieve

These are needed for industrial water extractors and industrial greenhouses.

- 2 Biosuppressant
- 3 Memory Substrate
- 1 Molecular Sieve
- 2 Sterile Nanotubes

#### Alpha Andraste III (biosuppressant, Chlorosilanes, Cl, Xe)

[Alpha Andraste III](https://inara.cz/starfield/starsystem/25/#area1284) has a domesticable source of **Biosuppressant**.

Biosuppressant is used for a few mods, Substrate Molecule Sieve and Repairing Immobiliser. Over the entire course of the game you'll likely use a hundred or so, this is another outpost where you can happily fill up the storage, collect one full load and then remove the outpost.

Design:

- Landing Pad with Shipbuilder
- Wind Turbine - Advanced (25 power)
- 1 Extractor - Liquid (water)
- 1 Storage - Liquid - Medium (water)
- Greenhouse (biosuppressant)
- Storage - Solid - Large (biosuppressant)
- Extractor - Gas (xenon)
- Storage - Gas - Medium (xenon)

Materials:

- Manufactured
  - Adaptive Frame: 43
  - Isocentered Magnet: 2
  - Reactive Gauge: 3
  - Zero Wire: 2
- Solid
  - Aluminum: 41
  - Beryllium: 2
  - Copper: 13
  - Iron: 53
  - Nickel: 16
  - Sealant: 3
  - Tungsten: 8
- Gas
  - Fluorine: 

#### Serpentis IV (fibre and water expansion)

To get Memory Substrate production at Fermi VII-a working we need a surplus of fibre and water. Serpentis is already producing both, this expansion is just to provide surplus.

NB: connect these to each other isolated from the local production chain. This production chain is specifically for Fermi VII-a inputs.

Design:

- Greenhouse (fiber)
- Extractor - Liquid (water)
- Storage - Liquid - Large (water)
- 4 Storage - Solid - Large (2 fiber, 2 memory substrate)
- Wind Turbine - Advanced (25 power)

Materials:

- Manufactured
  - Adaptive Frame: 25
  - Isocentered Magnet: 2
  - Reactive Gauge: 3
- Solid
  - Aluminum: 46
  - Iron: 23
  - Nickel: 20
  - Sealant: 3
- Gas
  - Fluorine: 4

#### Fermi VII-a (Memory Substrate)

[Fermi VII-a](https://inara.cz/starfield/starsystem/73/#area185) is the only place we can produce **Memory Substrate**. Import two storages of fiber and 1 of water, dump them in the large storage then come back to pick up the memory substrate. At that point delete the outpost, we won't be back. You need 3 Memory Substrate to make 1 Substrate Molecule Sieve, then 2 Substrate Molecule Sieve to make the industrial buildings of interest (extractors, greenhouses), which means 6 memory substrate for 1 building. With ~200 memory substrate from one load of fiber and water, you'll be able to make 30-odd buildings which is far more than this entire build guide needs (but I have gone over that budget just for fun).

Design:

- 1 Wind Turbine - Advanced (14 power)
- 1 Animal Husbandry Facility (memory substrate)
- 3 Storage - Solid - Large (2 fiber, 1 memory substrate)
- 1 Storage - Liquid - Large (water)
- 1 Landing Pad - Small

Materials:

- Manufactured
  - Adaptive Frame: 55
  - Isocentered Magnet: 2
  - Reactive Gauge: 3
- Solid
  - Aluminum: 94
  - Iron: 83
  - Nickel: 20
  - Sealant: 3
- Gas
  - Fluorine: 4

#### Serpentis IV (substrate molecule sieve)

Serpentis is already producing molecular sieve and sterile nanotubes.

Design:

- Wind Turbine - Advanced (25 power)
- Storage - Solid - Large (biosuppressant)
- Multiplex Fabricator (substrate molecule sieve)
- Warehouse - Small (substrate molecule sieve)

Materials:

- Manufactured
  - Adaptive Frame: 13
  - Isocentered Magnet: 2
  - Positron Battery: 3
- Solid
  - Aluminum: 27
  - Iron: 20
  - Lubricant: 6
  - Polymer: 8
  - Titanium: 13

### Veryl-Treated Manifold

- 1 Austenitic Manifold
- 2 Lubricant
- 4 Veryl
- 2 Ytterbium

#### Verne I (neon, veryl)

[Verne I](https://inara.cz/starfield/starsystem/22/#area390) is the unique source of **Veryl**.

Design:

- 1 Landing Pad with Shipbuilder
- 1 Wind Turbine - Advanced (25 power)
- 3 Extractor - Gas (neon, 2 veryl)
- 2 Storage - Gas - Large (neon, veryl)

Materials:

- Manufactured
  - Adaptive Frame: 38
  - Isocentered Magnet: 2
  - Zero Wire: 2
- Solid
  - Aluminum: 20
  - Beryllium: 2
  - Copper: 49
  - Iron: 30
  - Nickel: 12
  - Tungsten: 32

#### Alpha Tirna VIII-c (Lubricant expansion)

[Alpha Tirna VIII-c](https://inara.cz/starfield/starsystem/51/#area1536) has domesticable **lubricant** source. Note that the Inara database is incorrect: blistercrab drops lubricant, swarming crab drops antimicrobial, crab drops pigment (three crab types). Livestock will require water which can only be obtained through vapor extractors, and fiber which can be grown locally.

Design:

- Reactor
- 2 Extractor - Liquid Vapor (water)
- 1 Storage - Liquid (water)
- 1 Greenhouse (fiber)
- 2 Storage - Solid - Large (fiber, lubricant)
- 1 Animal Husbandry Facility (lubricant)

Materials:

- Manufactured
  - Adaptive Frame: 33
  - Reactive Gauge: 6
- Solid
  - Aluminum: 56
  - Iron: 40
  - Membrane: 8
  - Nickel: 5
  - Sealant: 6
- Gas
  - Benzene: 6
  - Fluorine: 4

#### Serpentis IV (veryl-treated manifold)

Set up the Transfer container as a feed-in for the various storages (see References: "Unlimited Storage & Automated Resources Guide").

The only materials you want in this storage system are feedstock for Substrate Molecule Sieve and Veryl-Treated Manifold as follows (source in parentheses):

- Austenitic Manifold (Bessel III-b)
- Biosuppressant (Alpha Andraste III)
- Ionic Liquids (Procyon II)
- Lubricant (Alpha Tirna VIII-c)
- Mag Pressure Tank (Bessel III-b)
- Membrane (Serpentis IV)
- Memory Substrate (Fermi VII-a)
- Solvent (Codos)
- Vanadium (Grimsey)
- Veryl (Verne I)
- Ytterbium (Zeta Ophiuchi I)

Monitor the fabricators in Outpost/Modify mode to ensure that you have sufficient quantities of the various inputs. The fabricators have enough storage internally to hold all the components you're likely to require.

Design:

- Wind Turbine - Advanced (25 power)
- Multiplex Fabricator (Veryl-Treated Manifold)
- Transfer Container
- 5 Storage - Liquid - Large (Ionic Liquid)
- 10 Storage - Solid - Large (Biosuppressant, Lubricant, Memory Substrate, Solvent, Titanium, Vanadium, Ytterbium)
- 5 Storage - Gas - Large (Veryl)
- 5 Warehouse - Large (Adaptive Frame, Austenitic Manifold, Mag Pressure Tank)

Materials:

- Manufactured
  - Adaptive Frame: 250
  - Isocentered Magnet: 2
  - Positron Battery: 3
- Solid
  - Aluminum: 365
  - Copper: 100
  - Iron: 208
  - Lubricant: 10
  - Nickel: 80
  - Polymer: 8
  - Titanium: 88
  - Tungsten: 85

## Industrial Solid Extractors

I'd go so far as to suggest that it's not worth the effort of building Aldumite Drilling Rig since you can get the quantities you need by [keeping an eye out for vendor supplies](https://inara.cz/starfield/resource/288/). Failing that, head to Schrodinger II, set up an outpost to collect a few hundred aldumite, remove that outpost and stow the aldumite away at Grimsey where you'll have an industry outpost ready to assemble the Aldumite Drilling Rig.

My order of preference for upgrades is:

- Build more of the simple extractors
- Build Sanitation Robots (10% extra production, multiplicative)
- Add crew with Outpost Management skill
- If more production is still required, upgrade to industrial extractors

The recipe for these:

- 5 Adaptive Frame
- 1 Aldumite Drilling Rig
  - 4 Aldumite (1.9kg)
  - 2 Caesium (0.8kg)
  - 1 Drilling Rig
    - 2 Lubricant
    - 1 Reactive Gauge
    - 3 Tungsten
  - 1 Microsecond Regulator
    - 4 Europium
    - 2 Lithium
    - 1 Supercooled Magnet
    - 1 Tau Grade Rheostat
- 4 Isotopic Coolant
- 6 Tungsten

I already collect Lubricant and Tungsten at Tirna VIII-c Ta/Ti/W/Alk/Lube, have Schrodinger VIII-e set up for Rothicite Magnets, so producing Drilling Rigs will consist of:

1. Pick up Reactive Gauge and Tau Grade Rheostat from Bessel III-b
2. Pick up Europium from Andraphon
3. Head to Tirna VIII-c outpost to construct Drilling Rig
4. Head to Schrodinger VIII-e to construct Microsecond Regulators
5. Pick up Aldumite from Schrodinger II (if you haven't already got a stash hidden away at Grimsey)
6. Head to Grimsey to construct Aldumite Drilling Rig
7. Drop Aldumite Drilling Rig off at home base. A large warehouse will store 42 Aldumite Drilling Rig

Vendors:

- Clint de Haven (Gagarin Landing)
- Outland (New Atlantis commercial district)
- Seighart's Outfitters (Neon)
- Shepherd's General (Akila City)
- Starborn Trader

### Schrodinger II (aldumite)

This is another one-and-done outpost. Once the storage has been filled, delete this outpost.

Design:

- Landing Pad - Small
- Solar Array (8 power)
- Extractor - Solid (aldumite)
- Storage - Solid - Large (aldumite)

Materials:

- Manufactured
  - Adaptive Frame: 10
- Solid
  - Aluminum: 32
  - Beryllium: 2
  - Copper: 3
  - Iron: 45
  - Tungsten: 2

Location:

Put this outpost anywhere you can find a patch of aldumite.

### Bessel III-b (aldumite drilling rig)

Instead of schlepping back and forth each time you want to build Aldumite Drilling Rig, consider one trip to fetch Europium from Andraphon, Lithium and Supercooled Magnet from Serpentis V-d, Lubricant and Tungsten from Tirna VIII-c, aldumite from Schrodinger II, Caesium from Grimsey (after installing the cargo link from Dalvik), then producing the components at Bessel III-b.

Design:

- 3 Storage - Solid (aldumite, europium, lithium, lubricant)
- Storage - Liquid - Medium (caesium)
- Warehouse - Large (aldumite drilling rig)
- 2 Warehouse - Small (microsecond regulator, supercooled magnet)
- Compound Fabricator (Drilling Rig)
- 2 Multiplex Fabricator (Microsecond Regulator, Aldumite Drilling Rig)

### Andraphon (He3/Be/Eu)

Andraphon is a convenient location to collect He3 to drive the Grimsey and Cruth outposts.

Solar Array: 6
Wind Turbine: 0

Design:

- Landing Pad - Small
- 3 Solar Dome (12 power)
- Extractor - Solid (beryllium)
- Storage - Solid - Large (beryllium)
- 4 Extractor - Gas (He3)
- Storage - Gas - Large (He3)

Bill of Materials:

- Adaptive Frame: 20
- Aluminum: 60
- Copper: 32
- Iron: 45
- Nickel: 16
- Tau Grade Rheostat: 6
- Tungsten: 18

Location:

The marking in the image is indicating to count four pixels to the left from the empty pixel on the same row. There should be a few pixels of mountains then one of craters.

<p>
<img src="images/andraphon-site-map.jpg" alt="Map of Adraphon with resources shown. There is a marker for the location of the outpost." width="40%">
<img src="images/andraphon-site-landscape-landing.png" alt="The landscape around the landing site on Andraphon intended to help players find the location once they have landed." width="40%">
<img src="images/andraphon-site-landscape-outpost.png" alt="The landscape around the outpost site on Andraphon intended to help players find the location once they have landed." width="40%">
</p>

TODO: update with new location: JRamosWorks Gaming Fun, [#Starfield Outposts - 5 Resources in One Spot on Andraphon | Great Starter Locations Video 1 of 4](https://www.youtube.com/watch?v=XEJNLgBUXVI)

## Advanced Reactor Production

Advanced reactors are great for outposts that require lots of industry. If you start deploying industrial extractors, they'll require 20 power to operate so you'll basically require an advanced reactor to provide the necessary power. On some worlds you'll get by just fine with wind turbines.

This project is really not about advanced reactors so much as it is about building outposts, setting up cargo links, and trying to figure out numbers for optimal production rates.

You will need Outpost Management 1 to work through these instructions since most outposts will use more than the base 3 cargo links. You will lose the perks from those skill points when starting NG+. Note that using these console commands will disable achievments and mark your game as "Creations". The console commands to restore the perks are:

1. player.removeperk 0023826F
2. player.addperk 0023826F (once for each level)

To build advanced reactors we need the following parts:

- Reactor - Advanced
  - 10 Adaptive Frame
  - 5 Control Rod
  - 20 Lead (14kg)
  - 3 Power Circuit
  - 5 Rothicite Magnet
  - 4 Tasine Superconductor
  - 8 Vytinium Fuel Rod

### Operation

Once the upgrades in this guide are complete:

1. Head to Grimsey and build 8 Vytinium Fuel Rods
  1. Build Indicite Wafers with half the available semimetal wafers
  2. Build Nuclear Fuel Rods with the remaining semimetal wafers
  3. Build all the Vytinium Fuel rods that resources allow
  4. Deposit remaining Indicite Wafers and Nuclear Fuel Rods in the warehouse
2. Head to Shoza VIII-b and build (per advanced reactor):
  - 3 Power Circuits
  - 4 Tasine Superconductors
3. Head to Schrodinger VIII-e and collect (per advanced reactor):
  - 5 Rothicite Magnets
  - 5 Control Rods
  - 20 Lead
4. Collect 10 Adaptive Frame from Bessel III-b (per advanced reactor)
5. Head to the site and build the Reactor - Advanced

### Experience grinding

If you're trying to grind XP instead of build advanced reactors, just build the Vytinium Fuel Rods:

1. Go to Grimsey, wait for containers to fill, create VFR as above, keep going until you run out of supplies
2. Visit these planets to sell the VFR:
  - Valo > Polvo > Hopetown
    - Pit Stop > Fast Hoang 11000 (82)
    - Carlos Shenton 4500 (33)
  - Cheyenne > Akila > Akila City
    - Emerson Shepherd 5000 (37)
    - Trade Authority 11000 (82)
  - Porrima > Porrima III > Red Mile
    - Sati Chandra (bartender) 11000 (82) (watch out for caraffe on the bench in front of her, quicksave on landing)
  - Volii > Volii Alpha > Neon Core
    - Trade Authority 11000 (82)
    - Newill's (as you leave TA, mining league is across the way, then to the right is Freestar Rangers then Newill's)
    - Mining League 5000 (37)
    - Sieghart's Outfitters 5000 (37)
  - Alpha Centauri > Jemison > New Atlantis
    - Jemison Mercantile 5000 (37)
    - The Well > Trade Authority 11000 (82)
    - Commercial District > Outland
  - Sol > Mars > Cydonia
    - Trade Authority 11000 (82)
    - UC Exchange (varies)
  - Wolf > Cthonia > The Den
    - Trade Authority 11000 (82)

That's 755 VFR in one trip. Each VFR represents 4XP for Nuclear Fuel Rod, 10XP for Indicite Wafer, 14XP for the VFR build for a total of 28XP.

### Shoza VII-c (palladium)

Design:

- Landing Pad with Shipbuilder
- Solar Dome
- Extractor - Solid (Pd)
- Storage - Solid - Large (Pd)
- Cargo Link (Pd to Shoza VIII-b)

Materials:

- Manufactured
  - Adaptive Frame: 28
  - Tau Grade Rheostat: 2
  - Zero Wire: 4
- Solid
  - Aluminum: 36
  - Beryllium: 4
  - Iron: 75
  - Tungsten: 2

Location:

This outpost can be set up on any palladium-rich location.

### Maal IX-b (positron battery)

Local power generation is 8 from a solar dome, 6 from a wind turbine - advanced, or 30 from a reactor.

Design:

- Landing Pad - Small
- Reactor
- 2 Extractor - Solid (antimony, vanadium)
- 2 Storage - Solid - Large (antimony, vanadium)
- 2 Warehouse - Large (tau grade rheostat, positron battery)
- Compound Fabricator (positron battery)
- 2 Cargo Link - Inter-system (tau grade rheostat from Shoza VIII-b, positron battery to Shoza VIII-b)

Materials:

- Manufactured
  - Adaptive Frame: 46
  - Comm Relay: 2
  - Control Rod: 3
  - Isotopic Coolant: 2
  - Nuclear Fuel Rod: 8
  - Paramagnon Conductor: 4
  - Reactive Gauge: 6
  - Supercooled Magnet: 5
  - Tau Grade Rheostat: 3
  - Zero Wire: 5
- Solid
  - Adhesive: 4
  - Aluminum: 112
  - Iron: 110
  - Lead: 10
  - Titanium: 32
  - Tungsten: 12

Location:

Land on the Frozen Hills side of the Sandy Desert/Frozen Hills border. Head to the biome border and follow the snowline to the left, keep going for about 1.6km until you see the stone pillars rock formation. Outpost site is immediately behind and to the right, in the direction of travel.

<p>
<img src="images/maal-ix-b-location-map.jpg" alt="Map of Maal IX-b with resources shown. There is a marker for the location of the outpost." width="40%">
<img src="images/maal-ix-b-landing-landscape.jpg" alt="The landscape around the landing site on Maal IX-b intended to help players find the location once they have landed." width="40%">
<img src="images/maal-ix-b-outpost-landscape.jpg" alt="The landscape around the outpost on Maal IX-b intended to help players find the location once they have landed." width="40%">
</p>

NB: you should be able to find a similar spot on most frozen hills/sandy desert biome borders. This is just the one that I documented poorly.

### Shoza VIII-b (Power Circuit)

Look for a site that provides Al, Be, Cu, Au, He3. Manually construct Power Circuit here to build advanced reactors:

- Palladium from Shoza VII-c
- Polymer from Zeta Ophiuchi I
- Positron Battery from Maal IX-b

Design:

- Landing Pad - Small
- Industrial Workbench
- 2 Reactor
- 4 Extractor - Solid (Al, Be, Cu, Au)
- 6 Storage - Solid - Large (Al, Be, Cu, Au, Pd, polymer)
- Simple Fabricator (tau grade rheostat)
- 4 Warehouse - Large (paramagnon conductor, positron battery, power circuit, tau grade rheostat)
- Multiplex Fabricator (power circuit)
- Cargo Link (Pd from Shoza VII-c)
- 4 Extractor - Gas (Helium-3)
- Storage - Gas - Large
- 4 Cargo Link - Inter-system (tau grade rheostat to Maal IX-b, positron battery from Maal IX-b, paramagnon conductor from Cruth, polymer from Zeta Ophiuchi I)

Materials:

- Manufactured
  - Adaptive Frame: 122
  - Comm Relay: 4
  - Control Rod: 6
  - Nuclear Fuel Rod: 16
  - Paramagnon Conductor: 8
  - Positron Battery: 3
  - Reactive Gauge: 12
  - Supercooled Magnet: 10
  - Tau Grade Rheostat: 6
  - Zero Wire: 5
- Solid
  - Aluminum: 292
  - Beryllium: 2
  - Copper: 32
  - Iron: 263
  - Lead: 20
  - Lubricant: 6
  - Nickel: 16
  - Polymer: 8
  - Sealant: 2
  - Titanium: 72
  - Tungsten: 28

Location:

This location is in the northern hemisphere, look for the row of Craters pixels just next to the Frozen Plains.

<p>
<img src="images/shoza-viii-b-location-map.jpg" alt="Map of Shoza VIII-b with resources shown. There is a marker for the location of the landing site." width="40%">
<img src="images/shoza-viii-b-scanner-view.jpg" alt="The landscape around the outpost on Shoza VIII-b intended to help players find the location once they have landed." width="40%">
</p>

Also see the "Advanced Reactor Assembly" document from MattGyver's "Starfield Manufacturing Flow Diagrams" which has a full page describing the location(s) at which you can build this outpost.

### Katydid III (Indicite)

Design:

- Wind Turbine - Advanced (14 power)
- Extractor - Solid (indicite)
- Storage - Solid - Large (indicite)
- Cargo Link - Inter-system (indicite to Grimsey)
- Landing Pad - Small

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Comm Relay: 1
  - Isocentered Magnet: 2
  - Reactive Gauge: 3
- Solid
  - Aluminum: 45
  - Iron: 65
  - Tungsten: 2

Location:

Only one resource being collected here, just find somewhere you like that has indicite.

### Dalvik (Caesium)

Design:

- Landing Pad - Small
- Cargo Link (caesium to grimsey)
- 2 Solar Dome (4 power)
- 1 Extractor - Liquid (caesium)
- 1 Storage - Liquid - Large (caesium)

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Tau Grade Rheostat: 4
  - Zero Wire: 2
- Solid
  - Aluminum: 53
  - Beryllium: 2
  - Iron: 43
  - Nickel: 20

### Decaran VII-b (Vytinium)

- Landing Pad - Small
- 2 Solar Dome (4 power)
- Extractor - Solid (vytinium)
- Storage - Solid - Large (vytinium)
- Cargo Link - Inter-system (vytinium to grimsey)

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Comm Relay: 1
  - Reactive Gauge: 3
  - Tau Grade Rheostat: 4
- Solid
  - Aluminum: 48
  - Iron: 65
  - Tungsten: 2

Location: Not important, you should be able to fully survey the planet on one landing. Here's a [Reddit post](https://old.reddit.com/r/Starfield/comments/17nbhmt/anyone_able_to_point_me_to_a_four_resource/k85fhn8/) purporting to show a site with all four resources available.

### Carinae III-a (Rothicite)

Design:

- Landing Pad - Small
- Solar Dome (8 power)
- Extractor - Solid (rothicite)
- Storage - Solid - Large (rothicite)
- Cargo Link - Inter-system (rothicite to Schroedinger VIII-e)

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Comm Relay: 1
  - Reactive Gauge: 3
  - Tau Grade Rheostat: 2
- Solid
  - Aluminum: 44
  - Iron: 65
  - Tungsten: 2

Location:

Any rothicite-rich area will do.

### Huygens VII-a (Tasine)

Design:

- Landing Pad - Small
- Extractor - Liquid (tasine)
- Storage - Liquid - Large (tasine)
- Solar Dome (8 power)
- Cargo Link - Inter-system (tasine to Shoza VIII-b)

Materials:

- Manufactured
  - Adaptive Frame: 10
  - Comm Relay: 1
  - Reactive Gauge: 3
  - Tau Grade Rheostat: 2
- Solid
  - Aluminum: 49
  - Iron: 43
  - Nickel: 20

Location:

Any tasine-rich area.

### Shoza VIII-b (tasine superconductor)

Design:

- Reactor
- Cargo Link - Inter-system (tasine from Huygens VII-a)
- 1 Storage - Liquid - Large (tasine)
- 1 Warehouse - Large (tasine superconductor)
- Multiplex Fabricator (tasine superconductor)

Materials:

- Manufactured
  - Adaptive Frame: 26
  - Comm Relay: 1
  - Control Rod: 3
  - Nuclear Fuel Rod: 8
  - Paramagnon Conductor: 4
  - Positron Battery: 3
  - Reactive Gauge: 3
  - Supercooled Magnet: 5
  - Tau Grade Rheostat: 3
- Solid
  - Aluminum: 52
  - Iron: 20
  - Lead: 10
  - Lubricant: 6
  - Nickel: 16
  - Polymer: 8
  - Titanium: 24

### Grimsey (Vytinium Fuel Rod)

Design:

- 2 Cargo Link - Inter-system (vytinium from decaran vii-b, indicite from katydid iii)
- 2 Storage - Solid - Large (indicite, vytinium)
- 1 Cargo Link (caesium from dalvik)
- 1 Storage - Liquid - Large (caesium)

Materials:

- Manufactured
  - Adaptive Frame: 30
  - Comm Relay: 2
  - Reactive Gauge: 6
  - Zero Wire: 2
- Solid
  - Aluminum: 88
  - Beryllium: 2
  - Iron: 100
  - Nickel: 16

### Grimsey (storage expansion)

By selling to all the Trade Authority vendors and the Red Mile bartender we should be able to clear 500 VFR sales per trip. As such, all storage is scaled to produce 500 VFR in one go. You can sell much more each trip if you are willing to visit each individual vendor.

Design:

- 8 Storage - Solid - Large (Vytinium)
- 7 Storage - Solid - Large (Indicite)
- 2 Storage - Solid - Large (Plutonium)
- 2 Storage - Solid - Large (Uranium)
- 17 Warehouse - Large (semimetal wafers)
- 3 Storage - Solid - Large (Iridium, Vanadium, Solvent)
- Storage - Liquid - Large (caesium)

Materials:

- Manufactured
  - Adaptive Frame: 400
- Solid
  - Aluminum: 712
  - Iron: 440
  - Nickel: 16
  - Titanium: 272

## Mass Production Upgrades

From here, I chose to upgrade all the feeders to Grimsey to allow producing 500 Vytinium Fuel Rods every two days (the reset period for merchants).

If you skipped the production lines for Aldumite Drilling Rig and Veryl-Treated Manifold, important vendors to visit are the ones that might sell Aldumite Drilling Rig and Veryl-Treated Manifold:

- Outland, New Atlantis commercial district
- Clint's, Gagarin Landing
- UC Exchange, Cydonia
- Sieghart, Neon
- Shepherd, Akila City
- Trader
- Zuri and Isra, The Key

The basic upgrade process for all production sites is:

- Expand local storage to hold production inputs and outputs to meet desired production target (in this example, 500 Vytinium Fuel Rods every 48h UT)
- Assess production rates
- Improve production to fill local storage in two days (with some slack due to hauling time meaning local production can catch up)

### Cruth: Production Rates and Passage of Time Walkthrough

In Starfield there are multiple ways to pass time. One is to just watch the screen for a while as real time and game time advance, another is to sit on a chair and wait, and another option is sleeping in a bed. Time will also pass when taking actions like grav-jumping or fast travelling.

#### Real Time to UT Ratio

Right up front, let's establish how time passes when just playing the game. This one's pretty simple: look at the clock in-game, then spend 10 minutes doing normal gameplay loop without opening menus, fast travelling, switching out of the game, or otherwise leaving the player character.

For my example I just started a 10 minute timer and wandered around enjoying the scenery. On Grimsey and Cruth, 10 minutes of real time translated to 2.5h of UT, or 150 minutes, so 1 minute of real time is 15 minutes of UT. Working the other way, 48h of UT is 192 minutes of real time (3h12m).

Can we verify this experimentally in-game through another means?

#### Assay Lab - Observing Production over Time

To verify the intial passage of time estimate, let's look at production rates.

Build an "assay lab" which in game is going to simply be extractors, storage, and a chair. What we'll be examining is how the time that passes maps to amount of material produced. Then we work backwards to see how much extra production will be needed to meet the 48h production requirement.

For established bases you can use the existing storage - for this assay the only quantity of interest is volume of production over time, so anything about the base that affects production per unit time (or more specifically, time per unit production) is not of concern - we'll look at production rate calculations later.

In my case I monitored the quantity of materials in the cargo link outgoing container at Dalvik (Caesium, 5 Extractor - Caesium):

- 15:26, 10
- 16:07, 8
- 16:48, 11
- 17:29, 11

This freighter (a cargo-link in the same system) had a round trip time of 41 minutes UT. I don't know the period of time it took to accumulate 10 units for that initial shipment, but we do have a start time for the second interval. The total time here was 123 minutes, with the three shipments in that time being 30 units. Thus at this rough level the estimate of production at Dalvik is 0.24 Caesium/minute, roughly 14.6 Caesium per hour.

Next comes waiting on a chair. Record the quantity in storage, then wait for a couple of hours UT - how long exactly depends on the local planet hour to UT ratio. For Dalvik with 1 local hour representing 21h59m UT, and a production rate of 14.6 per hour I'd expect to see 321 Caesium in the container at the end of a "1 hour of Dalvik time" wait. Also consider the local storage capacity, where in this case the storage capacity is 300kg, Caesium is 0.8kg per unit, so that 321 units of Caesium should be 257kg which is well within the mass capacity of the container.

After waiting on a chair for 1 Dalvik hour, from 21:29 local (17:48UT) till 22:29 local (15:48UT) I found 324 Caesium in the cargo link outgoing container. I really should expand my maths knowledge include proper error estimation, but to me the amount I found was within a couple of units of the expected result so I'm happy.

At this point we've established that production over time is the same while we are visiting that outpost regardless whether we're waiting in real time or speeding up the passage of UT by "waiting" on a chair.

Next we'll do the same experiment at Grimsey.

The plan for Grimsey is to look at the storage for Caesium when the freighter arrives, wait approximately 20h, then wait in real time while the freighter fetches the Caesium waiting at Dalvik and delivers it to Grimsey. Will the amount change because my character is not at the Dalvik outpost to influence production rates?

The longest I can wait at Grimsey is 14h21m, which translates to 861 minutes, so I'll expect the next freighter to deliver around 207 Caesium (861 x 0.24).

Before waiting, there were three tanks containing 375, 374, and 202 Caesium (total 951). With the next delivery there should be three full containers (~374) and one container with 35 Caesium.

Unfortunately, this was not the case. What ended up arriving was 143 Caesium. Over the next few deliveries the quantity of Caesium was:

- 345 (starting)
- 355 (9 delivered)
- 365 (10 delivered)
- 375 (10 delivered, no overflow)
- 11 (11 delivered)

The amounts delivered look to be the same as the amounts that were shipped while observing at Dalvik, so where is the difference creeping in?

Repeating the wait, with 11 Caesium in the last container, how much do we have when the freighter returns? 150 units (including 11 already there, so 139). Where did I go wrong? 139 represents 2/3 the expected quantity, yet the deliveries were within 10%.

Cargo links work in real time, while production happens in UT. If you sleep for a couple of days all the production sites will fill up with materials, then the freighters will start hauling materials between cargo links once you wake up. This means you need adequate storage at both ends of each cargo link: storage for 500 semimetal wafers at Grimsey will also require storage for 500 semimetal wafers at Cruth. There is room for some slack since the freighters will take time to move materials, and that time can be enough for the production site to replenish stocks.

In detail, expanding local storage means working back from the 500 Vytinium Fuel Rod target to find how much of each component and thus raw material is required (these numbers are not modified by skills):

- 500 Vytinium Fuel Rods (no storage, XP grind crafting, but 500 will be 5500kg)
  - 500 Indicite Wafer (no storage directly, the XP grind involves building these for XP)
    - 500 Caesium (800kg, 3 Storage - Liquid - Large)
    - 1000 Indicite (4600kg, 16 Storage - Solid - Large)
    - **500 Semimetal Wafer** (1750kg, 6 Warehouse - Large)
      - 1000 Antimony (800kg, 3 Storage - Solid - Large)
      - 1000 Gold (800kg, 3 Storage - Solid - Large)
      - 500 Zero Wire (850kg, 3 Warehouse - Large)
        - 500 Copper (300kg, 1 Storage - Solid - Large)
        - 500 Silver (300kg, 1 Storage - Solid - Large)
    - 500 Solvent (500kg, 2 Storage - Solid - Large)
  - 500 Nuclear Fuel Rod (no storage directly, as above)
    - **500 Semimetal Wafer** (another 6 Warehouse - Large)
    - 1000 Solvent (another 2 Storage - Solid - Large)
    - 1500 Uranium (1050kg, 4 Storage - Solid - Large)
  - 1000 Plutonium (1600kg, 6 Storage - Solid - Large just for plutonium)
  - 2000 Vytinium (5000kg, 17 Storage - Solid - Large just for vytinium)

Most extraction sites will benefit from an Advanced Reactor or two. It can be easier to simply add more extractors rather than upgrading to industrial extractors, since industrial extractors require 20 power which is four times a normal extractor, but they only deliver double the material over time. Switch to the industrial extractors when you run out of space for regular extractors. The same goes for greenhouses and animal husbandry facilities.

### Passage of Time Tutorial

From that 1000 Semimetal Wafer in 2 days figure, work back from the 12 warehouses full of Semimetal Wafer that are required, and build those warehouses at Grimsey and at Cruth. Then over at Cruth scale up the production chain to be able to build 1000 Semimetal Wafers in 48 hours UT (480 minutes game time, so 2.1 wafers per minute of play time). Note that production happens when you sleep or wait, but cargo links operate in "real time". Once you rest for 2 days the storage at Cruth will fill up, then the cargo links will bring the wafers to Grimsey at which point you'll be able to run through the manufacturing chain.

- 1000 Semimetal Wafers (2.1 per minute, 12 Warehouse - Large)
  - 2000 Antimony (4.2 per minute, 6 Storage - Solid - Large)
  - 2000 Gold (4.2 per minute, 6 Storage - Solid - Large)
  - 1000 Zero Wire (2.1 per minute, 6 Warehouse - Large)
    - 1000 Copper (2.1 per minute, 2 Storage - Solid - Large)
    - 1000 Silver (2.1 per minute, 2 Storage - Solid - Large)

Silver is produced elsewhere, so kick that can down the road.

#### Extractor Speed

This is where I get confused. Time seems to behave differently when you are standing around in an outpost versus when you are sleeping/waiting.

The locally extracted resources are Copper, Antimony and Gold. For each resource set up an independent extractor and storage, and see how much product appears after 10 minutes of real world time. My results include 31 gold, or 3 per minute (about 1 every 19 seconds). Then if I sleep for 1h local (3h UT) there will be 18 gold in the storage. If I then wait for 18 gold to appear, that will take about 6 minutes which is about 1.5h UT.

Noting with the gold that it took 6 minutes to accumulate 20 gold at approximately 19 seconds each unit.

Now it's a simple matter of dividing the desired rate by the rate per extractor then round any fractional extractor up to the next whole:

- Antimony 42/1.5 = 28
- Copper 21/3.7 = 5.676, round up to 6
- Gold 42/1.87 = 22.45, round up to 23

That's a lot of extractors. The number can be reduced slightly by using Sanitation Mini Bots to increase the production rate of inorganic resources by 10% (multiplicative, so 3 Sanitation Mini Bots will increase production by 33%), and assigning [Lin][INARALIN] to this outpost. This could trim the number of Antimony extractors required from 28 to 22. A further reduction could come from using industrial extractors, bringing that total down to 11. That's still 220 power required just for the Antimony extractors at this site!

Remember that the numbers in this section are indicative and will vary based on character skill, companions, robots, and glitches.

It may be useful to deploy in stages, bringing 1/4 of the total build online at any time: 1 advanced reactor, a few extractors, a few containers.

Design:

- 5 Reactor - Advanced
- 11 Extractor - Solid - Industrial (Antimony)
- 6 Extractor - Solid (Copper)
- 9 Extractor - Solid - Industrial (Gold)
- 6 Sanitation Mini Bot
- 18 Warehouse - Large (12 Semimetal Wafers, 6 Zero Wire)
- 16 Storage - Solid - Large (6 Antimony, 6 Gold, 2 Copper, 2 Silver)
- Four Wall Hab - Double
- Hab Round
- Hydroponic Hab Round
- Outpost Airlock
- 3 Crew Station

Materials:

- Manufactured
  - Adaptive Frame: 440
  - Aldumite Drilling Rig: 20
  - Control Rod: 25
  - Isotopic Coolant: 80
  - Power Circuit: 15
  - Rothicite Magnet: 25
  - Tasine Superconductor: 20
  - Vytinium Fuel Rod: 40
- Solid
  - Aluminum: 640
  - Iron: 350
  - Lead: 100
  - Titanium: 288
  - Tungsten: 132

### Decaran (extraction upgrade)

Producing 500 VFR every 48 hours requires 2000 Vytinium every 48 hours. A useful metric is the time it takes the freighter to travel back and forth which is about three minutes of real time, or about 30 min UT. Per-minute production is 2000 / 48 / 6, with 3 minutes between freight runs so 21 Vytinium per freighter.

Time to build an assay lab. This is simply going to be an industrial extractor feeding independent storage. Connect them together and watch the container for 10 minutes to get an initial estimate for production rate. Then empty the container and sleep for long enough to almost fill the container. Let's build the lab and then walk through the assay process.

Design:

- Reactor - Advanced
- Extractor - Solid - Industrial (vytinium)
- 2 Storage - Solid - Large (vytinium)

Materials:

- Manufactured
  - Adaptive Frame: 15
  - Aldumite Drilling Rig: 1
  - Control Rod: 5
  - Isotopic Coolant: 4
  - Power Circuit: 3
  - Rothicite Magnet: 5
  - Tasine Superconductor: 4
  - Vytinium Fuel Rod: 8
- Solid
  - Aluminum: 16
  - Iron: 20
  - Lead: 20
  - Tungsten: 6

For my experiment, the industrial extractor was producing 3 Vytinium per minute (10min UT). Vytinium has 2.5kg mass, which means about 120 will fit into a large storage container. At Decaran, 1 local hour is 45.5h UT, so resting for 1 local hour should mean the storage ends up containing 45.5 x 3 x 6 or roughly 810 vytinium, give or take.

I rested for 1 Decaran hour and came back to 425 units of vytinium. Something is wrong with those calculations, but what? It looks like 1 minute real time is 10 minutes UT, not 1h.

### Codos (production upgrade)

Set up an assay lab. Do the usual 10 minute observation. Then calculate required build-out on the basis of producing 500 solvent every 48h, roughly 11/h or 6 per freighter run.

Design:

- Wind Turbine - Advanced (power:14)
- Extractor - Liquid (water)
- Storage - Liquid - Large (water)
- Greenhouse (solvent)
- Storage - Solid - Large (solvent)

Materials:

- Manufactured
  - Adaptive Frame: 25
  - Isocentered Magnet: 2
  - Reactive Gauge: 3
- Solid
  - Aluminum: 46
  - Iron: 23
  - Nickel: 20
  - Sealant: 3
- Gas
  - Fluorine: 4

In my run, the greenhouse was producing 1 solvent every 1m25s (4.8/h UT). To get Codos to industrial level production in my game I should need two and a bit greenhouses.

## Restocking Quick Reference

In my playthroughs I had a home base - typically Bessel III-b or Serpentis IV - which I would keep stocked manually because there's no way to keep all the materials stocked using cargo links. I would look at each fabricator and ensure it had plenty of working stock with. If anything ran out, I'd go fetch new material. Here's my quick reference for where to get the materials I commonly use:

- Copper, Sealant, Ionic Liquid, Isotopic Coolant from Procyon III
- Lead, Lithium from Schrodinger VIII-e
- Europium from Androphon
- Alkanes, Lubricant, Tantalum, Titanium, Tungsten from Alpha Tirna VIII-c
- Vanadium from Grimsey

## Other Sites

Here are some sites I had built out at some point but can't bear to remove from this document.

### Leviathan II (He3/Be/Eu/Nd)

I found Leviathan II outpost hard to reproduce, so rather than condemn future readers to spending several hours just finding the spot for one outpost we'll archive this plan.

Design:

- Landing Pad - Small
- 4 Solar Dome (16 power)
- Extractor - Solid (beryllium)
- Storage - Solid - Large (beryllium)
- Extractor - Solid (europium)
- Storage - Solid - Large (europium)
- Extractor - Solid (neodymium)
- Storage - Solid - Large (neodymium)
- 8 Extractor - Gas (He3)
- Storage - Gas - Large (He3)
- Cargo Link - Inter-system (He3 to Bessel III-b)
- Cargo Link - Inter-system (He3 to Grimsey)

Bill of Materials:

- Manufactured
  - Adaptive Frame: 40
  - Comm Relay: 2
  - Reactive Gauge: 6
  - Tau Grade Rheostat: 8
- Solid
  - Aluminum: 148
  - Copper: 44
  - Iron: 135
  - Nickel: 32
  - Tungsten: 22

Location:

It's possible to find a location here with Al/Be/Eu/He3/Nd, but it feels like the "Craters" biome on Leviathan II is actually three separate biomes of Craters with beryllium, Craters with aluminium and He3, and Craters with neodymium/europium. They do mix but generally speaking He3 is harder to find where Europium is easier to find and vice versa. I don't know if it's just confirmation bias but it seems to me that some terrain is slighly shinier and paler than the neighbouring terrain and that's the biome with Europium and Neodymium. YMMV.

<p>
<img src="images/leviathan-ii-location-map.jpg" alt="Map of Leviathan II with resources shown. There is a marker for the location of the outpost." width="40%">
<img src="images/leviathan-ii-location-landscape.jpg" alt="The landscape at the landing site on Leviathan II intended to help players find the location once they have landed." width="40%">
<a href="images/leviathan-ii-outpost-landscape.jpg" target="_maps"><img src="images/leviathan-ii-outpost-landscape.jpg" alt="The landscape at the outpost site on Leviathan II intended to help players find the location once they have landed. Approx 870m slightly south of East from the landing site." width="40%"></a>
</p>

## References

- [Starfield Unlimited Storage & Automated Resources Guide][UNLIMSTOR]
- [Starfield Outpost Guide: Simplified Cargo Lnks & Gameplay Tips](https://www.youtube.com/watch?v=Vge2y-58lvk&list=PLgrQb2fZ1SEcQaD1Fw9g2Eq6ZjwrjixIU)
- [Starfield Outpost Guide: Simplified Cargo Links Inter System](https://www.youtube.com/watch?v=8aqUsuJJhN4&list=PLgrQb2fZ1SEcQaD1Fw9g2Eq6ZjwrjixIU&index=12)
- [Beginner's Guide to Outpost Building](https://www.youtube.com/watch?v=0CdDCPKychU)
- MattGyver [Starfield Outpost Pocket Reference](https://www.mattgyver.com/starfield-outpost)
- MattGyver [Starfield System Starmap v6](images/Starfield-System-Starmap-v6.png)
- MattGyver [Starfield Manufacturing Flow Diagrams](https://www.mattgyver.com/tutorials/2024/2/15/starfield-manufacturing-flow-diagrams)
- [Rafael character page][INARARAFAEL]
- [Lin character page][INARALIN]
- [Heller character page][INARAHELLER]
- [Andromeda character page][INARAANDROMEDA]

[INARAANDROMEDA]: https://inara.cz/starfield/companion/22/
[INARAHELLER]: https://inara.cz/starfield/companion/5/
[INARALIN]: https://inara.cz/starfield/companion/14/
[INARARAFAEL]: https://inara.cz/starfield/companion/62/
[UNLIMSTOR]: https://www.youtube.com/watch?v=4PpCgF9RtY4
