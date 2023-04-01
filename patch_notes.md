# Version 1.6.0

## General tweaks

### Nerfs
 * Unholy Matrimony Event (Necrophage and Fanatical Purifier): -25% purge speed penalty to all players (AIs not included)
 * STARBASE_CAPACITY_BASE: 2 from 3
 * STARBASE_CAPACITY_SYSTEM_MULT: 0.08 from 0.1
 * Starbase overcapacity upkeep penalty: +35% from +25%
 * Espionage Operations: difficulties reduced by 4
 * LEADER_AGE_DEATH_CHANCE_AGE: 75 from 80
 * LEADER_AGE_HIGH_DEATH_CHANCE_AGE: 95 from 100

### Boosts
 * Be careful out there (anti-rush event): All players (AIs not included) start with a passive -60% defense platform build cost and +15% starbase damage boost for the first 20 years of the game.

## AI exploitation

## Nerfs
 * Anti-AI Trade exploits:
   * FAVOR_CAP: 5 from 10
   * TRADE_VALUE_FAVORS_MULT: 5 from 10
   * RESEARCH_AGREEMENT_ACCEPTANCE_OPINION_FACTOR: 0.3 from 0.4
   * RESEARCH_AGREEMENT_ACCEPTANCE_NUM_PACTS: -40 from -30
   * RESEARCH_AGREEMENT_ACCEPTANCE_GIVEN_TECHS: -0.6 from -0.5
   * RESEARCH_AGREEMENT_SPEED_MULT: 0.15 from 0.25
   * TRADE_MIN_RESOURCE_STOCKPILE: 1000 from 500
   * TRADE_VALUE_RESOURCE: 1.5 from 2.0
   * TRADE_VALUE_SENSOR_CHARTS: 1 from 2
   * TRADE_VALUE_SENSOR_LINK_MAX: 0.75 from 1.0
   * EMBASSY_IMPROVE_RELATION_MULTIPLIER: 2.0 from 3.0
   * MIN_WILLINGNESS_TO_OFFER_TRADE: 0.85 from 0.75
   * Be careful out there (anti-ai exploit event): All players (AIs not included) start with a -50% penalty to envoy relationship improvements for 20 years, UNLESS they are
     * Government: Megacorporations
     * Ethic: Xenophile
     * Civics: Diplomatic Corps or Empath
 * Anti-AI vassal exploits:
   * NEGOTIATE_AGREEMENT_ACCEPTANCE_OPINION_FACTOR: 0.20 from 0.333
   * NEGOTIATE_AGREEMENT_RESOURCE_ACCEPTANCE_COEFICIENT_FOR_OVERLORD: 2.0 from 1.0

## Boosts
 * None

## Leader level cap

### Nerfs
 * Base Leader skill cap: 2 from 5
 * Meritocracy: leader cap level +0 from +1

## Boosts
 * Supremacy (War Games): General leader cap level +2
 * Unyielding (Adoption): General leader cap level +2
 * Venerable: +1 starting level to leaders
 * Quick Learners: +35% to leader leveling speed from +25%
 * Learning Algorithms: +35% to leader leveling speed from +25%
 * Generals:
   * Gain 25 experience every year
   * Gain 2 times more experience from a battle
   * GENERAL_DEATH_CHANCE: 0.01 from 0.05, Chance of dying from a battle more in line with that of Admirals. Note there is a bug where Generals die instantly if a unit dies from bombardment.
   * 5% army morale per level
   * 2.5% disengage chance per level
   * 5% army health per level
 * Admirals:
   * 1% ship speed per level
   * 2% ship hull per level
   * 1% ship evasion per level
   * 2% ship weapon damage per level
 * Scientists:
   * 3% research speed from 2% per level
   * 15% survey speed from 10% per level
   * 2 archaeological clues from 1 per level
 * Governors:
   * 3% job production from 2% per level
   * -3% population empire size from -2% per level
   * -4 crime from -3 per level
 * Ruler:
   * 0.5 planet stability per level
   * 5% diplomacy weight per level

## Ships

### Nerfs
 * Jump Drive:
   * Prethoryn and Contingency can now spawn if Jump Drives researched. Jump drives also increase the odds of the crisis spawning sooner from 19% to 37%.
   * Range decreased by 25%
   * Jump drive penalty increased to -60% to weapons/movement from -50%

### Boosts
 * none

## Ethics

### Nerfs
 * Materialist: 4%/8% research bonus from 5%/10%
 * Xenophobe: 8%/16% pop growth from 10%/20%

### Boosts
 * None

## Ascension Perks

### Nerfs
 * Technological Ascendency: +6% Research rate from +10%
 * Become the crisis: requires 3 ascension perks from 2 and requires Enigmatic Engineering perk
 * Hive World: Energy cost 11000 from 10000
 * Machine World: Energy cost 11000 from 10000
 * Arcology Project: requires 3 Ascension perks from 2
 * Executive Vigor: +80 edict funds from +100

### Boosts
 * Enigmatic Engineering: +4 encryption from +2 and ascension perks required dropped to 0 from 1
 * Galactic Force Projection: +5% sublight speed
 * Consecrate Worlds: Can now consecrate an occupied world

## Standard Civics

### Nerfs
 * Fanatical Purifier: 23% ship fire rate from 33%
 * Technocracy: -5% to Naval Capacity, -5 Naval Capacity, +5% to ship cost and -5% to ship build speed

### Boosts
 * Free Haven: +20% pop growth from immigration from 15% and 60% immigration pull from 50%
 * Warrior Culture: Duelists give +3 unity from +2
 * Catalytic Converter: Catalytic Technicians require 8 food from 9
 * Merchant Guilds: +1 Envoy and +3% Trade value

## Hive Mind Civics

### Nerfs
 * Ascetic: -10% amenities usage from -15%
 * Devouring Swarm: +50% market fee penalty

### Boosts
 * Catalytic Converter: Catalytic Drones require 8 food from 9

## Robot Civics

### Nerfs
 * Driven Assimilator: 3 pop per year assimilation speed from average of 7
 * Rogue Servitor: Bio Trophies produce +2 unity from +3 and 0.8% complex drone output boost from 1%
 * Determined Exterminator: +50% market fee penalty

### Boosts
 * Zero-waste Protocols: -20% robot upkeep from -10%
 * Static Research: +2 decryption from +1
 * Catalytic Converter: Catalytic Drones require 8 food from 9

## Megacorp Civics

### Nerfs
 * Free Traders: +8% trade value from +10%
 * Indentured Servitude: +8% slave output from +10%

### Boosts
 * Media Conglomerate: +10% diplomatic weight and -10% war exhaustion from -5% war exhaustion
 
## Origin:

### Nerfs
 * Prosperous Unification: +10% happiness from +15%
 * Scion: -5% happiness and -20% Ethics attraction
 * Imperial Fiefdom origin: -5% happiness, -20% Ethics attraction and Overlord starting opinion bonus 2 from 120
 * Clone Army: 1/4/5/8/12 to current pop assembly from 2/5/7/10/15 and +20% fire rate for clone admirals from +25%

### Boosts
 * Hegemon: "Long live the hegemony" event gifts the player with +200 influence and +75 alloy 30 days after game start.
 * Common Ground: "Live long and prosper" event gifts the player +125 influence 30 days after game start along with a crewed science ship.
 * Galactic Doorstep: +15% Physics research
 * Slingshot to the Stars: +15% Physics research
 * Post Apocalyptic: +10% Habitability bonus
 * Life Seeded: Starbase influence and material cost -10%
 
## Species Traits:

### Nerfs
 * Rapid Breeders: +6% population growth from 10%
 * Intelligent: +8% to research from +10%
 * Charismatic: +15% to amenities from +20%
 * Thrifty: +20% trade value from +25%

### Boosts
 * Slow Breeders: -6% from -10%
 * Resilient: +25% to defensive army health/morale
 * Very Strong: +60% Army damage and +7.5% resources from 40% army damage and +5% resources
 * Nonadaptive: -6% habitability from -10%
 * Repugnant: -15% to amenities from -20%
 
## Robot Traits:

### Nerfs
 * Mass Produced: +10% assembly speed from +15%
 * Emotion Emulator: +15% to amenities from +20%

### Boosts
 * Logic Engines: +8% research from +10%
 * Custom made: -10% assembly speed from -15%
 * Recycled: -30% assembly cost from -20%
 * Uncanny: -15% to amenities from -20%

## Plantoids

### Boosts:
 * none

### Nerfs:
 * Budding: +0.0175 assembly from 0.02

## Lithoid Traits

### Boosts:
 * Scintillating Skin: +0.02 Rare crystals from +0.01
 * Gaseous Byproduct: +0.02 Exotic gases from +0.01
 * Volatile Excretion skin: +0.02 Volatile motes from +0.01

## Toxoid Traits:

### Nerfs
 * Pre-planned growth: +25% growth from +30% and -35 leader age from -30
 * Elevated Synapses: +16% research from +20%, -35 leader age from -30 and +0 leader level from +2
 * Augmented Intelligence: +8% research from +10% and -15 leader age from -10

### Boosts
 * Inorganic Breath: 35% increase maintenance from 50%
 * Expressed Tradition: +15% unity from +10%
 * Gene Mentorship: +35% leader experience from +25%
