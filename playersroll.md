# Players Roll
_(back to [readme.md](readme.md))_

Rolling dice is fun. Wizards of the Coast once released some [Unearth Arcana: Variant Rules](https://media.wizards.com/2015/downloads/dnd/UA5_VariantRules.pdf) that provided some guidelines to allow players to roll to defend an attack or to determine a spells effect when typically those rolls (to hit and to save) would have been done by the DM. In that UA publication the math was very incorrect and did not properly invert the probability of success.

The system described below has correct math and has numerical adjustments consistent with other adjustments done by the players (e.g. Passive Perception = Perception - 10). You use the same measurment of success as all other checks in the game: the roller is trying to **meet or exceed** the determined difficulty target.

## General Idea

In a situation in which one character rolls and the DC is determined by another character you -10 the static number to get a modifier and you +12 the modificer to create the DC. This pattern has the players dealing in units of 10 which they already do when considering passive abilities.

### Math Time

```
SKIP THIS SECTION IF YOU DONT NEED PROOF
```

Lets observe the math real quick to sell you on the idea. If a PCs passive AC is 17 then how often will an attack made with a d20 meet or exceed the AC? The d20 has a 5% chance to land on any side. 5% \* 4 sides (20, 19, 18, 17) = 20% chance to hit. If the monster has a +3 to-hit bonus then the percentage increases 5% \* 3 sides = 15%. Chance that the monster (+3) will hit the PC (17) is 15% + 20% = 35%. Said a different way the chance that a PC will avoid the attack is 100% - 35% = 65%.

Lets turn the PCs passive AC into an active defense with -10: 17-10 = +7 defense bonus. Lets adjust the monster attack to be a static Attack DC with +12: 3 + 12 = 15 attack dc. The d20 will meet or exceed 15 with a probability of 5% \* 6 sides = 30%. Now we calculate in the defense bonus of 5% + 7 sides = 35%. Chance that the PC(+7) will successfully defend against the monster (15) is 65%. Or said another way the chance the monster will land an attack on the PC is 100% - 65% = 35%.

Now that you have seen the mathematical proof dont stress yourself out with all that percentage stuff. Just trust that players adjust -10 and the DM adjusts +12.

## Attacking and Defending

When an attack is made on a PC the player now rolls to defend. The modifier will be the characters current AC - 10. The DC for this incoming attack is 12 + the attacks "to hit" modifier.

On a successful defense roll the attack misses. On a failed defense roll the attack hits. On a critical fail, rolling a 1, treat the attack as a critical hit. On a critical defense roll, rolling a 20, you may treat that as a critical miss if applicable.

## Saving Throws

When a character forces an opponent to make a saving throw the player now rolls a spell effect. The modifier will be the spell save DC - 10. The DC for the opponents save is 12 + the appropriate save modifier.

On a successful spell effect roll the character overpowers the opponents resistence tgreating it as a failed save. On a failed spell effect roll the spell effect was resisted to some degree treating it as a successful save. Repeat the spell effect roll for each creature effected by the spell.

## Abilities and Advantage/Disadvantage

If the attacker would normally have advantage on the attack roll, you instead apply disadvantage to the defense roll, and vice versa if the attacker would have disadvantage.

> still in question: do we allow Aid, Inspiration, Bardic Inspiration, etc. to effect these new rolls? Are these new rolls categorized as saves and attack or as ability check or neither?
