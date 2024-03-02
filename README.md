# Text Adventure Game

This is a simple text-based adventure game implemented in JavaScript.

## Game Mechanics

- `xp`: Experience points of the player.
- `health`: Player's current health points.
- `gold`: Player's gold coins.
- `currentWeapon`: Index of the current weapon in the weapons array.
- `fighting`: Represents the type of monster the player is currently fighting.
- `monsterHealth`: Health points of the monster being fought.
- `inventory`: Array containing the player's weapons.

## UI Elements

- `button1`, `button2`, `button3`: HTML button elements.
- `text`: HTML element to display game text.
- `xpText`, `healthText`, `goldText`: HTML elements to display player stats.
- `monsterStats`, `monsterName`, `monsterHealthText`: HTML elements to display monster stats.

## Game Elements

- `weapons`: Array containing weapon objects with their names and power.
- `monsters`: Array containing monster objects with their names, levels, and health points.
- `locations`: Array containing location objects with name, button texts, button functions, and location text.

## Functions

- `update(location)`: Updates the game UI based on the current location.
- Functions for various actions such as moving to different locations, buying health/weapons, fighting monsters, dodging attacks, and handling game outcomes like winning or losing.

## Game Flow

- The game starts in the town square.
- Players can move to different locations, buy items, or fight monsters.
- Combat mechanics involve attacking, dodging, and managing health and inventory.
- Players win by defeating the dragon and lose if their health reaches zero.
- An Easter egg feature allows players to play a mini-game for extra rewards.

## Gameplay Instructions

- Click buttons to interact with the game.
- Read the text to understand the current situation.
- Make strategic decisions to progress through the game and achieve victory.

## Notes

- Ensure all HTML elements are properly linked and accessible for the game to run smoothly.
- The game logic and UI interactions are handled through JavaScript functions and event listeners.

