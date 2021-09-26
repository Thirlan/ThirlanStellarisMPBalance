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

Many thanks to Stefan and his team for laboriously going over the game mechanics.

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
 * Economic Chaos (anti-negative economy exploit) event: Any player whose stockpiles in mineral/food/energy are 0 or below with negative income will suffer a empire wide penalty of -20% production to mineral, food, energy, alloys, research and unity.


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