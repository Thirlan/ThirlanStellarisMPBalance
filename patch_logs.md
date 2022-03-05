# 2022/03/05 - 1.2.1

Quick clean up to add in game tool tip modifier texts to the following:
 * Venerable: +1 starting level to leaders
 * Transcendent Learning: +1 leader level cap from +2 and +1 starting level
 * Leader Capacity Booster: +1 leader level cap from +2 and +1 starting level

Changed:
 * Talented: +2 to leader level cap
 * Tweaked AI starting economy plans (better support for Megacorps, Hivemind, Fanatical Purifiers, etc...)

# 2022/02/23 - 1.2.0

Clean up after new 3.3.2 Libra update

Removed:
 * Executive Vigor: requires 2 ascension perks from 0
 * Feudal Realm: +10% Naval Capacity, -10% ship upkeep, -10% army upkeep
 * Spiritualist: +12%/+24% Unity from +10%/+24%
 * Merchant Guilds: +1.5 unity from +2 merchants
 * Capacity Subsidies: +40% energy from jobs from +50%
 * Dyson Sphere: 10% increase in costs to all stages
 * Ring World: 10% increase in costs to all stages
 * Shadow Council: +15% ruler pop output from +10%
 * Ingenious: +13% Energy production from +15%
 * Super Conductive: +13% Energy production from +15%
 * Quarrelsome: -6% Unity from jobs from -10%
 * Docile: -15% Empire Sprawl from -10%
 * Unruly: +15% Empire Sprawl from 10%
 * Conformist: +5% happiness and 25% Government Ethics attraction from 30%
 * Fleeting: -13 leader age from -10
 * Aristocratic Elite: Nobles give +6 stability from +5, +1 admin cap and trade and +5 to crime
 * Warrior Culture: +4 unity from +3 from duelists
 * Byzantine Bureaucracy: +1.2 unity/stability from +1
 * Franchising: -30% empire sprawl from branch office from -25%, -40% country subject power penalty from -33%
 * Determined Exterminator: +15% ship weapon damage from +25%
 * Devouring Swarm: -15% ship build cost from -25%
 * Xenophobe: +9%/18% to population growth from +10%/20%
 * Materialist: +4.5%/9% to research from +5%/+10%
 * Militarist: +9%/+18% to ship fire rate from +10%/+20%
 * Crime/Deviancy per pop: 2.2 from 2
 * Aristocratic Elite: Nobles give +4 stability from +2, +2 trade and +5 to crime
 * High Bandwidth: +15% Empire Sprawl from +10%
 * Streamlined Protocols: -15% Empire Sprawl from -10%
 
Changed:
 * Venerable: +1 starting level to leaders
 * Philosopher King: +3% to unity and research
 * Resilient: +50% army defense health/morale
 * Talented: +1 leader starting level
 * Transcendent Learning: 90% leadership bonus from 50% and +1 to starting leader skill
 * Base Leader skill cap: 4 from 5
 * Economic Chaos (anti-negative economy exploit) event: Any player whose stockpiles in mineral/food/energy are 0 or below with negative income will suffer a empire wide penalty of -20% to alloys, research and unity.
 * Private Military Companies: +30% to army health/damage/morale -30% to army cost/upkeep from 20% army damage and 20% upkeep
 * Strength of Legions: +30% to army health/damage/morale -30% to army cost/upkeep from 20% army damage and 20% upkeep

New:
 * Leader Capacity Booster: +1 leader level cap from +2 and +1 starting level

# 2021/12/12 - 1.1.1

Modified the crisis trigger so that it is not always the Unbidden that show up once jump drives are researched. In a typical multiplayer game, the majority of the players will reach jump drives by end game and as such the crisis rules only allow the Unbidden at this point. Now the rules are the following:
 - All Crisis can show up once Jump Drives are researched
 - Jump drives double the chances of the Prethoryn or Contingency showing up sooner
 - Jump drives quadruple the chances of the Unbidden showing up sooner
 
In short this means that once the end game arrives, on the first dice roll for the crisis, if you have jump drives the odds of the crisis showing up go from 19% to 38%.

In addition to this change the AI's planning economy has been greatly improved. As always, this follows the simple approach of updating this mod which involves touching as little as possible. 3.2's new AI Planning scripts make this possible. The AI, instead of using a single basic planning script for all AIs, now has 11 different AI scripts for each empire in the early phase of the game, which is the most critical phase of the game. Once the early phase of the game is over it switches back to the default script. Overall this has resulted in impressive improvements from the AI with no touching of the other game files.

# 2021/12/04 - 1.1.0

Latest 3.2 Aquatics Tournament has played out and there was a quick patch to the game. Updating the mod for compliance and to address some meta from the latest tournament.

https://forum.paradoxplaza.com/forum/threads/2021-november-aquatics-tournament.1500941/

Removed:
 * Egalitarian: +4%/8% to specialists from +5%/+10%
 * Hive Mind: +28% growth speed from +25%
 
Added:
 * Starbase overcapacity upkeep penalty: +35% from +25%
 * Spiritualist: +12%/+24% Unity from +10%/+24%
 * Materialist: +4.5%/9% to research from +5%/+10%
 * Militarist: +9%/+18% to ship fire rate from +10%/+20%
 * Aquatics: +9% energy/mineral/food production on Ocean worlds from +10%
 * Prosperity (Completion bonus): +3 Stability from +5
 * Fleeting: -13 leader age from -10

Also wanted to add a special thanks to OldEnt (ACE) and Corsairmarks for always being on hand to help out in the Stellaris Modding Den.

# 2021/11/26 - 1.0.0

Mod has been out long enough to have it upgraded to 1.0.0 as part of the Aquatics release. The following changes will be based on the lastest meta of the 2021 November tournament. Will keep an eye on the meta for 3.2 with the latest tournament:

https://www.youtube.com/watch?v=ug15NhTh-WM&t=1s&ab_channel=StefanAnon


Removed:
 * Leadership max cap: 15 from 10
 * Functional Architecture: -10% to building costs from -15%
 * New Life (Expansion tree): +6% pop growth from +10%
 * Catalytic Processing: Food upkeep reduced to 8 from 9

New:
 * Gestalts: -3% penalty to research
 * Void Dwellers: produce +12% from +15% on habitats
 * Merchant Guilds: +1.5 unity per merchant from +2
 * Xenophobe: +9%/18% to population growth from +10%/20%
 * Egalitarian: +4%/8% to specialists from +5%/+10%

Changed:
 * Base Leader skill cap: 3 from 5
 * Resilient: +65% defensive army damage from 50% and 65% defensive army health
 * Nonadaptive: -6% habitability from -10%
 * Be careful out there (anti-rush event): All players (AIs not included) start with a passive -60% defense platform build cost and +15% starbase damage boost for the first 20 years of the game.
 * The Flesh is Weak: 6% population assembly from +10%
 * Synthetic Evolution: 6% robotic job multiplier from 10%
 * Driven Assimilator: 3 pop per year assimilation speed from average of 7

# 2021/10/27 - 0.2.1

New changes based on the lastest meta and observations. Simple tweaks to the Traits.

New:
 * Budding: +0.0175 assembly from 0.02
 * Logic Engines: +9% research to all research from +10%
 * Super Conductive: +13% energy from +15% energy
 * Natural Engineers: +13% engineering research from +15% engineering research
 * Docile: -15% Empire Sprawl from -10%
 * Charismatic / Repugnant / Emotion Emulator / Uncanny: all changed to 15% from 20%
 * Phototrophic: 48% food and 48% energy from 50% food and 50% energy
 * Espionage: All difficulties dropped by 3

The most important tweak is to Espionage. It has been determined that espionage is too ineffective. This is mostly due to the fact that it takes forever to do anything meaningful. In light of this the difficulty of all espionage will be dropped by 3 so that Espionage missions can be done considerably faster and thus have a higher impact. Conversely this will improve the value of all espionage related game choices.

Change:
 * Enigmatic Engineering: +4 encryption from +2 and ascension perks required dropped to 0 from 1

Many thanks as usual from Stefan:

 * https://cdn.discordapp.com/attachments/598211045332484148/895097788365418516/Traits_Tier_List_31.png
 * https://www.youtube.com/c/StefanAnnon

# 2021/09/26 - 0.2.0

New changes to the list as the community gathers more intel on what is strongest and weakest now. 

New:
 * Functional Architecture: -10% to building costs from -15%
 * Barbaric Despoilers: +5% to ship speed
 * Byzantine Bureaucracy: +1.2 unity/stability from +1
 * Free Haven: +20% pop growth from immigration from 15% and 60% immigration pull from 50%
 * Cutthroat Politics: +2 decryption bonus from +1
 * Aristocratic Elite: Nobles give +6 stability from +5, +4 unity from +3, +1 admin cap and trade and +5 to crime
 * Environmentalist: -25% consumer goods consumption from -20%
 * Warrior Culture: +4 unity from +3 from duelists
 * Shadow Council: +15% ruler pop output from +10%
 * Idyllic Bloom: Building energy upkeep 15 from 20 and energy cost 1125 from 1500
 * Catalytic Processing: Food upkeep reduced to 8 from 9
 * Static Research: +2 decryption from +1
 * Devouring Swarm: -15% ship build cost from -25%
 * Determined Exterminator: +15% ship weapon damage from +25%
 * Clone Army: -10% to unity and -1 to current pop assembly
 * Hive Mind: +28% growth speed from +25%
 * Intelligent: +9% to research from +10%
 * Ingenious: +13% Energy production from +15%

Changed:
 * Executive Vigor: No longer requires Imperial Prerogative and instead requires 2 ascension perks from 0
 * Become the Crisis: requires 3 ascension perks from 2
 * Media Conglomerate: +10% diplomatic weight and -10% war exhaustion
 * Resilient: +75% defensive army damage from 50% and 75% defensive army health

Removing:
 * Subsumed Will

Many thanks to the Community (Stefan, ASpec, Komrad Truck, Montu) for laboriously going over the game mechanics.

# 2021/09/18 - 0.1.2

With 3.1 LEM update out the following patches have been removed from the balance mod as they are supposedly fixed:

Removed:
 * criminal_job_weight: 9 from 5 (one less than specialist)
 * Privy Council (Domination): +1 Leader Pool size
 * Technocracy: 0.5 unity from 1.0
 * Environmentalist: -15% consumer goods from 10%
 * Efficient Bureaucracy: 15% administrative capacity from 10%
 * Idealistic Foundation: +8% happiness from +5%
 * Nationalistic Zeal: -20% claim influence cost from 10% and -20% war exhaustions from -10%
 * Divided attention: +15% administrative capacity from 10%
 * Void Dwellers: 10% production bonus instead of 15%
 * Ring World Systems online event: -5% to energy, mineral and research for non-robots and -10% penalty to robots for 30 years
 * Necrophage: -10% to purge speed and -5% growth
 * Solitary: +20% housing usage from +10%
 * Communal: -20% housing usage from -10%
 * Bulky: 20% housing usage from 10%
 * Double-jointed: -20% housing usage from -10%

Yay for progress!

Changes:
 * Enigmatic Engineering: Ascension perks required dropped to 0 from 1
 * Quarrelsome: -6% Unity from jobs from -10% (1% adjustment)
 * Be careful out there (anti-rush) event: removed +40% starbase defense bonus
 * New Life (Expansion tree): +6% pop growth from +10% (1% adjustment)

The nerf to the anti-rush event is because it is no longer really needed. Rushing during the early phase is harder with the way first contact works and also there is a desire to emphasize the use of the new Unyielding tradition as an anti-rush option. Removing the +40% bonus also helps to coax people to stop the unmitigated tech rushing.

New:
 * Corvette Focus: -15% from -20% Corvette cost reduction and +10% build speed
 * Destroyer Focus: -14% from -20% Destroyer cost reduction and +10% build speed
 * Cruiser Focus: -13% from -20% Cruiser cost reduction and +10% build speed
 * Battleship Focus: -12% from -20% Battleship cost reduction and +10% build speed
 * Economic Chaos (anti-negative economy exploit) event: Any player whose stockpiles in mineral/food/energy are 0 or below with negative income will suffer a empire wide penalty of -10% production to mineral, food, energy and -20% to alloys, research and unity.


# 2021/08/12 - 0.1.1

https://www.youtube.com/watch?v=UqA4GFBYdyU&ab_channel=StefanAnon

Making additional updates to tackle exploits covered in the most recent Stellaris Tournament.

Criminal job weights are still too weak and as such crime exploits like Crime lord deal can function normally with job priority command. As such criminal job weight will be made one less than the specialist job.

Void Dwellers is deemed too strong as one of the current metas, as such will be nerfing it a bit.

Hivemind has been deemed to be too weak as as such will be removing the previous penalties that were given to it.

Applied the penalty to Ring world to all empires and a stronger debuf against robots.

# 2021/08/08 - 0.1.0

Patching ring world with machines. Stephan has presented a brutal exploit which shows that energy as a penalty is not enough for ring world robots. As such we mixed the penalty to be a combination of energy, research and mineral penalty for the first 30 years.

https://www.youtube.com/watch?v=Id19TyroN0k&ab_channel=StefanAnon

Rebalancing the Necrophage origin along with its combination of Fanatical Purifier. Stefan's videos on Necrophage indicate it is clearly very strong on its own.

https://www.youtube.com/watch?v=9-18Ua2poPA&ab_channel=StefanAnon

Removing modifications to Charismatic, Repugnant, Emotion Emulator and Uncanny. The general agreement was the modifications were non-intuitive and it isn't simple to modify the modifications in the game files, as such even though these are unbalanced traits we will simply leave them as is.

Common grounds effect has also been swapped out from +10 stability to two new events, "Live long and prosper", which will give the player first an additional science ship, scientist and +125 influence around 30 days after game start. The second time the event triggers it will give a construction ship 6 months after the first event along with another +125 influence. These events give the player the ability to avoid being squeezed in by their starting neighbors.

In the same light as Commong grounds, Hegemon has been given a slightly weaker boost to avoid players being trapped in by their starting neighbors. Hegemon will received the event "Long live the hegemony", will grant them with +200 influence and +75 alloys 30 days after game start.

In an effort to improve the value of the Starbase cap bonus game choices, such as Grasp the Void ascension perk, the STARBASE_CAPACITY_SYSTEM_MULT has been reduced from 0.1 to 0.8 and the STARBASE_CAPACITY_BASE reduced from 3 to 2, which implies that if you had 100 systems under your control you would get 8 + 2 = 10 starbases instead of 10 + 3 = 13 starbases.

Reduced Capacity Subsidies edict from 50% to 40% to help reduce the energy only exploit where you only build energy and buy the rest of the resources from the market. Reducing from 50% to 40% will not entirely remove this exploit as 40% is still above the market transaction cost of 30%, but it does blunt the player's ability to completely rely on the market. Price fluctuations will force the players to diversify with other resources to avoid getting hit with market price spikes.

Devouring swarm's minor penalty of -20% ship build cost instead of -25% has been removed. Devouring Swarm, much like Determined Exterminator, is not strong enough to deserve a nerf.

Philosopher King's boost of +1 edict has been replaced with +2% unity, research and administrative capacity to make it a touch weaker, more appropriate and easier for the AI to use.

# 2021/05/22 - 0.0.4

Latest release after Nemesis! Everything previously in the log has been cleared.