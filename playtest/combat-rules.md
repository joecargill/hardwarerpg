---
layout: default
title: Combat Rules
parent: Playtest v0.1
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

The attacker rolls their weapon die and subtracts the target's armor, then deals the remaining total to their opponent's Stamina. Attacks in combat automatically hit.

Attacks are resolved through the following steps:
1. All attackers targeting the same foe roll damage dice.
2. **Assist**: Final damage results of 4 or greater can be discarded to add 1 damage to the final attack. 
3. Take the value from the highest result remaining, adding assist damage.
4. Subtract the target's **Protection** (Armor + Cover).
5. The attack inflicts damage equal to the remaining total, and applies any effects from the source of the highest result. 

## Attack Modifiers

**Edges** are gained on attacks for every advantage you have over a target (such as high ground). Every Edge you improves the damage die one step, up to d12. For example, a Sniper Rifle (d8) attack with one Edge would instead roll d10 for damage. With two Edges it would roll d12.

**Impaired** attacks always use a d4 damage die, and cannot be improved by Edges.

**Dual-wielding** attacks roll both damage dice and keep the single highest result (denoted with a plus symbol, e.g. d8+d8).

**Aim** for a turn by designating a target you can see. On your next turn, your attack on that target deals maximum damage. A target that breaks line of sight ends your Aim.

## Protection

### Armor

Before calculating Damage to Stamina, subtract the target's **Armor** value from the result of damage rolls. 

Helmets and similar armor provide bonus protection (e.g. +1 Armor), but only while the item is held, worn, or installed.

A PC, NPC, or other creatures cannot have more than 3 Armor.

### Cover

Before calculating Damage to Stamina, subtract the target's **Cover** value from the result of damage rolls, before subtracting Armor. Combining cover with armor allows incoming damage to be reduced by _more than 3_.

Cover has two tiers: 

- **Light Cover** (+1 cover) such as wooden crates or a short wall.
- **Heavy Cover** (+2 cover) such as concrete pillars or a large vehicle.

Attacks from behind **Heavy Cover** are _Impaired_. 

Cover can be negated by flanking to get an unobstructed view of your target, or it can be destroyed with _destructive_ weapons. 

### Buffer

Before calculating Stress to Stamina, subtract the target's **Buffer** value from the result of stress rolls.

Cyberdecks and similar devices provide bonus protection (e.g. +1 Buffer), but only while the item is held, worn, or installed.

A PC, NPC, or other creatures cannot have more than 3 Buffer.

## Ranged Attacks

Ranged weapons can target any enemy within sight, and **Ammo** is normally only tracked after combat.

Attacks against especially distant targets or when an unimpaired enemy is beside you are _impaired_.

Some effects specify a range at which they apply. Use the following ranges as a rough guide:

|       |                                                     |
| ----- | --------------------------------------------------- |
| Close | Right beside the target.                            |
| Near  | Within 30m of the target.                           |
| Far   | Beyond 30m of the target.                           |

## Ammo & Reloading

Every Ammo takes one inventory slot. Ammo is shareable between weapons in the same Ammo Group; **Handgun**, **Rifle**, **Shotgun**, **Explosive**, and **Arrow**.

After combat, make a _reload_ check:

1. For any firearm used make an AGL save. If you used a _burst_ attack, roll with Disadvantage.
2. On a failure, you must reload discarding one Ammo of that weapon type from your inventory.
3. On a success, you keep your Ammo.

If a weapon has the _reload_ tag, you must discard 1 Ammo after every attack.

When changing Ammo type in combat, you must discard your current Ammo from your inventory. For example, if you attack with standard Rifle Ammo once then make your next attack with Explosive Rifle Ammo, you must discard the standard Rifle Ammo.

## Critical Damage

Damage that reduces a target's **Stamina** below zero is subtracted from their BOD by the amount of damage remaining. The target must then immediately make a BOD save to avoid taking **Critical Damage**, using their _new BOD score_. On a failure, they gain a **Wound** in an inventory slot. See [Wounds](/playtest/wounds-and-strain#wounds) for more.

NPCs and monsters that fail a Critical Damage save are considered dead, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical damage save.

## Critical Stress

Stress that reduces a target's **Stamina** below zero is subtracted from their CTR by the amount of stress remaining. The target must then immediately make a CTR save to avoid taking **Critical Stress**, using their _new CTR score_. On a failure, they gain a **Strain** in an inventory slot. See [Strain](/playtest/wounds-and-strain#strain) for more.

NPCs and monsters that fail a Critical Stress save must make a morale check, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical stress save.

## Attribute Loss

If a PC takes damage outside of combat, they should instead receive damage to an Attribute, typically BOD.

If a PC's BOD is reduced to 0, they die. If their AGL is reduced to 0, they are paralyzed. If their CTR is reduced to 0, they have a mental breakdown. Complete AGL and CTR loss renders the character unable to act until they are restored through extended rest or by extraordinary means.

## Character Death

When a character dies, the player should create a new character or take control of a contractor. They immediately join the party in order to reduce downtime.

## Retreat

Running away from a dire situation always requires a successful AGL save, as well as a safe destination to run to.

## Hardened

Very tough entities may _hardened_, representing their exceptional durability against multiple foes. Any attacks affected by armor made against _hardened_ targets are _impaired_. Fighting a _hardened_ enemy without access to _piercing_ or _shred_ weapons is very difficult.
