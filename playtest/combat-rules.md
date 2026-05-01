---
layout: default
title: Combat Rules
parent: Playtest
nav_order: 2
---

# Combat Rules

## Rounds

A **Round** is roughly ten seconds of in-game time and and proceeds with each side taking turns. Each round starts with any PC that is able to act, followed by their opponents. _The result of each side's actions occur simultaneously_.

Resolve rounds in the following order:

1. Each PC must make an AGL save in order to act before their opponents. PCs that fail their save _lose their turn_ for this round. 
2. Their opponents then take their turn.
3. The next round begins with the PCs taking their turn, followed by their opponents, and so on until combat has ended with one side defeated or fled.

Special circumstances, abilities, items, or skills may negate the need to make an AGL save to act first.

## Actions

On their turn, a character may move up to 10m and take up to one action. This may be deploying a hack, attacking, moving for a second time, or some other reasonable action. Each round, the PCs declare what they are doing before dice are rolled. If a character attempts something risky, the Admin calls for a save for appropriate players or NPCs. 

All actions are declared before being resolved.

## Attacking & Damage

The attacker rolls their weapon die and subtracts the target's armor, then deals the remaining total to their opponent's STA. Attacks in combat automatically hit.

Attacks are resolved through the following steps:
1. All attackers targeting the same foe roll damage dice.
2. **Assist**: Results of 4 or greater can be discarded to add 1 damage to the final attack. 
3. Take the result from the highest result remaining, adding assist damage.
4. Subtract the target's total **Protection** (Armor + Cover).
5. The attack inflicts that damage, applying any effects from the source attack. 

## Attack Modifiers

**Edges** are gained on attacks for every advantage you have over a target (such as high ground). Every Edge you improves the die one step, up to d12. For example, a Sniper Rifle (d8) attack would roll d10 for damage.

**Impaired** attacks roll d4 for attacks, and cannot be improved.

**Dual-wielding** attacks roll both damage dice and keep the single highest result (denoted with a plus symbol, e.g. d8+d8).

**Aim** for a turn by designating a target. On your next turn, your attack on that target deals maximum damage.

## Protection

### Armor

Before calculating Damage to STA, subtract the target's **Armor** value from the result of damage rolls. 

Helmets and similar armor provide bonus protection (e.g. +1 Armor), but only while the item is held, worn, or installed.

A PC, NPC, or other creatures cannot have more than 3 Armor.

### Cover

Before calculating Damage to STA, subtract the target's **Cover** value from the result of damage rolls, before subtracting Armor. Combining cover with armor allows incoming damage to be reduced by _more than 3_.

Cover has two tiers: 

- **Light Cover** (+1 cover) such as wooden crates or a short wall.
- **Heavy Cover** (+2 cover) such as concrete pillars or a large vehicle.

Attacks on targets behind cover cause that cover to degrade a tier, until destroyed.

Attacks from behind **Heavy Cover** are _Impaired_.

### Damping

Before calculating Stress to STA, subtract the target's **Damping** value from the result of stress rolls.

Cyberdecks and similar devices provide bonus protection (e.g. +1 Damping), but only while the item is held, worn, or installed.

A PC, NPC, or other creatures cannot have more than 3 Damping.

## Ranged Attacks

Ranged weapons can target any enemy within sight, and **Ammo** is normally only tracked after combat.

Attacks against especially distant targets or when an unimpaired enemy is beside you are _impaired_.

Some effects specify a range at which they apply. Use the following ranges as a rough guide:

|       |                                                     |
| ----- | --------------------------------------------------- |
| Melee | Right beside the target.                            |
| Close | Within 10m of the target.                           |
| Near  | Within 50m of the target.                           |
| Far   | Beyond 50m of the target.                           |

## Ammo & Reloading

Every Ammo takes one inventory slot. Ammo is shareable between weapons in the same Ammo Group; **Handgun**, **Rifle**, **Shotgun**, **Explosive**, and **Arrow**.

After combat, make a _reload_ check:

1. For any firearm used make an AGL save. If you used _autofire_, roll twice taking the worse result.
2. On a failure, you must reload discarding one Ammo of that weapon type from your inventory.
3. On a success, you keep your Ammo.

If a weapon has the _reload_ tag, you must discard 1 Ammo after every attack.

When changing Ammo type in combat, you must discard your current Ammo from your inventory. For example, if you attack with standard Rifle Ammo once then make your next attack with Explosive Rifle Ammo, you must discard the standard Rifle Ammo.

## Critical Damage

Damage that reduces a target's **STA** below zero is subtracted from their BOD by the amount of damage remaining. The target must then immediately make a BOD save to avoid taking **Critical Damage**, using their _new BOD score_. On a failure, they gain a **Wound** in an inventory slot. See [Wounds](/playtest/wounds-and-strain#wounds) for more.

NPCs and monsters that fail a Critical Damage save are considered dead, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical damage save.

## Critical Stress

Stress that reduces a target's **STA** below zero is subtracted from their CTR by the amount of stress remaining. The target must then immediately make a CTR save to avoid taking **Critical Stress**, using their _new CTR score_. On a failure, they gain a **Strain** in an inventory slot. See [Strain](/playtest/wounds-and-strain#strain) for more.

NPCs and monsters that fail a Critical Stress save must make a morale check, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical stress save.

## Attribute Loss

If a PC takes damage outside of combat, they should instead receive damage to an Attribute, typically BOD.

If a PC's BOD is reduced to 0, they die. If their AGL is reduced to 0, they are paralyzed. If their CTR is reduced to 0, they have a mental breakdown. Complete AGL and CTR loss renders the character unable to act until they are restored through extended rest or by extraordinary means.

## Character Death

When a character dies, the player should create a new character or take control of a contractor. They immediately join the party in order to reduce downtime.

## Retreat

Running away from a dire situation always requires a successful AGL save, as well as a safe destination to run to.

## Squads

Large groups of similar combatants fighting together are treated as a single _Squad_. When a _squad_ takes Critical Damage, it is routed or significantly weakened. When it reaches 0 BOD, it is destroyed.

Attacks against squads by individuals are _impaired_ (excluding _blast_ damage). Attacks against individuals by squads gain an Edge and deal _blast_ damage.

