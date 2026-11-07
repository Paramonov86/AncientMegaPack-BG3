# Ancient Mega Pack — changelog

Release notes for the **AMP Plus** line (`Ancient Mega Pack Plus 1.0` onward), in release order — the newest update is at the bottom.

---

Ancient Mega Pack Plus 1.0 — June 25

GENERAL CHANGES
The Reclamation Shard no longer hands back extra copies when an item carries several stacked shards (thanks @Bish)
Gale now hands over his void capsule gifts even when he is lounging back at camp instead of travelling with the party
The Improvise amulet shard's cantrip discount no longer chains across a whole turn off a deep Bardic Inspiration pool, it now eases only the first cantrip each turn (thanks @top5g04t)
The Master gloves shard now grants the Armour Class its tooltip promises while unarmed, instead of more (thanks @top5g04t)
Primemother's Spore can finally be purged for good: setting the cursed amulet itself alight wipes out the whole infestation at once, and once the amulet leaves your party the leftover spores burn themselves out instead of creeping back into your gear after every Long Rest (thanks @cathulhu_god_of_meowness, @mcpersson, @jerome_dracian)
The Warlock runic shard's bonus spell damage now lands only once per turn
The elemental unarmed shard tooltips now split into proper paragraphs like every other shard, and spell out that they only fail to stack with another copy of the same shard, not with a different element
The Life Draining shard's self-inflicted crit penalty was toned down

DIFFICULTY
A new ULTRA mini-boss now answers the call: U'kra the Enduring, a half-orc raider who buried her bloody past in the faith of Ilmater. She shrouds the deadliest soul beside her in a mantle nothing can pierce while she still breathes, so you must cut her down to reach it. Starve her of anyone to heal, and the beast she prays to keep chained tears loose
Doomflame is a touch sturdier now, and his Chaos Fireball bites a little harder
Eclipse is much improved: Slow is now applied through a saving throw, the stun is a little easier to resist, and the saves actually land regardless of elevation now
Eclipse now also grants a brief Armour Class boost
A boss fighting on your side no longer triggers Eclipse
ULTRA mode flow is much smoother: the early-level handicaps are fairer now, and the number of pursuers it summons follows a set scheme based on how many players are in the party
Mid and late-game enemies now hit more often but for less per blow: a high Armour Class no longer makes you untouchable, and one bad round is no longer a guaranteed death
The Pyre was reworked considerably based on feedback
The Astral's Interplanar Chest offer now lays out its bargain more clearly before you decide
Thanks to everyone who tested and gave feedback on ULTRA and Hard modes over this time
Forcing an Ultra boss to flee or approach with Command now counts toward summoning its mirror reinforcements, while merely soaking it no longer does
An ULTRA pursuer's 75 bonus damage on NPC no longer rubs off onto the retaliation and thorns damage your own gear deals back to it

ITEM CHANGES
The Crown of Vengeful Spirits no longer spirals into an infinite damage loop when worn with gear that re-applies statuses on hit (thanks @Cosmos, @wh1te_ghost, @LucarioKing)
The Venom Surge effect now reliably stops stacking once it reaches its cap, instead of occasionally creeping past the limit
The Devouring Pact boots' growing Force enchantment no longer rides along on a weapon you hand off or sell, and it now stops at its intended ceiling instead of being topped back up after every Long Rest
The acid gear's caustic brood now actually crawls up from a fresh acid pool in combat, instead of never showing up at all
The poison Orb ring's Detoxification now actually clears the toxemia off you at the end of your turn while Ancient Chaos lingers, instead of letting it sit there (thanks @Vludber)
The Shadow Magic Sorcerer's Sunset Clan Mask no longer lets you farm endless Sorcery Points by stalling a fight near an obscuring source, its Shadow Sustenance now refills only a limited reserve per Long Rest

Ancient Mega Pack Plus 1.2 — July 1

GENERAL CHANGES

Reclaiming runic shards from worn gear could quietly leave the effect stuck on the item while still handing the shard back, the reclamation now clears its leftover bookkeeping so the gear releases the shard cleanly (thanks @Bish)
The Metamorph shard's stat shift no longer slips past its cap during multi-hit attacks
Gale's habit of handing you a void capsule after his personal story beats now also pays out when he is resting back at camp, not only while he travels in your party - now for real (thanks @wh1te_ghost)
On Hard mode a boss's eclipse comeback now also kicks in at the start of its turn while it is wounded, not only the instant it takes a direct hit, so a boss worn down indirectly still gets its second wind (thanks @Zheaniv)
An eclipsed boss now also shrugs off Necrotic damage (these builds are beast in endgame)
Eclipse now lasts longer against higher-level parties, so groups that have learned to outlast it still feel the pressure
With Avarice switched on, hostile creatures now climb a difficulty tier higher than usual, so the richer loot comes with sharper teeth
Doomflame now spawns shielded by efreeti fire and cannot be harmed on its opening turn, so a single opening blast no longer wipes the whole ULTRA wave
Hard and ULTRA now add a new Full Moon affix that ramps up boss fights once the boss drops low
Full Moon can now be turned off from the AMP settings ring if you would rather not deal with it
Disarming a weakened boss now counts among the crowd-control states that can call in its ULTRA reinforcements

ITEM CHANGES

The little acid critters from the Mutacid orb no longer loiter on the battlefield forever once the fight is over (thanks @Foami)
Allies standing in the Orb of Shadow's Darkness Cloud kept blinking out of Devil's Sight partway through a fight, the cloud now keeps its sight on allies and its daze on foes for as long as it lingers (thanks @Fern @Bish @Tsumiki)
The Orb of Cold's promised sure footing on ice never actually kicked in, its wearer now keeps steady on slippery ice for good while it is worn (thanks @Flame)
Taking off Nomzeda's Unbroken Oath mid-fight used to leave you unable to spend your action for the rest of the battle, the oath's restraint now lifts the moment the sandals come off (thanks @Mars)
The Unmade Library only checked whether Intelligence was your highest ability the instant you equipped it, so a later boost left you getting shoved around, it now keeps watch as your stats shift and roots you in place once Intelligence pulls ahead (thanks @Inviniatar)

LOCALIZATION

h7a941fd4g9c26g4664g9818g0a8cdf2f41d3 in AMP_Plus_Eclipse
h04cd5133gf4feg41aega8a3g322eaf47b090 in AMP_Plus_Doomflame [ADDED]
h249ebca1g4546g4377gb900g8a8d22a74da3 in AMP_Plus_Doomflame [ADDED]
hfa11600dg9c26g4b71g8e3ag1d5f0a9c2b41 in AMP_Plus_FullMoon [ADDED]
hfa11600eg9c26g4b71g8e3ag1d5f0a9c2b42 in AMP_Plus_FullMoon [ADDED]

Update 1.2.1 — Difficulty Hotfix / July 1

A round of fixes for the boss mechanics and difficulty scaling from the last patch. Runaway enemy scaling is reined in, the comeback mechanics stop firing on your own allies and can no longer be skipped by opening burst, and a handful of boss-fight edge cases are cleaned up.

DIFFICULTY
- Fixed some enemies being scaled far above their proper difficulty grade, which was behind the ridiculous armour and health turning up on otherwise minor foes (thanks @Auzyris, @Dave, @Vludber)
- Difficulty buffs that get switched back off now lift from enemies already in the fight instead of lingering until a reload
- Enemies now gain their movement speed from difficulty as a percentage instead of a flat bonus
- Ultra bosses no longer spawn at a fraction of their health when their sustain buffs stack up
- Eclipse and the Pyre no longer switch on for a boss that is fighting on your side
- Eclipse can no longer be skipped by bursting a boss past its threshold before it gets to take a turn
- The Full Moon boss effect now starts off and can be switched on from the Settings Ring
- Fixed the Full Moon effect occasionally landing on the wrong target

Update 1.3 / July 3

Another round of difficulty and boss fixes on top of the last hotfix. ULTRA enemies hit less hard out of the gate, mini-bosses can reach for their potions again, mirror pursuers behave themselves between fights, and a new face joins the pool.

BOSSES & PURSUERS
- Doomflame no longer regains his opening-turn invulnerability at the start of every round (thanks @Inviniatar)
- The mirror pursuers' arrival effect now plays its full materialize VFX
- Mirror-support pursuers no longer warp onto you the instant a fight ends. They give you a breather and turn up on their own a while later, and they leave you alone while you are at camp (good for Scratch)
- ULTRA mini-bosses can finally use their consumables again, in exchange their survivability has been slightly lowered

DIFFICULTY
- The bonus base damage enemies gain from the ULTRA modifier has been significantly reduced
- Flipping difficulty settings back and forth mid-run no longer leaves enemies stuck on the wrong scaling, switching modes now re-scales everything cleanly on the spot
- Avarice no longer nudges enemy scaling upward, it only affects your loot now

LOOT
- Winning a fight with Avarice on can now shake a random void capsule loose, boss fights are likelier to pay and sometimes pay double

NEW CONTENT
- A new mirror pursuer has joined the pool: Neva, a blind executioner. A dangerous foe and a fresh challenge for anyone used to leaning on the same old reliable tricks (designed by @Bish)

Update 1.3.1

A small cleanup pass after 1.3, mostly around the mirror pursuers and the Pyre.

DIFFICULTY
- One of the ULTRA mini-bosses had secretly learned to cast Game Crash on his own turn. He has unlearned it (thanks @Bish)
- The Pyre got pickier than intended and refused to light for bosses who showed up late or pretended to be friendly at first. It burns properly again
- Mirror reinforcements no longer vanish into thin air the moment their master falls
- Mirror pursuers arrive properly again, veiled until the light finds them. The mirror had briefly gone shy about announcing its guests
- Host now carries a visible mark while ULTRA pursuer from a past fight is still hunting you

LOOT
- The avarice tribute cooldown now shows a proper hourglass instead of an icon it borrowed from someone else

ITEMS
- The Unmade Library's legendary pair stopped waiting for the dust to settle, its wizard can now perform Arcane Recovery in the heat of battle too (thanks @Inviniatar)

LOCALIZATION
- The in-game book's mirror pages now explain the reinforcement rules properly

Update 1.3.2

A quick follow-up to 1.3.1, tidying up a couple of bosses and a hireling slip-up.

DIFFICULTY
- Adrienne's ice cocoon now seals around her instead of around whoever struck her (thanks @Vludber)
- Neva now wears a title beneath her name, like the rest of the pool
- Hirelings no longer hold on to enemy difficulty bonuses they picked up before you recruited them (thanks @Bish)

Update 1.3.3

A short cleanup pass, mostly around the mirror pursuers and Avarice.

GENERAL CHANGES
- The Training Ring now has a Daylight VFX setting that switches off the blinding glow of Daylight spheres

DIFFICULTY
- Mirror reinforcements now pull a random mix from the pool each fight instead of the same recurring lineup
- Mirror pursuers no longer leave their loose consumables behind when they fall
- U'kra's warded ally no longer stays invulnerable after U'kra is dead
- Neva's attacks were actually fixed

LOOT
- The Avarice capsule cooldown now applies to the whole party instead of a single character, so it no longer looks like everyone else can still farm one

ITEM CHANGES
- Thunderous Wrath now actually triggers its reaction

Update 1.4

An ULTRA champions pass, plus some stage direction for Vludber.

GENERAL CHANGES
- The Leech shard's buff no longer shows a description from another mod when both are installed

DIFFICULTY
- Fixed a vanilla bug that quietly cut ULTRA champions' turns short, so the ones with long action lists never got to finish them
- ULTRA champions now roam the world more actively while out of combat
- ULTRA champions no longer drop dead to the shadow curse while prowling Act 2
- The Shambling Mound now counts as a boss, as it always should have
- Vludber's Final Performance now hits like an actual finale
- Vludber has been rehearsing a brand new number for his audience. He would hate for anyone to walk out early
- Vludber lost his taste for locking the whole party down, though he still loves making people dance
- Vludber brings noticeably fewer hit points to the stage

LOCALIZATION
- Added Italian localization for AMP & AMP Plus (by @AlexMail)

Update 1.4.1

A follow-up to 1.4, mostly ULTRA housekeeping and a few item fixes.

GENERAL CHANGES
- Autoloot and autosell setting spells now respond to every player in multiplayer instead of only the host (thanks @Astrylian)

DIFFICULTY
- Enemies dropped into an already running fight by dynamic-combat mods now pick up the boss progression stacks like everyone else (thanks @André)
- ULTRA champions that ambush the party after a rest now drop rewards too, and no longer stand around abandoned if the party flees mid-fight
- ULTRA settings moved into their own container on the Training Ring, with a separate toggle for every champion of the pool
- Hosts running the secret mode now carry a button that shuts it off for good, with a double confirmation
- ULTRA champions slain during a boss fight now actually pay out their reward roll (thanks @Vludber)
- Doomflame's final detonation now burns each victim once instead of stacking extra gazillion hits
- ULTRA champions no longer vanish mid-fight when the boss who summoned them falls
- Vludber's newest trick now actually happens

ITEM CHANGES
- The Blinding Light Pendant's tooltip now mentions its once per turn limit
- The acid synergy's slime now packs up when the fight ends and no longer turns on its maker (thanks @Vludber)
- The Stigma of Temperance guards against Stun again as its prayer always promised, and the status tooltip now lists it (thanks @Vludber)

Update 1.4.2

A follow-up to 1.4.1, more ULTRA and item cleanup.

DIFFICULTY
- Fixed the heavy performance drops tied to the Eclipse and the difficulty modes (thanks @Vludber for the Osiris logs)
- Doomflame and Adrienne got a small survivability bump, and both can now raise a Shield against an incoming spell or blow
- Two U'kra no longer shield each other into an unbreakable stalemate when they arrive together
- Adrienne's ice cocoon works again and finally plays its freezing animation (thanks @Bish)
- The ULTRA champions names and titles show up in your own language again instead of falling back to English
- The ULTRA champions' opening lines are a little shorter now

ITEM CHANGES
- The penetration weapon shards (Pierce, Lance and the rest) once again let a weapon's elemental damage cut through enemy Resistance (thanks @脆脆鲨)
- Fixed a possible softlock from the acid slimes (thanks @Vludber)

Update 1.5

A big quality-of-life update headlined by the Loot Manager, plus a round of Ilmater and difficulty fixes.

GENERAL CHANGES
- The Training Ring learned a new trick: a Quick Resolve menu that settles a few of the game's most drawn-out quests on the spot, pick an outcome and the journal, experience and rewards sort themselves out
- The Training Ring can now toggle a Loot Manager that tidies autolooted capsules, runic shards, planar coins, magic artifacts, alchemy ingredients and camp supplies into their own bags, and the first-time wizard offers to set it up
- Auto-sell no longer crashes the game when an autolooted supply pack ends up inside a container (thanks @Astrylian)
- The auto-loot value filter's lower threshold now holds onto a bit more of the cheap stuff
- Ilmater healer parties no longer chain-heal themselves into an endless loop (thanks @auzyris)
- The burden an Ilmater prayer lays on its caster no longer opens them to all damage for six turns, only two
- The Stigma of Communion now renews its temporary hit points at the start of each of the bearer's turns instead of a single dose per combat
- The Stigma of the Bone no longer leaves its bearer open to every non-physical damage type
- Ilmater artefacts now spell out exactly how to unlock the use of their Prayers

DIFFICULTY
- Vludber's Game no longer restarts itself over and over once one of the teams is wiped, the show gets a proper curtain and Vludber finally joins the fight himself (thanks @Bish)
- ULTRA champions now also turn up when the player drops a boss within two turns
- Eclipse no longer erupts off a boss's borrowed shape, wildshaped and disguised bosses wait for their real health bar before turning the tide (thanks @notkman and @top5g04t)
- Ethel's doubles and other boss copies no longer bring an Eclipse of their own to the fight (thanks @top5g04t)
- Grym now actually leaves his AMP tricks at home in Stock mode (thanks @mordh)

ITEM CHANGES
- The Staff of Woe's Blight now recharges every combat instead of every long rest
- Axemaster's Edge finally notices your maneuvers, including the ones without a saving throw (thanks @zensho1112)

Update 1.5.1

Improvements to the Loot Manager and ULTRA mode.

DIFFICULTY
A few fixes to how ULTRA pursuers spawn and follow you between areas
ULTRA pursuers no longer arrive half dead and heal back to full while out of combat
A boss that briefly reads as non-hostile mid-fight no longer loses Eclipse for the rest of the fight (thanks @Bish)
Vasht now sees through invisibility, so stealth no longer trivialises the astral hunter
Valdryn's weakening aura now also blocks reactions

ITEM CHANGES
Axemaster's Edge now echoes every Battle Master maneuver (thanks @Zensho)

Update 1.6

Mostly cleanup and quality-of-life: sturdier acid slimes, a couple of new Training Ring toggles, a reworked Toxemia, and a hotter Orb of Fire.

GENERAL CHANGES
- Quick Resolve gains a Skip Lockpicking toggle that pops open any locked chest, door or container the moment you touch it
- The settings ring gains a Disable Gold toggle that keeps the party purse endlessly full, and empties it again when switched off
- Ring settings that tip the balance now carry a legitimacy warning in their description, and the finale tells you whether you beat the AMP on a clean run. This is only my personal view of what a legitimate AMP run is, as its author, and it may not match yours!

ITEM CHANGES
- The Orb of Fire swaps its set-locked fire bonus for Primal Combustion
- Toxemia's paralysis trigger has been completely reworked, taking your wide-ranging feedback into account
- Acid slimes now emerge shielded and survive their first turn instead of dying before they can act (thanks @Moshindo)
- Rarer acid gear spawns a tougher slime
- The acid slime's mutation growth now advances from every acid item, not just the orb
- Acid slimes no longer linger on the map after combat ends

Update 1.7

I strongly advise against updating if you need a stable game experience today(wait for the hotfixes, as bugs may occur). Major overhauls to all modes and the addition of new mechanics – now you can choose exactly which challenges to take on! 

GENERAL CHANGES
- The Loot Manager now comes with its own hotbar toggle
- The Training Ring can now set Void Capsule charges, the reroll window and the reroll cost by hand
- The Master Wizard now asks about affixes as its last step
- Interplanar chests are an affix now, so you decide whether they turn up at all, and how many
- The Trials of Tav shop now pays better and stocks deeper the easier you play, instead of the other way round
- The Training Ring's practice dummy, ranger, Berbalang and their cleanup are gathered under a single Test Spawns button

DIFFICULTY
- The Training Ring has a new “Affixes” section, where you can configure any challenge separately, regardless of the mode (except STOCK)
- Mirror Support now sizes every batch the same way, whichever way it was spawned (thanks @Bish)
- Only one Mirror Support batch can arrive per fight now
- A fresh ULTRA batch no longer shows up while a pursuers from the previous one is still hunting you
- ULTRA reinforcement can now be tuned from the Training Ring, with separate dials for batch size, how often batches arrive, and how hard survivors chase you down
- Pyre, Battle Instinct, Item Move Cost, Last Stand, Undying Will and Eclipse can finally be turned off on Hard
- Reckoning, a new affix: enemies wind up for a turn where their attacks land as critical hits, and you get one window to stop it. The crit stat escalation baked into the difficulty modes is gone, Reckoning takes its place, so hunting for an anti-crit item is no longer the only answer
- Pyre now burns at its own strength on each mode instead of one fixed step up on Hard
- Casual mode now grades enemies the same way the other modes do, so affixes work there as well
- Anti-Theft and Anti-Darkness-Stealth-Abuse now start switched off on Casual, but may be enabled
- Vludber no longer watches his own Game from behind an untouchable curtain. Cut the Commentator down and The Game ends on the spot
- Vludber's Final Number is a finale again, once per fight rather than once per spell slot
- Doomflame's efreeti bulwark can now be snuffed out with wet condition

ITEM CHANGES
- 43 artefacts across 77 effects now roll their saves against the Potency DC, so they no longer care whether your caster or martial
- A batch of helmets and boots no longer demands light or medium armour proficiency, so wizards, sorcerers and monks can finally wear them
- Vex now hits about as often as a creature of its size should, instead of whiffing its way through a fight
- The Skinburster now keeps its wielder safe from critical hits once its Force Conduit has built up enough

Update 1.7.1

Minor fixes for ULTRA and new affixes in existing saves.

GENERAL CHANGES
A number of internal setting tables could end up empty on a save carried over from an older version, quietly switching off whatever read them, they now rebuild themselves on load

DIFFICULTY
ULTRA mini-bosses spawn again on saves carried over from the previous version (thanks @Bish)
Reckoning no longer burns off the moment it appears
Eclipse keeps Sanctuary out of reach for a couple of turns after it tears it off (thanks @Bish)
Neva's reaction to Sanctuary now seals it for as long as she claims it does

Update 1.7.2

A large difficulty update. Enemies no longer get extra actions from their difficulty tier: the affixes give those out instead. The Pyre is weaker, and immunity to Prone moved from the difficulty tiers into Eclipse and Full Moon. The Orb of Shadow, the Shadow rings and the War rings were fully redesigned.

GENERAL CHANGES
- The Resonance shard now grants Primordial Chaos once per turn at most, it was far too strong
- Handing Astarion to the Gur and killing Karlach for Mizora give epic-tier rewards again

DIFFICULTY
- The Pyre no longer feeds on the death blooms that Ketheric and Myrkul plant around their arena (thanks @Talam)
- The Pyre now gathers a little less heat from damage dealt and from enemies dying
- Enemies no longer gain extra actions, bonus actions and reactions just for standing on a difficulty tier, the very top tier aside (level 20 mods). Extra resources combined with extra damage created too much pressure by Act 3, so the action economy changes moved to the affixes
- The Apex affix is now enabled by default on Normal and Hard, and it affects more enemies
- Apex itself was reworked and now only affects enemies above half health
- Neva makes fewer attacks on her own turn (thanks @Bish)
- Immunity to Prone was removed from every difficulty tier and moved into Eclipse and Full Moon instead (thanks @Talam)
- Health bonuses were reduced on every difficulty tier and on the boss-kill progression
- The extra damage from the Pyre is now elemental, and the rite adds one more damage type every few stages, so resistances and immunities work against it (thanks @Talam)

ITEM CHANGES
- Ability score bonuses across the collection now grow with rarity, and were lightly rebalanced
- The Arcanizer shortbows lose their general Dexterity bonus and give archery bonuses instead
- The Shadow rings now create darkness of their own instead of only extending darkness cast by someone else, and you choose when to place it
- The legendary Shadow ring now lets its wearer hide inside that darkness and stay unseen for as long as they do not move
- The War rings now carry a military rank that rises as you defeat bosses in open battle. The wearer picks a permanent doctrine once the rank is high enough
- The Orb of Shadow was fully redesigned, again: it was too strong on builds it was never meant for, and it now stays closer to vanilla shadow mechanics

Update 1.8

A major update involving rebalancing (as in 1.7) of difficulty and items, as well as qualitative improvements to ULTRA.

GENERAL CHANGES
- The dodge Runic Shard finally does what it says and stops you provoking opportunity attacks while under Mage Armour
- The Divine Touch shard's tooltip now states its real cooldown
- Bosses now get a saving throw against the slow from the Drift shard (thanks @Bish)
- The Pendant of Glacial Destruction now also reacts to Eldritch Blast from blast overhaul mods, not only to the vanilla spell (thanks @Dreamyful)
- The Pledge shards give a stronger reward for worship
- Gale counts as a worshipper of Mystra for her Pledge shard, even without an Acolyte shard or cleric class

DIFFICULTY
- The extra damage from the Pyre is now elemental, and the rite adds one more damage type every few stages, so resistances and immunities work against it (thanks @Talam)
- A few small changes to how the Pyre works
- A few small changes to how Eclipse works
- Adrienne now properly seals herself in black ice
- Neva's ability drain lets go when the fight ends (thanks @gnomus)
- Zephra's tailwind no longer cuts through effects that prevent critical hits
- Reckoning no longer cuts through effects that prevent critical hits
- ULTRA mini-bosses no longer freeze on their turn and hang the fight
- ULTRA mini-bosses now drop coins and void capsules less often
- ULTRA mini-bosses called into a fight in progress shall no longer take a turn before you can answer them (thanks @Bish)
- Valdryn's aura no longer takes your reaction for free: every round you get a Wisdom saving throw against it, and stepping out of the aura frees it at once (thanks @Bish and @gnomus)
- Affixes now really switch off in Hard mode: the item move cost, Battle Instinct and the anti-stealth rule all kept working there (thanks @HongJul1)
- Anti-Theft now also switches off in Hard, apart from the attitude a trader remembers after a pickpocket
- An affix you switch on by hand now works in Casual mode as well
- In Vludber's Game, a player who kills someone from their own team now dies on the spot
- Vael speaks in combat again
- Vael now keeps his own name while he wears the face of a party member
- Every ULTRA mini-boss was rebalanced after a pass over their behaviour, their design and how hard they hit
- Hiding in a fog or darkness cloud now gives you the intended number of turns before enemies break morale, also on saves started before this change
- Reckoning now shows itself in ordinary fights: it can flare as a fight opens and when an enemy drops below half health, and a dying enemy passes it on more often

ITEM CHANGES
- The Umbral Trail rings now really lay their darkness, and the first ring's cloud lingers long enough to matter (thanks @Bish)
- The Brand of Darkness keeps the charges it collects instead of losing one every round, so its penalty finally grows the way its tooltip says
- The poison rings keep feeding Toxemia instead of seeding it once, so the poison can finally build towards its breaking point
- The Master's Cloak of Happy Ending now heals the wearer for a share of their own health instead of the attacker's
- Reaping now burns each Brand of Darkness for every charge it held
- The Burden of the Crying God now only leaves you vulnerable to physical damage
- Graviton Pulse no longer slows bosses for free: they get a saving throw against it, and it can catch them only once per turn (thanks @Bish)
- Bosses now get a saving throw against the slow from the Mark of Astral Ooze
- Bosses now get a saving throw against the bleeding and the chest wound from the Mark of the Grey Hare
- The shadow monk armour now carries a short shadow teleport of its own, so a wearer without Shadow Step can still set off its bonuses

Update 1.8.1

A follow-up to 1.8. Enemy pressure now leaves room for your defences to answer it, and a few enemies, items and settings were corrected as well.

GENERAL CHANGES
- The trial of Hubris of Kroneth no longer has one correct sequence of answers
- Autoloot is now turned on by default, and the hotbar toggle still switches it off for a character

DIFFICULTY
- Reckoning no longer grants guaranteed critical hits. A marked enemy now scores a critical hit on almost any attack roll and adds extra damage dice to it, and bosses are marked one turn in advance (thanks @Talam)
- Enemies now spend the Pyre when they attack or cast spells at your party, and the rite was calibrated further from community feedback (thanks @Bish, @Talam, @gnomus)
- Tickhara now draws a bow to fire her Sunbolt and has one more bonus action
- Vael's copy of a Fighter no longer ripostes for free (thanks @Talam)

ITEM CHANGES
- Gloves of Starlight's Embrace are now genuinely strong against bosses
- Nameless King's Form and Chaotic Undeadification now also give immunity to Bone Chilled. An undead body is no longer stopped from healing by an effect made for the living

Update 1.8.2

Runic Shard slots now step evenly across the rarities, and ULTRA mini-bosses wait longer before they bring reinforcements or drink a potion.

GENERAL CHANGES
- The Loot Manager now has a seventh bag for junk, and it fills itself as you loot
- Uncommon, Rare and Epic items now take one more Runic Shard each, so the slots step evenly from Common down to Legendary
- The bonfire Runic Shard's passive now has a proper icon

DIFFICULTY
- ULTRA reinforcements no longer arrive before the party has traded damage with the boss
- ULTRA mini-bosses now save their healing potions for the moment a fight has actually turned against them
- Valdryn's aura release now hits each target only once, and one beam takes almost all of the target's health (thanks @gnomus)

ITEM CHANGES
- Clothes of the Superior Assassin now give their extra Critical Hit dice after any Shadow Step, including the one the clothes grant themselves (thanks @Tuko322)
- Ancient Bulwark's Blur now runs on a timer, so its roll matters on every turn of the fight

Update 1.9

A major update covering three things: the rewards of Act 3, the economy around reactions, and how strongly enemies scale in the late game.

GENERAL CHANGES
- Reactions were the strongest currency in the mod, so the whole economy around them was rebuilt, and a character's reaction points now show on the resource panel (thanks @gnomus)
- The Legendary enchant shards no longer damage their bearer, who is now Vulnerable to the element the shard grants

DIFFICULTY
- Enemy ability DCs now match the difficulty mode you play on. They are taken from the creature's own maneuver save DC or spell save DC, so they rise with its proficiency bonus
- Nere is now a full boss of the mod: he is a little stronger, he gives a reward of his own, and he counts toward the boss progression
- ULTRA mini-bosses now fall into Eclipse once they are down to half their health, and they climb a difficulty tier - once most of the world's bosses are dead
- An ULTRA wave now sends every mini-boss once before any of them returns (thanks @Talam)
- ULTRA mini-bosses that missed their fight now wait for the party to leave camp before they strike (thanks @Talam)
- ULTRA mini-bosses summoned into a fight now bring their Battle Instinct with them on the turn they arrive
- Vludber's Game no longer takes performers who cannot die, and a show that runs too long now ends on its own

LOOT
- Three more Act 3 fights now open a reward window: the Steel Watch Titan, Mystic Carrion and the incubus of the House of Hope (thanks @Talam)
- Reward windows in Act 3 now offer a runic shard and a coin beside the gear, so a reward you cannot use still moves you forward (thanks @Talam)
- The House of Grief, the hag's line and Ptaris can now give a legendary reward, and no Act 3 boss is left without a chance at one (thanks @Talam)
- Mystra's vault and three other hidden caches in Baldur's Gate are no longer empty
- The deepest vault under the Counting House now holds a legendary find
- Turning a runic shard into a coin now works better the rarer the shard is (thanks @Talam)
- The Flind now leaves a runic shard and a piece of gear behind
- The junk bag now collects plain gear below Uncommon quality, along with barrels and crates, and it leaves gold and consumables alone. Loot Manager bags come back when you sell or lose one, so selling the junk bag with everything inside it is the way to empty it
- Interplanar chests spawn in Stock mode again (thanks @Mordh)

ITEM CHANGES
- The Orb of Shadow no longer brands enemies who are fighting somewhere else, and its sight in darkness no longer fills the combat log (thanks @Talam)
- Prayer of Preaching, Prayer of the Thread and Prayer of the Prophet now cost no action once per turn at every rarity. Holding several allies under a Stigma no longer takes your whole turn
- The Cloak of the Sixth Pit at Very Rare and Legendary now enters a fight with its free prayer ready, so the first prayer of the fight costs no action either
- Robe of Supreme Defences now uses your highest spellcasting ability for its saving throw bonus (thanks @Inviniatar)
- Dried Mucous Ring now raises its acid aura again on every turn you spend in acid (thanks @Inviniatar)
- Boots of the Skybound Warrior now give three times as many temporary hit points when you jump
- Voss' Silver Sword now recharges its Wrathful Smite every turn
- The Stoker's Beam Cascade now costs a bonus action, and the emitter carries one energy cell fewer
- Military ranks from the War rings now finally show their own icons

Update 1.9.1

Some fixes, mainly for ULTRA.

DIFFICULTY
- ULTRA reinforcements now each pick a party member of their own
- Setting all three ULTRA spawn options to their hardest now changes more than the numbers
- Reckoning now hits a little harder on the turn it fires
- Eclipse now stays off for the rest of the run once it is switched off on Hard (thanks @Air1Fire)

ITEM CHANGES
- Knuckles now give their base damage die to the Giant Barbarian's kick as well (thanks @Константин и никак иначе)
- Choosing a war doctrine now plays its cast animation

Update 1.9.2

Bernard becomes a boss of the mod, merchants stop losing their void capsules, and a long line of reported bugs is gone.

GENERAL CHANGES
- Shard series now share a single slot in the drop pool, so a lone shard turns up as often as a whole family(Damage types ones etc.)
- The Legendary enchant shards no longer make you Vulnerable to their element, they are a clean damage bonus now
- Cantrips carried by the Runic Shard of Pact can now put both hits into the same target, and self-cast cantrips like Blade Ward no longer get blocked by it (thanks @HongJul1, @Merc)
- The Runic Shard of Celerity now describes what it grants (thanks @Vludber)
- The legendary Underdark orb no longer re-brands its target endlessly from the brand's own damage (thanks @Tuko322, @Talam)
- The Daylight VFX setting now dims the glow on lit creatures too, not only the spheres (thanks @Bish)

DIFFICULTY
- Bernard now counts as a boss: Pyre, Eclipse and the other difficulty systems reach his fight, and beating him opens a reward window with a lightning slant (thanks @Inviniatar)
- Boss kills on Hard now feed less damage into the enemies that come after (thanks @Talam)
- Eclipse bonus damage reduced by ~25%
- ULTRA mini-bosses now carry a single healing potion (thanks @Bish, @Talam)
- U'kra no longer flies into a permanent rage while she keeps healing her allies
- Adrienne's ice cocoon now actually triggers when her health runs low

LOOT
- Merchants now carry two void capsules as personal stock, and they no longer disappear when the goods refresh
- Loot Manager bags no longer multiply when sent to camp or dropped; selling or losing a bag still brings a fresh one (thanks @Hatul)
- The junk bag now also takes paintings, plates, cups and skulls

ITEM CHANGES
- Force Mauls were fully redesigned
- Dwarf King's Golden Pendant was fully redesigned
- The Skinburster is now Very Rare
- Master's Cloak of Preparation grants less Initiative
- Potion of Invulnerability now costs 2000 gold
- Luminous Commotion at Very Rare and Legendary no longer puts Radiating Orbs on you when the damage came from an ally or from yourself (thanks @gnomus)
- Toxemia from the Arcanizer poison rings no longer falls off the moment it lands (thanks @Inviniatar)
- The Balduran Helm now also blocks the lethargy that follows broken Haste (thanks @Bish)

Update 1.9.3

Force damage is now a synergy instead of a pile of bonuses. Moleculation sits at the centre of it: it grows through five degrees on the enemy, and every artefact in the branch either feeds it or spends it. The redesign is raw, quite hasty(untested), and further revisions are expected.

GENERAL CHANGES
- Moleculation now grows through five degrees, each one heavier than the last, and a creature that dies under it sets off a gravity wave
- The Runic Shard of Singularity was fully redesigned
- The Runic Shard of Drift was fully redesigned
- The Runic Shard of Steadfast was fully redesigned and renamed
- Auto Loot is now disabled by default

DIFFICULTY
- ULTRA now turns itself off on Casual difficulty and in Stock mode. Switching back to Normal or Hard makes it available again (thanks @Weavil [OWLC])

LOOT
- Void capsules now actually appear in merchants' stock

ITEM CHANGES
- Glacial Destruction now deals force rather than cold, so Wet no longer doubles it, its share of maximum health rises evenly across the rarities, and the mark has to beat a saving throw before it lands
- The Force ring, amulet and orb were fully redesigned around Moleculation
- Amulet of the Sapphire Depths now shows proper visual effect
- Runes of Clan Rednag now flash the Rune of Power effect on every gained charge
Fire Seed now burns with its own visual over seeded enemies instead of the generic crit mark
- Helmet of the Third Day now grants its slashing immunity only below half health

VISUALS
- Small VFX fixes for ULTRA mini-bosses

Update 1.9.4

Some fixes, plus new visuals for Moleculation and Reckoning.

DIFFICULTY
- Ketheric no longer carries the Full Moon over into his apostle form. The apostle now counts as its own boss: it earns the Full Moon and the Eclipse on its own health, and calls its own ULTRA reinforcements (thanks @Bish)
- Valdryn's Aura of Dread now actually asks for its Wisdom Saving Throw every turn (thanks @Bish)

ITEM CHANGES
- The Inferno's Whisper now keeps making Silenced creatures vulnerable to fire after a long rest (thanks @Bish)
- Previously unpublished mechanical changes to force synergy have been corrected

VISUALS
- Each degree of Moleculation now shows its own icon and its own visual effect, growing heavier with every degree
- Reckoning now has its own visual effect on the carrier's hands and above their head

Update 1.9.5

LOOT
- Merchants now stock void capsules that suit what they trade in, one or two each
- Void capsules and planar coins are no longer worth thousands of gold outside the Trials of Tav shop

ITEM CHANGES
- Primal Courage Tincture now lowers the Critical Hit threshold for every attack while drunk, not just unarmed ones, and adds Intimidation and Constitution saving throw bonuses

Update 1.10

A major update covering the polish of the War rings, as well as a full redesign of a whole family of epic Runic Shards.

GENERAL CHANGES
- The ten penetration Runic Shards are now ten tinkers, each a loss on its own that pays out from what else is set in the weapon or from how the fight stands
- War Ring doctrines are now taken one step at a time as you rise, and doctrines of different cultures stack instead of replacing each other
- A seventh war doctrine has been added
- Some of the war doctrines were rewritten
- War Orders now come with the rank of Captain, and every rank above it lets you give them more often
- Mutating your ooze is no longer a spell and can no longer be countered (thanks @Bodrick [TAV])
- The Runic Shard of Weave Surge now rerolls the cantrip attack roll its text promises (thanks @Uturn)
- The Runic Shard of Warding now states the radius its temporary Hit Points reach

DIFFICULTY
- Everything that puts out the Pyre now works 25% better (thanks @Bish)
- A boss now enters the eclipse once in its life (thanks @Vludber)
- An eclipsed boss can no longer be made to flee or approach by Command (thanks @Bish)
- ULTRA mini-bosses now stay prone when the effect comes from an item, a surface or a status you placed on them
- An ULTRA mini-boss that stops acting on its turn now attacks the nearest player. This one is not certain yet
- Alpha no longer lands on party members (thanks @Vludber)
- Tickhara's light now falls on whoever joins her fight, and breaking off does not put it out (thanks @Vludber)
- Valdryn's charged strike now hits a single target, and his aura release can no longer reach a target under Sanctuary (thanks @Vludber, @Bish)
- Doomflame no longer pays health for a counterspell, his twin cast is spent on what he throws, and Efreeti's Bulwark now breaks against water he manifests into (thanks @brothero_)

LOOT
- The Swamp Void Capsule is now Very Rare, and is priced and found as rarely as the ring capsule
- Bernard's loot now drops as it should (thanks @wh1te_ghost)

ITEM CHANGES
- Percolation now reaches the wearer while an enemy under Moleculation stands within range
- Overshadowing now wraps you in Veil for three turns
- Master's Cloak of Wonders now counts a High Half-Elf among the elves its last gift is written for (thanks @Vludber)
- Duergar Torture Ring now answers to Reverberation from any source (thanks @Air1Fire)
- Chaotic Burst now deals the damage its text states (thanks @frivr [xdd])
- Spy Captain now hides you again after you act outside combat (thanks @Sir Saint Savage)
- Lord of War no longer lists a lower Critical Hit threshold, which the artefact grants on its own from Rare up (thanks @Uturn)
- The Booming Blade granted by Kyzr's commissioned armour now shows its proper icon (thanks @Air1Fire)

Update 1.10.1

A new face joins the ULTRA ranks, and Dark One's Grace no longer leaves its wearer neither dead nor alive.

GENERAL CHANGES
- Quest items and keys taken from a body no longer go to the camp chest (thanks @ldley)

DIFFICULTY
- A new ULTRA mini-boss has joined the pool: Tesshin, Blade of House Hozana, a swordsman who has spent a very long time trying to die and has not managed it yet (as part of paid commission from @gnomus)
- Eclipse now clears more harmful conditions

ITEM CHANGES
- Dark One's Grace no longer makes you invulnerable and now stops only weak hits. Players wrote to me about this for a long time: the wearer ended up neither dead nor alive, and the game could lock up
- Moleculation has been polished further
- Shockfront no longer hits your own party
- Smoke Spirit Essence now turns you Invisible once per turn at most, and the chance is lower on every rarity
- Master's Cloak of Happy Ending now restores a smaller share of your maximum HP and absorbs its charges once per turn at most
- The force orb no longer sets off an endless chain of gravity waves outside combat (thanks @Cacao_Spy)
- Tidal Disruption now adds its damage against Slowed enemies, as its text states
- Gravity waves from the force artefacts now reach only those already in the fight (thanks @wh1te_ghost)

Update 1.10.2

Some important ULTRA mini-bosses fixes.

DIFFICULTY
- ULTRA mini-bosses have had their behaviour reworked to run better, and this may also stop them freezing for no reason
- Eclipse no longer erupts outside combat, and a boss now actually reaches it only once in its life. The resistances and immunities it grants now name Eclipse as their source
- Tesshin can now be killed permanently, and he now drops his reward (thanks @Vludber)
- Vael's copy of a Cleric is now more mature and no longer useless

ITEM CHANGES
- Potent Magic charges now have a single limit shared by every item that grants them (everyone knows why)
- Gravity waves from Moleculation no longer set each other off in a chain, and now reach enemies only
- Nucleation now gives one charge of Moleculation per attack, and no longer marks a dying enemy


Update 1.10.3

Almost nothing this time. A few small things.

GENERAL CHANGES
- Moleculation has had a few small adjustments
- Anvil, Lead, Brick, Dissonance and Forestall shards now actually add the damage their tooltips promise (thanks @alexandr7088, @zeno3285)
- Arcane Surge shard now actually gives Arcane Acuity for killing a creature with a spell. It no longer gives Intelligence (thanks @wh1te_ghost)
- Drift shard now works the way its text describes
- Brick shard now names what its damage waits for (thanks @Air1Fire, @zeno3285)

DIFFICULTY
- The Reckoning affix is now called Massacre. Its extra damage has been reduced by 66%
- Zephra has had small behaviour changes after all the feedback. She leans on her blizzard less
- More fixes for ULTRA mini-bosses that freeze
- Battle Instinct no longer returns to a boss when you load a save in the middle of a fight
- Tesshin no longer leaves the Gaze of the Dark One behind him. He also no longer returns after you have already put him down. He now has more health and uses his reactions more freely. He also has his own toggle on the Training Ring, like every other champion of the pool (thanks @Uturn)
- Doomflame's death explosion is now visible (i hope)
- Vael no longer copies a party member without their armour (goodbye naked dudes)
- Gift of the Black Star now holds against Tickhara's Solar Curse and Eye of Ra (thanks @Vludber)
- Tickhara's curses now leave a creature that has stopped being her enemy
- Gaze of the Dark One now also marks you while an ambush waits for you to leave camp
- Grym no longer pulls you in or calls his drones in Stock mode (thanks @Mordh)

LOOT
- The Void Capsule no longer breaks down one legendary ring on the odds of a lesser rarity (thanks @ebonyape, @.mrten., @fateo1)
- A Void Capsule on a campaign that started before this update no longer hands your coin back instead of a reward. Celestial coins work in every capsule there again (thanks @ebonyape, @.mrten., @fateo1)

ITEM CHANGES
- Master's Cloak of the Hydra now calculates its acid toll from your own health (thanks @Inviniatar)
- Toxemia now loses a charge no more than once per turn (thanks @Air1Fire, @yjonu., @Inviniatar)
- Family Ring now adds its radiant damage to your attacks only. The bonus is slightly stronger (thanks @_.bananas._)
- Defender's Flail of Easthaven has been significantly weakened. The buff it got was a mistake
- Bulwark of Light now actually burns the one who hits you (thanks @Bodrick [TAV])
- Gauntlets of Reflection now build Lightning Charges from foes carrying Reverberation
- Rings of Underdark now lay the Darkness Cloud they promise (thanks @unknowngabi)
- Orb of Light now marks the one who hits you with a Radiating Orb. Its Daylight names the once per combat limit (thanks @Air1Fire)
- Orb of Lightning now states that its Legendary Chain Lightning strikes two targets (thanks @Air1Fire)
- Chronomancer's Stride now keeps the Temporal Distortion toggle where you left it (thanks @Bish)
- Hat of Eternal Echo now adds the damage its Very Rare version promises (thanks @Air1Fire)
- The Spy Captain amulet now brings its invisibility back after you act outside combat (thanks @Sir Saint Savage)
- Last Breath now hands its Action Surge at the start of your turn (thanks @Bish)


Update 1.10.4

Bonus damage now works one way across the whole mod, plus a few critical crash fixes.

GENERAL CHANGES
- Bonus damage has been redesigned across the whole mod: a bonus now applies once to the attack it belongs to. Smites and item effects that trigger on a hit no longer collect your whole set of bonuses. Item text now uses "also", "extra" and "additionally" for the three kinds of bonus damage, the book explains what each one does
- War Orders can now also be given outside combat
- The Devout shard now knows which god you pray to: pray to a dark one and its guardians answer in necrotic damage

DIFFICULTY
- By popular request, the Battle Instinct fix from the last update now works on campaigns that were already running when it arrived
- [CRITICAL FIX] Tesshin now actually stays down after you defeat him. No more endless pursuit (thanks @Uturn)
- The Gaze of the Dark One now marks your whole party and leaves all of it at once
- ULTRA mini-boss abilities are no longer countered "automatically"
- Adrienne has been reworked after a lot of feedback into a much more serious threat to anyone fighting in melee

ITEM CHANGES
- [CRITICAL FIX] Orb of the Underdark no longer crashes the game when a summon cannot get its Sight in Darkness (thanks @Bish)
- [CRITICAL FIX] Strategist no longer crashes the game when a summon cannot get its bonus
- Halo of Hope now fits the synergy it was built for


Update 1.11

A big round of critical fixes, including crashes that came from applying some AMP statuses.

GENERAL CHANGES
- Fixed a crash from effects that roll a saving throw after the creature that applied them is gone (thanks @CheeseFairy, @Yoko)
- Fixed a crash from bonus damage that grows with stacks on unarmed attacks (thanks @Lakil, @CheeseFairy)
- Several problems with the Pledge Runic Shards have been fixed (thanks @Air1Fire)
- The Runic Shard of Extended Reach now works with every kind of melee attack, including some spells (thanks @Air1Fire, @Nomit)
- The Runic Shard of Indomitable now triggers once per fight (thanks @wh1te_ghost)
- The Runic Shard of Reflection now says what happens when something tries to kill you outright (thanks @Inviniatar, @heatray, @Vludber)
- The Runic Shard of Finisher now adds a fixed amount of damage on a critical hit
- The Runic Shard of Fist now describes its damage more clearly (thanks @Zeno)
- Weapons designed for summoned creatures now work only in their own hands. The earlier fixes have been reverted
- Toxemia now comes off the creature it paralyses

DIFFICULTY
- ULTRA mini-bosses now show which conditions cannot touch them
- Kavir and U'kra now have status immunities of their own
- Tickhara and Vludber can finally no longer be put to sleep
- Valdryn's aura should now show its Wisdom saving throw in the combat log (thanks @Bish)
- Ansur should now get his Eclipse correctly (I still have no solution for his two phases) (thanks @Inviniatar)

ITEM CHANGES
- Many fixes for the new mechanic of the War Rings (thanks @Air1Fire, @Uturn, @Vludber)
- Dagger of Fate now keeps the souls it has taken when you unequip it or its wielder dies. A long rest still empties it (thanks @Inviniatar)
- Chronomancer's Stride now answers to Moleculation. Its legendary passive that never worked has been removed (thanks @Uturn, @Bish)
- Venom Surge no longer adds its poison three times to a single spell
- Venomous Siphon now adds its poison only to damage that is not an attack or a spell
- Void-Touched Circlet now hands out Void Capsules far less often (thanks @Zheaniv)
- Answered Prayer now also waives the Bonus Action when another item has moved the prayer onto one (thanks @Bodrick [TAV])
- Vampiric Gloves now hand over their second touch as a Bonus Action, like the first (thanks @Air1Fire)
- Othismos now actually makes its free strike once per turn (thanks @Inviniatar)
- The Son of Legion shield wall now covers a neighbour once per turn
- Dagger of Storm Wind now triggers once per turn
- Orb of the Underdark now hands the wearer sight of their own when they kill a creature inside a Darkness cloud (thanks @Bish)
- Arcane Infusion from the Weavebender Greaves now actually spends its charge on a single weapon attack (thanks @wh1te_ghost)
- Gauntlets of Precision now give their attack bonus and their reroll to off-hand attacks as well (thanks @Air1Fire)
- Heir's Poise now brings its reroll to off-hand attacks as well
- The Prayer of Ilmater's artefacts now opens for paladins of Ilmater and for a faith added by another mod (thanks @Air1Fire)
- Gear that rewards worship of Lathander or Talos now counts paladins of those gods among its worshippers
- The legendary Royal Messenger's Ring now states the Armour Class its own charges give, so it no longer reads the same as the Very Rare one (thanks @Bish)
- Gnoll Three-Finger Concentrate has had small wording changes (thanks @Undine)

LOCALIZATION
- Fixed the wrong version numbers on localisation strings that made every language fall back to English



Update 1.11.1

Big changes to the Pyre, important work on crit damage dice, and a couple of fixes from kind people on Discord.

GENERAL CHANGES
- Crit damage dice have been reworked across the collection: some branches changed a lot, so that power is shared fairly between synergies in the endgame
- The Fist shards (big family across all rarities) now work for a caster as well
- Mutacid's mutation picks now sit among the temporary hotbar tab and no longer hold your concentration. Some mistakes in their descriptions are fixed as well
- The Mind Shackle shard now Silences its wearer for taking damage without Concentration, considering how easy protection from paralysis was to get
- Kroneth's Vow of Silence is now broken only by a spell, so a fight carried by weapons keeps it (thanks @squesque)
- Reclamation now returns a Runic Shard set into a weapon after you have loaded a save
- Effects that skip Booming Blade now also skip the blade an item grants for free
- The Brutality shard is now Legendary, as part of the general toning down of crit damage dice
- The Precision shard now correctly counts as Very Rare in the Trials of Tav Shop
- The Gamble shard now states that damage dice added by other effects keep the weapon's original die (thanks @hatul91)

DIFFICULTY
- The Pyre has been fully redesigned and rebuilt around a lot of feedback. It now really gives boss fights a rich escalation and a difficulty that moves with you, custom bosses included. The former Pyre is still available as its own affix, considering how radically the whole mechanic changed. The main complaint from the loudest critics on Discord was how unevenly the Pyre landed on, say, the fight with Gut against the one with Dror Ragzlin, where a larger crowd of enemies changed the picture completely and made boss fights either very easy or very hard. The new Pyre is meant to be a smarter rubber band for difficulty, one that takes into account how differently story boss fights are filled. And of course, further reforms can be expected
- ULTRA reinforcements now come once per fight, however many times the boss gets back up (thanks @frivr)
- ULTRA mini-bosses now read difficult terrain each in their own way, going by what they are good at (thanks @Bish)
- Small changes to how the reward at the end of a LEGITIMATE run works

LOOT
- The capsule reward window now offers three Different capsules (thanks @balistafreak)
- Void Capsules on a campaign older than their settings now read those settings again, so charges, rerolls and salvage work as they should (thanks @Tøken)
- An empty reward cube no longer stays in your pack once the capsule has handed the reward over
- The ceremonial weapons from Rosymorn Monastery no longer go into the junk bag

ITEM CHANGES
- The second touch from the Vampiric Gloves now actually costs a Bonus Action, like the first (thanks @Air1Fire)
- Liquid Resonance now lays its Reverberation only in combat (thanks @daz96050)
- The Cultist's Shield has been slightly reworked, considering the known problem with Saving Throws

LOCALIZATION
- German now names the Wizard class Magier, the way the game does (thanks german friends @lukaria. and @Sir Saint Savage)

VISUALS
- The ULTRA spawn intensity button on the training ring now carries the settings icon instead of another ULTRA one
- The Item Move Cost affix button got an icon of its own instead of the shared settings one


Update 1.11.2

The new Pyre gets its first round of repairs, plus a few small fixes.

DIFFICULTY
- Otherworldly Scorch no longer makes its bearer roll a fear save against their own actions. It now blocks healing only from its eighth stage (thanks @Bish)
- Douse the Pyre now pulls down the level its target settles at
- Subdue the Pyre now actually gives back the Bonus Action when you pass its Strength Saving Throw
- The Pyre now ignores damage resistances only on its highest steps
- Enemies no longer lose the Pyre status above their heads when its level changes
- The Pyre now actually grows every round in a fight it joined after the fighting began
- Saving Throws forced by the Pyre now name their source in the combat log
- Pyre step tooltips no longer leave blanks where a number should be (a Divinity Engine limit, unfortunately, so no pretty text today)
- Pyre Equilibrium now shows one icon on every step
- Eclipse now blocks every harmful condition, not only the ones its tooltip named

LOOT
- Fist Runic Shards now take one place in the drop pools as a single family. Very Rare and Legendary rolls no longer fill up with the ring shards that only an unarmed character can use
- Void Capsules now reach merchant stock more reliably

ITEM CHANGES
- Halo of Hope now names the spell it grants and who else in the party receives it (thanks @Vludber)
- The Still Mantle now blocks Critical Hits while its own Blade Ward is on the wearer, not on the attacker
- Time Lock now states its duration correctly
- Frozen Instant now links Attack Rolls in its description

LOCALIZATION
- Brazilian-Portuguese localization brought up to date across the whole mod (by @Renan from Brasília)


Update 1.11.3

The Pyre steps out of Normal difficulty and a group of items that handed out endless Charisma now has ceilings.

GENERAL CHANGES
- The Runic Shard of Shadow now works exactly like the same mechanic in the base game (thanks @dragon)
- The Runic Shard of Relentless Drive now hands a Bonus Action back only once you have spent one (thanks @Air1Fire)
- The Runic Shard of Netherese Seed now actually detonates once per combat (thanks @Uturn)
- The Runic Shard of Tithe now gives more enchantment the fewer different Runic Shards sit in the same weapon. It no longer lowers Attack Rolls (thanks @wh1te_ghost)
- The Runic Shard of Sever now breaks the target's Concentration on any hit (thanks @wh1te_ghost)
- The Fist Runic Shards now show their own name in the damage list instead of an internal code
- Toxemia now works only in combat. Its poison no longer ticks outside a fight (thanks @Drothar [影の領域])
- The Netherbrain now actually counts as a boss
- The AI fix for Fog Cloud has had small corrections, so it stays consistent (thanks @Bish)

DIFFICULTY
- The Pyre is now off by default on Normal. On that difficulty a legitimate run no longer depends on it, whichever of the two versions you switch on. I think the new Pyre is too complex a mechanic, especially for someone who has only just met the game (since it asks for deep knowledge of bg3) and it should not be forced on anyone in the *recommended* mode. The Pyre stays required only for Hard Mode, where it belongs
- Choosing between the two versions of the Pyre now holds: switching one of them on no longer lets the other one return on the next load (thanks @Balor [ATD])
- The Pyre no longer lands on a creature on top of itself, so what happens in a fight should read more clearly
- Important fixes for Subdue the Pyre: it now subdues the way its description promises (thanks @Bish [TAV])
- Douse the Pyre now actually counts a second use in the same turn (thanks @Bish)
- Draining an ability score to zero now kills the creature, the way it does in the base game. Curse of Weakness and the collection's other draining effects all count now (thanks @Bish [TAV])
- Bosses no longer flee combat and walk off the level. Turning the response off in the Training Ring now stops it in a fight that already started (thanks @хльфмх)
- Doomflame's "Efreeti's Bulwark" can now be put out with water, the way its description promises (thanks @Uturn, @Bish [TAV])
- Allies fighting at your side no longer count as ULTRA bosses. When such an ally dies (it's you, Aylin!), they no longer call in endless mini-bosses (thanks @Vludber)
- ULTRA mini-bosses no longer come after you while your party is at camp (thanks @Bish)

ITEM CHANGES
- Jester's Comfort Cap now has a ceiling on the Charisma it grants, set by its rarity. It comes with a penalty passive now
- The Nightshield now has a ceiling on the ability scores it grants. Its protection now ignores damage below a threshold. It no longer makes the wearer fully invulnerable
- Flail of Glory now converts less Charisma into damage on its higher rarities. A new unique mechanic has been added to make up for it
- Bard's Birthright now grants less Charisma. It carries a unique bardic ability now
- Human Captain's Ring now puts the same ceiling on the Charisma from its buff as on its passive
- Master's Cloak of the Prince now raises Charisma to a lower value on its Legendary version, in line with its other rarities
- Medallion of the Holy Protector no longer loses its Aura of Protection when the wearer falls unconscious or is Incapacitated. It carries a new unique mechanic now (thanks @Air1Fire)
- Extra damage from War Ring ranks and doctrines now lands once on an unarmed attack. Every other item and buff that adds damage to weapon attacks counts the same way now
- The Aura of Terror from Bane's Tyrannical Vestments now returns in every fight
- Ring of Emerald Dreams now loses its bonus on your first weapon attack as well as on your first spell
- Arcanizer: Son of Legion now actually shields an ally without spending a Reaction when its wearer is Human (thanks @Forest)
- Trident of the Depths can be equipped again (thanks @TapoIII40k)

LOCALIZATION
- The English wording of the Pyre buttons now reads more clearly


Update 1.12

Too much content: 133 new Runic Shards go into the pool, community item rebalances, and Vludber comes back as the Chaos King.

NEW ITEMS

- Added 133 new Runic Shards, built to deepen the combinations and to mix synergies that never met before
- The Joltshooter now also drops in three higher rarities (designed by @wh1te_ghost)
- The Harmonic Dueller now has two stronger successors (designed by @wh1te_ghost)

GENERAL CHANGES

- Fixed the overflow that crashed any save at 70% loading when the DnD 5.5e mod was installed. Make sure you also have the compatibility patch installed
- A few boring Runic Shards are gone from the pool. Many others changed their rarity or their strength, from the feedback gathered over the summer
- Every Runic Shard now states in its description whether a second copy of the same shard adds to the first. The same note appears on the arcanized item itself. Shard families that replace each other will keep their own wording
- The Training Ring now has a button that summons every Runic Shard in the collection, sorted into containers by slot (thanks @Vludber for the solution)
- Quick Resolve now has a button for the Arcane Tower. One press brings the power back, settles Bernard peacefully and puts his ring together with Omeluum's ingredients into your bags (thanks @Vludber for the solution)
- As part of paid commission from @Silvio, added a Training Ring setting that gives up its tester functions for good. The chests, the shard vault, the cooldown reset, Quick Resolve, the endless gold and the practice targets are all removed. Your difficulty settings are also fixed at the same moment: after that you can still make the run harder, never easier. The choice cannot be taken back
- The Noblestalk now actually removes every negative condition, including the ones bosses inflict (thanks @Vludber)
- The Runic Shard of Glass now gives its wearer Disadvantage on all Saving Throws as the price for its critical hits. It no longer stuns them when they take damage, since protection from stun is easy to find in the collection (thanks @Vludber)
- The Runic Shard of Warlock's cantrip bonus now carries the cantrip's own damage type and lands inside the spell's own damage. A second copy of the shard adds to the first again. The bonus is now exactly the wearer's Strength modifier (thanks @Uturn)
- The Runic Shard of Elemental Harmony now works with Tidal Wave from Mystra's Spells, when cast while standing in water (thanks @Lexa Stormborn, that was needed)

DIFFICULTY

- Vludber has been fully redesigned. He no longer turns the fight into his Game and no longer watches it from the side. He is the Chaos King now: at the start of every turn he throws one of 47 Chaotisations onto the field and does other weird things (thanks @Vludber for contributing his Paramagic mod assets)
- The Pyre now scales with the level of your party. The abilities against it ask for Saving Throws that scale the same way. It grows from how fast you destroy the boss and no longer counts how much damage your party takes. In a large fight it presses evenly from the first round. Destroy the Pyre opens once you wear four Rare items. The boss now shows whether the Pyre is rising, fading or subdued
- Special thanks to @Vludber, @Bish, @Talam and @Uturn for testing the new Pyre, through all the quality pain it gave them
- Boss abilities no longer multiply the bonus damage from Eclipse. That old problem made some fights far harder than they were ever meant to be (thanks @TaIIo4ok)
- Companion bosses who later join your party no longer call in ULTRA reinforcements when they die (thanks @Vludber)
- Valdryn's Aura of Dread now asks for a Wisdom Saving Throw you can pass. Its description states the difficulty class again. Everything that gives Advantage against fear now helps against it (thanks @Bish)
- Otherworldly Scorch no longer makes its bearer roll a fear save when an ally heals them (thanks @abysswalker686)
- Tesshin now carries Early Arrival through all three of his forms (thanks @Bish)

LOOT

- The secret lockpick is no longer hidden in the world. It now comes from the random loot pool like any other Very Rare 1H weapon. Its description also finally states what it does
- Reward Cubes no longer come up empty when the DnD 5.5e mod is installed (thanks @ShinraTensei)
- Quest gear worn by an NPC is no longer destroyed when it dies (thanks @Vludber)

ITEM CHANGES

- Emissary's Attire again looks the way it should, in white and burgundy royal colors. Around 70 other pieces of gear, among them the Kyzr set, the New Year set and the Celestial set, now show their own appearance as well (thanks @Khaos)
- Items that check whether you are blessed now recognise every kind of Blessing, including the one the circus statue gives (thanks @dragon)
- Master's Cloak of the Killer Cat has been significantly reworked (designed by @wh1te_ghost)
- Master's Cloak of the Unburied Soul now hides its wearer once per combat, for several turns. The cloak is now Rare (thanks @IzunaOhra)
- The Lolth Cultist's Ring family has been significantly reworked (designed by @wh1te_ghost)
- The Court Scribe's Ring family has been significantly reworked (designed by @wh1te_ghost)
- The Antique Sports Ring family has been significantly reworked (designed by @wh1te_ghost)
- The Robes of the Elusive Master family has been significantly reworked (designed by @wh1te_ghost)
- Restored Ring now has a better chance to give back spell slots after a Short Rest, on every rarity (designed by @wh1te_ghost)
- Sword of Chaos now carries more enchantment on the Rare and Very Rare versions. Its healing has been increased (designed by @wh1te_ghost)
- Ring of Fire now adds more damage when you deal mostly fire (designed by @wh1te_ghost)
- The Phoenixheart Band and its stronger versions now add a damage die instead of a fixed amount (designed by @wh1te_ghost)
- Rellavar's Chilling Scimitar now covers everything it hits with frost, without a saving throw (designed by @GGTsune)
- Talos's Wrath now creates its storm only on the Legendary version, once per turn and over a smaller area (thanks @wh1te_ghost)
- Agonizing Blast now adds its damage to the blast granted by the Robe of Persistence (thanks @Air1Fire)
- Soul Shepherd on the Vestments of Rhokandra now gives back an Action no more than once per turn (thanks @Kanqiu)
- Primordial Chaos no longer gathers past a limited number of charges. Soul Infusion heals for less now (thanks @TaIIo4ok)
- Every degree of Moleculation now states how far the gravity wave from a death under it reaches


Update 1.12.1

Repairs after the big update, plus another batch of reworked gear.

NEW ITEMS

- The Hapless Thief's Gloves have been significantly reworked (redesigned by @wh1te_ghost)

GENERAL CHANGES

- Runic Shards that recently changed their rarity now count as the new rarity in the Trials of Tav shop and in the Void Capsule
- The Runic Shard of Architect now actually adds its enchantment slot on a weapon that carries no other shards (thanks @Vludber)

DIFFICULTY

- Eclipse now also protects the boss from Off Balance, Dazed and Hindered (thanks @Uturn)

LOOT

- All versatile weapons now come from both the 1H Weapon Void Capsule and the 2H Weapon Void Capsule, as they always should have (thanks @Ausar)

ITEM CHANGES

- Several infamous Very Rare gloves tied to thievery have been improved (redesigned by @wh1te_ghost)
- Torn Phantasmal Warden Armour now heals when False Life comes from any source, scrolls among them (thanks @Uturn)
- Fixed a bug with the Sword of Chaos family that caused its stronger versions to lose properties of the weaker ones
- The Meridian has been significantly reworked (redesigned by @wh1te_ghost)
- Rellavar's Chilling Scimitar has been significantly improved to become a more reliable core for cold synergy (redesigned by @wh1te_ghost, @TapoIII40k)
- The Harmonic Dueller's additional rarities now grant a duellist's bonus attack that asks for an empty off hand. The disarming strike is gone (redesigned by @wh1te_ghost)


Update 1.12.2

More repairs to the new Runic Shards, plus another batch of gear reworked with the community.

GENERAL CHANGES

- Runic Shards that raise Armour Class or Attack Rolls no longer lose their bonus after a reload (thanks @SuperKamiGuru)
- Reclaiming a weapon or a piece of gear now returns exactly the shards that went into it, however many times the game has been loaded (thanks @Bish)
- The arcanization limit a weapon gained from the Runic Shard of Architect no longer grows on every load
- The Runic Shard of Impostor now also repeats the shards set into a weapon, the Runic Shard of Architect among them (thanks @Vludber)
- The Runic Shard of Recurrence now returns only the boons a character can really lose (thanks @RusMage)
- The Runic Shard of Amber now deals exactly the fire damage its description states (thanks @wh1te_ghost)
- The Runic Shards of Free Mind, Self-Reliance and Mortal Resolve now recognise every deity
- The Runic Shard of Bulwark is now Rare
- The Runic Shard of Khormus is now Uncommon
- The Runic Shard of Warding now shows its temporary Hit Points on the ally that receives them (thanks @Schwanik)
- The Runic Shard of Goad now states that Rage gives no bonuses in heavy armour (thanks @Deonis)

DIFFICULTY

- The Pyre Equilibrium shown on a boss now falls when you Douse the Pyre. The description now correctly states it's once per turn cooldown (thanks @Uturn, @Bish)

LOOT

- Dusting a Runic Shard in a Void Capsule now returns a Runic Shard of Reclamation with a 10% chance
- The Legendary Sword of Chaos now also comes from the War Void Capsule (thanks @wh1te_ghost)

ITEM CHANGES

- Amulet of Dragon Taming has been significantly reworked on both rarities (designed by @wh1te_ghost & @RusMage)
- The Lightning Amulet family has been slightly reworked (designed by @wh1te_ghost & @RusMage)
- Faithful's Helm has been significantly reworked on both rarities (designed by @wh1te_ghost & @RusMage)
- Helm of Divine Perseverance is now Rare and has been improved (designed by @wh1te_ghost & @RusMage)
- The Hapless Thief's Gloves no longer come in two versions (thanks @wh1te_ghost)
- Bloodseeker Gloves now reduce the Critical Hit threshold by 1
- The Stayed Hands now actually heal once per turn and, together with The Whispering Promise, they no longer create an endless loop (thanks @Shinuki98)
- Nucleation and Singulation now keep working while Adhesion Limit is switched on (thanks @frivr)
- Momentum Transfer now actually raises the degree of Moleculation on the enemy it pushes (thanks @frivr)
- Bound State and Parametric Resonance now disappear as soon as the target is no longer under Moleculation (thanks @frivr)


Update 1.12.3

More Pyre and Runic Shard repairs, plus another batch of gear reworked with the community.

GENERAL CHANGES

- Conditional bonus damage from items and effects on unarmed strikes now only applies when its condition is met, including Shaman's Garb and War Rings
- The Runic Shard of Tithe tooltip now explains its mechanic more clearly (thanks @vludber)
- Runic Shards no longer stop working after loading a save until reclaimed, such as Elemental Harmony (thanks @Lexa Stormborn)
- Fixed a bug with the Runic Shard of Cannonade (thanks @Lexa Stormborn, @Jng)
- Fixed a bug with the Runic Shard of Commutation
- The Runic Shard of Bestiary now properly stacks (thanks @xXGalaxyXx [NEKO])
- Fixed localization errors in the Runic Shard of Threshold
- The Runic Shard of Wildwarden Oath now adds its damage against Ensnared creatures instead of Beasts (thanks @TapoIII40k)
- The Runic Shards of Pyrolysis and Wildfire worn together no longer freeze the game when the wearer is burning. The same goes for Typhlos and Scotoma on a Blinded wearer (thanks @Lakil)

DIFFICULTY

- Eclipse no longer appears on the Avatar of Myrkul when the affix is turned off (thanks @LlyrTheVoyager)
- The Massacre affix no longer keeps appearing on enemies after it is turned off (thanks @Enaun)
- The Pyre no longer stays on enemies after a fight ends, including after a retreat. A creature doused down to nothing now loses its step. The Pyre buttons now come back at the start of your turn when you return to a boss fight. Pyre Equilibrium is now shown on every enemy in a boss fight, including ULTRA mini-bosses and anyone who joins later (thanks @wh1te_ghost, @Uturn, @Vludber)
- Temporary: bosses and ULTRA mini-bosses in combat now show Pyre Growth - how close the Pyre is to its next step. This is just to make the system easier to understand for a while

ITEM CHANGES

- Heart of the Boiling Ocean may now melt the ice you stand on (but we'll see)
- Render of Scrumptious Flesh has been reworked around Bleeding synergy (redesigned by @wh1te_ghost, @TapoIII40k)
- Gloves of Fire Resistance have been reworked around self-ignition synergy (redesigned by @wh1te_ghost)
- Allandra's Whelm has been reworked around Wet synergy (redesigned by @wh1te_ghost)
- Corpsegrinder has been reworked around Reverberation synergy (redesigned by @wh1te_ghost)
- Gloves of Thievery have been significantly improved (redesigned by @wh1te_ghost)
- Liquefied Pegasus Tear Infusion has been reworked (redesigned by @wh1te_ghost)
- Shamanic Storm Pendant has been reworked into a druid amulet built around Concentration and Lightning Charges (redesigned by @wh1te_ghost)
- War Rings now show your Glory as a number on the rank status icon (thanks @TapoIII40k)
- Bulwark of Light now damages the one who hits you again
- Orb of Light now correctly applies Radiating Orbs
- Copper Crow Amulet no longer counts its own Dexterity bonus when checking your highest ability (thanks @Sylvanas Cry)
- Ilsensine's Psychic Lens now correctly uses your spell save DC for Mind Mastery on the Very Rare and Legendary versions (thanks @Uturn)
- Critical Virtuoso now states that the Critical Hit must be scored with "this weapon" (thanks @Gwydion13)
- Ray of Frost granted by a weapon now counts as an Aquamancer Power for Magic Oceanshell and other Aquamancer items (thanks @RusMage)
- Duergar Torture Ring now hits enemies with Reverberation only when you make yourself Invisible, as its description states (thanks @PurpleBallOfYarn)
- The Chronolith's Tidal Displacement now uses your actual Spell Save DC (thanks @Jesse [SOUL])
- Items whose saving throws happen outside of spells, such as on a hit taken, at the start of a turn or from a lingering effect, now use your actual Spell Save DC
- Items that use the Potency DC now use it on every rarity
- Souls raised by the Arcanizer necrotic amulets, including Velsharoon's, now disappear once no enemies are left, even when the last kill raises one - Trials of Tav rounds with these souls now end (thanks @Triode [CAKE])


Update 1.13

Significant changes to the difficulty curve and a number of minor fixes to items.

GENERAL CHANGES

- Runic Shard of Two-Faced now reacts to necrotic and radiant damage from any spell or attack (thanks @Cadavan [BEER], @rolandodata [OWLC])
- Runic Shard of Ice and Fire now reacts to fire and cold damage from any spell or attack (thanks @rolandodata [OWLC])
- Runic Shard of Blinding Radiance no longer needs Warding Flare charges when another mod gives Warding Flare its own resource (thanks @Kristóf)
- Runic Shard of Recurrence now also restores the Dark Lady's blessings from the Sharran Sanctuary (thanks @Vludber)
- Runic Shard of Scion now works when every other companion has left the party (not just died, as before). Gale is no longer an exception lol (thanks @Vludber)

DIFFICULTY

- From level 6, the difficulty tier of every enemy follows your party's gear as well as its level. This is the next step for the GearScore system that first came with the Pyre
- Every NPC now shows its current difficulty tier as a passive, from T1 to T6, with every bonus the tier gives
- Difficulty tiers no longer give NPCs and bosses bonus damage. Damage now grows only with Boss Kill Progression
- The Eclipse tooltip no longer shows the same saving throw DCs on every difficulty

LOOT

- The two old containers with the secret lockpick in Act 1 are now correctly removed (shenanigans inherited from the base AMP)
- Emergent boss rewards now offer Void Capsules

ITEM CHANGES

- The spider from the Lolth Cultist's Ring is now stronger on every rarity. On the Very Rare version it also gets an extra attack (redesigned by @wh1te_ghost)
- Boots of Psionic Movement have been reworked (redesigned by @wh1te_ghost)
- Soulbreaker Greatsword is now stronger (redesigned by @wh1te_ghost)
- Healing from the Ancient Necrotic Rapier now triggers Runic Shard of Requiem (thanks @RusMage)
- Knuckles now add their bonus damage to Wild Shape attacks again (thanks @Kristóf)
- Beastfriend's Leather Armour now gives its bonus damage to beast companions' natural attacks
- Ring of Skilthiryx: the tooltip now explains that the once-per-turn Bonus Action recast comes after the first cast (thanks @Slick [FATE])


Update 1.13.1

The second Hatul Expansion, another batch of gear reworked with the community and more work on the Pyre.

NEW ITEMS

- Hatul Expansion 2: 48 new items join the random loot pool. The collection now holds 2474 unique items (696/733/658/387). More than 50 vanilla and AMP items have been rebalanced along with them. The expansion is about gear spells and gear that spends your class resources. It also settles the question of weak two-handed weapons once and for all (community contribution from @Hatul)

GENERAL CHANGES

- The Runic Shard of Zenith is now Very Rare. Its Divine Smite now triggers once per turn and only against enemies
- Items and shards that react to Mage Armour now also recognise Mage Armour from the MageArmorRework mod (thanks @Хлебный мякиш [MEOW])
- A new hotbar icon, Legitimacy Preserved, shows that your settings and actions keep the run legitimate (per @TapoIII40k request)
- The Runic Shard of Recurrence now keeps the important effects the wearer HAS before a Long Rest. Each kept effect now also lowers the wearer's maximum hit points. The shard is now Uncommon, so it drops more often in the early game
- The Runic Shard of Adherence has been reworked (thanks @rolandodata [OWLC])
- The Runic Shard of Elemental Harmony now also restores spell slots of level 7 and above (thanks @Lexa Stormborn)

DIFFICULTY

- The Pyre no longer jumps to full strength after a fallen ally gets back up (thanks @wh1te_ghost)
- Subdue the Pyre now also costs your next turn, as the tooltip promises (thanks @wh1te_ghost)
- ULTRA enemies now deal more damage once the party reaches level 12. This balances the recent overall damage reduction in Hard and Normal modes
- Vludber's Madness is over: Attacking him no longer drives you mad every single time. A creature that has just recovered from his madness is safe from it for a while. He now has only one reaction

LOOT

- Bernard's reward screen now shows his own lore text (thanks @Roue)
- The Dark Urge reward that replaces the Butler's cloak now offers a richer selection

ITEM CHANGES

- The Legendary Amulet of Dragon Taming now lets you change the element of your weapon every turn, like a Giant Barbarian. Its elemental weapon is also stronger. Weapon attacks now inflict a condition that matches their element (redesigned by @wh1te_ghost and @TapoIII40k)
- Rays of Fire from Helldusk Gloves can now be used once per combat (redesigned by @wh1te_ghost)
- Hr'a'cknir Bracers have been reworked for githyanki warriors who fight with both blade and Eldritch Blast. They are now Very Rare (redesigned by @wh1te_ghost)
- Psionic Ward Armour has been reworked and now fully opens up on a githyanki. It is now also Very Rare (redesigned by @wh1te_ghost)
- The Very Rare Bracers of the Sharpshooter have been reworked around Hunter's Mark (redesigned by @wh1te_ghost)
- Shadow-Cloaked Ring is now Uncommon, like the other rings with a small conditional damage bonus (thanks @wh1te_ghost)
- Faithful's Helm no longer looks like it excludes clerics of Tyr (thanks @wh1te_ghost)
- Infernal Ring now protects nearby tieflings from hellfire only in combat and over a smaller area. This may also fix a crash in long sessions (thanks @Aries Abriel Debrusc [女子食我])
- The Watchful Eye aura of the Ring of the Red Window is now removed together with the ring
- Vanelona's Very Rare and Legendary Rapiers now deal less damage with their spells
- Fire Seed from the Orb of Fire now lasts as long as its description states (thanks @xXGalaxyXx [NEKO])
- Hat of Eternal Echo is now visible on male humans and halflings (thanks @superduper [PtM])
- Rallying Presence from Emissary's Attire now shows its name when it gives Advantage (thanks @heatray)
- Acid Spawn mutations can now be chosen without a melee weapon (thanks @Bodrick [TAV])

LOCALIZATION

- Chinese Simplified and Traditional localization by @Ye [QBOX] updated


Update 1.14

A major rebalance update that touches the foundations of the AMP gear economy.

GENERAL CHANGES

- The Acid Spawn now offers two mutations on each of its turns and takes one of them itself if you choose neither, so you can see the full mutation branch in a single fight. Growing into a larger slime now replaces the smaller one. The new body keeps every mutation
- The Acid Spawn now keeps its mutations between fights. Every fight it survives gives it guaranteed mutations
- The Acid Spawn now hatches in a cocoon that lasts two turns instead of one. It has more hit points at higher party levels and heals in acid
- The Acid Spawn no longer turns on the party (thanks @samwinshester, @Bodrick [TAV], @Air1Fire)
- The Runic Shard of Recurrence now asks you to choose its price when inserted. Each kept effect lowers either the wearer's maximum hit points or their Armour Class
- The AMP guide book now describes every affix
- Artifacts in the debug chests are finally sorted by rarity and slot

DIFFICULTY

- Massacre has been reworked based on the feedback gathered. It is now closer to its original idea and no longer forces you to look for protection from critical hits as fast as possible
- On the Unbelievable ULTRA frequency setting, ULTRA mini-bosses now join every boss fight at a random moment (per @Hatul request)
- Minthara and other story bosses no longer keep the extra actions of an enemy boss after joining the party (thanks @TheVillageIdiot [Lgnd])
- Ansur should no longer stand up before his scene (thanks @hatul91)
- Doomflame no longer sets the party on fire again and again near Wraiths
- Planar Scorch from the Pyre no longer stays on the party after combat until a Long Rest
- Gaze of the Dark One now has a clearer description (thanks @mturn)

LOOT

- Almost all quest rewards, except boss rewards, have been significantly reworked based on the feedback gathered. Act 1, for example, will offer more artifacts and Void Capsules, while Act 2 will offer more Runic Shards. Reward pools for story quests now match the theme of the quest
- The way Interplanar Chests fill their loot has been fully reworked. It now follows your current progress more closely to offer a relevant reward, which now also includes random artifacts. Act 1 also has 55 new potential spawn points for them
- The Trials of Tav shop now pays less for the items you sell on every difficulty. It can no longer be used as an endless source of gold
- Dusting a Runic Shard in a Void Capsule now returns a Runic Shard of Reclamation with a 20% chance (thanks @NQ)
- The basic Void Capsule now explains what it gives

ITEM CHANGES

- Robe of the Storm Prophet has been reworked into armour for spellcasters who keep Lightning Charges up (redesigned by @wh1te_ghost, @TapoIII40k)
- Ring of Master Wang has been reworked for melee fighters who are short on feats (redesigned by @wh1te_ghost, @TapoIII40k)
- Court Magician's Ring has been reworked into a ring you use in combat. Warlocks can now restore their spell slots with it (redesigned by @wh1te_ghost, @TapoIII40k)
- Master's Cloak of Endurance has been reworked to keep fragile characters alive (redesigned by @wh1te_ghost)
- Tribal Talisman is now a barbarian ring built around Rage (redesigned by @wh1te_ghost)
- Tempus's Divine Resonance no longer caps its Strength bonus. Its Cleave can now be used once per turn (redesigned by @wh1te_ghost)
- Gloves of Elven Grace are now Legendary
- Zephyr Gloves now give less Armour Class. The Uncommon version no longer gives it (thanks @8Bored)
- Hunter's Mark from the Hunting Shortbow can now be used once per combat (thanks @wh1te_ghost)
- Hunter's Mark from the Grymskull Helm can now be used once per combat (thanks @wh1te_ghost)
- Staff of the Ram no longer breaks other items that react to a resisted saving throw, such as Soul Shepherd. Its knockback now gets one attempt per turn (thanks @Kanqiu)
- The Runic Shard of Faerie Fire and the Hellrider Longbow no longer break other items that react to a resisted saving throw
- The Ring of Skilthiryx no longer switches its telekinesis recast to the action version after a target resists it (thanks @heatray)
- Embodiment of Primordial Fire no longer sets enemies on fire again and again near Wraiths (thanks @heatray)
- Faithful's Helm now reacts to a Disciple shard the moment it is inserted. It no longer grants both of its blessings at once (thanks @wh1te_ghost)
- Enchanted Ruby Pendant now shows its real ability score cap (thanks @Hatul)
- Primordial Amulet now shows its real ability score cap (thanks @Hatul)
- Archmage's Pendant now shows its real ability score cap (thanks @Hatul)
- Amulet of the Bull Cult now shows its real ability score cap (thanks @Hatul)
- Pendant of the Forest Ranger now shows its real ability score cap (thanks @Hatul)
- Pendant of the Great Council now shows its real ability score cap (thanks @Hatul)
- Chosen of Shar now states that its wearer is Shielded by Faith. Its Devil's Sight is now called Shar's Sight (thanks @milky [PSC], @Hatul)


Update 1.14.1

Improvements to the recent major reworks, based on fresh feedback.

GENERAL CHANGES

- Lamb Runic Shards have been fully redesigned
- The Runic Shard of Tithe in an off-hand weapon now counts the Runic Shards in its own weapon (thanks @Kristóf)
- The Runic Shard of Mosaic in an off-hand weapon now counts the Runic Shards in its own weapon
- The Runic Shard of Asceticism in an off-hand weapon now counts the Runic Shards in its own weapon
- The Runic Shard of Brick in an off-hand weapon now checks its own weapon for the Runic Shard of Architect
- The Runic Shard of Dissonance in an off-hand weapon now checks its own weapon for other Runic Shards that change its damage
- The Runic Shard of Juggler's toggle no longer disappears from the hotbar after a Long Rest (thanks @Scarcro)
- The Runic Shard of Improvisation's toggle no longer disappears from the hotbar after a Long Rest
- The Runic Shard of Cannonade's toggle no longer disappears from the hotbar after a Long Rest
- The Runic Shard of Commutation's toggle no longer disappears from the hotbar after a Long Rest
- The Runic Shard of Scion now also counts companions waiting in camp (thanks @Talam)

LOOT

- The transmutation economy of Void Capsules has been fully reworked
- The Trials of Tav shop has been fully reworked
- Legendary Runic Shards in the Trials of Tav shop now cost as much as a Celestial Coin
- The reworked Interplanar Chests now take the GearScore of a solo player into account more accurately
- Interplanar Chests no longer appear at every spawn point at once on Casual
- Tesseracts in Interplanar Chests now open by themselves
- The junk bag has finally been reworked. Letters, notes and books now go into it once you have read them. Quest items no longer end up there, even when the game does not mark them as quest items. Spoiled food, mugs, tin plates, bottles, jugs, bones, shells, ingots and gems now go into it. Junk already sitting in your pack is sorted on your next pickup

ITEM CHANGES

- Knock Knuckle Gloves now give a Runic Shard every time they roll one, not just the first time


Update 1.14.2

A few small fixes requested by the community on Discord.

GENERAL CHANGES

- Lamb Runic Shards now burn out after giving 5 Runic Shards (thanks @Hatul)
- The Runic Shard of Elemental Harmony now works with Chromatic Orb on any elemental surface (thanks @rolandodata, @Lexa Stormborn)
- The Loot Manager and autoloot should no longer empty, sort or throw away the Tutorial Chest and other chests summoned with the Training Ring (thanks @lord_megatron92, @joiewilder, @blekinfar, @snazzy_juan, @rolandodata)
- The Loot Manager no longer touches items you take out of your own bags
- The test chests from the Training Ring now hold every item of their loot pools again, including the versatile weapons in the two-handed chest (thanks @wh1te_ghost)
- The game should no longer crash when leaving the Nautiloid (thanks @ainzooalgown, @fabrit)
- The Runic Shard of Metamorph should no longer go past its stack limit from attacks that hit several times (thanks @nommi, @Hatul, @heatray, @rolandodata)
- The Runic Shard of Greater Shadowweaver should now create darkness when combat starts, not on the wearer's first turn, but only if you start the fight yourself, not when you join one already in progress (thanks @rolandodata [OWLC])
- Hunter's Mark from the Runic Shard of Sniper's Mark should no longer disappear from the hotbar after loading a save (thanks @Cadavan)
- Lay on Hands from the Runic Shard of Divine Touch should no longer disappear from the hotbar after loading a save

DIFFICULTY

- Enemies on Normal and Hard now deal extra flat damage with attacks and spells, based on their tier. Bosses get the bigger bonus. The bonus is flat so that protection against critical hits does not become more necessary
- Added a new anti-abuse setting: Shadow Blade keeps its base damage no matter which spell slot is used. It is on by default on Normal and Hard
- Small fixes to how Eclipse works
- Bosses should no longer gain extra hit points after reloading a save in the middle of a fight. They should also no longer get two difficulty tiers at once (thanks @scarcro, @heatray, @josh.pekockn, @ultrapoor, @rounstack)
- Ethel's doubles are no longer affected by difficulty tiers. They disappear after the first hit again (thanks @dunraven, @rickert, @tazliel, @Hatul, @ultrapoor)
- ULTRA mini-bosses should no longer arrive after ULTRA has been turned off with the ring (thanks @basbous, @nbryce, @Ridgur, @Rounstack)
- On the Moonrise Towers roof, ULTRA reinforcements now arrive when the fight with Ketheric begins (thanks @vladosxman, @grreggy)
- Fixes for the body of Tesshin in the Trials of Tav that could not be killed (thanks @luerovyn, @grreggy, @heatray, @joiewilder, @3champion3, @Scarcro)

LOOT

- Tesseracts sold by merchants in Avarice now open by themselves
- Dusting a Runic Shard in a Void Capsule now returns a Runic Shard of Reclamation with a 15% chance (it was 20%, which turned out to be too much)
- The AMP guide book no longer promises a Runic Shard for every Legendary artifact put into a Void Capsule (thanks @Scarcro, @Tazliel, @SuperKamiGuru, @jerovich, @nbryce)

ITEM CHANGES

- Gloves of Elven Grace have been fixed (thanks @khlebnyimiakish, @ФИР, @phaethon)
- Infernal Rapier has been reworked around hellfire to show its true Legendary power (redesigned by @Mogila Ispravit, @wh1te_ghost)
- The Arcanizer warhammers have been slightly reworked (redesigned by @wh1te_ghost, @Mogila Ispravit)
- The radiant rings of the Arcanizer have been reworked to be useful in any fight (redesigned by @wh1te_ghost)
- Justiciar's Scimitar has been reworked for stealth play (redesigned by @wh1te_ghost)
- Fixed the healing progression of Laeranel's Valiant Helm (thanks @wh1te_ghost)
- Fixed the progression of Jester's Comfort Cap (thanks @CoriSlayer)
- Hood of the Weave now also gives Advantage on Saving Throws against spells (thanks @nbryce)
- Knock Knuckle Gloves now correctly describe their lockpicking reward
- Gloves of Thievery now correctly describe their lockpicking reward
- Restored Ring now also restores spell slots of levels 7 to 9, as its description says (thanks @Lexa Stormborn, @Lunescense, @Scarcro, @rolandodata)
- Fixes for the critical hit bonus of Shaman's Garb in Wild Shape on the Very Rare and Legendary versions (thanks @rusmage, @avesemka, @Монах)
- Fixes for doctrine choices on the War Rings (thanks @8Bored, @Scarcro)
- Fixes for the Steel Watcher form of the Core of the Watcher (thanks @Scarcro, @heatray)
- Dagger of Fate now also takes souls from enemies under Hexblade's Curse (thanks @cadavan)
- Fixes for Solar Reflection on the Solarian Circlet when a fight starts in sunlight (thanks @heatray, @Hatul)
- Master's Cloak of Dissolution now keeps its Armour Class bonus for as many turns as its description says (thanks @levi_2505, @rolandodata)
- Fixes for the Magical Hand Crossbow bonus when it is held in the off-hand (thanks @Eugene)
- Vest of Soul Rejuvenation heals you again when you succeed on a saving throw against a spell (thanks @wh1te_ghost)
- Robe of the Weave heals you again when you succeed on a saving throw against a spell


Update 1.14.3

A batch of reworked artifacts and the usual round of community fixes.

GENERAL CHANGES

- The Runic Shard of Finisher now actually deals the extra critical damage its tooltip promises (thanks @bodoongo)
- The Runic Shard of Recurrence now carries its kept blessing into Act 3 (thanks @Uturn)
- The Runic Shard of Delirium should now drive a creature mad when it fails the mental saving throw (thanks @Uturn)
- The Runic Shard of Caldera now only creates its lava from fire damage dealt to enemies (thanks @rolandodata [OWLC])
- Weave Surge now applies its attack penalty to off-hand attacks as well (thanks @MRNameless0)
- Interplanar Chests now correctly spawn their loot when destroyed

DIFFICULTY

- A new ULTRA reinforcement setting has been added: limit how many reinforcement waves can be active in the same fight at once, from 1 to 5 or Unlimited. It is the last question in the reinforcement settings (thanks @rolandodata [OWLC])
- Myrkul has been further strengthened in ULTRA
- The Pyre now grants enemies less movement speed at every tier
- The Eclipse affix no longer triggers on a charmed or maddened companion (Minthara and others) who turns hostile for a moment (thanks @_jonf)

LOOT

- The Gauntlets of Hill Giant Strength have been added to the rare glove pool (thanks @rolandodata [OWLC])
- The autoloot no longer keeps working in some cases after it has been turned off (thanks @elvira.from.hell)
- The Loot Manager no longer empties, sorts or throws away the Tutorial Chest and other chests summoned with the Training Ring (thanks @wh1te_ghost)
- The Lolth Cultist's Ring is now part of the swamp pool (thanks @wh1te_ghost)
- The Vest of Soul Rejuvenation is now part of the psionic pool (thanks @wh1te_ghost)

ITEM CHANGES

- The Psionic Helm has been fully reworked (redesigned by @wh1te_ghost)
- Master's Cloak of Celestial Intuition has been fully reworked (redesigned by @wh1te_ghost)
- Diadem of Arcane Synergy has been reworked (redesigned by @wh1te_ghost)
- Jorgoral's Greatsword has been reworked (redesigned by @wh1te_ghost)
- Foebreaker has been fully reworked (redesigned by @wh1te_ghost)
- The Scorching Whirlwind has been fully reworked (redesigned by @wh1te_ghost)
- Spiderstep Staff has been fully reworked (redesigned by @wh1te_ghost)
- Infernal Ring has been fully reworked (redesigned by @wh1te_ghost)
- Halo of Hope no longer damages allied undead. Its overall power is significantly lower at the lower rarities. Fixed several other bugs with it (thanks @Roue)
- Viper's Fang (Very Rare) now ignores resistance and immunity to poison, as the Legendary version does (per @RusMage Request)
- The Core of the Watcher should no longer register you as a Steel Watcher, so its dialogue lines stop appearing over your head (thanks @Scarcro, @heatray)
- Prisoner's Paradox should no longer trigger on damage you deal to yourself, so falling damage stops paralysing the party. Its explosion now rolls the save its description promised (thanks @MRNameless0)
- Chauntean Boots of Jubilation no longer heal the whole party without limit outside combat (thanks @eli)
- Orb of the First Soul no longer turns Invoke Duplicity into a crowd of illusions (thanks @Roue)
- The crossbow class action can be used again (thanks @CoriSlayer)
- Fixed the blinding passive on Justiciar's Scimitar. Shadowsoaked Blow now deals Psychic damage (thanks @wh1te_ghost)
- Fixed issues related to the recent Mutacid rework (thanks @ilarios, @kovi257)
- Mystra's Footsteps from Hatul Expansion now correctly show their bonuses, not just Arcana +20 (thanks @KnockNoble)
- The Cormyrean Elite tooltip now states that shots beyond your weapon's normal range are made with Disadvantage

LOCALIZATION

- Corrected and completed item and effect descriptions across all supported languages, restoring missing damage and saving throw values (thanks @rolandodata [OWLC])
