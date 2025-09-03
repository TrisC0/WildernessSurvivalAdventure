# Wilderness Survival Adventure

## About The Game
Wilderness Survival Adventure is a retro-style, top-down 2D survival game built entirely in a single HTML file with JavaScript and Tailwind CSS.

You play as a researcher whose plane has crashed in an uncharted, procedurally generated wilderness. With your radio broken, your only hope for rescue is to find and reactivate three ancient monoliths scattered across the land, which are rumored to emit a powerful energy signal.

Explore a vast, randomly generated world, gather resources, craft essential tools, hunt for food, and survive the dangers of the wild, especially after the sun goes down.

## Features

### Core Gameplay
- **Infinite Replayability**: The world is procedurally generated with a random, natural shape and a surrounding mountain range for every new game.
- **Dynamic Day/Night Cycle**: The world changes as time passes. Nights are more dangerous, with an increased number of aggressive animals, but they also bring unique resources like the glowing Moonpetal Flower.
- **Deep Survival Mechanics**: Manage your Health, Hunger, and Energy. You'll need to find food, cook it, and rest to stay alive.
- **Robust Crafting System**: Gather wood and stone to craft essential tools like axes and pickaxes, a sword for defense, and survival items like campfires and tents.
- **Engaging Storyline**: Embark on a quest to find and activate three mysterious monoliths by providing them with rare offerings. Your survival depends on it!

### Combat & Survival
- **Combat System**: Defend yourself from aggressive wolves. Craft a sword to fight back more effectively.
- **Hunting & Cooking**: Hunt wolves for raw meat, then cook it over a campfire for a substantial meal that restores both health and hunger.
- **Wildlife Hunting**: Hunt rabbits (1 meat, 5 XP), deer (3 meat, 15 XP), and squirrels (1 meat, 3 XP) for food and experience points. Animals will flee when you approach, making hunting a challenge!
- **Resource Gathering**: Chop down trees, mine rocks, forage for berries, and discover rare items like Ancient Gems.

### New Features (Latest Update)
- **Interactive Wizard NPC**: A mysterious wizard appears on the map who provides quest hints and occasionally gifts you precious gems. Interact with them using the spacebar when standing in front of them.
- **Mini Map System**: A comprehensive 200x200 pixel mini map showing your location, the wizard, wolves, monoliths, and terrain. Click anywhere on the mini map to navigate quickly.
- **Speech Bubble System**: The wizard calls out to you when you're nearby with engaging messages like "Come here, young one!" and "The ancient secrets await!"
- **Gameplay Message Overlay**: Real-time message display at the bottom of the screen showing your recent actions, combat results, and quest updates with smooth fade effects.
- **Enhanced UI**: Improved log system that expands to fill available space, better organized crafting tabs, and more intuitive controls.
- **Huntable Animals**: New wildlife including rabbits, deer, and squirrels that can be hunted for food and XP. Each animal has unique behaviors and provides different rewards.
- **XP & Leveling System**: Gain experience points by hunting animals and level up to track your progress as a wilderness survivor.

## How to Play

### Controls
- **Movement**: Use the WASD or Arrow Keys to move your character.
- **Interact / Attack**: Press the Spacebar to interact with the object you are facing (e.g., chop a tree, mine a rock, pick a flower, attack an animal, or speak with the wizard).
- **Mini Map Navigation**: Click anywhere on the mini map to quickly move the camera to that location.

### Getting Started
1. **Gather Resources**: Your first priority is to gather wood by facing a tree and pressing the spacebar.
2. **Crafting**: Use the Actions Panel on the left to navigate to the "Craft" tab.
3. **Essential Tools**: Craft a Wooden Axe and Wooden Pickaxe to gather resources more efficiently.
4. **Defense**: Craft a Wooden Sword to defend yourself from wolves.
5. **Survival Setup**: Build a Campfire before nightfall (20:00) to keep aggressive animals at bay. You can also cook meat on it.
6. **Rest**: Build a Tent to sleep through the dangerous nights and restore health and energy.
7. **Find the Wizard**: Look for the wizard NPC (blue dot on mini map) who can provide quest hints and gifts.

### Objective
Your main goal is to find and activate the three monoliths. Each monolith requires a specific offering:

- **5 Ancient Gems**: Found randomly when mining stone.
- **5 Moonpetals**: Flowers that only bloom at night.
- **1 Carved Stone**: A special item crafted from 50 stone.

**Pro Tip**: The wizard NPC can provide helpful hints about these requirements and occasionally gift you gems!

Explore the world, gather the necessary items, and bring them to the monoliths to win the game!

## How to Run
This game is self-contained in the `index.html` file. Simply download it and open it in any modern web browser to play. No server or setup is required.

## Game Features Overview

### UI Elements
- **Inventory Panel**: Top bar showing all collected resources
- **Actions Panel**: Left sidebar with crafting and food action tabs
- **Mini Map**: Interactive map showing world overview and NPC locations
- **Message Log**: Scrollable log of all game events
- **Gameplay Messages**: Real-time overlay showing recent actions
- **Stats Panel**: Bottom bar displaying health, hunger, and energy bars

### World Features
- **Procedural Generation**: Unique world layout every game
- **Dynamic Weather**: Day/night cycle affecting gameplay
- **Resource Spawning**: Trees, rocks, and berries regenerate over time
- **Animal AI**: Wolves with realistic hunting and fleeing behaviors
- **Interactive NPCs**: Wizard with quest guidance and rewards

### Technical Features
- **Pixel Art Graphics**: Retro-style visual design
- **Smooth Animations**: Character movement and tool usage animations
- **Responsive Design**: Works on desktop and mobile devices
- **Performance Optimized**: Efficient rendering and game loop
- **Cross-Platform**: Runs in any modern web browser
