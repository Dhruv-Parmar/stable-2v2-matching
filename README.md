# stable-2v2-matching

The objective of this project is to create a Discord bot which will take a roster of players and create balanced teams for a 2v2 tournament.

There are currently 14 classes in BDO, but it wouldn't make sense to pair two warriors together and put them against two strikers, so each class will have a "preference ranking" for itself and every other class. 

The approach to solve this will be similar to the stable marriage / stable matching problem.
