# fish-finder

Using depth readings to determine whether to sound an alarm. The fish-finder will decide that a fish is swimming past if:

There are three consecutive depth readings which form a strictly increasing sequence (such as 3 4 7) (which the program will call “Fish Rising”)
There are three consecutive depth readings which form a strictly decreasing sequence (such as 9 6 5) (which the program will call “Fish Diving”)
There are three consecutive depth readings which are identical (which the program will call “Constant Depth”).
All other readings will be considered random noise or debris, which the program will call “No Fish.”
