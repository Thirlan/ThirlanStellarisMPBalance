# 2024/03/08 - 1.10.0

Updates to game's latest version 3.11

Removed:
 * Galactic Doorstep: +15% Physics research

# 2023/12/20 - 1.9.2

Updates to game's latest version also purged log notes older than 1 year

Added:
 * Machine malfunction: increased from 10% to 13%

# 2023/11/25 - 1.9.1

Updates for the latest version and some quick meta fixes

Added:
 * One Vision: +7% Unity and -7% Pop Amenity Usage from 10%
 * Determined Exterminator: +50% market fee penalty
 * Natural Engineers: +12% Engineering Research from +15%
 * Detox: +10% habitability and -10% terraforming cost multiplier
 * MIGRATION_PACT_ACCEPTANCE_OPINION_FACTOR: 0.4 from 0.5
 * EMBASSY_ACCEPTANCE_OPINION_FACTOR: 0.4 from 0.5

Changed:
 * Meritocracy: Specialist pop resource output +5% from +10%

# 2023/11/17 - 1.9.0

Updates for the new 3.10.0 release

Removed:
 * Galactic Force Projection
 * STARBASE_CAPACITY_BASE: 2 from 3
 * STARBASE_CAPACITY_SYSTEM_MULT: 0.08 from 0.1
 * Generals:
   * Gain 10 experience every year
   * Gain +60% more experience from a battle
 * Heroic Past: Leader upkeep +15%
 * Franchising: Empire size from Branch Offices -20% from -25%
 
# 2023/10/21 - 1.8.2

Updates for the new 3.9.3 release

Removed:
 * Emnity:
   * Adoption: +0 rivalries from +1
   * Reaffirmed Superiority: +2% to science from +20%
 * Anti-AI Trade exploits:
   * FAVOR_CAP: 5 from 10
   * TRADE_VALUE_FAVORS_MULT: 5 from 10
   * Be careful out there (anti-ai exploit event): All players (AIs not included) start with a -50% penalty to envoy relationship improvements for 20 years, UNLESS they are
     * Government: Megacorporations
     * Ethic: Xenophile
     * Civics: Diplomatic Corps or Empath
   * TRADE_VALUE_SENSOR_CHARTS: 1 from 2
   * TRADE_VALUE_SENSOR_LINK_MAX: 0.75 from 1.0
   * TRADE_MIN_RESOURCE_STOCKPILE: 1000 from 500
   * TRADE_VALUE_RESOURCE: 1.5 from 2.0
   * EMBASSY_IMPROVE_RELATION_MULTIPLIER: 2.0 from 3.0
   * MIN_WILLINGNESS_TO_OFFER_TRADE: 0.85 from 0.75
 * Anti-AI vassal exploits:
   * NEGOTIATE_AGREEMENT_ACCEPTANCE_OPINION_FACTOR: 0.20 from 0.333

Credit goes to: Thirlan and MetallicHydra

# 2023/09/30 - 1.8.1

Updates for the new 3.9.2 release

Added:
 * Existential Iteroparity: +20% population growth from +30%
 * Emnity:
   * Adoption: +0 rivalries from +1
   * Match: -5% to ship build cost from -10%
   * Reaffirmed Superiority: +2% to science from +20%
   * Antagonistic Stance: +0 rivalries from +2

# 2023/09/15 - 1.8.0

Updates for the new 3.9.0 release

Added:
 * Pre-ftl espionage difficulties also dropped by 4

Removed:
 * Calamitous Birth: +1 mineral districts when colonizing a planet
 * Rogue Servitor: Bio Trophies produce +2 unity from +3 and 0.8% complex drone output boost from 1%
 * NEGOTIATE_AGREEMENT_RESOURCE_ACCEPTANCE_COEFICIENT_FOR_OVERLORD = 2.0
 * Slingshot to the Stars: +15% Physics research

Changed:
 * Be careful out there (anti-rush event): All players (AIs not included) start with a passive -40% defense platform build cost and +20% starbase damage boost for the first 20 years of the game.

# 2023/07/22 - 1.7.6

Some meta tweaks based on recent community chatter and the latest tournaments:

https://www.youtube.com/watch?v=mjrBQwOeQvI

Added:
 * Hydrocentric: terraforming ocean world cost now -33% from -25% and -15% to terraforming ocean world time
 * Parliamentary System: +30% unity from factions from +40%
 * Memory Vault: Leader upkeep +15%
 * Heroic Past: Leader upkeep +15%

# 2023/06/24 - 1.7.5

Updating to the newest version

Removed:
 * Champions of the Empire Governor: -1 to Empire size, -1% to Colony and system size from -2 Empire size
 * Raiding stance: 50% less effective at abducting pops

# 2023/06/10 - 1.7.4

Tackling some existing exploits and meta.

Added:
 * Champions of the Empire Governor: -1 to Empire size, -1% to Colony and system size from -2 Empire size
 * Raiding stance: 50% less effective at abducting pops

# 2023/06/01 - 1.7.3

Updating to match 1.8.3 with some tweaks

Added:
* Espionage Operations:
  * Steal Techonology Operation: cooldown of 1 year from 6
  * Sabotage Starbase Operation: cooldown of 0 from 4 years
  * Delays between operations halved
  * Bribe costs halved

Removed:
 * Champions of the Empire: -0.5% empire size, empire size from pops and empire size from colonies from -2% empire size
 * Progenitor hive: Fleet without an off spring ship suffers -75% penalties from -50%
 * Enigmatic Engineering: +4 encryption from +2 and ascension perks required dropped to 0 from 1
 * Executive Vigor: +80 edict funds from +100
 * Post Apocalyptic: +10% habitability bonus

Changed:
 * Become the crisis: requires 4 ascension perks from 2
 * Hive World: requires 3 ascension perks from 0
 * Machine World: requires 3 ascension perks from 0
 * Arcology Project: requires 3 Ascension perks from 2

No balance changes have come to Espionage since the last boost around Nemesis so taking the time to adjust it.

# 2023/05/20 - 1.7.2

Adding a patch for the 0 Empire size exploit:

Added:
 * Champions of the Empire: -0.5% empire size, empire size from pops and empire size from colonies from -2% empire size

# 2023/05/12 - 1.7.1

Updating to be compliant with the patch.

After some test runs it seems generals are still underpowered and as such they have been given some incentives. The reasons are as follows:
 * It is easier now to capture without armies, and thus without a general
 * Generals have less opportunities to gain experience and so will advance slower, hence will not be picked early as you may be stuck with a low level council member
 * Because they cannot gain exp without wars, generals will not be recruited until there is a war, at which point the leadercap may have been filled adding disincentives to hire a general

Venerable is also still not entirely worth it because of the increased options to increase the maximum age of your leaders.

Added:
 * LEADER_AGE_DEATH_CHANCE_AGE: 70 from 80
 * LEADER_AGE_HIGH_DEATH_CHANCE_AGE: 90 from 100
 * Generals:
   * Gain 10 experience every year
   * Gain +60% more experience from a battle

2021 logs were also purged from the patch logs file.

# 2023/05/11 - 1.7.0

Updating to latest DLC and with some meta revisions

Added:
 * Franchising: Empire size from Branch Offices -20% from -25%
 * Naval Contractors: Naval Cap +10% from +15%
 * Divided Attention: -5% Empire size from pops
 * Necrophage: Population growth -5%
 * Progenitor hive: Fleet without an off spring ship suffers -75% penalties from -50%
 * Nomadic: +20% pop growth from immigration from 15% and -30% resettlement cost from -25%
 * Conservationist: -13% pop consumer goods upkeep from -10%
 * Extremely Adaptive: +25% Habitability from +20%
 * Conformist: +40% government ethics attraction from +30%
 * Unruly: +13% empire size from pop from +10%
 * High Bandwidth: +13% empire size from pops from +10%
 * Streamlined Protocols: -13% empire size from pops from -10%
 * Low Maintenance: -13% empire size from pops from -10%
 * Doomsday: stage 1 now takes ~2 years to trigger from 5 days, with stage 2 taking ~17 years from ~11 years
 * Calamitous Birth: +1 mineral districts when colonizing a planet

Removed:
 * Base Leader skill cap: 2 from 5
 * LEADER_AGE_DEATH_CHANCE_AGE: 75 from 80
 * LEADER_AGE_HIGH_DEATH_CHANCE_AGE: 95 from 100
 * Supremacy (War Games): General leader cap level +2
 * Unyielding (Adoption): General leader cap level +2
 * Venerable: +1 starting level to leaders
 * Quick Learners: +35% to leader leveling speed from +25%
 * Slow Learners: -35% to leader leveling speed from -25%
 * Learning Algorithms: +35% to leader leveling speed from +25%
 * Repurposed Hardware: -35% to leader leveling speed from -25%
 * Generals:
   * Gain 25 experience every year
   * Gain 2 times more experience from a battle
   * GENERAL_DEATH_CHANCE: 0.01 from 0.05, Chance of dying from a battle more in line with that of Admirals
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
 * Materialist: 4%/8% research bonus from 5%/10%
 * Xenophobe: 8%/16% pop growth from 10%/20%
 * Technocracy: -5% to Naval Capacity, -5 Naval Capacity, +5% to ship cost and -5% to ship build speed
 * Free Haven: +20% pop growth from immigration from 15% and 60% immigration pull from 50%
 * Merchant Guilds: +1 Envoy and +3% Trade value
 * Media Conglomerate: +10% diplomatic weight and -10% war exhaustion from -5% war exhaustion
 * Warrior Culture: Duelists give +3 unity from +2
 * Catalytic Converter: Catalytic Technicians require 8 food from 9
 * Catalytic Converter: Catalytic Drones require 8 food from 9
 * Determined Exterminator: +50% market fee penalty
 * Prosperous Unification: +10% happiness from +15%
 * Scintillating Skin: +0.02 Rare crystals from +0.01
 * Gaseous Byproduct: +0.02 Exotic gases from +0.01
 * Volatile Excretion skin: +0.02 Volatile motes from +0.01
 * Gene Mentorship: +35% leader experience from +25%

Changed:
 * Clone Army: 1/4/5/8/12 to current pop assembly from 2/5/7/10/15
 * Meritocracy: Specialist pop resource output +8% from +10%
 * Fanatical Purifier: 15% ship fire rate from 33%
 * Static Research Analysis: +0 intel decryption from +1
 * Rapid Breeders: +7% population growth from 10%
 * Elevated Synapses: +16% research from +20%

# 2023/04/01 - 1.6.0

Updating to latest DLCs with minor tweaks:
 
Changed
 * Technological Ascendency: +7% Research rate from +10%

# 2022/11/27 - 1.5.1

Preparing for 3.6.0 release and some other tweaks. Two major changes are focused on this modification. The first is an additional nerf to AI trade exploitation, specifically the Imperial Fiefdom. The second change is a simplification and buff to leader levels, which was becoming difficult to maintain the way it was in the mod. The largest buff by far is to Generals, who are essentially non-existent in the game because they have so little impact.

Added:
 * RESEARCH_AGREEMENT_SPEED_MULT: 0.15 from 0.25
 * TRADE_VALUE_FAVORS_MULT: 5 from 10
 * MIN_WILLINGNESS_TO_OFFER_TRADE: 0.85 from .75
 * Unyielding (Adoption): General leader cap level +2
 * Generals:
   * Gain 25 experience every year
   * Gain 2 times more experience from a battle
   * GENERAL_DEATH_CHANCE: 0.01 from 0.05, Chance of dying from a battle more in line with that of Admirals
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

Removed:
 * Discovery (Science Division): Scientist leader cap level +1 from +2
 * Capacity Booster: +1 leader level cap from +2, +1 starting level and 50% increase in cost from 100%
 * Selected Lineage: 25% increase in cost from 50%
 * Domination (Grand Council): Ruler leader cap level +1 from +2 and +1 to starting level
 * Domination (Viceroys): Governor leader cap level +1 from +2 and +1 to starting level
 * Philosopher King: Ruler leader cap level +1 from +2, +1 to starting level and +3% to unity
 * Pooled Knowledge: +1 starting level to leaders
 * Factory Overclocking: +1 starting level to leaders
 * Ruthless Competition: +1 starting level to leaders
 * Enhanced Memory: +1 starting level to leaders
 * Talented: +1 to starting level
 * Corvette Focus: -13% from -20% Corvette cost reduction and +10% build speed
 * Destroyer Focus: -13% from -20% Destroyer cost reduction and +10% build speed
 * Cruiser Focus: -13% from -20% Cruiser cost reduction and +10% build speed
 * Battleship Focus: -13% from -20% Battleship cost reduction and +10% build speed

Changed:
 * Imperial Fiefdom origin: -5% happiness, -20% Ethics attraction and Overlord starting opinion bonus 1 from 120
 * Be careful out there (anti-ai exploit event): All players (AIs not included) start with a -50% penalty to envoy relationship improvements for 20 years, UNLESS they are
   * Government: Megacorporations
   * Ethic: Xenophile
   * Civics: Diplomatic Corps or Empath
 * NEGOTIATE_AGREEMENT_RESOURCE_ACCEPTANCE_COEFICIENT_FOR_OVERLORD: 2.0 from 1.0
 * Base Leader skill cap: 2 from 5
 * Supremacy (War Games): General leader cap level +2
 * Executive Vigor: +80 edict funds from +100


# 2022/11/12 - 1.5.0

Upgrade to Stellaris version 3.6.0 beta

Removed:
 * Proton Launchers: -10% to min and max damage
 * Crystalline Hulls: 10% increased material cost
 * The Flesh is Weak: 6% population assembly from +10%
 * Synthetic Evolution: 6% robotic job multiplier from 10%
 * Shattered Ring: Starbase influence and material cost -10%
 * Aquatics: +7% energy/mineral/food/housing production on Ocean worlds from +10%
 * Masterful Crafters: +1.0 Mechanical Engineering from +1.1 and now cost 7 minerals in maintenance from 6
 * Gestalts: -3% to research
 * Anglers: Pearl Divers give +4 trade goods from +3
 * Prosperity (Completion bonus): +3 Stability from +5
 * Natural Engineers: +12% engineering research from +15% engineering research

Changed:
 * Common Ground: "Live long and prosper" event gifts the player +125 influence 30 days after game start along with a crewed science ship.
 * Merchant Guilds: +1 Envoy and +3% Trade value
 * Augmented Intelligence: +8% research from +10% and -15 leader age from -10
 * Elevated Synapses: +16% research from +20%, -35 leader age from -30 and +0 leader level from +2
 * Logic Engines: +8% research from +10%
 * Intelligent: +8% to research from +10%