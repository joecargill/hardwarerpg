---
layout: default
title: Core Rules
parent: Playtest
nav_order: 1
---

# Core Rules


## Attributes

Each of the three **Attributes** are used in different circumstances. (See **Saves**, below.)

- **Agility (AGL)**: Used for saves requiring poise, speed, reflexes, dodging, climbing, sneaking, balancing, etc.
- **Body (BOD)**: Used for saves requiring physical power, like lifting gates, breaking doors, resisting drugs, etc.
- **Control (CTR)**: Used for saves to persuade, deceive, keep composure, interface with technology, etc.

## Saves

- A save is a roll to avoid negative outcomes from risky choices. Characters roll a d20 and compare the results to the appropriate attribute. If they roll equal to or under that attribute, they succeed. Otherwise, they fail. A 1 is always a success, and a 20 is always a failure.
- If two opponents are each trying to overcome the other, whoever is most at risk should save.
- If two characters need to take an action together, whoever is most at risk should save (usually the character with the lowest relevant Attribute).

## Stamina

- Roll 1d6 to determine your PC's starting **Stamina (**STA**)**, which reflects their ability to avoid damage and endure stress. It does not indicate a character’s health or fortitude, nor do they lose it for very long. See [Healing & Recovery](/playtest/core-rules#healing--recovery).

## Healing & Recovery

- Resting for a few minutes restores lost Stamina but may leave the party exposed. Bandages can stabilize a character that has taken critical damage. Drugs can stabilize a character that has taken critical stress.
- Attribute loss (see [Wounds & Strain](/playtest/wounds-and-strain)) can usually be restored with a week's rest, facilitated by an appropriate source of expertise. 
- Recovering slowly at home is free, while more expedient means of recovery such as hospitals come at a cost.

## Deprivation & Fatigue

- A PC that lacks a crucial need (such as food or rest) is **Deprived**. Anyone **Deprived** for more than a day adds **Fatigue** to their inventory, one for each day. A **Deprived** PC cannot recover **STA**, Attributes, or item slots from **Fatigue**.
- Each Fatigue occupies one slot and lasts until the PC is able to recuperate (such as with a full night’s rest in a safe spot).
- If a character is forced to add **Fatigue** to their inventory but they have no free slots, they must drop an item from their inventory.

## Protection

### Armor

- Before calculating damage to **STA**, subtract the target's **Armor** value from the result of damage rolls. 
- Typical armor has a base defense (e.g. 2 Armor) that cannot be combined with other base defense. Shields and similar armor provide bonus defense (e.g. +1 Armor), but only while the item is held or worn. Bonus armor is stackable, provided you are capable of using it (e.g. spare hand for a second shield).
- A PC, NPC, or other creatures cannot have more than 3 Armor.

### Damping

- Before calculating stress to **STA**, subtract the target's **Damping** value from the result of stress rolls.
- Typical damping has a base defense (e.g. 2 Damping) that cannot be combined with other base defense. Neural implants and similar damping provide bonus defense (e.g. +1 Damping), but only while the item is held, worn, or installed. Bonus damping is stackable.
- A PC, NPC, or other creatures cannot have more than 3 Damping.

### Cover

- Before calculating damage to **STA**, subtract the target's **Cover** value from the result of damage rolls.
- Cover has two tiers: **Light Cover** (+1), and **Heavy Cover** (+2).
- Attacks on targets behind cover cause that cover to degrade a tier.
- Cover stacks with Armor; it is the only way to reduce incoming damage by more than the maximum 3 Armor.
- Attacks from behind **Heavy Cover** are _Impaired_.

## Reactions

When the PCs encounter an NPC whose reaction to the party is not obvious, the Admin may roll 2d6 and consult the following table:

|         |      |         |      |         |
| :-----: | :--: | :-----: | :--: | :-----: |
|    2    | 3-5  |   6-8   | 9-11 |   12    |
| Hostile | Wary | Curious | Kind | Helpful |

## Morale

- Enemies must pass a **CTR** save to avoid fleeing when they take their first casualty and again when they lose half their number. 
- Some groups may use their leader's **CTR** in place of their own. Lone foes must save when they're reduced to 0 Stamina. 
- Morale does not affect PCs.

## Contractors

- Crews can recruit contractors, relying on their unique skills, knowledge, and training to aid in completing jobs.
- To create a contractor, choose an appropriate role from the [Contractors](/marketplace#contractors-per-day) table in the Marketplace. Roll 3d6 for each attribute and 1d6 for their Stamina. Give them **equipment** appropriate to their station, then roll on the Character Traits tables to further flesh them out.

## Die of Fate  

- Optionally, roll 1d6 whenever the outcome of an event is uncertain or to simulate an element of randomness and chance.
- A roll of 4 or more generally favors the PCs, while a roll of 3 or under usually means bad luck for the PCs.

## Combat

### Rounds

- A **Round** is roughly ten seconds of in-game time and and proceeds with each side taking turns. Each round starts with any PC that is able to act, followed by their opponents. _The result of each side's actions occur simultaneously_. 
- During the _first round of combat_, each PC must make a **AGL** save in order to act. Special circumstances, abilities, items, or skills may negate this requirement. PCs that fail their save _lose their turn_ for this round.
- Their opponents then take their turn, and the first round ends. The next round begins with the PCs taking their turn, followed by their opponents, and so on until combat has ended with one side defeated or fled.

### Actions

On their turn, a character may move up to 40ft and take up to one action. This may be deploying a hack, attacking, moving for a second time, or some other reasonable action. Each round, the PCs declare what they are doing before dice are rolled. If a character attempts something risky, the Admin calls for a save for appropriate players or NPCs. 

### Attacking & Damage

- The attacker rolls their weapon die and subtracts the target's armor, then deals the remaining total to their opponent's **STA**. Attacks in combat automatically hit.
- If multiple attackers target the same foe, roll all damage dice and keep the single highest result. Attackers may discard a result of 4+ to add 1 damage to the final attack. Only effects from final attack are applied. All actions are declared before being resolved.
- If attacking with two weapons at the same time, roll both damage dice and keep the single highest result (denoted with a plus symbol, e.g. d8+d8).
- **Aiming:** You may spend your turn to _aim_, designating a target. On your next turn, your attack on that target deals damage equal to the maximum result of the damage die.

### Attack Modifiers

- For every advantage you have over a target for an attack (such as from high ground), you gain an **Edge**. For every Edge on an attack, you increase your die type by 1 step, e.g. a d8 Sniper Rifle attack with a Edge rolls d10 for damage (d8 -> d10).
- Edges cannot improve dice beyond d12 or below d4.
- When fighting with a large disadvantage you may be _Impaired_, rolling a d4 for attacks. _Impaired_ attacks cannot be improved by Edges.


### Critical Damage

- Damage that reduces a target's **STA** below zero is subtracted from their **BOD** by the amount of damage remaining. The target must then immediately make a **BOD** save to avoid taking **Critical Damage**, using their _new **BOD** score_. On a failure, they gain a **Wound** in an inventory slot. See [Wounds](/playtest/wounds-and-strain#wounds) for more.
- NPCs and monsters that fail a Critical Damage save are considered dead, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical damage save.

### Critical Stress

- Stress that reduces a target's **STA** below zero is subtracted from their **CTR** by the amount of stress remaining. The target must then immediately make a **CTR** save to avoid taking **Critical Stress**, using their _new **CTR** score_. On a failure, they gain a **Strain** in an inventory slot. See [Strain](/playtest/wounds-and-strain#strain) for more.
- NPCs and monsters that fail a Critical Stress save must make a morale check, per the **Admin's** discretion. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical stress save.


### Attribute Loss

- If a PC takes damage outside of combat, they should instead receive damage to an Attribute, typically **BOD**.
- If a PC's **BOD** is reduced to 0, they die. If their **AGL** is reduced to 0, they are paralyzed. If their **CTR** is reduced to 0, they have a mental breakdown. Complete **AGL** and **CTR** loss renders the character unable to act until they are restored through extended rest or by extraordinary means.

### Character Death

- When a character dies, the player should create a new character or take control of a hireling. They immediately join the party in order to reduce downtime.

### Units

- Large groups of similar combatants fighting together are treated as a single _Unit_. When a _unit_ takes **Critical Damage**, it is routed or significantly weakened. When it reaches 0 **BOD**, it is destroyed.
- Attacks against units by individuals are _impaired_ (excluding _blast_ damage). Attacks against individuals by detachments gain an _edge_ and deal _blast_ damage.

### Retreat

- Running away from a dire situation always requires a successful **AGL** save, as well as a safe destination to run to.

### Ranged Attacks

- Ranged weapons can target any enemy near enough to see the whites of their eyes. 
- Attacks against especially distant targets are _Impaired_.
- Attacks with ranged weapons when any enemy is within close range are _Impaired_, unless the enemy is _Impaired_ themselves.
- Ammunition usage usually only tracked after combat, except for weapons with the _reload_ tag. See [Ammo & Reloading](/playtest/core-rules#Ammo & Reloading).
- While the effective range of weapons is at the Admin's discretion, some weapons have effects that specify a range at which they apply. Use the following ranges as a rough guide.

|       |                                                    |
| ----- | -------------------------------------------------- |
| Close | Right beside the target.                           |
| Near | Within 15ft/6m of the target, outside close range. |
| Far  | Beyond 100ft/40m of the target.                    |

### Ammo & Reloading

- After combat, for any firearm used roll d6. On a result of 2 or less, you must reload discarding 1 Ammo from your inventory. 
- If you used _autofire_ with a weapon, you must reload on a result of 4 or less.
- If a weapon has the _reload_ tag, you must discard 1 Ammo after every attack.
- Every Ammo takes 1 inventory slot. Ammo is shareable between weapons in the same Ammo Group; **Handgun**, **Rifle**, **Shotgun**, **Explosive**, and **Arrow**.
- When changing Ammo type in combat, you must discard 1 Ammo of the type you were previously using from your inventory. For example, if you attack with normal Ammo once then make your next attack with Armor Piercing Ammo, you must discard 1 normal Ammo.

## Hacking

### Modules

- **Modules** contain a single hack and take up one slot. They cannot be easily copied or created; instead they are recovered from other hackers or corporate datastores.
- Modules will attract the attention of those others hackers, and NetWatch, and it is considered dangerous to display them openly.

### Deploying Hacks

- Anyone with a *Cyberdeck* can trigger a hack by activating the Module, which then takes about 10 seconds to deploy. They must take Stress equal to a roll of the Module's die. 
- If the PC is _deprived_ or under extreme pressure, the Admin may require a PC to make a **CTR** save to avoid any complications from deploying the hack. Consequences of failure are on par with the intended effect and may result in added **Strain**, the destruction of the Module, injury, and even death.

### Scripts

**Scripts** are similar to Modules, however:

- They are _petty_.
- They do not cause **Stress**.
- They disappear after one use.
- Do not require a _Cyberdeck_ to deploy, if directly plugged into target.

### Prototypes

**Prototypes** are one-of-a-kind items of significant power or unique capability. Prototypes usually have limited use, as well as a **Recharge** condition. Typically created by corporations, it is likely they will take efforts to reclaim them.