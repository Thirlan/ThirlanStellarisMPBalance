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

# 2022/10/22 - 1.4.1

Compatibility changes with 3.5.3. Also cleared the logs below to make sure there is only a years worth of logs.


# 2022/10/01 - 1.4.0

Updated to be compatible with version 3.5.2 as well as to include some but not all new multiplayer meta

Added:
 * Espionage Operations: difficulties reduced by 4
 * Pre-planned growth: +25% growth from +30%
 * Elevated Synapses: +18% research from +20% and +1 leader level from +2
 * Augmented Intelligence: +9% research from +10%
 * Expressed Tradition: +15% unity from +10%
 * Gene Mentorship: +35% leader experience from +25%
 * LEADER_AGE_DEATH_CHANCE_AGE: 75 from 80
 * LEADER_AGE_HIGH_DEATH_CHANCE_AGE: 95 from 100

Changed:
 * Consecrate Worlds: Can now consecrate an occupied world
 * Very Strong: +60% Army damage and +7.5% resources from 40% army damage and +5% resources

Removed:
 * Phototrophic: 48% food and 48% energy from 50% food and 50% energy

# 2022/07/16 - 1.3.9

AI in general has been exploitable in trades, especially with the Imperial Fiefdom Origin. Some additional changes have been made to prevent this.

Added:
 * Imperial Fiefdom origin: -5% happiness, -20% Ethics attraction and Overlord starting opinion bonus 90 from 120
 * Anti-AI Trade exploits:
   * FAVOR_CAP: 5 from 10
   * RESEARCH_AGREEMENT_ACCEPTANCE_OPINION_FACTOR: 0.3 from 0.4
   * RESEARCH_AGREEMENT_ACCEPTANCE_NUM_PACTS: -40 from -30
   * RESEARCH_AGREEMENT_ACCEPTANCE_GIVEN_TECHS: -0.6 from -0.5
   * TRADE_MIN_RESOURCE_STOCKPILE: 1000 from 500
   * TRADE_VALUE_RESOURCE: 1.5 from 2.0
   * TRADE_VALUE_SENSOR_CHARTS: 1 from 2
   * TRADE_VALUE_SENSOR_LINK_MAX: 0.75 from 1.0
   * EMBASSY_IMPROVE_RELATION_MULTIPLIER: 2.0 from 3.0
 * Anti-AI vassal exploits:
   * NEGOTIATE_AGREEMENT_ACCEPTANCE_OPINION_FACTOR: 0.20 from 0.333
   * NEGOTIATE_AGREEMENT_RESOURCE_ACCEPTANCE_COEFICIENT_FOR_OVERLORD: 1.5 from 1.0

Favors cannot be used so readily to drain the AI of resources. The AI will also be less willing to do Research agreements that are not in their favor as well as give away resources.

For AI overlords, opinion will matter less in a deal and they will be more sensitive to how good the deal is for them.

# 2022/07/01 - 1.3.8

Updated for emergency patch. Also did more analysis on the Leader cap bonuses and tweaked them.

Added:
 * Supremacy (War Games): Admiral leader cap level +1 from +2
 * Discovery (Science Division): Scientist leader cap level +1 from +2
 * Domination (Grand Council): Ruler leader cap level +1 from +2 and +1 to starting level
 * Domination (Viceroys): Governor leader cap level +1 from +2 and +1 to starting level
 * Star Slingshot: +15% Physics research

Changed: 
 * Base Leader skill cap: 3 from 5
 * Talented: +1 to starting level
 * Philosopher King: Ruler leader cap level +1 from +2 and +1 to starting level and +3% to unity
 * Jump Drive:
   * Range decreased by 25%

# 2022/06/25 - 1.3.7

Updated to include 3.4.4 fixes

Added:
 * Shattered Ring Origin: Starbase influence and material cost -10%
 * Life Seeded: Starbase influence and material cost -10%

Removed:
 * Expansion (a new life): +6% to population growth from +10%

Added a slight buff to the single planet origins that allows them to expand faster with starbases to compensate for the one planet they have early game.

# 2022/05/22 - 1.3.6

Added:
* Proton Launchers: -10% to min and max damage
* Crystalline Hulls: 10% increased material cost
* Jump Drives: -10% to jump drive range and -60% to ship damage/speed from -50%

Changed:
* Consecrate Worlds:
  * Can now consecrate an occupied world
  * Capitals or Second Home have a 30% chance of being a Respected World, 60% chance of being a Venerated World and 10% of being a Holy world
  * Worlds with either Titanic Life, Atmospheric Aphrodisiac or Natural Beauty have a 15% chance of being a Respected World, 65% chance of being a Venerated World and 20% of being a Holy world
  * Planets with Dead God, Paradise Made, Sentinels or the Loop Temple Pilgrims' Way event have a 100% chance of being a Holy World

Some additional fixes based on some of the more RNG parts of the game. These weapons are often considered to be so good they radically alter the game for those who get them. This slightly reduces their effectiveness but make no mistake they are still very good.

Small tweak to Consecrate Worlds, mostly with Capitals. Original boost was too easy for Capitals. With this change there is still a desire to go out and hunt for Holy Worlds to get a better chance at an upgrade.

# 2022/05/21 - 1.3.5

Small text clean ups

# 2022/05/21 - 1.3.4

Some updates based on metas both old and new.

Removed:
 * Barbaric Despoilers: +5% to ship speed
 
Changed:
 * Resilient: +25% to defensive army health/morale
 * Rogue Servitor: Bio Trophies produce +2 unity from +3 and 0.8% complex drone output boost from 1%
 * Clone Army: 1/4/5/8/12 to current pop assembly from 2/5/7/10/15 and +20% fire rate for clone admirals from +25%
 * Aquatics: +7% energy/mineral/food/housing production on Ocean worlds from +10%

Added:
 * Devouring Swarm: +50% market fee penalty
 * Determined Exterminator: +50% market fee penalty
 * Prosperous Unification: +10% happiness from +15%
 
The big change here is the market fee to the two Total War civics. These two in general are a hotly debated civic. They are generally banned in multiplayer but there are arguments they are between S and A rank and might not deserve the ban as much as Determined Assimilators or Fanatical Purifiers.

Their combat bonuses are impressive but the fact that both of them destroy pops they conquer tends to mean that all wars have very poor return on investment. Combine with the fact that your pops are destroyed upon being conquered and people can declare war on you as easily as you can on them, which results in multiple players attacking at once, there is a double edged sword to the entire mechanic.

As such it has been a back and forth mentally about whether they should or should not be nerfed. In the end the decision is to give them a nerf but ultimately an interesting one. The penalty to market fees radically changes these civics and make them a bit more challenging in an interesting way. Most professional players in Stellaris will carefully regulate their resources per month to be optimal. Much of this is done by buying and selling resources on the market, but with this taken away from the two exterminators it now means they have to focus a lot more on job and stockpile logistics.

This change, beyond making it harder at the start of the game to optimize, also feels more flavorful for these two civics. There is no internal market in a gestalt society bent on killing everyone, only the humming of your drones as they collect resources that have to be stockpiled.

Note the penalty is not 70%, which would result in a 100% fee and cause all selling to be worth 0 and all buying to cost double. The reason behind this is for (1) at least give the option to get out of death spirals and (2) the AI does use the market a little bit so we didn't want it to cause really bad AI issues (3) we did not want to create some kind of exploit or bug. The penalty as it is though is bad enough that it will only be used in emergencies and not for daily purchases.

# 2022/05/19 - 1.3.3

Minor changes to be compliant with 3.4.3

# 2022/05/15 - 1.3.2

Removing the incorrect description for Technocracy

# 2022/05/14 - 1.3.1

Updating to handle some of the new meta. As usual many thanks to the community such as Montu, Stefan, Komrad Truck, ASPec for posting such great videos.

Removed:
 * Cutthroat Politics: +2 decryption bonus from +1
 * Galactic Contender: Number of ascension perks required dropped to 1 from 3

Added:
 * Materialist: 4%/8% research bonus from 5%/10%
 * Xenophobe: 8%/16% pop growth from 10%/20%
 * Pooled Knowledge: +1 starting level to leaders
 * Rutheless Competition: +1 starting level to leaders
 * Factory Overclocking: +1 starting level to leaders
 * Enhanced Memory: +1 starting level to leaders
 * Efficient Bureaucracy: -40% administrator upkeep from -20%
 * Free Traders: +8% trade value from +10%
 * Indentured Servitude: +8% slave output from +10%
 * Thrifty: +20% trade value from +25%
 * Quick Learners: +35% to leader leveling speed from +25%
 * Slow Learners: -35% to leader leveling speed from -25%
 * Learning Algorithms: +35% to leader leveling speed from +25%
 * Repurposed Hardware: -35% to leader leveling speed from -25%
 * Executive Vigor: +90 edict capacity from +100
 * Galactic Force Projection: +5% sublight speed
 * Arcology Project: requires 3 ascension perks from 2
 * Anglers: Pearl Divers give +4 trade goods from +3
 * Warrior Culture: Duelists give +3 unity from +2
 * Merchant Guilds: +5% diplomatic weight and +3% trade value
 * Corporate Hedonism: Decadant Lifestyle upkeep increased by 10%
 * Pleasure Seekers: Decadant Lifestyle upkeep increased by 10%
 * Catalytic Converter: Catalytic Technicians/Drones require 8 food from 9
 * Technocracy: -5% to Naval Capacity, +5% to ship cost, -5% to ship build speed
 * Consecrate Worlds:
  * Can now consecrate an occupied world
  * Capitals or worlds with either Titanic Life, Atmospheric Aphrodisiac, Natural Beauty, Second Home have a 15% chance of being a Respected World, 35% chance of being a Venerated World and 50% of being a Holy world
  * Planets with Dead God, Paradise Made, Sentinels or the Loop Temple Pilgrims' Way event have a 100% chance of being a Holy World
 
Changed:
 * Natural Engineers: +12% engineering research from +15% engineering research
 * Become the crisis: requires 3 ascension perks from 2 and requires Enigmatic Engineering perk
 * Zero-waste Protocols: -20% robot upkeep from -10%
 * Transcendent Learning: +1 leader level cap from +2, +1 to starting leader skill and 75% to leader leveling speed from +50%
 * Aquatics: +8% energy/mineral/food production on Ocean worlds from +10% and -8% housing usage from -10%
 * Post Apocalyptic: +10% Habitability bonus

No patches yet to the more recent exploits found such as Imperial Fiefdom because those are going to be patched for sure in a week.

# 2022/05/12 - 1.3.0

Clean up after Overlord update. Once again, yay for progress!

Removed:
 * Economic Chaos (anti-negative economy exploit) event: Any player whose stockpiles in mineral/food/energy are 0 or below with negative income will suffer a empire wide penalty of -20% to alloys, research and unity.
 * Idyllic Bloom: Building energy upkeep 15 from 20 and energy cost 1125 from 1500
 * Strength of Legions: +30% to army health/damage/morale -30% to army cost/upkeep from 20% army damage and 20% upkeep
 * Warbots: +30% to army health/damage -30% to army cost/upkeep from 20% army damage and 20% upkeep
 * Private Military Companies: +30% to army health/damage/morale -30% to army cost/upkeep from 20% army damage and 20% upkeep
 * Espionage: All espionage operation's difficulty decreased by 3, resulting in much faster completion times.
 * Environmentalist: -25% consumer goods consumption from -20%
 * Void Dwellers: produce +12% on habitats from +15% 
 * AI early game economic plans

Added:
 * Expansion (a new life): +6% to population growth from +10%
 * Masterful Crafters: +1.0 Mechanical Engineering from +1.1 and now cost 7 minerals in maintenance from 6
 
Changed:
 * Scion: -5% happiness and -20% Ethics attraction
 * Post Apocalyptic: +7% Habitability bonus
 * Galactic Doorstep: +15% Physics research
 * Aquatics: +8% energy/mineral/food production on Ocean worlds from +10%
 * Capacity Booster: +1 leader level cap from +2 and +1 starting level and 50% increase in cost from 100%
 * Selected Lineage: 25% increase in cost from 50%
 * Corvette Focus: -13% from -20% Corvette cost reduction and +10% build speed
 * Destroyer Focus: -13% from -20% Destroyer cost reduction and +10% build speed
 * Cruiser Focus: -13% from -20% Cruiser cost reduction and +10% build speed
 * Battleship Focus: -13% from -20% Battleship cost reduction and +10% build speed

# 2022/03/25 - 1.2.2

Updated the files to reflect the changes of the hotfix

# 2022/03/05 - 1.2.1

Quick clean up to add in game tool tip modifier texts to the following:
 * Venerable: +1 starting level to leaders
 * Transcendent Learning: +1 leader level cap from +2 and +1 starting level
 * Leader Capacity Booster: +1 leader level cap from +2 and +1 starting level

Changed:
 * Talented: +2 to leader level cap
 * Tweaked AI starting economy plans (better support for Megacorps, Hivemind, Fanatical Purifiers, etc...)