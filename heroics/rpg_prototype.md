\# Astral Archive RPG Mechanics



> Converted and cleaned from the provided PDF text. Repeated extraction artifacts and corrupt numeric tables have been removed. Where the source table was unreadable, a placeholder note is included.



\---



\## Section 1: Core Mechanics



\### 1. The Core Stats



Every character is built on six core stats:



1\. \*\*Strength\*\* — Physical power; cornerstone of physical damage. Interacts with Stamina to determine physical attack effectiveness against defense.

2\. \*\*Stamina\*\* — Endurance against physical attacks; reduces incoming physical damage.

3\. \*\*Intelligence\*\* — Magical prowess; dictates spell potency and magical damage.

4\. \*\*Spirit\*\* — Resistance against magical attacks; reduces incoming spell damage.

5\. \*\*Dexterity\*\* — Accuracy and critical hit chance for physical and ranged attacks.

6\. \*\*Agility\*\* — Evasion and parry ability; improves dodge chance and counterattack opportunities.



\### 2. Derived Attributes



| Attribute | Formula | Notes |

|---|---|---|

| \*\*HP\*\* | Strength + Stamina | Health Points |

| \*\*MP\*\* | Intelligence + Spirit | Magic Points; used for spells and magical abilities |

| \*\*Speed\*\* | Dexterity + Agility | Determines combat turn order |



\*\*Speed Tally System:\*\* Each character’s speed tally increases by their Speed stat every combat tick. The first character to reach a tally of 100 acts, creating a dynamic turn order.



\### 3. Primary, Secondary, and Tertiary Stats



| Character Type | Primary | Secondary (×2) | Tertiary (×3) |

|---|---:|---:|---:|

| \*\*Players\*\* | 5 points | 4 points each | 3 points each |

| \*\*Beasts\*\* | 4 points | 3 points each | 2 points each |

| \*\*Bosses\*\* | 10 points | 8 points each | 6 points each |



Players choose these during character creation; they remain fixed throughout the game.



\#### Scaling for Beasts and Bosses



Beasts and bosses grow dynamically by level using a 30% stat-growth-per-level system:



\- \*\*Primary:\*\* +8% per level

\- \*\*Secondary (×2):\*\* +5% each per level

\- \*\*Tertiary (×3):\*\* +4% each per level



\### 4. Stat Interactions in Combat



\#### Attacking Factors



1\. \*\*Type of Attack:\*\* Physical, magical, or hybrid.

2\. \*\*Relevant Stats:\*\*

&#x20;  - Physical attacks use \*\*Strength\*\*.

&#x20;  - Magical attacks use \*\*Intelligence\*\*.

3\. \*\*Chance to Hit:\*\*

&#x20;  - `Chance to Hit = (Attacker's Dexterity / (Attacker's Dexterity + Defender's Agility)) × 100`

4\. \*\*Chance to Crit:\*\*

&#x20;  - `Chance to Crit = (Dexterity / Modifier)`

&#x20;  - Successful critical hits deal double damage.

5\. \*\*Elemental Enhancement:\*\* Adds percentage bonuses to attack power based on elemental attributes.



\#### Defending Factors



1\. \*\*Relevant Stats:\*\*

&#x20;  - Physical defense uses \*\*Stamina\*\*.

&#x20;  - Magical defense uses \*\*Spirit\*\*.

2\. \*\*Chance to Dodge:\*\*

&#x20;  - `Chance to Dodge = (Defender's Agility / (Defender's Agility + Attacker's Dexterity)) × 100`

3\. \*\*Chance to Parry:\*\*

&#x20;  - `Chance to Parry = (Defender's Agility / Modifier)`

&#x20;  - \*\*Parry Damage:\*\* `Strength × 0.5`

&#x20;  - Successful parries negate damage and counterattack with reduced strength.

4\. \*\*Elemental Resistance and Weakness:\*\* Modifies incoming elemental damage based on defender attributes.



\#### Damage Formulas



\- \*\*Physical Damage:\*\*

&#x20; - `Final Damage = Base Weapon Damage × (1 + (Attacker's Strength / 100)) / (1 + (Defender's Stamina / 100))`

\- \*\*Magical Damage:\*\*

&#x20; - `Final Damage = Base Spell Damage × (1 + (Attacker's Intelligence / 100)) / (1 + (Defender's Spirit / 100))`



\### 5. Elemental System



\#### Elemental Wheel



1\. \*\*Fire\*\* beats \*\*Earth\*\*

2\. \*\*Earth\*\* beats \*\*Air\*\*

3\. \*\*Air\*\* beats \*\*Water\*\*

4\. \*\*Water\*\* beats \*\*Fire\*\*



\#### Modifiers



\- \*\*Strong Against:\*\* Doubles damage (×2)

\- \*\*Weak Against:\*\* Halves damage (×0.5)

\- \*\*Multi-Elemental Attacks:\*\* Calculate resistances and weaknesses for each element separately, then combine results for total damage.



\### 6. Leveling System



\#### XP Requirements



\- Level 1 → 2: \*\*6 XP\*\*

\- Each subsequent level requires \*\*6 additional XP\*\*

&#x20; - Example: Level 2 → 3 requires 12 XP.



\#### XP Gains



\- \*\*Beasts:\*\* Always award 1 XP per defeat.

\- \*\*Bosses:\*\* Award significantly more XP, e.g., 12 XP.



\### 7. Boost System



\#### Permanent Boosts



Applied during level-ups and based on choices and equipment.



| Source | Permanent Boost |

|---|---:|

| Primary Job Class | +3% |

| Secondary Job Class | +1% |

| Elemental Pairing | +2% |

| Weapon | +2% |

| Instrument | +2% |

| Headgear | +1% |

| Body Gear | +1% |



\#### Temporary Boosts



Active as long as the associated item or pairing is equipped.



\- Effect: \*\*Triples the permanent boost\*\*

\- Total Temporary Boost: \*\*36%\*\*, recalculated dynamically when equipment changes.



\### 8. Row Mechanics



| Row | Physical Damage Taken | Magical Damage Taken | Weapon Damage |

|---|---|---|---|

| \*\*Front Row\*\* | Full | Half | Full damage with melee weapons |

| \*\*Back Row\*\* | Half | Full | Full damage with ranged weapons |



\---



\## Section 2: Jobs



\### Overview of the Job Class Hexad



The Job Class Hexad forms the backbone of character specialization. Each of the six classes ties directly to a core stat, defining combat roles, equipment options, and skill trees.



\### 1. Job Class Profiles



\#### 1. Solist (Fighter)



\- \*\*Core Stat:\*\* Strength

\- \*\*Role:\*\* Physical damage dealer, excelling in raw power and melee combat.

\- \*\*Weapons:\*\* Melee and Ranged

\- \*\*Armor:\*\* Light, Medium, Heavy

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Strength, +3% permanent Strength per level

&#x20; - Secondary Class: +3% temporary Strength, +1% permanent Strength per level

\- \*\*Combat Focus:\*\* Dominates the frontlines with devastating physical attacks and versatile equipment.



\#### 2. Prophet (Tank)



\- \*\*Core Stat:\*\* Stamina

\- \*\*Role:\*\* Defensive specialist focused on absorbing damage and maintaining aggro.

\- \*\*Weapons:\*\* Melee and Ranged

\- \*\*Armor:\*\* Light, Medium, Heavy

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Stamina, +3% permanent Stamina per level

&#x20; - Secondary Class: +3% temporary Stamina, +1% permanent Stamina per level

\- \*\*Combat Focus:\*\* Acts as the team’s shield, protecting allies and withstanding prolonged battles.



\#### 3. Sacred Scribe (Mage)



\- \*\*Core Stat:\*\* Intelligence

\- \*\*Role:\*\* Magic damage dealer leveraging powerful spells and elemental attacks.

\- \*\*Weapons:\*\* Magic and Melee

\- \*\*Armor:\*\* Light

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Intelligence, +3% permanent Intelligence per level

&#x20; - Secondary Class: +3% temporary Intelligence, +1% permanent Intelligence per level

\- \*\*Combat Focus:\*\* Brings unparalleled magical firepower and exploits enemy weaknesses.



\#### 4. Shrinebearer (Healer)



\- \*\*Core Stat:\*\* Spirit

\- \*\*Role:\*\* Dedicated healer, restoring HP and removing negative effects.

\- \*\*Weapons:\*\* Ranged and Magic

\- \*\*Armor:\*\* Light and Medium

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Spirit, +3% permanent Spirit per level

&#x20; - Secondary Class: +3% temporary Spirit, +1% permanent Spirit per level

\- \*\*Combat Focus:\*\* Ensures party survival through powerful healing and support.



\#### 5. Astrologer (Rogue)



\- \*\*Core Stat:\*\* Dexterity

\- \*\*Role:\*\* Debuffer specializing in status ailments and weakening enemies.

\- \*\*Weapons:\*\* Magic and Melee

\- \*\*Armor:\*\* Light and Medium

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Dexterity, +3% permanent Dexterity per level

&#x20; - Secondary Class: +3% temporary Dexterity, +1% permanent Dexterity per level

\- \*\*Combat Focus:\*\* Cunning disruptor using Dexterity for precise strikes and debilitating effects.



\#### 6. Singer (Bard)



\- \*\*Core Stat:\*\* Agility

\- \*\*Role:\*\* Support specialist focused on buffs and positive effects.

\- \*\*Weapons:\*\* Ranged and Magic

\- \*\*Armor:\*\* Light

\- \*\*Stat Boosts:\*\*

&#x20; - Primary Class: +9% temporary Agility, +3% permanent Agility per level

&#x20; - Secondary Class: +3% temporary Agility, +1% permanent Agility per level

\- \*\*Combat Focus:\*\* Enhances allies with powerful buffs and support.



\### 2. Equipment Rules



\#### Weapons



Each class’s primary job determines weapon proficiencies:



| Job Class | Weapon Proficiencies |

|---|---|

| Solist \& Prophet | Melee and Ranged |

| Sacred Scribe \& Astrologer | Magic and Melee |

| Shrinebearer \& Singer | Ranged and Magic |



\#### Armor



| Job Class | Armor Access |

|---|---|

| Solist \& Prophet | Light, Medium, Heavy |

| Shrinebearer \& Astrologer | Light and Medium |

| Sacred Scribe \& Singer | Light only |



\### 3. Skill System



\- \*\*Skill Points:\*\* Earned at 1 Skill Point per defeated beast or equivalent enemy.

\- \*\*Boss Rewards:\*\* Bosses award significantly more Skill Points, e.g., 12.

\- \*\*Skill Trees:\*\* Each job class has a skill tree containing 10 skills tied to tiers.

\- \*\*Unlocking:\*\* Players may unlock skills in any order if they meet level and Skill Point requirements.



> \*\*Note:\*\* The source table for “Skill Tier Costs and Level Requirements” was corrupted during extraction and could not be recovered reliably.



\---



\## Section 3: Elemental Powers Hexad



\### 1. Overview



The Elemental Powers Hexad integrates Fire, Air, Water, and Earth into spells, stats, and summons. Players equip two elements at a time, creating unique combinations that shape combat style and unlock constellation-themed summons.



\### 2. The Four Elements



| Element | Properties | Focus |

|---|---|---|

| \*\*Fire\*\* | Dry (Debuff), Hot (Damage) | Offensive magic: damage and weakening enemies |

| \*\*Air\*\* | Hot (Damage), Wet (Buff) | Hybrid magic: damage while enhancing allies |

| \*\*Water\*\* | Wet (Buff), Cold (Heal) | Defensive/restorative magic: healing and support |

| \*\*Earth\*\* | Cold (Heal), Dry (Debuff) | Resilient magic: healing combined with enemy debuffs |



\### 3. Elemental Combinations



| Combination | Stat Boost | Focus |

|---|---|---|

| Fire + Air | Strength | Physical power with damage and debuffs |

| Air + Water | Intelligence | Magical precision, buffs, and healing |

| Water + Earth | Spirit | Magical defense and restorative abilities |

| Earth + Fire | Stamina | Physical defense and endurance |

| Air + Earth | Agility | Mobility, evasion, and resilience |

| Fire + Water | Dexterity | Accuracy and critical hit potential |



\### 4. Stat Boosts



\- \*\*Temporary:\*\* +6% to the associated stat while the elemental combination is equipped.

\- \*\*Permanent:\*\* +2% to the associated stat upon leveling up.



\### 5. Spell System



\#### Spell Points



\- Earned at 1 per defeated enemy (beasts/monsters).

\- Bosses award significantly more Spell Points, e.g., 12.



\#### Spell Tree Structure



Each element has a 10-tier spell tree that must be unlocked sequentially.



| Tier | Spell Point Cost | Level Requirement |

|---:|---:|---:|

| 1 | None | 1 |

| 2 | 12 | 3 |

| 3 | 24 | 7 |

| 4 | 36 | 13 |

| 5 | 48 | 21 |

| 6 | 60 | 31 |

| 7 | 72 | 43 |

| 8 | 84 | 57 |

| 9 | 96 | 73 |

| 10 | 108 | 91 |



\### 6. Summon System



\#### Unlocking Summons



\- \*\*First Summon:\*\* Unlocked when a player reaches Tier 5 in both equipped elements. Tied to the elemental pairing.

\- \*\*Additional Summons:\*\* Each additional two tiers unlocked for both elements grants another summon:

&#x20; - Tier 6: Two summons

&#x20; - Tier 7: Three summons

&#x20; - Tier 8: Four summons

&#x20; - Tier 9: Five summons

&#x20; - Tier 10: Six summons

\- \*\*Total Summons:\*\* 36 unique summons tied to 36 Constellations.



\#### Summon Behavior



\- \*\*One Summon Active at a Time:\*\* A new summon replaces the previous one.

\- \*\*One Summon Per Player Per Battle:\*\* Up to six summons can be used sequentially by a full party.

\- \*\*Duration:\*\* Summons persist for three turns before vanishing.

\- \*\*Autonomous Actions:\*\* Summons act independently, randomly selecting from a predefined action subset each turn.



\#### Summon Abilities



Each summon has 3–5 unique abilities tied to its elemental pairing and tier level.



Examples:



\- \*\*Offense:\*\* AoE or single-target damage

\- \*\*Support:\*\* Buffs or healing for allies

\- \*\*Debuff:\*\* Weakening enemies with status effects



\### 7. Party-Wide Elemental Dynamics



\- \*\*Coordination:\*\* Players must strategize when and how to summon, maximizing efficiency and avoiding overlap.

\- \*\*Synergy:\*\* Summons can chain effects, such as debuffs from one summon enhancing damage from another.



\### 8. Elemental Interactions



\- \*\*In Combat:\*\* Elemental properties influence spell and summon effects.

\- \*\*Between Players:\*\* Complementary elements enhance team dynamics through shared buffs, debuffs, and synergy.



\### 9. Summary



The Elemental Powers Hexad links elements, stats, spells, and summons. Constellation-themed summons tie the system to the grand narrative and add power and spectacle to battles.



\---



\## Section 4: Deities



\### 1. Overview



The Deity Hexad introduces divine influence. Every combatant aligns with one of six deities, gaining elemental resistances, weaknesses, and access to Blessings and Curses.



\### 2. The Six Deities and Their Roles



\#### 1. Bendix (Dark)



\- \*\*Resistance:\*\* +25% to Earth and Water

\- \*\*Weakness:\*\* +25% to Fire and Air

\- \*\*Blessings:\*\* Defensive actions such as shields or Spirit buffs.

\- \*\*Curses:\*\* AoE debuffs reducing Strength, Dexterity, or healing effectiveness.



\#### 2. Kadmilos (Light)



\- \*\*Resistance:\*\* +25% to Fire and Air

\- \*\*Weakness:\*\* +25% to Water and Earth

\- \*\*Blessings:\*\* AoE healing, cleansing debuffs, boosting Agility or Strength.

\- \*\*Curses:\*\* Precision strikes and accuracy debuffs.



\#### 3. Dardanos (Fire)



\- \*\*Resistance:\*\* +50% to Fire

\- \*\*Weakness:\*\* +50% to Water

\- \*\*Blessings:\*\* Temporary Strength and Dexterity boosts with minor healing.

\- \*\*Curses:\*\* High single-target fire damage or AoE burn effects.



\#### 4. Iasion (Air)



\- \*\*Resistance:\*\* +50% to Air

\- \*\*Weakness:\*\* +50% to Earth

\- \*\*Blessings:\*\* Healing over time with large Agility boosts.

\- \*\*Curses:\*\* Speed-based attacks that reduce enemy evasion.



\#### 5. Kotys (Earth)



\- \*\*Resistance:\*\* +50% to Earth

\- \*\*Weakness:\*\* +50% to Air

\- \*\*Blessings:\*\* Shields scaling with Stamina and healing over time.

\- \*\*Curses:\*\* Ground-based attacks that reduce enemy Stamina or immobilize them.



\#### 6. Zerynthria (Water)



\- \*\*Resistance:\*\* +50% to Water

\- \*\*Weakness:\*\* +50% to Fire

\- \*\*Blessings:\*\* Large AoE healing and buffs to Spirit or Intelligence.

\- \*\*Curses:\*\* AoE debuffs targeting Intelligence or Spirit.



\### 3. Elemental Resistance and Weakness System



\- Each deity grants resistance to associated element(s).

\- \*\*Fire, Air, Water, Earth Deities:\*\* +50% resistance to their element, +50% weakness to the opposing element.

\- \*\*Dark and Light Deities:\*\* +25% resistance to two elements, +25% weakness to the remaining two.



\### 4. Divine Interventions: Blessings and Curses



\#### Trigger Mechanism



\- \*\*Chance to Trigger:\*\* Each combatant has a 3% chance per action to summon their deity for an intervention.

\- \*\*Intervention Type:\*\*

&#x20; - \*\*Blessing:\*\* Defensive action; buffs, healing, or both for the summoner’s party/band.

&#x20; - \*\*Curse:\*\* Offensive action; damage, debuffs, or both targeting the opposing side.



\#### Intervention Scaling



\- \*\*Blessings:\*\* Scale with defensive stats (Stamina, Spirit, Agility).

\- \*\*Curses:\*\* Scale with offensive stats (Strength, Intelligence, Dexterity).



\### 5. Examples of Blessings and Curses



\#### Blessing Examples



1\. \*\*Bendix (Dark):\*\* Party-wide shield that absorbs damage and increases Spirit.

2\. \*\*Kadmilos (Light):\*\* AoE healing with cleanse and Agility boost.

3\. \*\*Dardanos (Fire):\*\* Strength and Dexterity buff with minor healing.

4\. \*\*Iasion (Air):\*\* Healing over time with large Agility boost.

5\. \*\*Kotys (Earth):\*\* AoE shield reducing incoming physical damage for three turns.

6\. \*\*Zerynthria (Water):\*\* Large AoE heal with Spirit boost.



\#### Curse Examples



1\. \*\*Bendix (Dark):\*\* AoE debuff reducing Strength and Dexterity for three turns.

2\. \*\*Kadmilos (Light):\*\* Single-target precision attack with defense debuff.

3\. \*\*Dardanos (Fire):\*\* AoE fire attack with burn status to all enemies.

4\. \*\*Iasion (Air):\*\* AoE damage reducing enemy evasion.

5\. \*\*Kotys (Earth):\*\* Ground-based attack reducing enemy Stamina and immobilizing them.

6\. \*\*Zerynthria (Water):\*\* AoE debuff reducing Intelligence and Spirit.



\### 6. Party-Wide Dynamics



\- \*\*Coordination:\*\* Parties must factor in potential divine interventions.

\- \*\*Randomized Tension:\*\* The 3% trigger chance adds unpredictability.

\- \*\*Synergy:\*\* Blessings and curses may synergize with skills, spells, or elemental powers.



\### 7. Enemy Dynamics



\- \*\*Beasts and Bosses:\*\* All enemies align with a deity, gaining resistances and weaknesses. They can trigger blessings and curses, scaled appropriately.

\- \*\*Balancing:\*\* Enemy interventions are balanced by lower stats relative to bosses and players.



\### 8. Strategic Implications



\- \*\*Player Builds:\*\* Players can design builds to maximize blessing or curse effectiveness.

\- \*\*Risk vs. Reward:\*\* Certain deities introduce vulnerabilities but grant powerful benefits.

\- \*\*Dynamic Combat:\*\* Deity interventions create unexpected reversals.



\### 9. Summary



The Deity Hexad adds divine influence that scales with the summoning combatant’s stats. Blessings and curses enrich strategy and unpredictability, tying the elemental framework to a grand narrative.



\---



\## Section 5: Weapons



\### Overview of the Weapon Hexad



The Weapon Hexad defines tools used to attack, defend, and strategize. It has six categories, each split into two types and four subtypes, tied to stats, job classes, and elemental affinities.



\### 1. Weapon Mechanics



\#### Stat Associations



| Weapon Type | Stat Used |

|---|---|

| Offensive Melee | Strength |

| Defensive Melee | Stamina |

| Offensive Ranged | Dexterity |

| Defensive Ranged | Agility |

| Offensive Magic | Intelligence (counts as a physical attack) |

| Defensive Magic | Spirit |



\#### Damage Types



Each weapon type is split into \*\*Fixed Damage\*\* and \*\*Variable Damage\*\*, each with two subtypes:



\- High Accuracy, Low Damage

\- Low Accuracy, High Damage



\#### Weapon Switching



\- Players can switch weapons by reassigning all associated ability points.

\- Cost scales with the number of abilities tied to the weapon.



\### 2. Weapon Types and Subtypes



\#### A. Offensive Melee (Strength)



\- \*\*Fixed Damage: Blades\*\*

&#x20; - One-Handed Sword: High Accuracy, Low Damage

&#x20; - Two-Handed Sword: Low Accuracy, High Damage

\- \*\*Variable Damage: Axes\*\*

&#x20; - One-Handed Axe: High Accuracy, Low Damage

&#x20; - Two-Handed Axe: Low Accuracy, High Damage



\#### B. Defensive Melee (Stamina)



\- \*\*Fixed Damage: Clubs\*\*

&#x20; - Mace: High Accuracy, Low Damage

&#x20; - Flail: Low Accuracy, High Damage

\- \*\*Variable Damage: Bracers\*\*

&#x20; - Bracers: High Accuracy, Low Damage

&#x20; - Daggers: Low Accuracy, High Damage (dual-wielded by default)



\#### C. Offensive Ranged (Dexterity)



\- \*\*Fixed Damage: Polearms\*\*

&#x20; - Spear: High Accuracy, Low Damage

&#x20; - Halberd: Low Accuracy, High Damage

\- \*\*Variable Damage: Staves\*\*

&#x20; - Quarterstaff (Wizard Staff): High Accuracy, Low Damage

&#x20; - Martial Staff: Low Accuracy, High Damage



\#### D. Defensive Ranged (Agility)



\- \*\*Fixed Damage: Arrows\*\*

&#x20; - Bow: High Accuracy, Low Damage

&#x20; - Crossbow: Low Accuracy, High Damage

\- \*\*Variable Damage: Missiles\*\*

&#x20; - Sling: High Accuracy, Low Damage

&#x20; - Thrown (e.g., Chakrams, Throwing Knives): Low Accuracy, High Damage



\#### E. Offensive Magic (Intelligence)



\- \*\*Fixed Damage: Rods\*\*

&#x20; - Wands: High Accuracy, Low Damage

&#x20; - Scepters: Low Accuracy, High Damage

\- \*\*Variable Damage: Books\*\*

&#x20; - Tomes: High Accuracy, Low Damage

&#x20; - Scrolls: Low Accuracy, High Damage



\#### F. Defensive Magic (Spirit)



\- \*\*Fixed Damage: Lots\*\*

&#x20; - Runes: High Accuracy, Low Damage

&#x20; - Cards: Low Accuracy, High Damage

\- \*\*Variable Damage: Talismans\*\*

&#x20; - Charms: High Accuracy, Low Damage

&#x20; - Pendants: Low Accuracy, High Damage



\### 3. Job Class Weapon Access



| Job Class | Weapon Categories |

|---|---|

| Solists (Fighter) \& Prophets (Tank) | Melee and Ranged |

| Singers (Bard) \& Shrinebearers (Healer) | Ranged and Magic |

| Sacred Scribes (Mage) \& Astrologers (Rogue) | Magic and Melee |



\### 4. Strategic Implications



\- \*\*Player Builds:\*\* Weapon choice should align with job class and elemental affinities. Switching is costly.

\- \*\*Combat Versatility:\*\* Each category offers distinct playstyles; subtypes balance accuracy and damage.

\- \*\*Role Integration:\*\* Weapon types reinforce synergy between the Weapon, Job Class, and Elemental Powers Hexads.



\### 5. Summary



The Weapon Hexad provides a robust framework tied to stats, roles, and job classes. Meaningful weapon choices support depth and dynamic gameplay.



\---



\## Section 6: Instrument Hexad



\### Overview



The Instrument Hexad governs spellcasting and magic customization. Instruments are tied to stats, grant bonuses, and serve as the foundation for learning and performing spells.



\### 1. Instrument Mechanics



\#### Stat Associations and Bonuses



| Instrument Type | Stat | Bonus |

|---|---|---|

| Bowed Strings | Dexterity | +5% Hit Chance |

| Plucked Strings | Agility | +5% Dodge Chance |

| Brass | Strength | +5% Maximum HP |

| Percussion | Stamina | +5% Maximum MP |

| Winds/Woodwinds | Intelligence | +5% Critical Hit Chance |

| Reeds | Spirit | +5% Parry Chance |



\#### Temporary and Permanent Boosts



\- Instruments provide a \*\*6% Temporary Boost\*\* to their associated stat while equipped.

\- Players gain a \*\*2% Permanent Boost\*\* to the associated stat upon leveling up.



\#### Spell Assignment



\- Spells are tied to the equipped instrument.

\- Players use Spell Points to unlock spells for their current instrument.



\#### Switching Instruments



\- Switching refunds all previously spent Spell Points.

\- Switching cost scales with the number of spells previously tied to the instrument.



\### 2. Instrument Types



1\. \*\*Bowed Strings (Dexterity):\*\* Violin, Viola, Erhu, etc.

2\. \*\*Plucked Strings (Agility):\*\* Harp, Lute, Guitar, etc.

3\. \*\*Brass (Strength):\*\* Trumpet, Trombone, Horn, etc.

4\. \*\*Percussion (Stamina):\*\* Drums, Marimba, Djembe, etc.

5\. \*\*Winds/Woodwinds (Intelligence):\*\* Flute, Oboe, Pan Flute, etc.

6\. \*\*Reeds (Spirit):\*\* Clarinet, Bassoon, Sheng, etc.



Players may choose any specific instrument within these types for thematic customization.



\### 3. Strategic Implications



\- \*\*Customization:\*\* Align instrument choice with elemental affinities, job class, and combat style.

\- \*\*Complementary Mechanics:\*\* Instruments amplify elemental affinities and work alongside job classes.

\- \*\*Flexibility in Spellcasting:\*\* Reassigning Spell Points allows adaptability, but scaling costs encourage commitment.



\### 4. Summary



The Instrument Hexad integrates with broader systems by offering meaningful bonuses, dynamic spellcasting, cross-Hexad synergy, and player creativity.



\---



\## Section 7: Character Hexad



\### 1. Party



\- \*\*Definition:\*\* A group of up to six Players forming the core combat and exploration team.

\- \*\*Positions:\*\* Three front-row and three back-row positions.

&#x20; - \*\*Front Row:\*\* Full damage from physical attacks, half from magical attacks.

&#x20; - \*\*Back Row:\*\* Full damage from magical attacks, half from physical attacks.

\- \*\*Customization:\*\* Players bring unique abilities, equipment, and stats for strategic builds.



\### 2. Players



Controllable characters within a Party. Each Player equips:



1\. 2 Job Classes (Primary and Secondary)

2\. 2 Elemental Powers (Primary and Secondary)

3\. 1 Weapon (tied to skills)

4\. 1 Instrument (tied to spells)

5\. 1 Deity (influences resistances/weaknesses and blessings/curses)

6\. Head Gear (Helmet)

7\. Body Gear (Armor)

8\. 1 Peon (Companion)



Stats increase through leveling and equipment.



\### 3. Peons



Companion entities tied to a Player, providing passive bonuses or random combat interactions.



\- \*\*Passive Effects:\*\* Unique bonuses to the Player or Party.

\- \*\*Random Abilities:\*\* May act independently, such as:

&#x20; - Stealing items from enemies

&#x20; - Providing buffs or debuffs

&#x20; - Dealing small amounts of damage

\- \*\*Example:\*\* A goblin Peon may randomly attempt to steal items.



\### 4. Bands



Groups of monsters serving as the counterpart to Parties.



\- \*\*Composition:\*\* Bosses, Beasts, or a mix.

\- \*\*Variety:\*\* Vary in size, difficulty, and composition.

\- \*\*Combat Dynamics:\*\* Utilize coordinated attacks.



\### 5. Bosses



High-difficulty enemies designed as unique challenges.



\- \*\*Scaling Stats:\*\* Primary, Secondary, and Tertiary stats scale dynamically with level.

\- \*\*Deity Influence:\*\* Each Boss has an associated Deity that may activate a Blessing or Curse.

\- \*\*Encounter Design:\*\* Appear in story-driven events or major challenges; rare random encounters may include them.



\### 6. Beasts



Standard monsters encountered in random battles.



\- \*\*Scaling Stats:\*\* Like Bosses, stats scale with level.

\- \*\*Deity Influence:\*\* Each Beast has an associated Deity.

\- \*\*Frequency:\*\* Form the majority of encounters, providing XP, loot, and skill/spell points.



\### Summary



The Character Hexad organizes Parties, Players, Peons, Bands, Bosses, and Beasts into a cohesive framework supporting dynamic combat, strategic customization, and engaging encounters.



\---



\## Section 8: Gear Hexad



\### Overview



The Gear Hexad defines six categories of helms and armor, tied to core stats and enhancing attributes and combat performance.



\### 1. Gear Types



| Gear Type | Stat Tie | Focus |

|---|---|---|

| Heavy Physical | Strength | Raw physical power and durability |

| Heavy Magical | Stamina | Endurance and magical defenses |

| Medium Physical | Agility | Mobility and physical defense |

| Medium Magical | Spirit | Magic resistance and spirit-based abilities |

| Light Physical | Dexterity | Speed and evasion |

| Light Magical | Intelligence | Magical precision and power |



\### 2. Stat and Bonus Mechanics



\- Each piece of gear (helm and armor) grants:

&#x20; - \*\*3% Temporary Boost\*\* to its associated stat while equipped.

&#x20; - \*\*1% Permanent Boost\*\* to the stat upon leveling up.

\- Gear can directly modify stats beyond standard boosts.

\- Gear can influence:

&#x20; - Critical Hit Chance

&#x20; - Parry Chance

&#x20; - Dodge Chance



\### 3. Additional Gear Features



\- \*\*Elemental Effects:\*\* Resistances and weaknesses.

\- \*\*Status Effects:\*\* Immunity to debuffs or applied buffs.

\- \*\*Special Abilities:\*\* HP/MP regeneration, bonus damage vs. enemy types, enhanced spell/skill potency.



\### 4. Acquisition and Scaling



\- \*\*Battle Drops:\*\* From Beasts, Bosses, and Bands; quality scales with encounter difficulty.

\- \*\*Shops:\*\* Purchase gear for reliable upgrades.

\- \*\*Scaling:\*\* Static bonuses complement leveling and stat growth.



\### 5. Summary



The Gear Hexad enhances stats and combat versatility through core attributes, elemental interactions, and combat modifiers.



\---



\## Section 9: Shops Hexad



\### Overview



The Shops Hexad organizes hubs for progression, resource management, and customization.



\### 1. Blacksmith



\- \*\*Purpose:\*\* Weapons and job class changes.

\- \*\*Services:\*\*

&#x20; - Weapon Upgrades

&#x20; - Job Class Respec: Redistribute skill points from one weapon to another at a cost.

\- \*\*Theme:\*\* A classic forge with hammers and molten steel.



\### 2. Conservatory



\- \*\*Purpose:\*\* Instruments and magic changes.

\- \*\*Services:\*\*

&#x20; - Instrument Upgrades

&#x20; - Spell Respec: Redistribute spell points from one instrument to another at a cost.

\- \*\*Theme:\*\* A serene, music-filled hall.



\### 3. Armory



\- \*\*Purpose:\*\* Helms and armor.

\- \*\*Services:\*\*

&#x20; - Gear Acquisition: Purchase or find helms and armor of various weights and focuses.

&#x20; - Customization: Special effects such as status resistances, elemental bonuses, or raw stat boosts.

\- \*\*Theme:\*\* A fortified shop lined with shields, breastplates, and helmets.



\### 4. Apothecary



\- \*\*Purpose:\*\* Healing, buffs, and consumables.

\- \*\*Services:\*\*

&#x20; - Item Stock: Potions, elixirs, stat boosters, antidotes.

&#x20; - Restoration: Rare or limited-use recovery items.

\- \*\*Theme:\*\* A cozy, aromatic space filled with vials and herbs.



\### 5. Bar



\- \*\*Purpose:\*\* Quests, bounties, and side missions.

\- \*\*Services:\*\*

&#x20; - Bounty Board: Hunting beasts, delivering items, etc.

&#x20; - Questing Info: Intel on major storyline missions.

\- \*\*Theme:\*\* A lively tavern with a central bounty board.



\### 6. Church



\- \*\*Purpose:\*\* Change deity allegiance.

\- \*\*Services:\*\*

&#x20; - Deity Realignment: Switch deities for a fee, resetting elemental affinities.

&#x20; - Spiritual Guidance: Lore and insights into deities.

\- \*\*Theme:\*\* A tranquil sanctuary with stained glass windows.



\### Summary



The Shops Hexad offers diverse, strategically vital services supporting progression, customization, and immersion.



\---



\## Section 10: Drops Hexad



\### 1. Drop Categories



\#### Experience Points (XP)



\- Progresses character levels.

\- Beasts: 1 XP per kill.

\- Bosses: 12 XP or more.



\#### Skill Points (SP)



\- Unlocks and upgrades job class abilities.

\- Beasts: 1 SP per kill.

\- Bosses: 12 SP.



\#### Spell Points (MP)



\- Unlocks and upgrades elemental magic spells.

\- Earned at the same rate as XP and SP.



\#### Gold



\- Currency for items, equipment, and services.

\- Beasts drop gold within a level-based range:

&#x20; - Level 1: 2–3 gold

&#x20; - Each additional level adds +2 gold to the range

&#x20;   - Level 2: 4–5 gold

&#x20;   - Level 3: 6–7 gold



\#### Items



\- Consumables for healing, buffs, and other effects.

\- Includes potions, elixirs, antidotes, and stat boosters.

\- Beasts and bosses have specific item drops.



\#### Gear



\- Enhances stats and adds special effects.

\- Includes helms and armor from the Gear Hexad.

\- Higher-quality gear is more likely from bosses or challenging beasts.

\- May include rare/unique equipment.



\### 2. Beasts



Each beast has three drop categories:



\- \*\*Common Drop:\*\* Consumable item

\- \*\*Uncommon Drop:\*\* Common gear

\- \*\*Rare Drop:\*\* Uncommon gear



Drop chances (1 drop per beast):



| Drop Type | Chance |

|---|---:|

| Common | 12% |

| Uncommon | 6% |

| Rare | 3% |



\*\*Steal Mechanic:\*\*



| Steal Type | Chance |

|---|---:|

| Common | 36% |

| Uncommon | 18% |

| Rare | 9% |



\### 3. Bosses



\- \*\*Fixed Drops:\*\* Always drop one predetermined item tailored to theme/narrative/challenge.

\- \*\*Steal Mechanic:\*\* Each boss has one stealable item, typically rare gear or high-value consumables. Steal chance: 9% for the rare drop.

\- \*\*Additional Rewards:\*\* Significantly more XP, SP, and gold than beasts. Unique gear/consumables may only be obtainable from bosses.



\### 4. Balancing and Progression



\- \*\*Scaling Gold Drops:\*\* Increase with enemy level.

\- \*\*Dynamic Drop Tables:\*\* Drops tied to individual enemies for immersion and replayability.

\- \*\*Strategic Stealing:\*\* Adds decision-making and resource management.



\### Summary



The Drops Hexad makes every encounter meaningful through scalable XP and gold, unique items, boss-specific rewards, and the Steal mechanic.



\---



\## Section 11: Status Hexad



\### Overview



The Status Hexad defines persistent combat effects, including damage over time, regeneration, and stat debuffs.



\### 1. HP and MP Down (Damage Over Time)



\- \*\*Poison:\*\* Reduces 5% max HP per turn for exactly 3 turns. Does not stack; refreshes duration.

\- \*\*Shock:\*\* Reduces 5% max MP per turn for exactly 3 turns. Does not stack; refreshes duration.

\- \*\*Burn:\*\* Reduces 2% max HP and MP per turn for exactly 3 turns. Does not stack; refreshes duration.



\### 2. HP and MP Up (Regeneration Over Time)



\- \*\*Regain:\*\* Restores 5% max HP per turn for exactly 3 turns. Does not stack; refreshes duration.

\- \*\*Renew:\*\* Restores 5% max MP per turn for exactly 3 turns. Does not stack; refreshes duration.

\- \*\*Revive:\*\* Restores 2% max HP and MP per turn for exactly 3 turns. Does not stack; refreshes duration.



\### 3. Stats Down (Debuffs)



\- \*\*Blind:\*\* Reduces Dexterity and Agility by 20% for 3 turns.



> \*\*Note:\*\* The source extraction was corrupted after this point; additional statuses were not recoverable.



\### Strategic Considerations



\- \*\*Persistent Effects:\*\* Indefinite statuses such as Confusion, Sleep, Berserk, and Shine add urgency and unpredictability.

\- \*\*Interactions:\*\* Magical attacks uniquely counter Berserk and Shine.

\- \*\*Balance:\*\* Most statuses last 3 turns.

\- \*\*Flexibility:\*\* Variety of buffs/debuffs supports adaptable strategies.



\---



\## Section 12: Command Hexad



\### Overview



The Command Hexad defines six fundamental combat actions.



\### 1. Fight



\- Execute a standard physical attack with the equipped weapon.

\- Damage stat depends on weapon:

&#x20; - Melee: Strength

&#x20; - Ranged: Dexterity

&#x20; - Magic: Intelligence

\- Targets a single enemy.



\### 2. Defend



\- Assume a defensive stance for one turn.

\- \*\*Physical Damage Reduction:\*\* −50%

\- \*\*Magical Damage Reduction:\*\* −25%

\- Additional effects may apply based on gear.



\### 3. Skills



\- Activate abilities tied to equipped weapon and primary job class.

\- Unlocked by spending Skill Points.

\- Tied to job class and weapon.

\- Unique effects, costs, and level requirements.



\### 4. Spells



\- Cast magical abilities tied to equipped instrument and elemental powers.

\- Unlocked by spending Spell Points.

\- Tied to equipped elemental powers.

\- Includes offensive, defensive, and summoning options.



\### 5. Items



\- Use consumable items from inventory.

\- Includes potions, ethers, status cures, etc.

\- Consumed on use.

\- Some items may have AoE or party-wide applications.



\### 6. Flee



\- Attempt to escape battle.

\- \*\*Base Chance:\*\* 33%

\- \*\*Bosses:\*\* Fleeing not allowed.

\- Success escapes entirely; failure forfeits the turn.



\### Strategic Considerations



\- Combat roles are supported by specific commands.

\- Risk and reward: Fight/Skills emphasize offense; Defend/Flee offer mitigation or retreat.

\- Skills and spells tied to job classes, elemental powers, and equipment ensure party variety.

\- The command system encourages experimentation and mastery.



\---



\## Section 13: Act I Gear



\### Gear Types



\#### Helms



| Helm | Type | Stat Boost |

|---|---|---|

| Trapper | Heavy Physical | Strength |

| Earmuffs | Heavy Magical | Stamina |

| Scarf | Medium Physical | Dexterity |

| Balaclava | Medium Magical | Spirit |

| Beanie | Light Physical | Agility |

| Headband | Light Magical | Intelligence |



\#### Armor



| Armor | Type | Stat Boost |

|---|---|---|

| Peacoat | Heavy Physical | Strength |

| Parka | Heavy Magical | Stamina |

| Windbreaker | Medium Physical | Dexterity |

| Hoodie | Medium Magical | Spirit |

| Sweater | Light Physical | Agility |

| Cardigan | Light Magical | Intelligence |



\### Gear Tiers



Each piece of gear can appear in one of five tiers:



1\. \*\*Frayed (Tier 1):\*\* Basic, worn-out gear

2\. \*\*Used (Tier 2):\*\* Functional but slightly aged

3\. \*\*Worn (Tier 3):\*\* Dependable and solid

4\. \*\*Tailored (Tier 4):\*\* Refined and specialized

5\. \*\*Pristine (Tier 5):\*\* Impeccably crafted, top-tier quality



\### Affixes



Affixes enhance gear with unique properties.



\#### Stat Boost Affixes (6 Total)



\- Strength Boost: +6% Strength

\- Stamina Boost: +6% Stamina

\- Dexterity Boost: +6% Dexterity

\- Agility Boost: +6% Agility

\- Intelligence Boost: +6% Intelligence

\- Spirit Boost: +6% Spirit



\#### Stat Pair Boost Affixes (15 Total)



Each boosts two stats by +3% each:



\- Strength + Stamina

\- Strength + Dexterity

\- Strength + Agility

\- Strength + Intelligence

\- Strength + Spirit

\- Stamina + Dexterity

\- Stamina + Agility

\- Stamina + Intelligence

\- Stamina + Spirit

\- Dexterity + Agility

\- Dexterity + Intelligence

\- Dexterity + Spirit

\- Agility + Intelligence

\- Agility + Spirit

\- Intelligence + Spirit



\#### Elemental Affinity Affixes (4 Total)



\- Fire Affinity: +15% Fire damage

\- Air Affinity: +15% Air damage

\- Earth Affinity: +15% Earth damage

\- Water Affinity: +15% Water damage



\### Gear Stats



\- \*\*Helm:\*\* Provides a 3% temporary boost and a 1% permanent boost upon leveling to the stat associated with its type.

\- \*\*Armor:\*\* Provides a 3% temporary boost and a 1% permanent boost upon leveling to the stat associated with its type.



\### Uncommon Gear System



\- \*\*Common Gear:\*\* Standard items with no affixes.

\- \*\*Uncommon Gear:\*\* Items with a single affix applied.



\#### Uncommon Gear Combinations



\- Base Items: 12 (6 Helms, 6 Armor)

\- Tiers: 5 tiers for each item type

\- Affixes: 36 unique affixes

\- Result: \*\*60 common gear pieces\*\* and \*\*2,160 uncommon gear combinations\*\*



\### Examples of Early Game Gear



\#### Common Gear



1\. Frayed Trapper

2\. Used Scarf

3\. Worn Hoodie

4\. Tailored Beanie

5\. Pristine Cardigan



\#### Uncommon Gear



1\. Frayed Trapper of Strength (+6% Strength)

2\. Used Scarf of Fire Resistance (+15% Fire Damage)

3\. Worn Hoodie of MP Boost (+10% Max MP)

4\. Tailored Beanie of Dodge Boost (+5% Dodge Chance)

5\. Pristine Cardigan of Intelligence and Spirit (+3% Intelligence, +3% Spirit)



\### Gear Drops



\- \*\*Common Drops:\*\* Regular gear from battles, treasure chests, and shops.

\- \*\*Uncommon Drops:\*\* Rare gear with affixes; more likely from tougher enemies and bosses.

\- \*\*Acquisition Methods:\*\*

&#x20; - Shops: Purchase common and uncommon gear at escalating prices.

&#x20; - Enemies: Random drops based on encounter difficulty.

&#x20; - Crafting (Future): Combine materials to upgrade or customize gear.



\---



\## Section 14: Act I Spells



This section details the 16 elemental spells available in Act I: four elements, each with four tiers.



\### Fire Spells (Damage + Debuff)



\#### Tier 1: Eye of Kadmilos



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Moderate fire damage and applies Blind (50% chance)

\- \*\*Blind Effect:\*\* Reduces Dexterity and Agility by 20%

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Low

\- \*\*Visual Concept:\*\* A concentrated burst of searing light blinds and burns the enemy.



\#### Tier 2: Dardanos’s Flame



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* High fire damage with moderate accuracy penalty (85%)

\- \*\*Cost:\*\* Moderate

\- \*\*Visual Concept:\*\* A blazing flame erupts, focusing raw destructive power.



\#### Tier 3: Dardanos’s Blightfire



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Inflicts Burn (HP + MP drain of 5% per turn)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Moderate

\- \*\*Visual Concept:\*\* A cursed, dark flame consumes the enemy, sapping strength.



\#### Tier 4: Sight of Kadmilos



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Significant fire damage to all enemies and applies Weaken (reduces Stamina by 20%)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* High

\- \*\*Visual Concept:\*\* A radiant burst of fire saps endurance while searing enemies.



\### Air Spells (Buff + Damage)



\#### Tier 1: Breath of Kadmilos



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Grants the caster a random buff (+20% to one stat)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Low

\- \*\*Visual Concept:\*\* A revitalizing wind surrounds the caster.



\#### Tier 2: Iasion’s Gale



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Moderate air damage

\- \*\*Cost:\*\* Moderate

\- \*\*Visual Concept:\*\* A sharp, slicing gust of wind targets the enemy.



\#### Tier 3: Iasion’s Tempest



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Grants the entire party a random buff (+15% to one stat)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* High

\- \*\*Visual Concept:\*\* Uplifting winds cascade over the party.



\#### Tier 4: Voice of Kadmilos



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Significant air damage to all enemies and grants the party Boost (+10% to all stats)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Very high

\- \*\*Visual Concept:\*\* A majestic gale strikes enemies while uplifting allies.



\### Water Spells (Heal + Buff)



\#### Tier 1: Tear of Bendix



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Heals moderate HP for one ally and grants the caster Renew (MP recovery of 5% per turn)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Low

\- \*\*Visual Concept:\*\* A glistening tear rejuvenates an ally while fortifying the caster’s magic.



\#### Tier 2: Zerynthria’s Surge



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Grants the entire party Regain (HP recovery of 5% per turn)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Moderate

\- \*\*Visual Concept:\*\* A steady wave of water restores vitality.



\#### Tier 3: Zerynthria’s Deluge



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Powerful group heal

\- \*\*Cost:\*\* High

\- \*\*Visual Concept:\*\* A torrential downpour refreshes and restores the party.



\#### Tier 4: Fountain of Bendix



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Massive group heal and grants Revive (HP + MP recovery of 2% per turn)

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Very high

\- \*\*Visual Concept:\*\* An ethereal fountain washes the battlefield with renewal.



\### Earth Spells (Heal + Debuff)



\#### Tier 1: Touch of Bends



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Heals a small amount of HP for all allies and has a 50% chance to apply Blind, Deaf, or Dumb to all enemies

&#x20; - \*\*Blind:\*\* −20% Dexterity and Agility

&#x20; - \*\*Deaf:\*\* −20% Strength and Stamina

&#x20; - \*\*Dumb:\*\* −20% Intelligence and Spirit

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Low

\- \*\*Visual Concept:\*\* A subtle tremor heals allies and disrupts enemies.



\#### Tier 2: Kotys’s Boulder



\- \*\*Type:\*\* Single-target

\- \*\*Effect:\*\* Powerful single-target heal

\- \*\*Cost:\*\* High

\- \*\*Visual Concept:\*\* A solid surge of energy grounds and heals the target.



\#### Tier 3: Kotys’s Tremor



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Inflicts Poison (5% HP drain per turn) on all enemies

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Moderate

\- \*\*Visual Concept:\*\* A violent quake unleashes a toxic cloud.



\#### Tier 4: Thicket of Bends



\- \*\*Type:\*\* Multi-target

\- \*\*Effect:\*\* Massive group heal for all allies and inflicts Shock (MP drain of 5% per turn) on all enemies

\- \*\*Duration:\*\* 3 turns

\- \*\*Cost:\*\* Very high

\- \*\*Visual Concept:\*\* A lush, magical thicket heals allies and disrupts enemy magic.



\### Summary of Mechanics



\- \*\*Single vs. Multi-Target:\*\*

&#x20; - Fire: Tiers 1–3 single-target; Tier 4 multi-target.

&#x20; - Air: Tiers 1–2 single-target; Tiers 3–4 multi-target.

&#x20; - Water: Tier 1 single-target; Tiers 2–4 multi-target.

&#x20; - Earth: All spells multi-target.

\- \*\*Buffs/Debuffs:\*\*

&#x20; - Regain/Revive: 5% HP/MP recovery per turn.

&#x20; - Poison/Shock: 5% HP/MP drain per turn.

&#x20; - Single-target stat changes: ±20%

&#x20; - Multi-target stat changes: ±15%

\- \*\*Deities and Themes:\*\*

&#x20; - Fire: Kadmilos inspires power and brilliance.

&#x20; - Air: Kadmilos uplifts with empowering winds.

&#x20; - Water: Bendix heals and rejuvenates.

&#x20; - Earth: Bendix grounds and protects while destabilizing foes.



\---



\## Section 15: Act I Skills



Each job class has four skills with increasing potency and cost per tier.



\### Prophet (God: Kotys)



1\. \*\*Guard (Tier 1):\*\* Reduces damage taken by 50% physical, 25% magical for one turn. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Shine (Tier 2):\*\* Grants Shine status, drawing enemy aggro for three turns. \*\*MP Cost:\*\* 4.

3\. \*\*Cover (Tier 3):\*\* Automatically intercepts attacks on allies with less than 1/3 HP.

4\. \*\*Blessing of Kotys (Tier 4):\*\* Grants Shine and boosts Agility, Stamina, and Spirit by 15% for three turns. \*\*MP Cost:\*\* 8.



\### Astrologer (God: Bendis)



1\. \*\*Steal (Tier 1):\*\* Attempts to steal an item from an enemy. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Venom (Tier 2):\*\* Inflicts Poison on a single target (5% HP damage per turn for three turns). \*\*MP Cost:\*\* 3.

3\. \*\*Blight (Tier 3):\*\* Inflicts Blind, Deaf, and Dumb on a single target for three turns. \*\*MP Cost:\*\* 6.

4\. \*\*Mark of Bendis (Tier 4):\*\* Inflicts Slow on all enemies for three turns. \*\*MP Cost:\*\* 10.



\### Shrinebearer (God: Zerynthria)



1\. \*\*Mend (Tier 1):\*\* Heals a single target for 10% of their max HP. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Cleanse (Tier 2):\*\* Removes all negative statuses from a single target. \*\*MP Cost:\*\* 3.

3\. \*\*Raise (Tier 3):\*\* Revives a fallen ally with 10% HP. \*\*MP Cost:\*\* 8.

4\. \*\*Prayer of Zerynthria (Tier 4):\*\* Group heal restoring 25% HP to all allies and removes all negative statuses. \*\*MP Cost:\*\* 12.



\### Solist (God: Dardanos)



1\. \*\*Strike (Tier 1):\*\* Deals 125% of normal attack damage. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Charge (Tier 2):\*\* Delays for one turn, then deals 225% of normal attack damage. \*\*MP Cost:\*\* 4.

3\. \*\*Rush (Tier 3):\*\* Deals 200% attack damage but forfeits next turn. \*\*MP Cost:\*\* 3.

4\. \*\*Dardanos’s Fury (Tier 4):\*\* Deals AoE damage to all enemies equal to 150% attack power. \*\*MP Cost:\*\* 8.



\### Singer (God: Kadmilos)



1\. \*\*Hum (Tier 1):\*\* Raises party speed by 10% for one turn. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Chorus (Tier 2):\*\* Buffs a single target’s Strength and Dexterity by 10% for three turns. \*\*MP Cost:\*\* 4.

3\. \*\*Melody (Tier 3):\*\* Reduces the MP cost of all allies’ abilities by 1 for two turns. \*\*MP Cost:\*\* 5.

4\. \*\*Harmony of Kadmilos (Tier 4):\*\* Raises all party members’ six stats by 10% for three turns. \*\*MP Cost:\*\* 12.



\### Sacred Scribe (God: Iasion)



1\. \*\*Scan (Tier 1):\*\* Reveals an enemy’s stats, elemental weaknesses, resistances, and potential drops. \*\*MP Cost:\*\* 0 (free action).

2\. \*\*Quillstrike (Tier 2):\*\* Deals damage to a single target equal to their Intelligence stat. \*\*MP Cost:\*\* 3.

3\. \*\*Copy (Tier 3):\*\* Learns and allows use of a single enemy ability once per battle. \*\*MP Cost:\*\* 6.

4\. \*\*Scripture of Iasion (Tier 4):\*\* Debuffs all enemies’ Intelligence and Spirit by 10% while restoring MP to allies and boosting Intelligence/Spirit by 10%. \*\*MP Cost:\*\* 10.



\### Notes on MP Costs



\- \*\*Tier 1:\*\* Free actions, accessible at all levels.

\- \*\*Tier 2:\*\* Moderate costs (3–4 MP).

\- \*\*Tier 3:\*\* Higher costs (5–8 MP).

\- \*\*Tier 4:\*\* Expensive (8–12 MP), impactful climactic skills in Act I.



\---



\## Section 16: Invocations of Act I



The invocations introduce the six primeval gods and their effects when summoned in battle.



\### Cadmalos (Field of Turquoise)



\*\*Blessing: Divine Clarity\*\*



\- All allies gain Haste for 3 turns (speed +20%)

\- All allies’ Hit Chance increased by 15%

\- Random ally regains 10% MP each turn for 3 turns



\*\*Curse: Shattering Gaze\*\*



\- All enemies gain Blind for 3 turns (Dexterity and Agility reduced)

\- All enemies’ Critical Hit Chance reduced by 20%

\- One random enemy loses 25% of current HP immediately (cannot be fatal)



\### Bendix (Teeth of Okeanos)



\*\*Blessing: Primal Endurance\*\*



\- All allies gain Regen (5% HP per turn) for 3 turns

\- All allies gain +15% Stamina and Strength for 3 turns

\- Random ally gains immunity to debuffs for 3 turns



\*\*Curse: Howling Abyss\*\*



\- All enemies take Poison damage (5% HP per turn) for 3 turns

\- All enemies’ Stamina reduced by 20%

\- Random enemy is inflicted with Fear for 2 turns (may skip their turn)



\### Dardanos (Cypress of White)



\*\*Blessing: Ethereal Protection\*\*



\- All allies gain Barrier (absorbs damage equal to 15% max HP) for 3 turns

\- All allies’ Spirit and Agility increased by 10% for 3 turns

\- Removes all negative status effects from the party



\*\*Curse: Cypress Vines\*\*



\- All enemies are inflicted with Slow for 3 turns (speed reduced by 20%)

\- One random enemy is inflicted with Bind for 3 turns (cannot act)

\- All enemies’ Spirit reduced by 15% for 3 turns



\### Iasion (House of Life)



\*\*Blessing: Wisdom’s Gift\*\*



\- All allies gain Renew (5% MP per turn) for 3 turns

\- All allies’ Intelligence increased by 15% for 3 turns

\- Random ally regains 25% of current MP immediately



\*\*Curse: Stifling Silence\*\*



\- All enemies lose 5% MP per turn for 3 turns

\- All enemies’ Intelligence and Hit Chance reduced by 10% for 3 turns

\- Random enemy is inflicted with Mute (cannot cast spells) for 2 turns



\### Zerynthria (Lake of Memory)



\*\*Blessing: Flow of Remembrance\*\*



\- All allies gain Revive for 3 turns (recover HP and MP upon death at 25%)

\- All allies’ Critical Hit Chance increased by 10% for 3 turns

\- Random ally regains 15% HP and MP immediately



\*\*Curse: Drowning Echoes\*\*



\- All enemies take Shock damage (5% MP loss per turn) for 3 turns

\- All enemies’ Agility and Dexterity reduced by 10% for 3 turns

\- One random enemy takes 15% of current HP as damage immediately



\### Kotys (Chamber of Darkness)



\*\*Blessing: Shadow’s Embrace\*\*



\- All allies gain Stealth for 3 turns (enemies have reduced chance to hit)

\- All allies’ Strength and Dexterity increased by 10% for 3 turns

\- Random ally’s next attack becomes an automatic Critical Hit



\*\*Curse: Devouring Roots\*\*



\- All enemies are inflicted with Paralysis for 1 turn (cannot act)

\- All enemies’ Speed and Strength reduced by 15% for 3 turns

\- Random enemy loses 20% of max HP (cannot be fatal)



\### Invocation Rules and Mechanics



\- \*\*Chance to Invoke:\*\* Each boss, beast, or player has a 3% chance per turn to invoke their associated god.

\- \*\*Trigger Announcement:\*\* “\[God’s Name] smiles upon \[Player/Enemy],” followed by effects.

\- \*\*Region Change:\*\* Battlefield transforms to the god’s domain:

&#x20; - Cadmalos: Field of Turquoise

&#x20; - Bendix: Teeth of Okeanos

&#x20; - Dardanos: Cypress of White

&#x20; - Iasion: House of Life

&#x20; - Zerynthria: Lake of Memory

&#x20; - Kotys: Chamber of Darkness



\---



\## Section 17: Personas with Their Peons



| Persona | Stats | Job Classes | Elemental Powers | Weapon | Instrument | Headgear | Body Gear | Peon | Passive Bonus |

|---|---|---|---|---|---|---|---|---|---|

| \*\*Cory C. Childs\*\* | Primary Agility; Secondary Strength and Intelligence | Primary Shrinebearer; Secondary Solist | Fire and Air | Epimenides Orthria (Spear) | Orpheus Nychta (Plucked) | Frayed Scarf | Frayed Hoodie | Porropogon (Gremlin) | 25% chance to steal items during battle |

| \*\*Meri Mi Matere\*\* | Primary Spirit; Secondary Stamina and Dexterity | Primary Prophet; Secondary Astrologer | Water and Earth | Linus Dusia (Bracers) | Musaeus Hemera (Percussion) | Frayed Scarf | Frayed Cardigan | Rocco (Rock) | 10% damage reduction to all incoming damage for party |

| \*\*Koryphanes\*\* | Primary Strength; Secondary Spirit and Agility | Primary Solist; Secondary Shrinebearer | Fire and Air | Agallis (Spear) | Ballis (Brass) | Frayed Scarf | Frayed Sweater | Argyra (Torch) | TBD |

| \*\*Isaac Cory\*\* | Primary Intelligence; Secondary Dexterity and Agility | Primary Sacred Scribe; Secondary Astrologer | Water and Earth | Picos (1H Sword) | Rhomphaia (Brass) | Frayed Scarf | Frayed Sweater | Chryseos (Key) | TBD |

| \*\*Leia Clive\*\* | Primary Stamina; Secondary Strength and Spirit | Primary Prophet; Secondary Solist | Air and Water | Satine (Daggers) | Rhodon (Woodwind) | Frayed Scarf | Frayed Sweater | Bython (Sack) | TBD |

| \*\*Cora Cadmia\*\* | Primary Spirit; Secondary Intelligence and Stamina | Primary Shrinebearer; Secondary Singer | Earth and Fire | Zeira (Talisman) | Briza (Percussion) | Frayed Scarf | Frayed Sweater | Atria (Owl) | TBD |

| \*\*Choros Cadmia\*\* | Primary Agility; Secondary Stamina and Dexterity | Primary Singer; Secondary Sacred Scribe | Air and Earth | Pelte (Quarterstaff) | Molgos (Plucked) | Frayed Scarf | Frayed Sweater | Aletheia (Fox) | TBD |

| \*\*Corax Cadmia\*\* | Primary Dexterity; Secondary Strength and Intelligence | Primary Solist; Secondary Shrinebearer | Fire and Air | Kausia (Bow) | Brutos (Bowed) | Frayed Scarf | Frayed Sweater | Pyxis (Compass) | TBD |

| \*\*Abaris Nyxidou\*\* | Primary Intelligence; Secondary Spirit and Agility | Primary Sacred Scribe; Secondary Shrinebearer | Air and Water | Onomacritus (Wand) | Cercops (Woodwind) | Frayed Scarf | Frayed Sweater | Peripious (Map) | TBD |

| \*\*Pamphos Goldenheart\*\* | Primary Agility; Secondary Strength and Dexterity | Primary Singer; Secondary Solist | Fire and Air | Prodicus (Crossbow) | Theognetus (Brass) | Frayed Scarf | Frayed Sweater | TBD | TBD |

| \*\*Aristeas Etemenanki\*\* | Primary Strength; Secondary Intelligence and Dexterity | Primary Solist; Secondary Sacred Scribe | Fire and Water | Brontinus (2H Axe) | Critodemus (Plucked) | Frayed Scarf | Frayed Sweater | Melaina (Skunk) | TBD |

| \*\*Ari Grimm\*\* | Primary Strength; Secondary Spirit and Dexterity | Primary Solist; Secondary Prophet | Fire and Earth | Whip | Brass | TBD | TBD | Squonk | TBD |

| \*\*Angelique Grimm\*\* | Primary Spirit; Secondary Agility and Intelligence | Primary Shrinebearer; Secondary Singer | Water and Air | TBD | TBD | TBD | TBD | TBD | TBD |



> \*\*Source note:\*\* An orphaned continuation line appears after Pamphos in the extraction: “Instrument: Zopyrus (Percussion); Headgear: Frayed Scarf; Body Gear: Frayed Sweater; Peon: Echinos (Shovel); Passive Bonus: TBD.” It could not be reliably matched to a persona header.



\---



\## Act I Creatures by Path



\### Path 1: \[Header Missing in Source]



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Blaze Hopper\*\* | Fiery rabbit-like creature with flame-colored fur that sparks when it leaps. | Strength | Dexterity, Intelligence | Water |

| 2 | \*\*Slick Diver\*\* | Sleek, otter-like creature with a water-repellent coat that shimmers like oil on water. | Agility | Spirit, Strength | Earth |

| 3 | \*\*Bramble Climber\*\* | Vine-covered lizard that scales trees and cliffs, leaving thorny growths behind. | Dexterity | Stamina, Spirit | Air |

| 4 | \*\*Sky Rattler\*\* | Serpentine creature that flies on thin, membranous wings, releasing hissing gusts of wind. | Intelligence | Agility, Strength | — |

| 5 | \*\*Iron Crawler\*\* | Bright, metallic beetle that reflects light, creating blinding flashes when it moves. | Stamina | Strength, Spirit | Dark |

| 6 | \*\*Nutty Chucker\*\* | Mischievous squirrel-like creature that throws shadow-infused acorns, causing confusion. | Spirit | Agility, Intelligence | — |



\### Path 2: Gatestone Wall (Lake of Memory)



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Coal Drifter\*\* | Coal-skinned salamander that leaves glowing embers in its path. | Spirit | Intelligence, Dexterity | Fire |

| 2 | \*\*Bubble Prowler\*\* | Translucent frog-like creature that creates floating, acidic bubbles. | Agility | Strength, Intelligence | Water |

| 3 | \*\*Murmur Moss\*\* | Sentient moss that whispers eerie secrets and binds its prey. | Stamina | Spirit, Dexterity | Earth |

| 4 | \*\*Zephyr Lark\*\* | Small bird-like entity with sharp, cutting wind currents around its wings. | Intelligence | Agility, Strength | Air |

| 5 | \*\*Wheel Grumbler\*\* | Mechanical creature resembling a wagon wheel, grinding out sparks as it moves. | Strength | Spirit, Intelligence | Light |

| 6 | \*\*Log Tosser\*\* | Corrupted, animated log that throws chunks of itself with surprising speed. | Dexterity | Stamina, Agility | Dark |



\### Path 3: Forked Black Bridge (House of Life)



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Char Spinner\*\* | Fiery spider that weaves burning webs of ash. | Strength | Spirit, Dexterity | Fire |

| 2 | \*\*Goo Crawler\*\* | Slug-like creature that secretes acidic mucus, corroding anything it touches. | Stamina | Strength, Agility | Water |

| 3 | \*\*Twig Snapper\*\* | Bipedal, tree-branch creature that snaps limbs with violent precision. | Dexterity | Agility, Spirit | Earth |

| 4 | \*\*Air Waiter\*\* | Ghostly avian that emits chilling, disorienting cries. | Intelligence | Spirit, Stamina | Air |

| 5 | \*\*Bolt Clanker\*\* | Humanoid automaton with bright, sparking joints and clanging footsteps. | Agility | Strength, Intelligence | Light |

| 6 | \*\*Trash Juggler\*\* | Shadowy imp that throws pieces of garbage with uncanny accuracy. | Spirit | Dexterity, Stamina | Dark |



\### Path 4: Old Pump House (Cypress of White)



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Cinder Skip\*\* | Flame-fueled frog that leaps, leaving scorched earth in its wake. | Dexterity | Stamina, Intelligence | Fire |

| 2 | \*\*Droplet Creeper\*\* | Snake-like creature with a glistening, water-slick body that can flood small areas. | Intelligence | Spirit, Strength | Water |

| 3 | \*\*Gnash Bark\*\* | Snarling, bark-covered wolf-like beast with crushing jaws. | Strength | Stamina, Agility | Earth |

| 4 | \*\*Ribbon Cutter\*\* | Swift, ribbon-like entity that slashes with the air itself. | Agility | Dexterity, Spirit | Air |

| 5 | \*\*Oil Spitter\*\* | Clunky automaton that sprays slick oil, blinding foes and causing slips. | Stamina | Intelligence, Spirit | Light |

| 6 | \*\*Shriek Bird\*\* | Black-feathered bird that screams so loudly it stuns enemies. | Spirit | Dexterity, Strength | Dark |



\### Path 5: Riverside Ridge (Teeth of Okeanos)



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Blaze Drifter\*\* | Fiery snake that slithers quickly and bursts into flames when cornered. | Intelligence | Spirit, Dexterity | Fire |

| 2 | \*\*Ripple Lurker\*\* | Stealthy fish-like creature that creates dangerous water currents. | Stamina | Strength, Agility | Water |

| 3 | \*\*Thorn Strangler\*\* | Large plant-based creature that uses tendrils to constrict prey. | Dexterity | Spirit, Strength | Earth |

| 4 | \*\*Chill Whisper\*\* | Ghostly figure that freezes the air with its haunting murmurs. | Spirit | Intelligence, Dexterity | Air |

| 5 | \*\*Spark Grinder\*\* | Machine with grinding gears that emits bright, sparking flashes. | Strength | Agility, Spirit | Light |

| 6 | \*\*Glimmer Doe\*\* | Shadowy deer-like creature with glowing antlers that disorient enemies. | Agility | Dexterity, Stamina | Dark |



\### Path 6: Willow Basin Hollow (Chamber of Darkness)



| # | Creature | Description | Primary Stat | Secondary Stats | Element |

|---:|---|---|---|---|---|

| 1 | \*\*Ash Drifter\*\* | Floating, ember-spewing shadow that burns anything nearby. | Spirit | Strength, Dexterity | Fire |

| 2 | \*\*Whisper Coil\*\* | Snake-like water entity that glides silently, its presence unsettling. | Dexterity | Spirit, Agility | Water |

| 3 | \*\*Bog Snapper\*\* | Swamp-dwelling turtle with spiked, moss-covered shells. | Stamina | Agility, Intelligence | Earth |

| 4 | \*\*Root Shaker\*\* | Ground-tethered entity that shakes the area to destabilize enemies. | Strength | Dexterity, Spirit | Air |

| 5 | \*\*Scrap Hound\*\* | Mechanical dog that scavenges metal and uses it as weapons. | Agility | Strength, Intelligence | Light |

| 6 | \*\*Panic Possum\*\* | Frightened but chaotic creature that spreads terror as it scurries. | Intelligence | Stamina, Agility | Dark |

