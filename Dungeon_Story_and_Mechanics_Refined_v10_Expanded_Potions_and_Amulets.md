# THE DUNGEON BELOW — STORY & MECHANICS REFINEMENT v2

This document refines the **story structure, gameplay loop, progression, combat, item-risk system, transformation rules, dungeon generation, and long-form pacing** of the existing visual text RPG specification.

It is intended to sit alongside the existing UI specification. Where this document is more specific about gameplay mechanics, use this version.

---

# 1. CORE DESIGN PILLARS

The game should be built around six pillars:

1. **Forward-only exploration**
   - Most rooms become permanently inaccessible after leaving.
   - Every door choice is a commitment.
   - The player rarely knows exactly what lies ahead.

2. **Information is a resource**
   - Notes, rumours, symbols, monster behaviour, item tests, witches, and environmental clues help the player make better decisions.
   - Information can be incomplete or unreliable.
   - Good play means learning how to judge evidence.

3. **Survival through preparation**
   - Health, stamina, equipment condition, healing supplies, safe rests, light, cures, and inventory space matter.
   - The player should often be deciding whether to spend a resource now or gamble on finding something better later.

4. **Transformation is optional risk, not the plot forcing itself onto the player**
   - Every new game begins completely human.
   - No hidden infection, dormant curse, secret transformation, or predetermined species exists at game start.
   - A careful player can remain human for the entire run.
   - Transformations are acquired only through events that occur after play begins.

5. **Transformation is discovered through symptoms**
   - The engine knows the real effect.
   - The character only knows what they can observe or reliably learn.
   - Species, stage, trigger, source, and hidden progress remain secret until there is sufficient evidence.

6. **Power should create interesting trade-offs**
   - Dangerous items should often be genuinely useful.
   - A transformation effect can be the price of power.
   - Some transformations stop after one or two body changes.
   - Others can continue toward a full transformation.
   - Transformation should sometimes be useful, sometimes inconvenient, and sometimes dangerous.

---

# 2. STORY PREMISE

The player wakes in a locked stone cell beneath an unknown ruined complex.

They are:

- Completely human.
- Injured only in ordinary, non-magical ways if the opening difficulty requires it.
- Carrying no curse.
- Carrying no transformation.
- Carrying no hidden contamination.
- Unsure exactly where they are.
- Unsure who brought them there.
- Unsure how long they have been underground.

Their last clear memory is fragmented but mundane enough that it does not imply a supernatural infection. They remember travelling, being attacked or captured, and losing consciousness.

The first mystery is:

**Who brought me here, why am I still alive, and how do I get out?**

The dungeon initially appears to be an enormous ancient prison.

Over time the player discovers that it was much more than that.

It was once a combined:

- Prison.
- Research complex.
- Alchemical laboratory.
- Magical containment facility.
- Military vault.
- Ritual site.
- Underground transport network.

Different generations reused the same structure for different purposes. That is why the dungeon contains architecture and technology from several eras.

The current inhabitants do not control the entire dungeon.

No single faction fully understands it.

---

# 3. WHY THE DOORS LOCK

The forward-locking room structure should have an in-world explanation.

Long ago, the dungeon was built around a magical containment system called the **Warden Mechanism**.

Its purpose was to prevent dangerous prisoners, creatures, experiments, and magical contamination from travelling freely between sectors.

When a chamber detects movement through one of its exits, the other routes normally seal.

Centuries of damage have made the mechanism unreliable, but it still controls much of the dungeon.

This explains why:

- Doors lock behind the player.
- Unchosen exits are often permanently lost.
- Some rooms seal during combat.
- Certain doors require keys, symbols, blood, magical charge, or mechanical activation.
- Rare witches, keys, lifts, and teleport systems can break the normal rules.

The dungeon's most frustrating gameplay rule therefore becomes part of the mystery.

Later, the player may learn ways to manipulate the Warden Mechanism, but should never completely remove the forward-only structure.

---

# 4. THE CENTRAL MYSTERY

The main plot should unfold through several questions rather than one exposition dump.

## Early questions

- Where am I?
- Who captured me?
- Is there a route upward?
- Why do the doors behave this way?
- Who else is alive down here?
- Why are witches using parts of the dungeon?
- Why are some animals and monsters physically altered?

## Mid-game questions

- What was this place originally built to contain?
- Why were alchemical and transformation experiments performed here?
- Why do some witches want the ancient laboratories working again?
- Why do old maps contradict each other?
- Why are several supposed "surface lifts" disconnected or false?

## Late-game questions

- What powers the Warden Mechanism?
- Who is bringing new prisoners into the dungeon?
- Is the dungeon still functioning automatically, or is someone directing it?
- Are the known escape routes genuine?
- What would happen if the central mechanism were shut down?

The player should not receive a complete answer until deep into the game.

---

# 5. MAJOR FACTIONS

Factions give the long dungeon recurring characters and reasons for regions to feel connected.

## THE LANTERN COVEN

A small group of witches and alchemists who study the dungeon instead of worshipping it.

Typical behaviour:

- Identify items.
- Sell medicines.
- Trade information.
- Study transformations.
- Offer suppression and reversal treatments.
- Ask the player to recover journals, samples, and old equipment.

They are useful but not automatically trustworthy.

**Mirella**, the coven alchemist, can be a recurring character.

Mirella should remember:

- What the player has told her.
- Whether the player lied.
- Whether the player paid debts.
- Whether the player accepted experimental treatments.
- What physical changes she has personally observed.

## THE THORN COVEN

Pragmatic witches who treat transformation magic as another source of power.

Some Thorn witches are merchants or negotiators. Others are hostile dungeon enemies, hunters, guards, or ritualists.

They may offer:

- Strong enchanted equipment.
- Dangerous bargains.
- Stable partial transformations.
- Combat enhancements.
- Rare cures at very high prices.

Hostile Thorn witches may attack if the player enters protected territory, steals from them, breaks a bargain, kills one of their allies, or has sufficiently poor reputation.

They should create genuine temptation rather than being automatically evil.

## THE PALE CHOIR

A secretive faction that believes the dungeon's altered creatures represent deliberate evolution.

They are more willing to cause uncontrolled transformations.

Many Pale Choir witches are outright enemies. They may hunt prisoners, guard laboratories, conduct rituals, release altered beasts, or deliberately expose the player to dangerous magic.

They may still know important late-game information, making them dangerous but potentially valuable. A hostile witch does not always have to fight to the death; some may bargain, retreat, surrender, or offer information when wounded.

## SURVIVORS

Other prisoners, explorers, smugglers, failed treasure hunters, and abandoned guards may appear.

Some become recurring characters if the player chooses compatible routes.

Because routes close behind the player, it should be possible to permanently miss NPCs.

## THE WARDENS

Not necessarily a living faction.

The player gradually learns that old constructs, seals, statues, runes, and automated mechanisms are remnants of the dungeon's ancient security system.

Some still follow rules written centuries ago.

---

# 6. ESCAPE ROUTES

There should be several possible escape plans.

The player should not know which are real at first.

Examples:

## THE CHAIN LIFT

An enormous ancient cargo lift said to reach an upper gate.

Problems:

- Requires several control seals.
- Some controls are in different regions.
- The lift may stop at intermediate levels.
- The upper gate may still be sealed.

## THE PILGRIM SHAFT

A narrow route described in old temple records.

Problems:

- Difficult to locate.
- Partially collapsed.
- May require climbing, small-body access, special tools, or another route around damaged sections.

It must still be possible for a fully human player to complete it through equipment, puzzle-solving, or an alternate entrance.

## THE FLOODGATE

An old water-management tunnel that may lead outside.

Problems:

- Flooding.
- Mechanical controls.
- Aquatic monsters.
- Limited air in some sections.
- One-way descent.

## THE GLASS GATE

A magical transport system.

Problems:

- Destination uncertain.
- Requires calibration.
- Several factions want control of it.
- Incorrect activation can lead deeper into the dungeon.

A normal run does not need to complete every escape route.

The player gradually builds evidence and commits to one.

---

# 7. ENDINGS

Avoid one single "correct" ending.

Possible ending families:

- Escape completely human.
- Escape with a stable partial transformation.
- Escape while progressively transformed.
- Escape after being fully transformed but retaining identity.
- Escape after curing a transformation.
- Escape with a companion or NPC.
- Shut down part of the Warden Mechanism before escaping.
- Leave the mechanism active and simply survive.
- Accept a witch bargain that provides another route out.
- Discover a false exit and be forced into another major region.
- Become trapped through a failed late-game decision.
- Die.

Transformation should not automatically determine whether an ending is good or bad.

Player choices, identity, alliances, survival, and what they learned should matter more.

---

# 8. OPENING SEQUENCE — ROOMS 1 TO 3

The opening must establish the game without forcing transformation.

## ROOM 1 — THE PRISON CELL

The player wakes on a cold stone floor.

Visible elements:

- Locked iron door.
- Cracked water basin.
- Straw bedding.
- Scratched tally marks.
- Loose stone.
- Dead wall lamp.
- Small barred drain.

Possible actions:

- Examine door.
- Search bedding.
- Inspect scratches.
- Check body.
- Search loose stone.
- Drink from basin.
- Call out.
- Wait and listen.

The water is ordinary unless the generation system explicitly creates a later risky interaction. Do not use the opening to secretly infect the player.

Useful discoveries can include:

- A bent metal strip.
- A previous prisoner's note.
- A simple bandage.
- A rough map fragment.
- A clue about door timing.

The player escapes through observation, improvisation, or a brief scripted disturbance.

No transformation occurs automatically.

## ROOM 2 — INTAKE HALL

The cell opens into an old prisoner-processing chamber.

The player finds:

- Several empty restraints.
- A broken desk.
- An old inventory ledger.
- Their first basic weapon.
- Their first armour or clothing upgrade.
- Three sealed exits.

One weak enemy or environmental threat can introduce combat.

After the encounter, the exits unlock.

Door clues might be:

**LEFT:** cold moving air.

**CENTRE:** old blood and scrape marks.

**RIGHT:** faint herbal smell.

The player now understands the central rule:

**Choose one. The others may be lost.**

## ROOM 3 — FIRST REAL BRANCH

Room 3 depends on the chosen door.

Possible branches:

### Cold route
An abandoned maintenance chamber with useful tools and a safer early game.

### Scratched route
A guard room with stronger combat and better weapon loot.

### Herbal route
An abandoned apothecary with several tempting unknown items.

The apothecary may contain a transformation-capable potion or amulet, but it must be optional.

This is the earliest point at which the player can reasonably acquire transformation risk.

The player can also ignore every suspicious item and continue fully human.

---

# 9. CORE ROOM LOOP

Use this as the default loop:

**ENTER → OBSERVE → ASSESS → RESOLVE THREAT → SEARCH / LOOT → PREPARE → CHOOSE EXIT → COMMIT**

Do not make every room use every phase.

A room can contain:

- Combat.
- Trap.
- Puzzle.
- NPC.
- Witch.
- Merchant.
- Rest opportunity.
- Treasure.
- Lore.
- Environmental hazard.
- Nothing important.
- Several of the above.

Empty or low-event rooms are necessary because they make dangerous rooms less predictable.

---

# 10. ROOM GENERATION RULES

Each generated room should have internal tags.

Example:

- Region.
- Threat level.
- Room type.
- Encounter type.
- Loot tier.
- Hazard.
- Special interaction.
- Exit count.
- Door clues.
- Story clue chance.
- NPC chance.
- Transformation-source chance.
- Rest safety.
- Secret chance.

Do not generate rooms independently with no regard for the run.

Use **pacing memory**.

The generator should remember recent rooms and avoid patterns such as:

- Five combats in a row.
- Four empty rooms in a row.
- Several merchants close together.
- Constant transformation items.
- Repeated identical monsters.
- Repeated identical door clues.

A rough room-type target over a long stretch can be:

- 30–40% combat-focused.
- 10–15% trap or environmental hazard.
- 10–15% puzzle / mechanism / exploration.
- 10–15% NPC, witch, merchant, or story.
- 10–15% treasure, lore, or abandoned location.
- 5–10% safe/rest room.
- 5–10% genuinely quiet or empty room.

These are pacing targets, not visible odds.

Bosses and major story rooms are placed deliberately rather than rolled completely at random.

---

# 11. SOLVABILITY GUARDRAILS

Random generation must never make a run impossible through bad luck alone.

The game engine must guarantee:

- At least one viable escape route remains possible until the player knowingly destroys or abandons it.
- Required keys or tools cannot be placed exclusively behind an already-lost route.
- A fully human route always remains possible.
- No mandatory door requires a transformation ability without a human alternative.
- Transformation cures should not be guaranteed, but the player should have multiple possible ways to seek treatment.
- The player should not be forced to use an unknown potion to survive a scripted encounter.
- Bosses must always have at least one non-transformation strategy.

Randomness creates uncertainty, not unwinnable states.

---

# 12. PLAYER STATS

Keep the visible system compact.

Recommended core stats:

## HEALTH
Physical survival.

## STAMINA
Spent on heavy attacks, dodges, special moves, sprinting, and some exploration actions.

## ARMOUR / GUARD
Reduces or absorbs damage.

## DAMAGE
Weapon and ability output.

## ACCURACY
Chance to connect with difficult attacks.

## SPEED
Affects initiative, dodge, and some escape actions.

## RESOLVE
Resistance to fear, coercion, instinctive behaviour, and certain curses.

## GOLD
Trade currency.

## HUMANITY
Use this only as a broad physical-form indicator.

Humanity does **not** represent morality.

A cruel human can still have 100% Humanity.

A kind transformed character can have low Humanity.

At game start:

- Humanity: 100%
- Form: Human
- Transformation: None
- Exposure: None

If no physical change has occurred, Humanity should normally remain 100 even if the engine has registered a hidden magical effect that has not yet changed the body.

---

# 13. CHARACTER PROGRESSION

The player should improve even if they never transform.

Use three skill tracks:

## COMBAT
Examples:

- Efficient Guard.
- Heavy Strike.
- Counterattack.
- Weapon familiarity.
- Better critical attacks.
- Lower stamina cost.

## SURVIVAL
Examples:

- Better searching.
- Improved resting.
- More effective bandages.
- Larger practical inventory.
- Better trap detection.
- Slower equipment wear.

## OCCULT
Examples:

- Better item examination.
- Improved curse recognition.
- Better potion testing.
- More accurate rune interpretation.
- Increased resistance to magical effects.
- Better ability to recognise transformation symptoms.

Progress comes from:

- Major encounters.
- Discoveries.
- Bosses.
- Completing objectives.
- Rare training opportunities.
- NPC teaching.

Avoid awarding experience for repetitive farming, because the forward-only structure does not support normal grinding.

---

# 14. COMBAT — REFINED SYSTEM

Combat should be tactical but fast enough for a text RPG.

Each combat round:

1. Enemy intent is described.
2. Player chooses one main action.
3. Quick actions may be available if permitted.
4. Player action resolves.
5. Enemy action resolves.
6. Status effects update.
7. New enemy intent is shown.

## ENEMY INTENT

Whenever reasonable, enemies telegraph behaviour.

Examples:

- **The skeleton raises its shield and braces.**
- **The wolf lowers its body, preparing to leap.**
- **The witch begins tracing a symbol in the air.**
- **The giant rat backs toward the wall, looking for an opening to flee.**

This creates meaningful decisions instead of random damage exchanges.

## BASIC ACTIONS

### ATTACK
Reliable normal damage.

### HEAVY ATTACK
Higher damage.
Costs stamina.
Lower accuracy or slower initiative.

### DEFEND
Reduces incoming damage.
Restores a small amount of stamina.
May enable a counterattack skill.

### EVADE
Costs stamina.
Strong against heavy telegraphed attacks.
Less useful against fast or area attacks.

### USE ITEM
Drink, throw, apply, or activate an item.

### ABILITY
Combat skill, equipment ability, or transformation ability.

### EXAMINE
Gain information about the enemy.
May reveal armour, weakness, injury, behaviour, or magical signs.

### FLEE
Only available when the room and enemy allow it.
Fleeing usually commits the player to a specific exit and may mean abandoning loot.

---

# 15. STAMINA

Stamina prevents the strongest move from being used every turn.

Suggested behaviour:

- Normal attack: little or no stamina.
- Heavy attack: moderate stamina.
- Dodge: moderate stamina.
- Powerful ability: moderate/high stamina.
- Defend: restores some stamina.
- Resting outside combat restores stamina.
- Some potions restore stamina.

At zero stamina:

- Heavy attacks unavailable.
- Dodge becomes weaker or unavailable.
- Some abilities disabled.
- Speed may temporarily decrease.

This creates a rhythm:

**PRESS ATTACK → MANAGE STAMINA → DEFEND / RECOVER → ATTACK AGAIN**

---

# 16. ENEMY DESIGN

Enemies should have behaviours, not just different health totals.

Examples:

## SKELETON GUARD
- Blocks often.
- Vulnerable after missed heavy swing.
- Resistant to bleeding.

## DUNGEON WOLF
- Fast.
- Low armour.
- Strong leap attack.
- Can be interrupted.

## FUNGAL HOST
- Slow.
- Releases spores when damaged.
- Fire or distance is valuable.

## WARDEN CONSTRUCT
- Heavy defence.
- Predictable attack cycle.
- Weak point can be discovered with Examine.

## WITCH
Witches are a full enemy family, not just NPCs.

A hostile witch can:

- Cast direct-damage spells.
- Place curses.
- Create shields or wards.
- Heal herself.
- Summon creatures.
- Alter the room.
- Teleport or reposition.
- Drain stamina.
- Disable equipment temporarily.
- Create illusions.
- Attempt transformation magic.
- Suppress or accelerate an existing magical condition.
- Flee.
- Surrender.
- Bargain during combat.
- Change tactics according to the player's condition and reputation.

A witch should rarely feel like a normal monster with a larger health bar.

Witch combat should emphasize **interrupting, reading intent, deciding which spell is most dangerous, and managing magical pressure**.

### WITCH INTENT EXAMPLES

**The witch raises two fingers. Black threads of light begin gathering around your boots.**

Possible interpretation:
- Binding curse being prepared.

**She cuts her palm and begins whispering toward the dead wolf beside her.**

Possible interpretation:
- Summoning or resurrection ritual.

**The silver ring on her hand flashes. The air around her hardens like glass.**

Possible interpretation:
- Defensive ward.

**Her eyes move over your altered hands and she smiles.**

Possible interpretation:
- A spell may interact with an existing transformation.

The player should normally receive enough narrative information to make a tactical decision without being told the exact spell name unless they have learned it.

### WITCH ARCHETYPES

Each archetype should draw from its **own attack / intent line pool**. Avoid reusing the same generic spell wording across every witch. The writing itself should help the player recognise the witch's style before they know every exact ability.

Attack lines can be:
- Spoken threats or taunts.
- Physical casting descriptions.
- Environmental reactions.
- Short intent telegraphs.
- Follow-up lines after an attack succeeds or fails.

Do not require a spoken line every turn. Silent witches, injured witches, ambushes, and rapid attacks can rely entirely on physical descriptions.


#### THORN HEXER
Focuses on curses and debuffs.

Typical abilities:
- Weakness curse.
- Accuracy curse.
- Stamina drain.
- Temporary equipment hex.
- Fear or confusion effect.

##### Casting

- “The Thorn Hexer drags one nail through the air. Green-black thorns begin to grow from the mark.”
- “The Thorn Hexer whispers, ‘Roots remember blood,’ and twists her wrist toward you.”

##### Ward

- “The Thorn Hexer presses a thorn into her palm. A cage of briars coils around her.”
- “The Thorn Hexer stamps her staff down and spectral brambles knot themselves into a shield.”
- “A wall of spectral thorns twists shut around the Thorn Hexer.”

##### Hex

- “The Thorn Hexer points at your shadow. Barbed roots crawl across the floor toward your feet.”
- “The Thorn Hexer murmurs your shape into a curse; thorny lines tighten around your boots.”
- Hit: “Barbed roots bite into your shadow. Your legs turn heavy as wet earth.”
- Resist: “You wrench your shadow free before the thorn-curse can take hold.”

##### Potion preparation

- “The Thorn Hexer uncorks a moss-green bottle wrapped in roots.”
- “The Thorn Hexer tears a vine-sealed flask from her belt and raises it with a crooked smile.”

##### Interrupted

- “The Thorn Hexer’s briar-sign collapses into dead leaves.”
- “The Thorn Hexer hisses as the spell snaps and the spectral thorns fall apart.”

##### Dangerous spell

- Hit: “The Thorn Hexer crushes a seed-black charm. Something wild claws through your nerves, then goes still.”
- Resist: “The wild pressure reaches for your bones, but you force it back before it can root.”

##### Normal magical attack

- “The Thorn Hexer lashes out with a whip of green-black force.”

##### Potion effects

- Exposure: “The Thorn Hexer smashes a sap-thick amber flask across your shoulder. Your skin prickles as if tiny roots are searching beneath it.”
- Heal: “The Thorn Hexer drinks a bitter green draught. Colour returns to her face.”
- Mutation: “Dark, bark-like ridges creep over the Thorn Hexer’s knuckles and sharpen her nails.”
- Vapour: “The Thorn Hexer breaks a root-wrapped vial at your feet. Bitter green vapour steals your breath and strength.”

Thorn Hexer lines should feel **organic, invasive, and entangling**. Her magic should make the player associate her with roots, thorns, restraint, and bodily corruption.

#### BATTLE WITCH
Uses direct magical attacks and defensive wards.

Typical abilities:
- Fire bolt.
- Force strike.
- Magical shield.
- Counterspell.
- Short teleport.

##### Casting

- “The Battle Witch plants her feet and draws a burning combat rune across the air like a blade.”
- “The Battle Witch barks, ‘Stand still,’ and gathers a fistful of red force around her gauntlet.”

##### Ward

- “The Battle Witch slams one forearm across her chest. Red runes lock together into a shield.”
- “The Battle Witch snarls a short command and a hard crimson ward snaps into place.”
- “A hard crimson ward locks around the Battle Witch like a second suit of armour.”

##### Hex

- “The Battle Witch points two fingers at your knees. Red chains of light whip across the floor.”
- “The Battle Witch growls, ‘Slower,’ and stamps a binding rune beneath your feet.”
- Hit: “Red chains lock around your legs. Strength bleeds out of your muscles as you fight them.”
- Resist: “You break the binding rune before the red chains can close.”

##### Potion preparation

- “The Battle Witch yanks a reinforced combat vial from her belt with her teeth.”
- “The Battle Witch crushes the seal on a thick black-red flask without taking her eyes off you.”

##### Interrupted

- “The Battle Witch’s combat rune bursts apart under the interruption.”
- “The Battle Witch stumbles half a step as the spell detonates harmlessly in her hand.”

##### Dangerous spell

- Hit: “The Battle Witch crushes a bone charm in her fist. A brutal wave punches through your body and leaves a dangerous magical residue behind.”
- Resist: “You brace through the Battle Witch’s corrupting wave and refuse to let it settle inside you.”

##### Normal magical attack

- “The Battle Witch drives a compact blast of red force straight into your guard.”

##### Potion effects

- Exposure: “The Battle Witch hurls a reinforced amber flask. It bursts across your shoulder and burns cold against your skin.”
- Heal: “The Battle Witch drains a black-red combat tonic. Her posture firms immediately.”
- Mutation: “The Battle Witch flexes her hand as black claws push from the ends of her fingers.”
- Vapour: “The Battle Witch spikes a flask into the floor. A choking red-grey cloud steals your breath and stamina.”

Battle Witch lines should feel **direct, disciplined, and militarised**. Her actions are compact, forceful, and built around combat pressure rather than elaborate spellcraft.

#### PALE CHOIR BEAST WITCH
Uses animals, transformed creatures, body-altering magic, and the Pale Choir's distinctive vocal magic.

Typical abilities:
- Summon beast.
- Strengthen beast.
- Mark prey.
- Rare transformation attack.
- Accelerate an already-active compatible transformation.

Transformation attacks must obey the same secrecy rules as every other transformation source. The UI must not announce the true effect when the spell lands.

##### Casting

- “The Pale Choir Beast Witch opens her mouth and a second, quieter voice begins singing from somewhere inside her.”
- “The Pale Choir Beast Witch tilts her head. A thin note rises until your teeth begin to ache.”

##### Ward

- “The Pale Choir Beast Witch hums a single pure note. Pale rings of sound harden around her body.”
- “The Pale Choir Beast Witch sings into her cupped hands, shaping the note into a shimmering shell.”
- “A glassy shell of vibrating sound closes around the Pale Choir Beast Witch.”

##### Hex

- “The Pale Choir Beast Witch sings your footsteps back to you. Your own shadow starts moving out of rhythm.”
- “The Pale Choir Beast Witch whispers, ‘Kneel for the chorus,’ and pale threads gather around your ankles.”
- Hit: “The chorus catches your name. Pale threads cinch around your legs and drain the strength from them.”
- Resist: “You drown out the whispered chorus before it can fasten itself to you.”

##### Potion preparation

- “The Pale Choir Beast Witch lifts a milk-white vial that vibrates softly in her hand.”
- “The Pale Choir Beast Witch bites the wax from a pale flask while the glass hums against her teeth.”

##### Interrupted

- “The Pale Choir Beast Witch chokes on the note; the chorus breaks into a harsh gasp.”
- “The Pale Choir Beast Witch’s spell fractures into several dying whispers.”

##### Dangerous spell

- Hit: “The Pale Choir Beast Witch snaps a tiny bone whistle. A many-voiced pressure passes through your body and leaves something unfamiliar behind.”
- Resist: “The chorus presses against your body, but your resolve breaks its rhythm.”

##### Normal magical attack

- “The Pale Choir Beast Witch releases a shriek compressed into a hammering wave of force.”

##### Potion effects

- Exposure: “A pearly flask bursts over you. The liquid hums against your skin, and for a moment you hear your pulse singing back.”
- Heal: “The Pale Choir Beast Witch swallows a silver-white tonic. Her ragged breathing settles into rhythm.”
- Mutation: “Her fingertips lengthen subtly, the nails paling into hard hooked points.”
- Vapour: “The Pale Choir Beast Witch shatters a white vial. A sweet, choking mist fills your lungs and drains your stamina.”

Pale Choir Beast Witch lines should feel **unnatural, choral, bodily, and ritualised**. Sound itself should feel like part of the threat, with the player's body treated as something that can be tuned or rewritten.

#### ALCHEMIST WITCH
Uses potions, bombs, powders, and unstable mixtures.

Typical abilities:
- Healing draught.
- Smoke bomb.
- Acid flask.
- Paralysing powder.
- Random experimental potion.
- Dangerous splash effects.
- Rare transformation potion throw.

##### Casting

- “The Alchemist Witch snaps two glass ampoules together. Their vapours spiral into a glowing reaction sigil.”
- “The Alchemist Witch flicks powder across a blue flame and watches the colour change with clinical interest.”

##### Ward

- “The Alchemist Witch sprays a silver reagent into the air. It crystallises into a translucent barrier.”
- “The Alchemist Witch pours a clear solution in a circle; the liquid rises from the floor like glass.”
- “A hard shell of crystallised reagent flashes into place around the Alchemist Witch.”

##### Hex

- “The Alchemist Witch shakes black powder from a paper packet. Every grain lands pointing toward you.”
- “The Alchemist Witch marks the air with a reagent-stained finger. Your muscles begin to feel strangely heavy.”
- Hit: “The black reagent reacts with the air around you. Your limbs become leaden and slow.”
- Resist: “You move before the reagent can finish reacting, breaking the hex’s pattern.”

##### Potion preparation

- “The Alchemist Witch selects one labelled vial from a crowded bandolier.”
- “The Alchemist Witch holds a flask to the light, swirls it once, and smiles at the colour change.”

##### Interrupted

- “The Alchemist Witch’s reaction goes wrong; the mixture spits sparks and dies.”
- “The Alchemist Witch curses as the unstable formula collapses into harmless smoke.”

##### Dangerous spell

- Hit: “The Alchemist Witch crushes a mutagen capsule. Hot chemical pressure rushes through you, leaving a strange aftertaste in your blood.”
- Resist: “The mutagenic pressure reaches you, but your body rejects the reaction before it can settle.”

##### Normal magical attack

- “The Alchemist Witch flings a bead of volatile blue fire that bursts against you like a physical blow.”

##### Potion effects

- Exposure: “An amber mutagen splashes across your shoulder. Your skin tingles sharply as the mixture sinks in.”
- Heal: “The Alchemist Witch downs a measured crimson dose. Her wounds tighten and her breathing steadies.”
- Mutation: “She checks her hand with interest as her nails darken, thicken and sharpen into rough claws.”
- Vapour: “The Alchemist Witch cracks a yellow vial at your feet. Acrid fumes burn your lungs and sap your stamina.”

Alchemist Witch lines should feel **chemical, measured, experimental, and hazardous**. Her effects should read like reactions and compounds rather than generic spellcasting.


### RARE TF POTION THROW

When an Alchemist Witch uses an eligible offensive potion throw, there is approximately a **5% hidden chance** that the potion contains a transformation effect.

This chance is rolled internally and must never be displayed to the player.

The transformation potion may be:

- A partial-transformation effect.
- A progressive-transformation effect.
- A delayed transformation effect.
- A transformation effect combined with an ordinary combat effect.

The player should NOT receive messages such as:

**Transformation potion hit you.**

**Wolf transformation acquired.**

**+1 transformation stage.**

Instead, describe only the immediate perceptible result.

Example:

**The witch hurls a cloudy amber flask.**

**It bursts across your shoulder in a spray of warm liquid.**

**Your skin tingles sharply for several seconds, then the feeling fades.**

The player may initially believe it was only an irritant, poison, weakening potion, or failed attack.

Symptoms can begin later according to the transformation's normal latency and trigger rules.

The approximately 5% chance applies only when the Alchemist Witch actually performs an appropriate potion-throw attack. It is NOT a 5% chance every combat turn.

Most thrown potions must remain ordinary combat mixtures so that a potion throw does not automatically signal transformation risk.

### SELF-USE TF POTIONS

An Alchemist Witch can also drink one of these transformation-capable potions herself.

This can happen in two ways:

1. **Deliberate combat use**
   - The witch knows the potion is dangerous but drinks it for a temporary advantage.
   - She may gain strength, speed, regeneration, armour, claws, enhanced senses, or another useful effect.
   - The transformation may begin during the fight or shortly afterward.

2. **Experimental self-use**
   - The witch drinks an uncertain mixture because she needs healing or a combat advantage.
   - She may not know its complete effect.
   - A hidden transformation effect can activate just as it can for the player.

A self-use transformation potion should be uncommon. It is most appropriate when:

- The witch is below half health.
- The witch is losing badly.
- The witch has been cornered.
- The witch is a reckless experimental alchemist.
- The witch belongs to a faction comfortable with transformation magic.

Example:

**The witch glances at the dark green vial in her hand.**

*"I was saving this."*

**She tears out the stopper and drinks.**

For the next turn, she may only show a combat benefit:

**Her breathing steadies. Her movements become faster.**

Later in the same fight:

**She suddenly grips the edge of the table.**

**Her fingernails darken and lengthen into rough claws.**

If the transformation becomes physically obvious, the player can see it. The UI still should not reveal the exact hidden species, stage, or progression data unless the player has enough evidence.

A witch may continue fighting while partially transformed.

A sufficiently strong self-use potion may temporarily change her combat profile. For example:

- New claw attack.
- Increased speed.
- Increased defence.
- Enhanced regeneration.
- Improved dodge.
- Increased melee damage.

The transformation does not have to complete during one battle. If the witch survives or escapes, later encounters may show that the transformation has progressed.

If the player already has an active transformation from another species, the normal transformation-conflict rules still apply. Do not create accidental hybrids.

#### RITUAL WITCH
Begins relatively weak but becomes dangerous if allowed to complete rituals.

Typical abilities:
- Summon.
- Room-wide curse.
- Seal exits.
- Drain health from a captive or corpse.
- Empower herself.
- Alter dungeon mechanisms.

Attack / intent line pool:
- **The Ritual Witch kneels and presses both palms to the floor. Red lines begin spreading through the cracks.**
- *"You should have interrupted me sooner."*
- **She continues chanting even after you raise your weapon. The symbols around the room brighten one by one.**
- **A nearby corpse jerks as a thin stream of light pulls from it toward her hands.**
- *"One more verse."*
- **The witch turns a rusted Warden seal upside down. Somewhere behind you, a door begins to close.**
- **Three candles gutter at once. The unfinished circle around her starts filling itself with light.**

Ritual Witch lines should feel **deliberate, escalating, and time-sensitive**. Her telegraphs should make it clear that allowing the action to finish is often more dangerous than the witch's immediate physical attack.

The player can often interrupt these rituals.

#### MIRROR WITCH
Uses illusion and deception.

Typical abilities:
- False copies.
- Hidden position.
- Fake item or false door image.
- Misleading combat messages.
- Short-lived charm or confusion effects.

Attack / intent line pool:
- **The Mirror Witch smiles — and three identical smiles appear around the room.**
- *"Which one of us did you mean to hit?"*
- **Her reflection moves half a second before she does.**
- **A second witch appears beside the first, but only one of them disturbs the dust underfoot.**
- *"That door was always there. Weren't you paying attention?"*
- **Her voice comes from behind you while her body remains directly ahead.**
- **For an instant, your own silhouette raises its weapon before you do.**
- *"Try again. I enjoyed watching you miss."*

Mirror Witch lines should feel **taunting, contradictory, and perceptually unreliable**. At least some descriptions should contain a fair visual, auditory, or environmental clue that careful players can use to identify the real threat.

The game must still remain fair. Careful observation, prior knowledge, equipment, or repeated behaviour should provide ways to identify the real witch.

### WITCH DEFEAT STATES

Not every witch encounter ends with death.

At low health, depending on personality and faction, a witch may:

- Flee through a magical passage.
- Offer gold.
- Offer an item.
- Offer information.
- Offer to identify an unknown item.
- Promise a cure.
- Threaten a future consequence.
- Surrender.
- Attempt one last desperate spell.

The player may then choose to:

- Accept the bargain.
- Refuse.
- Demand information.
- Take equipment.
- Let the witch escape.
- Continue attacking.

These decisions can affect faction reputation and later encounters.

---

# 17. HEALTH, INJURY, AND REST

Do not overload the game with simulation.

Use Health plus a limited injury system.

At low health or after certain attacks, the player may gain:

- Bleeding.
- Bruised ribs.
- Sprained ankle.
- Burn.
- Poison.
- Magical fatigue.

Injuries create temporary tactical problems.

Rest can:

- Restore stamina.
- Restore a limited amount of health.
- Advance dungeon time.
- Trigger certain curse or transformation events.
- Risk interruption in unsafe rooms.

A "safe room" reduces interruption risk but should still consume time.

---

# 18. WEAPON AND ARMOUR CONDITION

Avoid tedious durability micromanagement.

Use condition bands:

- Excellent.
- Worn.
- Damaged.
- Critical.
- Broken.

Condition decreases after significant combat rather than every single attack.

Effects:

- Worn: mostly cosmetic warning.
- Damaged: small penalty.
- Critical: significant penalty and risk of breaking.
- Broken: unusable until repaired.

Repair kits, blacksmith-like NPCs, enchanted repair, and salvaged parts can restore condition.

---

# 19. INVENTORY, CAPACITY, AND DROPPING

Inventory limits should create decisions without becoming annoying.

Use slot-based capacity, but give the player enough room to experiment with loot instead of forcing constant inventory cleanup.

## BASE INVENTORY CAPACITY

The player begins with **24 backpack slots**.

Equipped gear does not consume backpack slots while it is actively equipped:

- Equipped main weapon: 0 backpack slots.
- Equipped armour: 0 backpack slots.
- Equipped amulet or accessory: 0 backpack slots.
- Spare weapons, spare armour, and unequipped accessories use normal inventory space.

Typical carried-item sizes:

- Small item: 1 slot.
- Potion: 1 slot, with identical common potions stacking where sensible.
- Amulet or small magical object: 1 slot.
- Weapon: 2–3 slots.
- Armour piece: 2–4 slots.
- Bulky tool or large salvage item: 3–5 slots.
- Large quest object: special slot or temporary burden rather than normal backpack space.

Common low-value materials, bandages, ammunition-like supplies, and alchemy ingredients should stack where sensible.

## INVENTORY UPGRADES

The player can find or buy better carrying equipment during a run.

Examples:

- Reinforced Satchel: **+4 slots**.
- Explorer's Pack: **+6 slots**.
- Warden Field Pack: **+8 slots**.

Normal inventory capacity should usually be able to grow from **24 slots to roughly 32–36 slots** during a long run.

Rare magical storage may exceed this slightly, but inventory upgrades should never become effectively unlimited.

Upgrades replace or improve the player's carrying equipment rather than requiring several backpacks to be carried inside one another.

## DROP MECHANIC

The inventory screen includes a **DROP** action for normal carried items.

Dropping an item:

- Immediately frees the slots used by that item.
- Places the item in the current room.
- Adds it to a temporary **Dropped Items** list for that room.
- Allows the player to pick it back up while the room remains accessible.
- Does not destroy the item immediately.

Because the dungeon is forward-only, dropped items become permanently lost once the player commits to an exit and the room becomes inaccessible.

The game should clearly warn the player before leaving a room that still contains valuable or unusual dropped items.

Example warning:

**You have left items behind in this room. Once you leave, you may not be able to return.**

[ LEAVE THEM ]

[ REVIEW DROPPED ITEMS ]

## FULL INVENTORY DURING LOOTING

If the player finds an item while their inventory is full, do not automatically destroy either item.

Give the player choices such as:

- **TAKE — DROP SOMETHING ELSE**
- **SWAP WITH CARRIED ITEM**
- **LEAVE ITEM HERE**
- **EXAMINE BEFORE DECIDING**

This is especially important for unknown potions, amulets, witch loot, weapons, and rare cures.

## DROP RESTRICTIONS AND WARNINGS

Quest-critical items, essential keys, and objects required to preserve a viable escape route should normally be protected from accidental dropping.

If an authored quest allows such an item to be abandoned, require a strong confirmation warning.

Rare, unidentified, equipped, cursed, or unusually valuable items should also receive a confirmation prompt before being dropped.

Example:

**This item is unidentified. If you leave this room, it may be lost permanently. Drop it anyway?**

Dropping an equipped item automatically unequips it first.

A magically bound item may refuse to be dropped if its established rules say it cannot be removed.

## DROPPING TRANSFORMATION-RELATED ITEMS

Dropping a transformation-capable item does not automatically cure anything.

For example:

- Dropping or removing a prolonged-wear amulet stops further wear exposure while it is no longer equipped, subject to that amulet's normal rules.
- Any physical transformation that has already activated remains unless reversed or cured.
- Dropping a potion bottle does not remove exposure from doses already consumed.
- A cursed or magically bound item may resist being discarded if that behaviour is explicitly part of the item.

The player should therefore be able to discard a suspicious source without being falsely told that doing so has undone its effects.

## COMBAT DROPPING

Normal inventory dropping is primarily an exploration action and is not normally available during combat.

A specific combat encounter may allow an authored **DROP / THROW AWAY** action when relevant, but players should not need to reorganise their backpack while enemies are attacking them.

## INVENTORY PRESSURE GOAL

The larger capacity should reduce tedious item management without removing meaningful choices.

The player should still sometimes choose between:

- Carrying another healing potion.
- Keeping an unidentified amulet.
- Taking valuable loot for sale.
- Keeping a spare heavy weapon.
- Carrying alchemy ingredients.
- Leaving room for possible witch or boss loot.

Inventory pressure should come from carrying several valuable possibilities, not from the backpack filling after only a few ordinary pickups.

---

# 20. ITEM KNOWLEDGE SYSTEM

Every unknown magical item has two separate records:

## TRUE EFFECT
Known only by the engine.

## PLAYER KNOWLEDGE
What the character currently believes.

Use four identification states:

### UNKNOWN
Appearance only.

### OBSERVED
The player has noticed one or more effects.

### PARTIALLY IDENTIFIED
At least one effect is known, but hidden properties may remain.

### RELIABLY IDENTIFIED
A trustworthy method has revealed the complete relevant effect.

Identification sources have a reliability rating.

Examples:

- Visual guess: Poor.
- Old note: Questionable.
- Personal symptom: Direct but incomplete.
- Cheap merchant appraisal: Moderate.
- Skilled alchemist: Good.
- Specialist test: Excellent.
- Ancient diagnostic device: Near-certain.

A wrong identification should be rare and should normally come from an explicitly unreliable source.

The system should create uncertainty without making all information meaningless.

---

# 21. POTION AND AMULET RISK

Unknown potions and amulets should remain tempting.

Do not make every unknown item dangerous.

Keep the existing broad philosophy of a roughly mixed pool, but use **region weighting**.

Example internal tendency:

## EARLY / ORDINARY REGIONS
Transformation-capable unknown items are less common.

## ALCHEMY / WITCH / BEAST REGIONS
Transformation-capable unknown items become more common.

## DEEP CURSED REGIONS
The chance can approach or exceed the game's overall 40–50% target for unknown magical items.

Across the whole adventure, the player should never be able to infer:

- "Unknown means transformation."
- "Strong buff means cursed."
- "Strange appearance means dangerous."
- "Normal appearance means safe."

---


## EXPANDED POTION POOL

The dungeon should contain a much larger potion catalogue than the small number of transformation examples listed elsewhere.

The following categories are **internal design information**. The game should not label bottles as SAFE, RISKY, TRANSFORMATION, or CURSED unless the player has identified them through a reliable method.

Potions may appear under alternate bottle shapes, colours, makers, and regional names so that the player cannot identify them purely by memorising one visual description.

### SECOND WIND DRAUGHT

Visible / identifiable effect:
- Restores a large amount of Stamina immediately.
- Removes one level of ordinary physical exhaustion.

Hidden:
- No transformation effect.

Possible appearance:
- Cloudy blue liquid with a sharp mint smell.

### REDMOSS RESTORATIVE

Visible / identifiable effect:
- Restores moderate Health.
- Slightly improves natural recovery for the next room.

Hidden:
- No transformation effect.

Possible appearance:
- Thick red-brown tonic with plant sediment at the bottom.

### CLEARBLOOD PHIAL

Visible / identifiable effect:
- Reduces or removes ordinary poison.
- Weakens some alchemical damage-over-time effects.

Hidden:
- No transformation effect.

Possible appearance:
- Almost colourless fluid with silver bubbles that cling to the glass.

### IRONHEART TONIC

Visible / identifiable effect:
- +20 temporary Maximum Health for 4 rooms.
- Small resistance to bleeding while active.

Hidden:
- No transformation effect.

Possible appearance:
- Dark metallic liquid that leaves a copper taste.

### FOCUS ELIXIR

Visible / identifiable effect:
- +15% Accuracy for 4 rooms.
- Examine actions reveal slightly more combat information while active.

Hidden:
- No transformation effect.

Possible appearance:
- Thin violet liquid that becomes perfectly still when held.

### STONEGUARD DECOCTION

Visible / identifiable effect:
- +20% Defence for 3 rooms.
- Reduced knockback or interruption from heavy enemy attacks.

Hidden:
- Normally safe.
- Some rare counterfeit batches may instead belong to the Scale-affinity potion family.

Possible appearance:
- Grey suspension with gritty mineral flakes.

This item is useful for preventing the player from assuming that every defence potion connected with scales or stone must transform them.

### LUCID SALT TONIC

Visible / identifiable effect:
- Restores some Resolve.
- Improves resistance to fear, charm, coercion, and magical confusion for 3 rooms.

Hidden:
- No transformation effect.

Possible appearance:
- Pale liquid containing slowly dissolving white crystals.

### EMBERGLASS SERUM

Visible / identifiable effect:
- Temporary resistance to fire and heat.
- Reduces burn duration.

Hidden:
- Most versions are safe.
- Rare alchemical variants may carry dormant reptilian or dragon-affinity magic.

Possible appearance:
- Orange liquid that remains warm even in cold rooms.

### WHISPERSTEP INFUSION

Visible / identifiable effect:
- +15% Speed for 4 rooms.
- Slight bonus to Evade and stealth-related room actions.

Hidden:
- No transformation effect in the ordinary version.

Possible appearance:
- Clear green liquid that makes almost no sound when shaken.

### GRAVEWATER DRAUGHT

Visible / identifiable effect:
- Temporarily suppresses pain penalties from injuries.
- Prevents Magical Fatigue from worsening for 2 rooms.

Hidden:
- Does not heal the underlying injury.
- No transformation effect.

Possible appearance:
- Black water with a cold mist inside the bottle.

Its ominous appearance should make it a useful example of a frightening-looking potion that is not secretly transformative.

### RED FANG TONIC

Visible / identifiable effect:
- +20% Damage for 4 rooms.
- Small bonus to tracking wounded enemies.

Hidden:
- Wolf-affinity exposure.
- Repeated use may add to the same cumulative pool as Hunter Draught and Moonblood Elixir.
- Can be partial or progressive depending on the generated batch.

Possible early symptoms after activation:
- Improved hearing.
- Tooth pressure.
- Stronger awareness of blood or scent.

### MOONBLOOD ELIXIR

Visible / identifiable effect:
- Restores Health when the player is below half Health.
- +10% Speed for 3 rooms.

Hidden:
- Wolf-affinity exposure.
- Risk rises considerably when used repeatedly while injured or during night/deep-dungeon conditions.

Possible appearance:
- Dark red liquid with a pale film across its surface.

### GLASS-EYE SERUM

Visible / identifiable effect:
- Improved dark vision for 6 rooms.
- +10% Critical Chance against enemies that have not yet hit the player.

Hidden:
- Delayed cat-affinity transformation chance.
- Often has a long latency, so symptoms may begin after the useful effect has ended.

Possible symptoms:
- Pupils reacting strangely to light.
- Improved balance.
- Increased sensitivity to movement.

### SOFTPAW NECTAR

Visible / identifiable effect:
- +20% stealth effectiveness.
- Quieter movement.
- Small Evade bonus.

Hidden:
- Fox-affinity exposure.
- Usually capped as a partial transformation, but rare stronger batches may be progressive.

Possible symptoms:
- Sharper hearing.
- Pressure around the ears.
- Unusual balance changes.

### QUICKTALON DRAUGHT

Visible / identifiable effect:
- +25% Speed for 3 rooms.
- Heavy Attacks cost less Stamina while active.

Hidden:
- Raptor-affinity exposure.
- Repeated doses can accelerate hand, foot, and balance changes.

Possible symptoms:
- Cramped fingers.
- Hardening nails.
- Unusually precise footing.

### CINDER-SCALE ELIXIR

Visible / identifiable effect:
- +20% Defence.
- Fire resistance for 4 rooms.

Hidden:
- Reptilian or dragon-family exposure depending on the generated formula.
- Usually begins with skin or scale changes rather than behavioural effects.

Possible symptoms:
- Dry heat beneath the skin.
- Roughened patches along the arms or shoulders.
- Increased heat tolerance after the potion should have worn off.

### HOLLOWHORN CORDIAL

Visible / identifiable effect:
- +20% Heavy Attack damage.
- Increased resistance to knockback.

Hidden:
- May cause a stable partial horned transformation.
- Normally capped well below a full transformation.

Possible symptoms:
- Pressure across the forehead.
- Headaches concentrated above the temples.
- Hard spots beneath the skin.

### SILVER VEIL ANTIDOTE

Visible / identifiable effect:
- Removes one minor curse or reduces its duration.
- Strong resistance to magical contamination for the next 2 rooms.

Hidden:
- No transformation effect.
- Does not cure an established transformation source unless that specific transformation explicitly lists it as compatible.

This prevents ordinary anti-curse potions from becoming universal transformation cures.

### BLACKSTAR RESERVE

Visible / identifiable effect:
- Restores both Health and Stamina.
- +10% Damage and Defence for the next battle.

Hidden:
- Rare and powerful, but not automatically transformative.
- Some dungeon-made imitations may contain an unknown secondary effect.

Possible appearance:
- Completely ordinary brown medicine bottle with a faded paper label.

This is another deliberate false tell: a plain-looking bottle can be extremely valuable, and a plain-looking imitation can be dangerous.

## POTION GENERATION VARIATION

Named potion families should not always be mechanically identical.

The generator may vary:

- Strength of the visible buff.
- Duration.
- Whether the bottle is genuine, diluted, spoiled, or counterfeit.
- Whether a transformation-capable batch is partial, progressive, delayed, or cumulative.
- Latency.
- Exposure decay.
- Transformation cap.
- Side effects such as nausea, Magical Fatigue, temporary Accuracy loss, or Stamina drain.

However, variation must remain authored within sensible limits. A potion should not randomly become unrelated to its established family simply to trick the player.

---

## EXPANDED AMULET POOL

Amulets should include ordinary protective charms, exploration tools, strong combat items, cursed objects, and transformation-capable pieces.

Not every powerful amulet should transform the wearer.

Not every transformation-capable amulet should look sinister.

### WARDEN'S TOKEN

Visible / identifiable effect:
- +10% Guard / Defence.
- Slightly improves Examine results on Warden mechanisms and ancient security devices.

Hidden:
- No transformation effect.

Appearance:
- Heavy iron disc stamped with a nearly worn-away tower symbol.

### LANTERN EYE

Visible / identifiable effect:
- Improved searching in dark rooms.
- Small bonus to detecting traps, hidden compartments, and unusual item markings.

Hidden:
- No transformation effect.

Appearance:
- Brass eye-shaped charm holding a cloudy yellow stone.

### QUIET BELL

Visible / identifiable effect:
- +15% Resolve against fear and coercion.
- Slightly reduces the effect of auditory illusion magic.

Hidden:
- No transformation effect.

Appearance:
- Tiny black bell that never makes a sound when shaken.

### MENDER'S LOOP

Visible / identifiable effect:
- Equipment condition degrades more slowly.
- Repair kits are slightly more effective while the amulet is equipped.

Hidden:
- No transformation effect.

Appearance:
- Simple copper loop threaded with red cord.

### PILGRIM'S KNOT

Visible / identifiable effect:
- +10% Stamina recovery from Defend.
- Reduced Stamina cost for climbing, forcing doors, and similar exploration actions.

Hidden:
- No transformation effect.

Appearance:
- A rough knotted cord containing a smooth river stone.

### GLASS WARD PENDANT

Visible / identifiable effect:
- Once per battle, reduces the damage of one magical attack.
- The ward must recharge outside combat before working again.

Hidden:
- No transformation effect.

Appearance:
- Clear triangular crystal with a hairline crack through its centre.

### BLOOD-PRICE MEDALLION

Visible / identifiable effect:
- +25% Damage while below 40% Health.

Hidden:
- No transformation effect.
- The danger is ordinary: it encourages fighting while badly injured.

Appearance:
- Dark red metal coin on a chain.

This is useful because a mechanically dangerous item does not need a supernatural hidden consequence.

### HUNTER'S TOOTH

Visible:
- +25% Damage.
- +10% Critical Chance.

Hidden:
- Prolonged wear can begin a partial wolf transformation.
- Usually behaves as a Memory Amulet and remembers previous wear exposure.

### MOONFANG RELIQUARY

Visible:
- Improved tracking.
- +15% Speed after the player or an enemy begins bleeding.

Hidden:
- Progressive wolf-affinity transformation.
- Wear exposure rises faster during combat and while the player is injured.

Appearance:
- A small silver case containing what appears to be a chipped animal tooth.

### NIGHTGLASS CHARM

Visible:
- Improved dark vision.
- +15% Dodge.

Hidden:
- Prolonged wear can begin a progressive cat transformation.

### VELVET CLAW LOCKET

Visible:
- +10% Speed.
- +15% Critical Chance against unaware or recently missed enemies.

Hidden:
- Cat-affinity partial transformation.
- Common caps include eyes, ears, reflexes, or nails rather than complete transformation.

Appearance:
- Innocent black velvet locket with no obvious animal design.

### FOXFIRE LOCKET

Visible:
- Improved stealth.
- Once per room, grants a small bonus when distracting, deceiving, or slipping past an enemy.

Hidden:
- Fox-affinity prolonged-wear effect.
- Often behaves as a Resetting Amulet, allowing accumulated risk to fade after long periods unequipped.

Appearance:
- Warm orange stone in a plain bronze setting.

### TALON SIGIL

Visible:
- +15% Speed.
- Reduced Stamina cost for Heavy Attacks and jumping actions.

Hidden:
- Raptor-affinity transformation.
- Progression gains additional pressure from repeated Heavy Attacks and high-intensity combat.

Appearance:
- Flat bone charm engraved with three narrow lines.

### IRON SCALE PENDANT

Visible:
- +20% Defence.
- +20 Maximum Health.

Hidden:
- Prolonged wear can begin a stable partial reptilian transformation.

### EMBER SCALE

Visible:
- Fire resistance.
- Small natural regeneration after taking burn damage.

Hidden:
- Dragon-family prolonged-wear transformation chance.
- Usually slow to activate but difficult to suppress once firmly established.

Appearance:
- A dark red scale mounted in an iron frame. It may be genuine, carved, or impossible to identify by sight alone.

### HOLLOW ANTLER CHARM

Visible:
- +20% resistance to knockback and stagger.
- Heavy Attacks deal slightly more interruption damage.

Hidden:
- Can produce a stable partial horned transformation.
- Usually does not progress toward a full beast form.

Appearance:
- Pale carved charm shaped like a branching twig.

### CHAINED HEART

Visible:
- +20% Resolve.
- Strong resistance to charm and coercion.

Hidden:
- After prolonged wear, the amulet may become Bound and difficult to remove.
- It is cursed, but does **not** transform the wearer.

Appearance:
- Small iron heart wrapped in delicate chain.

This reinforces that a bound or cursed amulet is not automatically a transformation item.

### MIRROR SHARD PENDANT

Visible:
- First illusion or confusion effect in a battle has reduced potency.
- Small bonus to detecting Mirror Witch deception.

Hidden:
- No transformation effect.
- Rare damaged versions can produce misleading sensory messages without changing the body.

Appearance:
- Polished sliver of mirror wrapped in wire.

### EMPTY COLLAR TAG

Visible:
- +20% Damage against summoned beasts.
- +10% Resolve against Beastcaller Hex effects.

Hidden:
- Some versions are ordinary anti-beast charms.
- Rare corrupted versions carry a compatible beast-affinity effect and may react strongly to Beastcaller magic.

Appearance:
- Plain iron tag with a blank face.

The item should not reveal which version the player has without testing or experience.

## AMULET SLOT AND SWAP RULE

Amulets use a dedicated accessory slot and therefore do not consume backpack slots while equipped.

The player may normally carry additional amulets in the backpack and swap them outside the resolution of an enemy attack.

Changing an amulet:

- Does not erase accumulated wear exposure unless that particular amulet uses Resetting behaviour.
- Does not reverse physical changes already caused.
- May pause an active source if the source requires continued wear.
- May be impossible if the amulet has become Bound.

This makes the expanded amulet pool useful without encouraging the player to stack every bonus simultaneously.

## ITEM-POOL FAIRNESS RULE

Across a long run, the loot generator should maintain enough ordinary potions and safe amulets that cautious players still have reasons to experiment with unidentified items.

Transformation-capable loot should remain a meaningful minority outside specialised regions.

The game should deliberately include:

- Safe items with ominous names.
- Dangerous items with ordinary names.
- Strong safe buffs.
- Weak risky buffs.
- Powerful risky buffs.
- Cursed items that do not transform.
- Transformation items that are not technically cursed.

This prevents the player from solving the whole item-risk system through superficial pattern recognition.

---

# 22. ITEM TESTING

Give cautious players tools other than simply drinking the potion.

Possible methods:

- Smell.
- Examine sediment.
- Compare bottle symbols.
- Use alchemy paper.
- Apply a drop to metal.
- Feed a tiny amount to a reagent creature or magical test culture.
- Ask an alchemist.
- Compare against journal notes.
- Use an identification scroll.
- Use a rare diagnostic device.

Testing should not always reveal everything.

For example:

**Alchemy paper turns silver.**
Journal knowledge may suggest:
- Strength effect possible.
- Beast-affinity magic possible.
- Exact outcome unknown.

The player now has more information but still must decide.

---

# 23. PROLONGED-WEAR AMULET RISK

Some transformation-capable amulets should not begin changing the player immediately.

Instead, they provide a genuine useful bonus first and become risky only after being worn for a long enough period.

Among **transformation-capable amulets**, approximately **20%** may use this prolonged-wear transformation mechanic.

This 20% chance is internal and is never shown as a numerical probability to the player.

## BASIC RULE

When equipped:

- The amulet's visible stat benefit begins normally.
- Nothing immediately confirms a transformation effect.
- The game secretly tracks how long the amulet remains equipped.
- The longer it remains worn, the greater the chance that its hidden transformation effect begins.
- Removing the amulet before activation may prevent the transformation from starting.
- Once the transformation has actually activated, removing the amulet does not necessarily reverse changes that have already occurred.

This creates a decision:

**Keep the powerful bonus, or remove the amulet before the unknown long-term effect becomes worse.**

## PLAYER-FACING WARNING

Some of these amulets can be partially identified well enough to give the player a warning without revealing exactly what will happen.

Example:

### UNKNOWN SILVER FANG

Known effect:

**+25% Damage while worn**

Appraisal note:

**Prolonged wear may produce an unknown secondary effect.**

or:

**The enchantment becomes more active the longer the amulet remains in contact with its wearer.**

or:

**Wear for the combat benefit, but extended use may have consequences.**

The player is NOT automatically told:

- That the secondary effect is a transformation.
- What species it causes.
- Whether it is partial or progressive.
- When it will activate.
- Which body part will change.

A poor identification may reveal only the bonus.

A good identification may warn that prolonged use is unsafe.

A very reliable specialist may eventually identify the secondary effect more clearly.

## HIDDEN WEAR TIMER

Each prolonged-wear amulet secretly tracks **wear exposure**.

Wear exposure increases only while the amulet is equipped.

Example internal model:

- First 3 rooms worn: essentially dormant.
- 4–6 rooms worn: low activation chance.
- 7–10 rooms worn: moderate activation chance.
- 11+ rooms worn: high activation chance.

These numbers are examples and should vary by item.

Do not make activation happen at the exact same room count every time.

The game can use an increasing hidden chance so the player cannot simply memorize:

**"Take every amulet off after Room 6."**

## REMOVING AND RE-EQUIPPING

Different amulets may behave differently.

### MEMORY AMULET

The amulet remembers previous wear time.

Removing it pauses the hidden counter.

Re-equipping it continues from the previous exposure.

### RESETTING AMULET

The hidden risk slowly fades while unequipped.

After enough rooms without wearing it, some or all accumulated wear exposure disappears.

### BOUND AMULET

After sufficient wear, the amulet becomes magically attached or difficult to remove.

This should be uncommon and should have warning signs before it happens.

## ACTIVATION EVENT

When the hidden wear threshold finally activates, do not announce:

**Transformation started.**

Instead use a normal symptom.

Example:

After wearing the amulet for nine rooms:

**A dull ache develops behind your ears.**

Two rooms later:

**The metal pendant feels strangely warm against your chest.**

Later:

**You brush your hair aside and stop. The upper edge of one ear feels different.**

The player must connect the symptoms to the amulet themselves unless they obtain reliable identification.

## BENEFIT CAN MAKE REMOVAL DIFFICULT

The stat bonus should be strong enough that keeping the amulet is genuinely tempting.

Examples:

### HUNTER'S TOOTH

Visible:
- +25% Damage.
- +10% Critical Chance.

Hidden:
- Prolonged wear can begin a partial wolf transformation.

### NIGHTGLASS CHARM

Visible:
- Improved dark vision.
- +15% Dodge.

Hidden:
- Prolonged wear can begin a progressive cat transformation.

### IRON SCALE PENDANT

Visible:
- +20% Defence.
- +20 Maximum Health.

Hidden:
- Prolonged wear can begin a stable partial reptilian transformation.

A cautious player may remove the amulet early and keep their human form.

A risk-taking player may knowingly continue wearing it because the bonus is helping them survive.

This mechanic must never make transformation unavoidable.

---

# 24. DELAYED / CUMULATIVE POTION TRANSFORMATION RISK

Some transformation-capable potions should work similarly to prolonged-wear amulets.

They provide a genuine useful effect immediately, while the hidden transformation risk may not activate until later.

Among **transformation-capable potions**, approximately **20%** may use this delayed or cumulative transformation mechanic.

This percentage is internal and must never be shown directly to the player.

## BASIC RULE

When the player drinks one of these potions:

- The advertised or observable benefit begins normally.
- No transformation is immediately announced.
- The potion secretly creates a hidden transformation exposure.
- The transformation may activate only after enough time, rooms, triggers, or repeated doses.
- A single dose may never progress far if the effect is weak.
- Repeated use of the same or compatible potion can increase the chance of activation.

This creates a similar temptation to prolonged-wear amulets:

**The potion is useful now, but continued reliance on it may have consequences later.**

## PLAYER-FACING WARNING

A partially identified potion may reveal the useful effect plus an uncertain warning.

Example:

### CRIMSON HUNTER DRAUGHT

Known effect:

**+30% Damage for 5 rooms**

Appraisal note:

**Repeated use may cause an unknown secondary reaction.**

or:

**Residual magic may accumulate in the body.**

or:

**The immediate combat effect is understood. Long-term effects are uncertain.**

or:

**Safe in limited use according to incomplete records.**

The player is NOT automatically told:

- That the secondary effect is a transformation.
- Which species it may cause.
- Whether it is partial or progressive.
- How many doses are safe.
- Exactly when activation will happen.

A poor appraisal may reveal only the combat bonus.

A good appraisal may reveal that repeated use is risky.

A highly reliable specialist may identify the likely transformation effect.

## SINGLE-DOSE DELAYED POTIONS

Some potions need only one dose, but their hidden effect has a long latency.

Example internal structure:

- Immediate effect: +25% Speed for 4 rooms.
- Hidden effect: partial fox transformation.
- Latency: 3–7 rooms.
- Activation chance rises after the visible buff has already ended.

Example player experience:

Room 21:

**You drink the orange potion. Warmth spreads through your legs.**

Visible result:

**Speed increased.**

Room 26:

**Your balance feels strangely precise.**

Room 28:

**A dull pressure develops near the base of your spine.**

The player may only then begin suspecting the potion.

## CUMULATIVE POTIONS

Other potions become dangerous mainly through repeated use.

The engine secretly tracks **potion exposure** for compatible mixtures.

Example:

- First dose: very low transformation risk.
- Second dose: low risk.
- Third dose: moderate risk.
- Fourth dose: high risk.
- Further doses: very high risk.

These values are examples only.

Different potions should have different thresholds and exposure rates.

Do not make the system predictable enough that players can always memorise an exact safe number of doses.

## EXPOSURE DECAY

Some cumulative potion effects can slowly fade if the player stops using them.

Example:

- 1–2 rooms without another dose: no change.
- Several rooms without another dose: exposure begins decreasing.
- Long periods without another compatible potion: much of the accumulated risk may disappear.

Other stronger magical compounds may leave permanent hidden exposure until cured or activated.

This property should depend on the individual potion.

## COMPATIBLE POTION STACKING

Repeated doses do not have to be the exact same bottle type.

Potions built around the same hidden transformation family may add to the same exposure pool.

Example:

- Hunter Draught — hidden wolf affinity.
- Red Fang Tonic — hidden wolf affinity.
- Moonblood Elixir — hidden wolf affinity.

Using several of these can accumulate compatible hidden exposure.

The player does not know this automatically.

Research or reliable alchemy notes may reveal that several potions share the same magical signature.

## ACTIVATION

When the transformation finally activates, show symptoms rather than a system announcement.

Do NOT display:

**Cumulative Wolf Transformation Activated.**

Instead:

**Your teeth ache when you bite down.**

Later:

**For a moment, you hear something moving behind the next door far more clearly than you should.**

Later:

**Several hairs along your forearm have become noticeably darker and coarser.**

The player must infer the cause from timing, repeated use, testing, or reliable identification.

## POTION BENEFIT VS RISK

These potions should be strong enough that repeated use is tempting.

Examples:

### HUNTER DRAUGHT

Visible:
- +30% Damage for 5 rooms.
- +10% Critical Chance.

Hidden:
- Repeated use can begin a partial or progressive wolf transformation.

### NIGHTSTEP TONIC

Visible:
- +20% Speed.
- Improved dark vision.

Hidden:
- Cumulative use can begin a cat transformation.

### SCALEBLOOD ELIXIR

Visible:
- +20% Defence.
- Temporary resistance to fire.

Hidden:
- Repeated use can gradually produce stable reptilian scales.

### RAPTOR RUSH

Visible:
- +25% Speed.
- Reduced stamina cost for heavy attacks.

Hidden:
- Repeated doses may eventually trigger raptor-like changes.

## USING A POTION AFTER SYMPTOMS BEGIN

Once symptoms appear, the player may still choose to drink another dose.

That decision should be allowed.

If another compatible dose is consumed:

- Hidden progression may increase.
- The immediate buff still works.
- Symptoms may intensify.
- The next transformation event may occur sooner.

This creates a real risk/reward decision when the player is low on resources or facing a boss.

## ALCHEMIST WITCHES AND CUMULATIVE POTIONS

Alchemist Witches may carry and use these delayed/cumulative potions as well.

A witch who repeatedly uses the same dangerous combat mixture across encounters may gradually transform herself.

If she escapes and is encountered later, the player may notice that she has changed since the previous fight.

Example:

First encounter:

**She drinks a red tonic and becomes faster.**

Second encounter much later:

**The witch looks familiar, but her pupils are narrower now and her movements have an unnatural quickness.**

This can create recurring enemy progression without immediately revealing the potion's true nature.

## FAIRNESS RULE

The player must always have ways to reduce risk:

- Stop using the potion.
- Test similar potions.
- Seek identification.
- Use suppression.
- Use reversal.
- Seek a cure.
- Avoid compatible mixtures.

Delayed and cumulative potion transformation must create temptation and uncertainty, not unavoidable punishment.

---

# 25. TRANSFORMATION ENGINE — INTERNAL MODEL

Every transformation source should use a consistent hidden data structure.

Suggested fields:

- Species.
- Source.
- Effect type.
- Progressive or partial.
- Maximum stage.
- Current hidden stage.
- Stage progress.
- Latency.
- Progression trigger.
- Trigger intensity.
- Resistance difficulty.
- Symptom schedule.
- Physical-change schedule.
- Behavioural-effect schedule.
- Cure compatibility.
- Suppression compatibility.
- Player knowledge level.

None of this should automatically be shown to the player.

---

# 26. TRANSFORMATION TYPES

## PARTIAL TRANSFORMATION

A partial transformation has a hard hidden cap.

Examples:

- Wolf ears only.
- Wolf tail only.
- Cat eyes only.
- Raptor claws only.
- Dragon scales across the arms.
- Goat horns.
- Animal-like feet.
- Sharper senses plus one visible feature.

When the cap is reached:

- Passive progression stops.
- The change remains stable.
- The item or curse may continue providing its benefit.
- The player is not secretly pushed toward a full transformation.

Further progression can occur only if the player later acquires a compatible additional effect that explicitly raises the cap.

## PROGRESSIVE TRANSFORMATION

A progressive transformation can advance through the full stage system.

It still should not progress automatically every room.

It advances according to its trigger rules.

Examples:

- Combat.
- Taking damage.
- Resting.
- Night.
- Magic use.
- Drinking potions.
- Entering cursed regions.
- Equipping the source item.
- Low health.
- Emotional stress.
- Specific rituals.

The player can therefore sometimes slow progression by changing behaviour.

---

# 27. TWELVE-STAGE TRANSFORMATION MODEL

Keep twelve internal stages for full transformations.

The exact stage number remains hidden unless a reliable diagnostic method reveals it.

Suggested pacing:

## STAGE 0
No transformation.

## STAGE 1
Subtle sensory or internal effects.

## STAGE 2
Minor discomfort or tiny physical sign.

## STAGE 3
One clearly abnormal feature.

## STAGE 4
Several small changes.

## STAGE 5
Visible change difficult to dismiss.

## STAGE 6
Mostly human, unmistakably altered.

## STAGE 7
Major limbs, face, skin/fur/scales, or posture begin changing.

## STAGE 8
Equipment fit becomes a serious issue.

## STAGE 9
Movement and combat abilities change substantially.

## STAGE 10
Human appearance is heavily reduced.

## STAGE 11
Near-complete transformation.

## STAGE 12
Full physical transformation.

Not every species uses identical body-part order.

Not every transformation changes intelligence, personality, or speech.

---

# 28. TRANSFORMATION PROGRESSION

Do not use "one room = progress."

Instead, each effect has hidden progress points.

Example:

A progressive wolf effect might use:

- Normal room cleared: +0.
- Combat entered: +1.
- Player takes heavy damage: +2.
- Rest during deep night: +1.
- Source amulet remains equipped after battle: +1.
- Resistance success: reduce gain.
- Suppression active: gain paused.

When hidden progress crosses the next threshold, the next transformation event occurs.

This makes transformation connected to behaviour rather than arbitrary time.

---

# 29. LATENCY

Transformation effects should often have latency.

Example:

The player drinks a potion in Room 14.

Immediate visible effect:
- +30% damage for six rooms.

Hidden effect:
- Wolf partial transformation.
- Latency: 2–4 rooms.
- Maximum stage: 3.

Room 16:
- Unusually sharp hearing.

Room 18:
- Ear pain.

Room 20:
- Ear shape visibly changes.

Then progression stops.

The player can plausibly connect cause and effect, but not instantly.

---

# 30. TRANSFORMATION STACKING

The one-species rule needs an explicit conflict rule.

## SAME-SPECIES EFFECTS

Compatible effects may:

- Increase progression speed.
- Raise the partial cap.
- Add a different body feature.
- Extend duration of a buff.
- Increase resistance difficulty.

Example:

A wolf-ear partial effect capped at Stage 3 plus a second compatible wolf-tail effect can create both ears and tail while still remaining partial.

A later full progressive wolf curse can convert the existing changes into part of the full progression.

## DIFFERENT-SPECIES EFFECTS

Never create hybrids by accident.

If the player already has an active species transformation, a conflicting transformation effect should use one of these authored outcomes:

- Fail to transform the body.
- Cause temporary magical sickness.
- Be suppressed by the dominant transformation.
- Replace the old effect only if the new source is explicitly powerful enough.
- Produce an ordinary curse instead.

The game engine must choose an outcome defined by the source.

Do not combine wolf ears with raptor claws unless the game contains a deliberately authored hybrid mechanic. By default, it does not.

---

# 31. HUMANITY AND SELF-CONTROL

Physical transformation and mental control are separate systems.

A wolf transformation does not automatically make the player violent.

A raptor transformation does not automatically remove speech.

A cat transformation does not automatically change personality.

Use **Resolve / Self-Control** only when a specific effect actually creates instincts, compulsions, rage, fear, or behavioural pressure.

Examples:

- Some transformations are entirely physical.
- Some curses create hunting instincts.
- Some witch bargains create compulsions.
- Some full transformations preserve normal thought.

This prevents transformation from becoming a generic "lose your mind" mechanic.

---

# 32. CLOTHING AND EQUIPMENT

Equipment interaction should happen at meaningful physical thresholds.

Examples:

- Slightly pointed ears: helmet still fits.
- Large ears: closed helmet uncomfortable.
- Small tail: trousers tight.
- Large tail: normal lower-body armour unusable unless modified.
- Clawed hands: some gloves unusable.
- Digitigrade legs: normal boots unusable.
- Large horns: helmets restricted.
- Scales: may provide small natural armour.

The player should have options:

- Modify equipment.
- Replace equipment.
- Remove equipment.
- Buy transformed-fit equipment from certain merchants.
- Use straps, wraps, or open armour.
- Accept a defence penalty for keeping ill-fitting gear.

---

# 33. TRANSFORMATION ADVANTAGES

Transformations should sometimes unlock real gameplay options.

Examples:

## WOLF
- Enhanced smell.
- Track enemies.
- Detect blood.
- Bite/claw abilities.
- Better hearing.

## FOX
- Improved stealth.
- Distraction.
- Small-space movement at later stages.
- Better detection of movement.

## RAPTOR
- Claw attacks.
- Better jumps.
- Faster sprint.
- Strong balance.

## CAT
- Dark vision.
- Quiet movement.
- Improved reflexes.
- Narrow ledge traversal.

## DRAGON
- Natural armour.
- Heat resistance.
- Strength.
- Rare breath-related ability at advanced stages if appropriate.

A human player must still have alternate tools, routes, skills, or equipment.

Transformation gives **different solutions**, not mandatory solutions.

---

# 34. TRANSFORMATION DISADVANTAGES

Possible drawbacks:

- Equipment no longer fits.
- Some NPCs react differently.
- Certain witches charge more or less.
- Some mechanisms detect altered magic.
- Large forms cannot use narrow passages.
- Hands may become worse at delicate tasks.
- Hunger or stamina costs may increase.
- Certain potions affect transformed bodies differently.
- Disguising as an ordinary prisoner becomes difficult.

Avoid making every transformation purely beneficial or purely punitive.

---

# 35. CURING, REVERSING, AND SUPPRESSING

Use three separate concepts.

## SUPPRESSION
Stops progression temporarily.
Does not undo existing changes.

## REVERSAL
Moves the transformation backward by one or more stages.

## CURE
Removes the underlying transformation effect.

A cure may or may not automatically reverse existing physical changes depending on the cure.

Examples:

- Weak Reversal Potion: -1 stage, source remains active.
- Greater Reversal Potion: -2 stages.
- Suppression Potion: no progression for several rooms.
- Specialist ritual: removes active source but does not restore the body immediately.
- Rare Complete Cure: removes the source and restores the player fully.

The journal should record what the player has actually learned about each treatment.

---

# 36. HOSTILE WITCH ENCOUNTERS

Witches should appear as enemies throughout the dungeon, especially in:

- Witch-controlled levels.
- Laboratories.
- Ritual chambers.
- Beast pens.
- Shrines.
- Sealed archives.
- Deep cursed regions.
- Areas controlled by a specific coven.

A hostile witch encounter may begin in several ways:

- Immediate attack.
- Ambush.
- Warning followed by a choice to leave.
- Failed negotiation.
- Player trespassing.
- Player stealing an item.
- Faction hostility.
- The witch guarding a route or ritual.
- The witch hunting another NPC.
- The witch attempting to capture the player.

Witch enemies should have personalities and motives.

Examples:

- A frightened apprentice who attacks because she believes the player is a Warden agent.
- A Thorn enforcer protecting a laboratory.
- A Pale Choir witch actively searching for test subjects.
- An elderly ritualist who only attacks if the player interrupts her work.
- A mercenary witch who can be bribed.
- A healer who becomes hostile if the player previously betrayed her coven.

Witches can also appear in groups or alongside other enemies, but this should be rarer because their abilities are tactically complex.

## TRANSFORMATION MAGIC FROM ENEMY WITCHES

Some witches can use transformation magic as an attack.

This should be relatively uncommon and clearly treated as dangerous magic, but its exact result remains hidden.

Example:

**The witch snaps a bone charm in half. A wave of hot pressure passes through your body.**

Visible immediate result:

**You feel dizzy for a moment.**

The game does NOT display:

**Wolf Transformation +1**

The hidden internal result might instead be:

- No transformation; temporary weakness.
- Partial wolf effect.
- Progressive wolf curse.
- Suppression of an existing effect.
- Acceleration of an existing compatible effect.
- Ordinary magical sickness.

This keeps hostile witches unpredictable without making every witch attack a transformation attack.

## INTERRUPTING SPELLS

Powerful witch spells should often require preparation.

Example:

**The witch begins tracing a red circle in the air.**

The player may choose:

[ ATTACK ]

[ HEAVY ATTACK ]

[ THROW ITEM ]

[ TAKE COVER ]

[ USE ABILITY ]

[ EXAMINE THE SPELL ]

If the player deals enough interruption damage or uses the correct ability, the spell fails.

Fast spells may not be interruptible.

## WITCH RESISTANCES

Witches should not all share identical resistances.

Possible specialties:

- Strong curse resistance.
- Weak physical defence.
- Strong magical ward.
- Weakness to interruption.
- Resistance to poison.
- Vulnerability while casting.
- Dependency on a ritual focus or magical object.

Examine, journal knowledge, and previous encounters should help the player learn these patterns.

## WITCH LOOT

Defeated witches may drop:

- Gold.
- Potion ingredients.
- Unknown potions.
- Amulets.
- Ritual components.
- Identification tools.
- Spell notes.
- Keys.
- Coven tokens.
- Journals.
- Rare cures.
- Dangerous cursed objects.

A powerful witch's loot should be tempting, but it should not automatically be safe.

---

# 37. WITCH BARGAINS

Witch bargains should be one of the game's strongest risk/reward systems.

A bargain has:

- Clear promised benefit.
- Price the player understands.
- Possible hidden consequence only when justified by the witch's honesty/reputation.
- Reputation effect.
- Future callback.

Examples:

**"I will open the sealed door. Bring me the black ledger."**

**"I can stop the changes for a while. You will owe me a favour."**

**"I can make you stronger. I did not say you would remain unchanged."**

If a witch is known to honour literal wording, players can learn to negotiate carefully.

Dialogue should therefore become a mechanical skill, not just flavour.

---

# 38. REPUTATION

Track reputation separately for important factions and major NPCs.

Possible states:

- Hostile.
- Distrustful.
- Neutral.
- Familiar.
- Trusted.
- Indebted.
- Allied.

Reputation can change:

- Prices.
- Information quality.
- Cure availability.
- Dialogue.
- Secret routes.
- Companion events.
- Whether a witch warns the player about an item.
- Whether an NPC lies.

Do not expose exact numeric reputation unless the UI deliberately uses a visible reputation meter.

---

# 39. QUEST DESIGN

Quests should fit the forward-only structure.

Avoid quests that require returning to an inaccessible room.

Use:

## FORWARD QUESTS
"Find the archive somewhere below."

## CONDITIONAL QUESTS
"If you encounter the Thorn Coven, give them this token."

## BRANCH QUESTS
"Take the left route if you want to search for the surgeon."

## CARRY QUESTS
"Bring this sealed vial to any Lantern alchemist."

## INFORMATION QUESTS
"Discover what happened to Cell Block Nine."

A quest can fail naturally when a route is lost.

The journal should mark:

- Active.
- Completed.
- Failed.
- Route lost.
- Outcome unknown.

---

# 40. STORY CLUE SYSTEM

Major mysteries should use clue sets.

Example mystery:

**Who is bringing prisoners into the dungeon?**

Possible clues:

- Intake ledger.
- Survivor testimony.
- Warden transport schedule.
- Witch rumour.
- Recently used rope.
- Surface-made food.
- Guard insignia.
- Broken transport token.

The player does not need every clue.

After enough reliable clues, the journal updates from:

**Unknown**

to:

**Possible explanation**

to:

**Likely**

to:

**Confirmed**

This uses the same information philosophy as transformation discovery.

---

# 41. DOOR CLUES

Door descriptions should provide hints, not labels.

Good:

**Cold air moves under the left door.**

**The centre door is scored by deep scratches.**

**The right-hand frame smells faintly of herbs.**

Bad:

**LEFT — SAFE ROOM**

**CENTRE — HARD MONSTER**

**RIGHT — ALCHEMIST**

Skills and equipment can improve clues.

Examples:

- Survival skill notices footprints.
- Wolf smell detects blood.
- Occult skill recognises a ward.
- Listening tube detects machinery.
- Map fragment suggests a staircase.

Information creates an advantage without guaranteeing certainty.

---

# 42. BOSS DESIGN

Bosses should be tests of learned mechanics, not giant health bars.

Each boss should have:

- Recognisable behaviour.
- Several phases or changing tactics.
- At least one discoverable weakness.
- Environmental interaction.
- More than one viable strategy.
- Reward beyond simple gold.

Example:

A Warden Knight may:

- Block frontal attacks.
- Charge after two guarded turns.
- Expose its back after hitting a pillar.
- Be disabled briefly by an old control rune.
- Be defeated normally without discovering the rune.

A transformation ability may create another option, but never the only option.

---

# 43. LONG-FORM PACING

The game can contain hundreds of rooms, but meaningful events must be spaced deliberately.

Suggested pacing philosophy:

## EARLY GAME
- Learn controls.
- Establish forward-only rule.
- Obtain basic equipment.
- Meet first survivor or find evidence of other people.
- First optional unknown items.
- Transformation risk remains easy to avoid.

## EARLY-MID GAME
- First major region transition.
- First witch encounter.
- First credible escape rumour.
- Better item-identification tools.
- First mini-boss.
- Optional partial transformation opportunities become more common.

## MID GAME
- Several factions active.
- Conflicting maps and escape claims.
- Stronger builds.
- Equipment modification.
- Multiple treatment options.
- Major transformation arcs have room to develop slowly.

## LATE-MID GAME
- Player commits toward one or two plausible escape routes.
- Faction consequences become important.
- Dungeon origin becomes clearer.
- Major bosses and mechanisms appear.

## LATE GAME
- Truth of the Warden Mechanism.
- Final route preparation.
- Major alliance or betrayal consequences.
- Final cure / transformation decisions if relevant.
- Escape attempt.

The game should never reveal the total number of rooms remaining.

---

# 44. ANTI-REPETITION RULES

Because the game is text-heavy and long, repetition is dangerous.

Track recently used:

- Room descriptions.
- Enemy types.
- Door clues.
- Trap types.
- Item descriptions.
- Transformation symptoms.
- Combat narration.
- NPC greetings.
- Loot types.

Do not reuse the same transformation symptom sentence repeatedly.

For example, hearing improvement can be expressed through events:

- Hearing water behind a wall.
- Hearing claws on stone before an enemy appears.
- Hearing a whisper across a chamber.
- Being bothered by a loud metal impact.

Show the change through play instead of repeatedly stating:

**Your hearing is sharper.**

---

# 45. CONSEQUENCE MEMORY

The game should maintain persistent flags.

Examples:

- Saved prisoner Elian.
- Lied to Mirella.
- Stole from Thorn Coven.
- Broke Chain Lift control.
- Learned old Warden symbols.
- Used unknown silver amulet.
- Observed night-time symptoms.
- Refused Pale Choir ritual.
- Lost route to Flooded Archive.

Later events should reference these flags.

This is essential for making the game feel authored rather than randomly generated.

---

# 46. DEATH AND FAILURE

Death should be possible.

Avoid excessive unavoidable instant-death traps.

Dangerous choices should usually have:

- Warning.
- Clue.
- Skill check.
- Resource cost.
- Escape possibility.

An obviously reckless action can still kill the player.

On death, show:

- Final room.
- Cause of death.
- Major discoveries.
- Form at death.
- Escape leads discovered.
- Important choices.

Do not reveal hidden item effects or undiscovered transformation data in the death summary unless a separate optional "run analysis" mode is enabled.

---

# 47. SAVE SYSTEM

Recommended:

- Autosave on entering each room.
- Manual save in safe rooms or through menu depending difficulty.
- Optional Ironman mode.
- Separate run seed.

The run seed determines much of the procedural content but should still allow authored story events.

---

# 48. DIFFICULTY MODES

Difficulty should modify survival pressure, not violate core rules.

## STORY
- Easier combat.
- More healing.
- Better identification reliability.
- Lower equipment wear.

## STANDARD
- Intended balance.

## HARD
- Scarcer resources.
- Stronger enemies.
- More dangerous traps.
- Less reliable cheap identification.
- Higher equipment wear.

## DESCENT / IRONMAN
- Limited saves.
- Harsh survival.
- More dangerous region generation.

Even on the hardest setting:

- The player still starts human.
- Transformation is still not mandatory.
- Random generation must still preserve a viable human path.

---

# 49. REFINED PLAYER DECISION LOOP

The most important gameplay loop is:

**SEE SOMETHING → JUDGE THE RISK → USE INFORMATION → COMMIT → LIVE WITH THE CONSEQUENCE**

Examples:

- Do I drink the unknown potion now or save it?
- Do I trust the witch's identification?
- Do I choose the scratched door or the herbal door?
- Do I spend my last healing potion before the next room?
- Do I keep the powerful amulet after noticing strange symptoms?
- Do I use a reversal potion now or wait for stronger evidence?
- Do I take a dangerous shortcut?
- Do I accept a partial transformation for a strong permanent benefit?
- Do I pursue the Chain Lift or abandon it for the Floodgate?

This should matter more than raw stat grinding.

---

# 50. FINAL DESIGN RULE

The dungeon should feel like a place the player is **surviving, learning, and interpreting**, not merely a sequence of random encounters.

The game engine may know everything.

The player should know only what they have earned through:

- Observation.
- Experience.
- Research.
- Reliable diagnosis.
- Experimentation.
- NPC relationships.
- Environmental clues.

The strongest version of the game is not:

**"The player gets transformed."**

It is:

**"The player enters an enormous uncertain dungeon, makes irreversible choices, learns how the place works, decides which risks are worth taking, and may or may not be transformed as a consequence of those choices."**
