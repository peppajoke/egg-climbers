# Egg Climbers: The Zombocom Saga
## Game Design Document
### Creative Directors: Matt (.moejontana) & John (jkclancey7)

---

## Overview
A retro pixel-art 2D platformer (Ice Climbers style) where two heroes must save Zombocom from the invading Egg People. Browser-based, HTML/CSS/JS. Must be deployable to Railway.

## Story
The Egg People are trying to destroy Zombocom, the one place on the internet where anything is possible. They declared something IS impossible. This cannot stand. Matt and John, trained in kung fu by Danny DeVito, survive a flaming blimp crash and begin their climb to save Zombocom.

## Intro Sequence
- Text crawl or brief cutscene: Matt and John walk away from a flaming blimp crash
- Danny DeVito is their kung fu master who prepared them for this gauntlet
- Set the tone: silly, epic, absurd

## Playable Characters

### Matt
- Short hair, short beard
- T-shirt with "Matt" on it
- Weapon: Katana (fast, sleek)
- Professional hopscotch player, 3x MVP, Seattle Cups of Water

### John
- Long hair, big beard
- T-shirt with "John" on it
- Weapon: Claymore sword (large, Scottish greatsword, Highlander reference)
- Zombocom philosopher, Dumpster Champion

## Enemies
- **Egg People** (basic enemies): the invading force trying to destroy Zombocom
- **Raccoons**: allied with the Egg People, dumpster operatives, traitors to Zombocom
- **Gatorade Lawyers**: corporate enemies
- **Sea Witches**: magical enemies
- **Food-Stealing Doctor**: steals your power-ups/health, annoying enemy type

## Bosses

### Mid-Boss: Mrs. Palmeri's Chicken Farm (full level)
- **Mrs. Palmeri**: farmer lady who breeds the Egg People's army
- **Large Marge**: her giant chicken monster, spawns little egg minions during the fight
- Level is a chicken farm, fight through waves of egg minions before the boss

### Final Boss: Chip from Gatorade
- Corporate villain, the ultimate antagonist
- Matt has dirt on him (lore only, not gameplay relevant)

## Power-Ups & Items
- **Zombocom Terminals**: scattered throughout levels. Interact to see "the only limit is yourself" and get a random buff:
  - Speed boost
  - Egg magnet
  - Raccoon repellent  
  - Temporary margarita invincibility
- **Janky Jetpack**: Zombocom-powered, looks cobbled together, temporary flight boost
- **Gallon Margarita**: power-up item

## Healing
- **Chili's Restaurants**: appear on random platforms as healing stations. Walk in damaged, walk out healed. Should look like a little pixel Chili's building.

## Bonus Stage
- **The Chili's Dumpster**: bonus area, raccoon-themed

## Character Quips
Random speech bubbles pop up from characters during gameplay:
- "All hail the Chili's"
- "I hate raccoons"
- "Anything is possible at Zombocom"
- "The only limit is yourself"
- "Is that a Presidente Margarita?"
- "Raccoons took my eggs"
- Other lines referencing Chili's worship and raccoon hatred

## Art Style
- Retro pixel art
- Embrace the jank, keep it simple and charming
- Not trying to be polished, trying to be fun

## Technical Requirements
- Single-page HTML/CSS/JS browser game (or small Express server serving static files)
- Deployable to Railway (include package.json with start script)
- Controls: Arrow keys to move, space to jump, attack button
- Must actually be playable and fun
- Keep it all in /Users/clea/.openclaw/workspace/egg-climbers/

## Lore Glossary
- **Zombocom**: Sacred website where anything is possible. The thing being saved.
- **Zombocoming** (verb): to confidently state something completely fictional with such conviction that the listener believes it
- **The Matt Challenge**: eating 50 raw eggs. Nobody has completed it.
- **Dumpster Champion**: John's title, earned behind a Chili's
- **The Egg People**: villains who said something is impossible at Zombocom
