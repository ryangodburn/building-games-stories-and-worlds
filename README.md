# Building Games: Stories and Worlds

Coursework from **Building Games – Stories and Worlds** at the **University of New Haven**, Spring 2025 (third year, spring semester).

- **Author:** Ryan Godburn
- **Tools:** Twine 2 (Harlowe 3.3.9), Bitsy 8.13, HTML/CSS/JavaScript, Bambu Studio

## Projects

### Forsest Escape (`Making a Twine Game/`)

A short Twine interactive-fiction game (23 passages). You wake up in a forest at sunset with no memory of how you got there, and your choices decide whether you find your way out.

### Hollywood Hustling (`Hollywood Hustling/`)

A tabletop auction-and-bluffing game for up to four players, with two companion web pages and a 3D-printed QR code:

- `game website code/index.html`: the auction site. It explains the rules and reveals the movie props up for auction (15 of 20 per game), each with its film, point value, image and description. Players bid with play money placed face up (real) or face down (bluff), can call each other's bluffs, and earn bonus points for genre collections.
- `score website code/index.html`: a score tracker for points and prop ownership.
- `QR Code 3D Print.gcode`: Bambu Studio print file for a two-color 3D-printed QR code made for the game.

### The Curse of the Speedway 1000 (`The Curse of the Speedway 1000/`)

A Bitsy game set at the 3053 Speedway 1000, a jet-ship race with a deadly history. You line up on the grid, start the race, and the story ends one of two ways. Its sound effects (`sam.mp3` and `crash.mp3`) need to stay in the same folder as the `.html` file. The background music track isn't included in this repository, so the game plays without it.

### Journey to Yellowstone, final project (`BuildingGames_Final_Godburn/`)

A post-apocalyptic survival story in Twine (211 passages). You wake from a hibernation pod in the ruins of Eagar, Arizona, and set out for a sanctuary at Yellowstone. On the way you scavenge parts, fuel and supplies, and the items you collect (tracked with story variables) decide which paths open up.

- `game/index.html`: the playable game.
- `Journey to Yellowstone.twee`: the Twee source.
- `AI Images/`: the AI-generated scene images used in the game, grouped by section. The game loads its copies from an online image host, so it needs an internet connection to show them.

## Playing and editing

- Open any `.html` file in a web browser to play.
- To edit a Twine game, import the `.html` or `.twee` file into [Twine 2](https://twinery.org/) (Library → Import).
- To edit the Bitsy game, open it in the [Bitsy editor](https://bitsy.org/) and load the game data from the `.html` file.

---

*Archived coursework, shared as part of my portfolio. If you're taking this course now, please follow your instructor's academic integrity policy.*
