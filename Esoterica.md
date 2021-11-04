# Esoterica

## Infusion Altar
* Powered by Vis obtained from stabilised nodes connected via [Vis Pipes](#vis-pipes).
* All infusions have a stability level, and can have disatrous consequences (Flux everywhere) if the Infusion Altar isn't properly stabilised.
  * Can be stabilised by having the auxiliary items and altar modifiers placed symmetrically around the primary item.
* Structure requires a minimum space of 7x6x7 and a maximum space of 25x12x25.
  * Central Pedestal with the Infusion Matrix 4 blocks above it.
  * 8 surrounding 3 block-tall pillars of Polished Deepslate, with a Copper on top.
    * Pillars directly North/East/South/West of the Central Pedestal are placed 3 blocks out.
    * Pillars diagonal to the Central Pedestal are placed 2 blocks out.
    * The bottom of the pillars act as Vis Pipe inputs. They will redirect Gaseous Vis put into them into the Infusion Matrix. They can only accept 1 pipe at a time.
  * There can technically be as few, or as many, Auxiliary Pedestals as the player wants.
    * However, Pedestals should have rotational symmetry to reduce instability in the Infusion Matrix.
    * Instability can be further reduced using things such as Vis Crystal Clusters and Mob Heads.
    * Instability has 4 stages:
      * Safe
      * Risky
      * Volatile
      * Dangerous
  * The items placed on the Auxiliary Pedestals will be picked up one at a time from their pedestal and will slowly spiral into the Infusion Matrix, before disappearing.
  * The Infusion ends when the Central Pedestal Item is lifted up into the Infusion Matrix and infused with the Gaseous Vis and essence of the auxiliar items. It will then be placed back into the Central Pedestal and the ritual ends.

## Vis
* Made up of five Primal Vis:
  * **Aqua (Water)** - Strong against Ignis and Empyreo. Associated with the South.
  * **Ventus (Wind)** - Strong against Terra and Aqua. Associated with the West.
  * **Ignis (Fire)** - Strong against Empyreo and Ventus. Associated with the North.
  * **Terra (Earth)** - Strong against Aqua and Ignis. Associated with the East.
  * **Empyreo (Otherworld)** - Strong against Ventus and Terra. Associated with the Divine.
<!--- TODO need to make more, easier to understand, charts. Talk to Rebel.
  * <details>
      <summary>Primal Vis Strengths Chart</summary>
  
      [<img src="./imgs/primal_vis_chart.png" alt="Vis Chart" width="512"/>](./imgs/vis%20chart.png)
    </details> --->
* Primal Vis can be combined with their direct neighbors (in the chart) to create five Compound Vis:
  * **Fulgur (Lightning)** - Ignis + Ventus.
  * **Motus (Motion)** - Ventus + Aqua.
  * **Metallum (Metal)** - Empyreo + Terra.
  * **Victus (Life)** - Aqua + Empyreo.
  * **Mortem (Death)** - Terra + Ignis.
<!--- TODO need to make more, easier to understand, charts. Talk to Rebel.
  * <details>
      <summary>Compound Vis Generation Chart</summary>
  
      [<img src="./imgs/compound_vis_chart.png" alt="Vis Chart" width="512"/>](./imgs/vis%20chart.png)
    </details> --->
* Primal Vis can be combined with their compliments (strengths/weaknesses) to create five Complimentary Vis:
  * **Animus (Soul)** - Ventus + Empyreo.
  * **Volatus (Flight)** - Aqua + Ignis.
  * **Vacuous (Void)** - Ventus + Terra.
  * **Lux (Light)** - Ignis + Empyreo.
  * **Arbor (Wood)** - Terra + Aqua.
<!--- TODO need to make more, easier to understand, charts. Talk to Rebel.
  * <details>
      <summary>Complimentary Vis Generation Chart</summary>
  
      [<img src="./imgs/complimentary_vis_chart.png" alt="Vis Chart" width="512"/>](./imgs/vis%20chart.png)
    </details> --->
* Compound Vis cannot be used in Spell Casting, and have no known strengths/weaknesses as a result.
* Comes in two forms:
  * **Ethereal Vis** - requires a focusing element to be transferred from a node. Wands act as focusing elements into themselves, and Amethyst can focus Ethereal Vis to move it around.
  * **Gaseous Vis** - can only be transferred via pipe, and is considered acidic. Is used in the **Infusion Altar** and **Homunculus Incubator**. Might be able to be mixed into new forms to take the place of Essentia.

## Nodes
* Nodes store Vis in its Ethereal form, and are the only way to generate Vis. They cap at 128 total Vis.
* Nodes will "bully" other nearby Nodes, stealing their Vis aspects.
  * Typically the Node with more Vis will win, but if a Node's main aspect is strong against the aspects of the other Node, it may win out.
  * Most interactions steal 1-2 aspect from whichever aspect was randomly targetted, but if the main aspect of a Node is strong to the targetted aspect, it will steal 2-4 of that aspect instead.
* Nodes are defined by their primary aspect (i.e. if a Node has more Ignis than any other aspect, it is an Ignis Node).
* Most Nodes are non-dangerous to their surroundings.
  * Warped Nodes are the exception, as they will drag in everything in their immediate vicinity, as well as tear up their surroundings. They are the most sought after due to their danger, and their unique uses as a result of their strange functions.
  * Warped Nodes have to be created, and require intentional creation of high-concentrations of Warp.
* Nodes can be fabricated, and allowing players to control the aspects their Nodes have.

## Vis Pipes
* Vis Pipes can have up to 32 PSI before getting overpressurised
  * Pressure can be raised by adding Gaseous Vis to the system, or by adding pumps to the system
  * Overpressurised Vis Pipes will explode after a given amount of time, releasing all of their Gaseous Vis into the environment
* Vis Pipes can form leaks if not properly sealed, causing them to slowly leak out their Gaseous Vis into the environment
* If two Primal Vis that can form a Compound Vis or Complimentary Vis are in the same pipe, they will mix together
  * If a Compound Vis and Complimentary Vis share the same pipe, that pipe will explode, releasing Warp into the environment
* Pipes update their contents ever 5 ticks, and will attempt to equalise across their length
* Gaseous Vis will not flow upwards in pipes without a pump attached, or if the upward flow is shorter than previous downward flow

## Research
* There are two types of research:
  * **Field Studies** - the simplest of the forms of research, Field Studies require the player to go out into the world and study certain objects utilising the Thaumometer.
  * **Sigil Puzzles** - the player is given a random set number of lines depending on the complexity level of the research being done (Novice - 10, Apprentice - 15, Journeyman - 20, Expert - 25, and Master - 30), and a 7x7 dot-grid, as well as a point placed randomly on the grid.
    * The point is where the Sigil must start and end.
    * The Sigil must be a closed shape and make use of all the lines.
    * The smaller the area of the Sigil, the less exp the research will cost to finish.
    * Exp is determined by the complexity of the research and the area of the sigil.

## Wands
* Consists of two parts:
  * **Cores** - Affects the Vis capacity of a wand.
  * **Caps** - Affects the Vis affinity of a wand.
* Vis Affinity affects how much of a specific Vis element a spell will cost (i.e. an Ignis affinity will reduce the Ignis cost of spells).
* Some Wand Cores and Wand Caps can have special attributes tied to them but no other.

## Spells
* There are two Spell Components:
  * **Spell Shapes** - Control the method in which the Spell Effect is delivered (i.e. Touch, Projectile, AOE, etc).
    * <details>
      <summary>Spell Shape Components</summary>
  
      * Beam Shape
      * Projectile Shape
      * Touch Shape
      * Trap Shape
      * Explosion Shape
      * Cloud Shape
      * Lob Shape
      * Self Shape
    </details>
  * **Spell Effects** - What the Spell does upon the activation criteria defined in the Spell Shape (i.e. Damage, Teleport, Heal, etc).
    * <details>
      <summary>Spell Effect Components</summary>
  
      * Mine Effect
      * Heal Effect
      * Shield Effect
      * Teleport Effect
      * Jammer Effect
      * Pulling Effect
      * Pushing Effect
      * Fire Effect
      * Ice Effect
      * Fertiliser Effect
      * Warding Effect
    </details>
* A Spell can have up to 4 Spell Components applied to them at once in the following order:
  * Spells must begin with a Spell Shape and end with a Spell Effect.
  * Spell Shapes have to be followed by a Spell Effect.
  * Spell Effects have to be followed by either a Spell Shape or a Spell Effect.
* If a Spell Shape is the second in a Spell, it will be cast based on the first Spell Shape (i.e. an AOE->Projectile would fire multiple projectiles in a circle).
* Spells by default are fairly weak, but can be upgraded in a Focal Manipulator.
  * Upgrades take place in 4 tiers.
  * The player can select an upgrade for an individual component.
  * Each component can have 1-3 upgrades per tier.
  * Once an upgrade from Tier N is taken, all other upgrades in that tier are locked.
  * <details>
      <summary>Spell Upgrades</summary>
  
      * Potency Upgrade (All Effect Components)
      * Duration Upgrade (Trap, Cloud, Shield, and Jammer Components)
      * Size Upgrade (Trap, Explosion, and Cloud Components)
      * Frugal Upgrade (All Components)
      * Range Upgrade (Beam and Touch Components)
      * Bouncy Upgrade (Lob Component)
      * Split Upgrade (Beam and Projectile Components)
      * Homing Upgrade (Projectile Component)
      * Cure Upgrade (Heal Component)
    </details>

## Thaumaturgical Flux & Warp
* **Thaumaturgical Flux** is the byproduct of wayward magic. It is basic, and will neutralise Gaseous Vis. If left uncleaned, it will inevitably begin to warp its surroundings. It can be stored within magical wards.
* **Warp** is a malevolent form of magic, often caused by Thaumaturgical Flux. It is called such due to how it warps living beings it touches, inevitably draining and killing them, leaving nothing more than a husk animated by malevolent energy.
  * Spreads from its epicenter, and can only be contained by either magical wards or a specific magical plant.
  * Will affect all instances of LivingEntity.
  * Is required for, and can be gained by, some forbidden research.

## Warped Abominations
*

## Schools of Magic
* There are five Schools of Magic (+the fundamentals), each having its own section within the Grimoire, the research/guide book for Esoterica.
  * **Fundamentals:**
    * Contains the starting research for the player to get into the mod.
  * **Thaumaturgy:**
    * Contains research pertaining to castable magic, as well as magical processes and machines used in other schools of magic.
  * **Alchemy:**
    * Contains research, particularly pertaining to Gaseous Vis and its uses.
  * **Artifice:**
    * Contains research on how to augment physical mechanical objects with magic to make them more useful.
  * **Homunculi:**
    * Contains research on how to make and use Homunculi. Go to the [Homunculi Section](#homunculi) for more info.
  * **Apocrypha:**
    * Contains research on magic long forgotten to history, all of it highly forbidden and dangerous if you should delve deeper into it.

## Homunculi
* Homunculi are soulless, artificial humanoids. They will not, on their own, do anything aside from mill about and take up space, but with the right magical influence, can be put to use.
* There are two ways to make a homunculus be useful:
  * Use magical tags to force them to complete menial, simple tasks. These can range from pressing a button to reading a gauge and flipping colour-coded valves.
  * Give it a soul. This is a forbidden art, as it requires a soul from a living humanoid. Even so, they are not that smart, and can only do moderately more complex tasks depending on the soul given to them, such as farming, tending to animals, and bringing jars of Gaseous Vis.
* You can also transfer your soul into a homunculus, allowing your old body to die. This also handily deals with temporary warp, but is a far more forbidden practice.
* Because homunculi are artificial, you can give them certain physical attributes that you may desire them, or yourself, to have.

## The Cult of Truth
* Cultists will spawn in your world while actively engaging in some mysterious ritual. They are neutral to the player.
* There will be an Arch-Cultist that the player can speak to. They will offer the player two options: join them, or leave.
* If the player chooses to leave, they can still join later. However, the player can also kill the Arch-Cultist, who won't die until the other Cultists are dead, and receive their book of Ancient Rites, which will unlock initial section of the Apocrypha tab.
* If the player chooses to join them, they will given a number of small quests to prove their loyalty to the cult and their deity, The Truth.
  * The player will have to complete <N> quests, ranging from bringing the Cultists a jar of one of the fifteen Gaseous Vis to bringing them a magical artifact.
  * If the player does prove their loyalty, the Cultists will begin a ritual, bathing the player in the blood of a Villager child and helping the player see [The Truth](#the-truth-boss) in a vision, which will unlock a good portion of the Apocrypha tab automatically, but not quite to the point where the player knows how to break The Truth's bindings. The player still has to do some research to help their further the Cult of Truth's goals.
  * If, on June 1st, starting at 00:00 UTC and ending at 23:59 UTC, the player participates in the ritual, the Arch-Cultist's dialogue will change to just one line: "This will be the second worst thing to ever happen to this orphan." before killing the Villager Child.
* If the player is a part of the Cult of Truth and has been assimilated, they will not have to fight The Truth when they release its chains. Instead, they will be rewarded by The Truth and will be given a portion of its power if the player offers it an Amethyst Shard, allowing the player to continue the progression of the Apocrypha tab.

## Pocket Dimensions & Planar Vortecies
* Planar Vortecies can be created by stabilising a Warped Node and blasting it with large amounts of Gaseous Vis.
* Planar Vortecies are highly unstable and will collapse into large amounts of Flux if not kept stable.
* Planar Vortecies can only be stabilised by constantly feeding them the same Vis that made up the Nodes they were born from.
* If stabilised, a Planar Vortex can be entered, and contains a Pocket Dimension.
  * A Pocket Dimension's generation is dependant on the amount and type of Vis aspects contained by the Warped Node.
  * If the Planar Vortex that grants access to the Pocket Dimension is destroyed or collapses, the Pocket Dimension will cease to exist, along with everything it contained.

## The Truth (Boss)
* The player has to beat the Warden to obtain a key to a locked door somewhere in the Warden's area. On the other side of this is a 25x12x25 room.
* Within this room will be a pedestal with an Amethyst Shard in it, surrounded by 5 pillars, each about 7 blocks away from the pedestal.
  * When the player opens the door and walks inside, the door will shut behind them with a thud. The pedestal will begin to glow and a white orb will slowly rise from it, with beams of all 5 Ethereal Primal Vis connecting it to the pillars. The pillars will then begin to shut off, one by one.
  * A moment later, the orb will begin to expand rapidly, causing the room to be bathed in bright light. From there, The Truth will spawn, and if the player did not side with the Cult of Truth, a Planar Vortex will open behind The Truth that it will receed into.
    * The player will have no choice but to follow into the [Planar Vortex](#pocket-dimensions--planar-vortecies), as the door is shut and the player is unable to use items or break blocks.
    * On the other side, The Truth will greet the player, floating above a replica of what was on the other side, before telling them that they have made a mistake releasing it from its prison, as it will result in the destruction of the player's world, however it will grant the player a quick death as thanks for freeing it.
    * The fight will then begin, and The Truth will begin with regular damaging spells, with only the shape differing. The Truth will not move during the fight, remaining above the pedestal. Occasionally, The Truth will attack with a specialised beam attack that resembles the beams of Ethereal Primal Vis that held it trapped in the Overworld. If the player causes The Truth to hit one of the pillars, that pillar will become active, and will lock The Truth from using that Primal Vis in future attacks. This will repeat for all 5 Primal Vis.
    * Once the player has activated all 5 pillars, The Truth will grow aggrivated and open up more Planar Vortecies. From these will emerge [Cultists of Truth](#the-cult-of-truth), along with [Warped Abominations](#warped-abominations). The player has to fight through these and defeat all of the Arch-Cultists that The Truth brought to this plane of existence.
    * Once all of the Arch-Cultists are dead, the Planar Vortecies will collapse, and the binding ritual will begin. The Truth will be slowly lowered into the Amethyst Shard in the pedestal, trapping it once more, and the player can take this new item.
