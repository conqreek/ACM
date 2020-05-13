# ACM
Army Composition Mod for Victoria 2
(Intended to work with HPM)

---

# Notes

## Day 1
- Ensure that the beginning troops of each nation are appropriate for the technology level, soldier pops, and supplies of the nation

## Technology
- Ensure that technology upgrades appropriately upgrade each army composition stats
- Ensure that nations cannot build armies without all required technologies (i.e. artillery unlocked for an army with artillery

## Army Goods Supplies
- Ensure that the goods required for each army make sense based on the composition

## Map Supply Limits
- Ensure that the supply limit of the army makes sense for the map

## Soldier Pops
- Ensure that the amount of soldier pops required for an army make sense
- Ensure that the amount of armies allowed to be created based on the number of soldier pops available makes sense

## Mobilization
- How does mobilization look in a format like this?
- Possibly avoid normal mobilization in favor of heavily increased reinforcement rates of existing armies

## Combat
- This is the trickiest part to solve, as the combat expects different unit types, i.e. infantry, cavalry, and support, and treats them differently.
- Initial solution will be to treat each army as "infantry" and attempt to modify its stats appropriately based on what they would likely be if cavalry and support were used properly
- Still remains the issue that artillery equipment will take more damage than usual since it won't actually be on the backline
- Other issue is that combat width will never really come into play at all, since each army will only take one spot in the width. Could change this to lower width down to one or two armies.

---

# Armies
Heavily based on this post: https://www.reddit.com/r/paradoxplaza/comments/3rd47p/victoria_ii_optimal_army_compositions/

## Army 1: 30k Artillery-Backed Infantry
- 4 Infantry
- 1 Hussar
- 5 Artillery

---

# Phase One
- 
