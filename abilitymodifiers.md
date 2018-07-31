Creating ability scores and then converting those to abilities is a complicated process that requires a chart or memorizing a formula. Interestingly enough ability scores are rarely used in the game yet they take up a portion of the character sheet and and make the process more confusing for new players. Is there a way during character creation we could only deal in ability modifiers?

My proposal is to use the [d6-d6](d6-d6 b722da1b.md) mechanic to create a range of numbers -5 to +5. We will also sprinkle in some [highest 1 in pool](highest 1 in pool 3bbb1a9d.md) mechanics

First select your Race. Your parents conceived of you prior to us knowing how smart you would be so this is simulating that pattern and allowing our Race to influence our rolls. 

In order (STR, DEX, CON, INT, WIS, CHA) roll for your ability modifiers.

You are rolling a white d6 that represents your race and fortune, and a black d6 the represents fate or bad luck. Always treat the white as positive and the black as negative. Take the white result and subtract from it the black result. This is the [d6-d6](d6-d6 b722da1b.md) mechanic.

Your race grants a bonus to an ability. In standard D&D 5e its a static bonus to the ability Score. In this variant it is a bonus number of white dice to be added to your roll. When you roll more than 1 white dice use the [highest 1 in pool](highest 1 in pool 3bbb1a9d.md) mechanic so that the resulting value is still a single value between 1 and 6. If your race ability bonus is +2 to Dexterity then you will roll now 3 white die and 1 black die. 1 white die is from the baseline mechanic and 2 of those white dice from the racial ability bonus.

This makes it so that abilities that your race are known for will statistically have a tendency to roll higher but it is not guaranteed. 

> I'd like to make a Hill Dwarf character. Lets see how it turns out. 
>
> The Hill Dwarf race has ability bonuses of CON+2 and WIS+1
>
> Rolling for STR my dice show: White=6 Black=1. 6 - 1 = **+5 STR**
>
> For DEX dice show: White=2 Black=5. 2 - 5 = **-3 DEX**
>
> For CON I have a +2 racial bonus: White=2,1,2 so ill take a 2 Black=2. 2 - 2 =** 0 CON**
>
> For INT the dice show: White=2 Black=3. 2 - 3 = **-1 INT**
>
> For WIS racial bonus is +1. White=4,1 so I take the 4. Black=5. 4 - 5 = **-1 WIS**
>
> Finally CHA dice show: White=5 Black=4. 5 - 4 = +1** CHA** 
>
> It looks like this Hill Dwarf will make a good fighter, slightly charismatic even. Maybe someday the even the leader of a patrol. 

This could produce pretty wild characters. I think if you just look at the character and it feels unplayable your DM may let you try again. But the goal is to produce something that you may not have intentionally decided to play. 

You may consider using d4-d4 to bring the possible bounds to -3 and +3. 

## UPDATE

after playing with this for a while and comparing some probability graphs I determined that 3d4-3d4 is much closer to the typical distribution of 3d6-10/2. But this starts to get complicated and its impossible to get a +4 out of the gate. I can see roll 2d4-2d4 (described as [Advantage/Disadvantage](Advantage_Disadvantage bd5c54d5.md)) then after the roll add the racial bonus without adjustment. The real problem here is that d4s suck. 

> \\ anydice \\
>
> output (3d6-10)/2 named "3d6" output \[highest 1 of 2d4\] - \[highest 1 of 2d4\]
>
> output (\[highest 3 of 4d6\]-10)/2 named "4d6 drop lowest"
> output \[highest 1 of 3d4\] - d4