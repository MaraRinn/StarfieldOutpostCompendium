# Miscellany

Some things to mention before we get into the body of this guide.

## Broken Skills

Outpost Management will stop working when you transition to the next NG+. The current workaround requires console commands, disabling achievements:

1. player.removeperk 0023826F
2. player.addperk 0023826F (once for each level)

You can get by without Outpost Management 4 but the industrial expansions for Advanced Reactor Production (specifically the Vytinium Fuel Rod produciton line) require more than 3 cargo links for a few key hubs.

## Nice Outpost Habitat

Here's a standard habitat I like to install just for the RP flavour. It has a two-storey hab from which two round habs are joined, stacked on top of each other. One hab is the "accommodations" and the other ("hydroponic" glass-walled hab) will be the observation deck.

- Four Wall Hab - Double
- Hab Round
- Hydroponic Hab Round
- Outpost Airlock
- 3 Crew Station
- 3 Bed 10
- Landing Pad - Small

Materials:

- Aluminium: 82 (41kg) small storage
- Iron: 41 (25kg) small storage
- Nickel: 27 (17kg) small storage
- Lead: 20 (14kg) 2 storage box
- Sealant: 16 (8kg) 2 storage box
- Fiber: 36 (18kg) 2 storage box
- Structural: 48 (25kg) 3 storage box

When positioning the Four Wall Hab - Double, make sure to use the trapezoid on top as an arrow to point to where the view is, the short side of that trapezoid marks the side where the stairs meet the top storey. Then join the round habs on to that side of the Four Wall Hab - Double. Now add the airlock where it will fit on the Four Wall Hab - Double.

## Containers

Containers that can be included in storage chains:

- Storage Box (10kg) (2,3)
- Warehouse (60kg)
- Storage Crate (157kg) (2)
- Warehouse - Medium (157kg)
- Warehouse - Large (300kg)

When crafting at a workbench you can not pull resources from the storage boxes or storage crates, only the Storage and Warehouse components (along with personal inventory and home ship inventory if it is within 250m).

### Measured Components for Cargo Link - Inter-system

This is a simple idea for pre-measuring the amounts of materials required for common outpost items.

- 12 Aluminium (6kg) Storage Box
- 1 Comm Relay (3.5kg) Storage Box
- 20 Iron (12kg) 2 Storage Box
- 3 Reactive Gauge (4.5kg) Storage Box

Put those storage boxes on a table, link them into the production chain to receive the materials, then any time you want to build inter-system cargo links just grab the contents of those boxes and you're set!

## Estimating Structures Required for Production Rates

Each producer structure has a certain rate of production, and those that take inputs will have their own rate of consumption. As an example, extractors will vary the quantity produced and the time between outputs based on character skills, material being extracted, and extractor tier.

To estimate the structures required to meet certain production rates, first measure the actual production:

1. Build the required power supply including a Powered Switch
2. Wire the power supply to the Powered Switch and turn it off
3. Build the required storage for inputs and outputs
4. Build a producer with any required input and output storage connected
5. Supply the appropriate inputs (just fill up the input storage)
6. Start a 10 minute timer
7. Switch the Powered Switch on
8. When the timer expires, turn the switch back off

Now you have an estimate of ten hours of production and consumption (1 minute real time is 1 hour UT in-game). Note that a more accurate method would be to use a stopwatch and record "lap times" as each batch of material is produced, but this requires watching the screen for ten minutes whie doing nothing else. I'm lazy so I go for the units produced in a fixed period of time, rather than the time between produciton of units.

NB: **you can not do anything else during the sample interval**. Checking character screen, inventory, switching to other programs or even letting your computer sleep will all interrupt the production chain. Just be near the computer and waggle the mouse or wobble the controller stick every now and then to keep the computer awake and the game running.

### Worked example: Greenhouse producing fiber

Design:

- Wind Turbine
- Greenhouse
- Storage - Liquid - Large (water)
- Storage - Solid - Large (fiber)
- Powered Switch

Materials:

- Adaptive Frame: 25
- Aluminum: 43
- Cobalt: 2
- Copper: 2
- Fluorine: 4
- Iron: 20
- Nickel: 19
- Reactive Gauge: 3
- Sealant: 3

Connect these as Liquid storage -> Greenhouse -> Solid Storage, then wire the turbine to the powered switch and wire the powered switch to the greenhouse.

Storage state:

- 59 water
- 0 fiber

Start the 10 minute timer, turn the power on.

At 10 minutes turn the power off.

Storage state:

- 42 water (- 17 water)
- 17 fiber (+ 17 fiber)

This works out to roughly 1.7 fiber per minute, or  1 fiber every 35 seconds, with a 1:1 conversion rate from water to fiber. As your production rate increases, the game reduces the time between each batch of production.

In other experiments I have determined that **water extractors** produce the following amounts in 10 minutes real time:

- Extractor: 18
- Commercial: 42
- Industrial: 68

So for a base level greenhouse, slightly more than one water extractor per greenhouse is sufficient water supply.

*These figures will all change as you add robots and crew, so make sure you perform the tests every time you change robot or crew assignments*.

### Worked Example: Animal Husbandry Facility producing membrane

This experiment took place on Serpentis IV.

Design:

- Wind Turbine (25 power)
- Storage - Liquid - Large (water)
- 2 Storage - Solid - Large (fiber, membrane)
- Animal Husbandry Facility (membrane)
- Powered Switch

Materials:

- Manufactured
  - Adaptive Frame: 35
  - Reactive Gauge: 3
- Solid
  - Aluminum: 67
  - Cobalt: 2
  - Copper: 2
  - Iron: 40
  - Nickel: 19
  - Sealant: 3

Method:

- Build the components (animal husbandry facility, liquid storage for water, solid storage for fiber, solid storage for membrane, powered switch, wind turbine)
- Hook up water and fibre to animal husbandry facility
- Hook up animal husbandry facility to empty storage for membrane
- Wire powered switch to animal husbandry facility
- Wire the wind turbine to the powered switch
- Ensure the powered switch is off (no power to the production facility)
- Fill the input containers with water and fibre respectively
- Empty the output container
- Records the quantities of materials in each container
- Start a 10 minute timer and turn the powered switch on
- At the expiry of the 10 minute timer, turn the powered switch off
- Record the quantities of materials in each container

Results:

- Start
	- 600 water
	- 594 fiber
	- 0 membrane
- End
	- 590 water
	- 574 fiber
	- 10 membrane

Conclusion:

The Animal Husbandry Facility consumes 1 water, 2 fibre each minute to produce 1 membrane.

Based on previous results with water extractors, 1 water extractor is almost enough to provide water for 2 animal husbandry facilities (18 produced vs 10 consumed over the 10h game time), but each AHF requires more than 1 greenhouse producing fiber (17 produced vs 20 consumed).

### Worked Example: Lithium Extractors

This experiment took place on Serpentis IV.

Design:

- 2 Reactor
- 1 Extractor - Solid
- 1 Extractor - Solid - Commercial
- 1 Extractor - Solid - Industrial
- Powered Switch
- 3 Storage - Solid

Materials:

- Manufactured
  - Adaptive Frame: 29
  - Aldumite Drilling Rig: 1
  - Control Rod: 6
  - Drilling Rig: 1
  - Isotopic Coolant: 6
  - Nuclear Fuel Rod: 16
  - Paramagnon Conductor: 8
  - Supercooled Magnet: 10
  - Tau Grade Rheostat: 6
- Solid
  - Aluminum: 21
  - Copper: 2
  - Iron: 23
  - Lead: 20
  - Tungsten: 12

Method:

- Build the components
- Wire the reactors to the switch and the switch to the extractors
- Turn the switch off
- Connect the extractors to their own storages
- Empty the storage and extractors
- Start a 10 minute timer and switch the power on
- At the conclusion of the timer, turn the power off
- Record the volume of lithium produced
 
Result:

- Standard: 18
- Commercial: 22
- Industrial: 36

## Storage Requirements

![An example layout of various storages in roughly the proportions used for one game](<images/arrangement of storage.jpg>)

Mineral Solids (small/medium unless otherwise specified, 30):

- Aldumite
- Aluminum (large)
- Antimony
- Aqueous Hematite
- Beryllium
- Caelumite
- Cobalt
- Copper (large)
- Dysprosium
- Europium
- Gold
- Indicite
- Iridium
- Iron (large)
- Lead
- Lithium
- Neodymium
- Nickel
- Palladium
- Platinum
- Plutonium
- Rothicite
- Silver
- Tantalum
- Titanium
- Tungsten
- Uranium
- Vanadium
- Vytinium
- Ytterbium

Organic Solids (31):

- Adhesive
- Amino Acids
- Analgesic
- Antimicrobial
- Aromatic
- Biosuppressant
- Cosmetic
- Fiber
- Gastronomic Delight
- Hallucinogen
- High-Tensile Spidroin
- Hypercatalyst
- Immunostimulant
- Lubricant
- Luxury Textile
- Membrane
- Memory Substrate
- Metabolic Agent
- Neurologic
- Nutrient
- Ornamental Material
- Pigment
- Polymer
- Quark-Degenerate Tissues
- Sealant
- Sedative
- Solvent
- Spice
- Stimulant
- Structural Material
- Toxin

Liquids (7):

- Caesium
- Carboxylic Acids
- Chlorosilanes
- Ionic Liquids
- Mercury
- Tasine
- Water

Gasses (10):

- Alkanes
- Argon
- Benzene
- Chlorine
- Fluorine
- Neon
- Tetrafluorides
- Veryl
- Xenon

Warehouses (1 large, 28 small):

- Adaptive Frame (large)
- Aldumite Drilling Rig
- Austenitic Manifold
- Comm Relay
- Control Rod
- Drilling Rig
- Indicite Wafer
- Isocentered Magnet
- Isotopic Coolant
- Mag Pressure Tank
- Microsecond Regulator
- Molecular Sieve
- Monopropellant
- Nuclear Fuel Rod
- Paramagnon Conductor
- Polytextile
- Positron Battery
- Power Circuit
- Reactive Gauge
- Rothicite Magnet
- Semimetal Wafer
- Sterile Nanotubes
- Substrate Molecule Sieve
- Supercooled Magnet
- Tasine Superconductor
- Tau Grade Rheostat
- Veryl-Treated Manifold
- Zero Wire
- Zero-G Gimbal

## Crew Skills

Outpost Engineering increases manufacturing line production by 10/20/30/30%:

- [Heller][INARAHELLER] 30%
- [Andromeda][INARAANDROMEDA] 20%
- [Rafael][INARARAFAEL] 10%

Outpost Management increases production of resources by 5/10/15/15%:

- [Lin][INARALIN] 15%
- [Rafael][INARARAFAEL] 5%

