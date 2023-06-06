# dnd_mc
MonteCarlo Simulation of D&D dice rolls for main characteristics
In classic D&D character creation, one has to roll 4d6, take away the lowest value and add up the rest.
This is for every characteristic, and there are six of them.
Additionally, every characteristic value has a modifier (mod) value that goes from -5 (if the characteristic value is a 1) to +10 (if the characteristic value is a 30).
It goes like this:
Value   Mod
1       -5
2,3     -4  
4,5     -3  
6,7     -2
8,9     -1
10,11    0
12,13   +1  
14,15   +2
16,17   +3
18,19   +4
20,21   +5
22,23   +6
24,25   +7
26,27   +8
28,29   +9
30      +10

Of course, in the initial roll, the lowest possible value is a 3 (mod of -4) and the highest is an 18 (mod of +4). 
In the codes that accompany there is an analysis of the individual probabilities for a characteristic roll and a MC analysis of the aggregated mod values.
For the aggregated mod values I just added the mods from the 6 characteristics, so a character can go from having a -24 (with -4 in every mod) to +24 (with +4 in every mod).
This is useful to know how likely it is to obtain a character equal or better (or worse, obviously) than a certain one.
