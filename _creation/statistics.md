---
layout: distill
title: Statistics
permalink: /creation/statistics/
toc:
 - name: Strength (STR)
 - name: Resilience (RES)
 - name: Ki (KI)
 - name: Dexterity (DEX)
 - name: Agility (AGI)
 - name: Vitality (VIT)
 - name: Life Points (LP)
 - name: Damage bonuses
 - name: Willpower (WP)
 - name: Powerlevel (PL)
---

Attributes (also commonly referred to as statistics, or ‘stats’ for short) are numerical representations of your character’s overall physical condition: how strong they are, how fast they are, and so forth. They are the baseline for determining performance.

The five primary attributes make up, in game terms, the core of a character’s capabilities. Baseline ‘normal human’ stats are around 10. Player characters will quickly exceed these numbers, as they hone their bodies and minds to supernatural levels to achieve feats which your average person would normally consider impossible.

##### Strength (STR)
Strength is a measurement of your ability to exert physical force on the world around you. Exceptionally strong people may be correspondingly muscular, though beware that some fighters draw 'strength' from their chakra, and thus can be deceptively lean.

- Your Physical Damage Bonus (PDB) is STR/15, rounded down to one decimal point.
- Your Vitality is (RES * 6 + STR * 4)

##### Resilience (RES)
This is your body's ability to endure hardship without suffering from debilitating injuries.  Many believe it is best to avoid being hit entirely.. but nobody will say that not being able to take a blow is a good thing.

- Your Vitality is (RES * 6 + STR * 4)
- Your LP (Life Points) are (RES * 2 + KI)
- You add (RES/10) to your Stamina rolls.

##### Ki (KI)
The spiritual energy that exists within everyone and every living thing, it suffuses the world, but not everyone is 'in tune' with it, nor do they even realize it exists, much less have a capacity to make use of it.  Ki is both a measure of your own reserves of energy, and your ability to make use of that Ki.

- Your Ki Damage Bonus (KDB) is KI/25, rounded down to one decimal point.
- You add (KI/10) to your Ki Exhaustion rolls.

##### Dexterity (DEX)
Representing your deftness, precision, and reflexes.  This statistic is very important in combat, as it is what helps determine whether you can actually hit things that are moving at high speeds (such as other people you are likely to fight).

- Your Accuracy bonus is DEX/10.

##### Agility (AGI)
The sister attribute to dexterity, measuring how quickly you can react to danger, how fast you can move, and as the name suggests, how agile you are overall.

- Your Dodge bonus is AGI/10.
- Your Initiaitve bonus is AGI/10.

#### Secondary Stats
##### Vitality (VIT)
Vitality represents your character's ability to withstand or shrug off damage, to turn a dangerous blow into a glancing one, and to take a beating without getting seriously injured. You have a current and maximum vitality; whenever you take damage, you reduce your current vitality by that amount, though your maximum Vitality is unaffected.

- Your Vitality equals your (RES * 6 + STR * 4)

##### Life Points (LP)
Life points are your 'life force', representing injuries that have significantly harmed you and caused serious damage to your body.  After your Vitality reaches 0, you take damage to your Life Points; an attack which depletes your Vitality has the rest of its damage carry over into your LP. When you reach 0 LP, you become incapacitated, leaving you unable to perform any actions and vulnerable to being knocked out or killed; you die automatically if you reach -100% of your Maximum LP (so track if you go into 'negative' LP).

- You have (RES * 2 + KI) Life Points.

##### Damage Bonuses
As the name suggests, this is potent you are at inflicting injuries to others.  Full details on how they work can be found in the Combat chapter, but by default you multiply every attack's Speed by its relevant Damage Bonus, either Ki or Physical.  Damage Bonuses are unique in that they are calcualted to a single decimal place, rounded down.  For example, with a STR of 25, you'd have a damage bonus of (25/15 = 1.6666) = 1.6.

- Your Physical Damage bonus (PDB) is STR/15.
- Your Ki Damage Bonus (KDB) is KI/15.

##### Willpower (WP)
Your overall strength of will.  This is both your raw determination, and your confidence in your body's ability to keep going, and perform at a higher level, even when it, well, can't.

 - Your Willpower is calculated as (STR + RES + KI + DEX + AGI)/200, with a minimum of 1.

##### Powerlevel (PL)
Your powerlevel is, as the name implies, a numerical measurement of how strong you are.  The higher someone's powerlevel is, the more formidable they are - supposedly. It only measures raw ability, not skill or many other factors, so it is not entirely accurate, but some people swear by it being a true measurement of whom can defeat whom. 

- Your Powerlevel is (Current Vitality + KI)*(STR+DEX+SPD)/10

Someone reduced to below 0 Life Points (who is near death) still has a power level; however, some races might have 'Sub-LP', and when reduced to this extra pool of Life Points, they do not give off a powerlevel, appearing dead.
