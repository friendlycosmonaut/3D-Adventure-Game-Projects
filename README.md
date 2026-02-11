# Make a 3D Adventure Game with Godot
A collection of demo projects for the [Make a 3D Adventure Game with Godot](https://www.youtube.com/playlist?list=PLSFMekK0JFgxQPVPf-w9Bh4JQQz-Vyydr) tutorial series by [FriendlyCosmonaut](https://www.youtube.com/c/FriendlyCosmonaut), created using the [Godot](https://godotengine.org/) game engine. 

<img width="1543" height="916" alt="image" src="https://github.com/user-attachments/assets/7889ac88-aa99-4d84-9c66-f6fe7b9e7c20" />

## I'm watching a tutorial - what should I download?

The easiest way is to scroll to the top of the page, click on the green `<>Code` button. A pop up will appear - click `Download Zip`. This will download ALL the project files. After it downloads, unzip the files. Open the folder and find the tutorial you're looking for - it will match the title of the video. 

> Note: Unfortunately, if you wanted just ONE of the project files, there is no built-in way to download *part* of a GitHub repository. However, you *can* copy the folder link and paste it into [this website](https://download-directory.github.io/) to download the isolated tutorial demo project. 

Hopefully you have some files downloaded now! 

Assuming you have [Godot](https://godotengine.org/) installed, you should be able to double click on the project file `project.godot`. Otherwise, you can open Godot, click Import, and then navigate to the folder destination.

Once the project has loaded, feel free to poke around!

## Navigating the project
Remember, not ALL projects will contain these objects, depending on what tutorial you are watching/downloading. Some of the important ones are:
- `world.tscn` is the main level/scene of the demo.
- `Player.tscn` and `player.gd`, containing the player's movement, states and logic.
- `Character.tscn` and `character.gd`, containing character logic.
- `Interactable.tscn` and `interactable.gd`, containing logic for interactables.
- `Game.gd` containing high-level game logic.
- `camera.gd` containing third person camera logic.
- `pause.tscn` containing the four UI menu tabs: home, quests, inventory, settings.
- `example_balloon.tscn` and `example_balloon.gd` containing text logic.

<img width="2255" height="1503" alt="screenshot" src="https://github.com/user-attachments/assets/7ade8e30-ca54-4ce0-a8d9-d46037566963" />

## Tutorial series features
Across the series, we will be implementing the following features: 
- **Player controller** with a configurable moveset capable of grounded locomotion/walking, flying, and hovering.
- **Third person camera**; the length of the spring arm and FOV can be configured.
- **Interactable objects** in the form of flowers (that will bloom) and characters (that face and talk to you).
- **Character/NPC class** with their own names/dialogue/models.
- **Dialogue** using the [Dialogic](https://github.com/dialogic-godot/dialogic) plugin, with a customised "balloon" (the UI font/speech bubble), and Undertale-like gibberish/beep voices
- **Quests** which can be referenced/reacted to eg. in Dialogue (get a Character to say something different if you have started/progressed/finished a quest).
- **Terrain** using the [Terrain3D](https://github.com/TokisanGames/Terrain3D) plugin.
- **Save and Load** scripts which can save/load data (in the form of Dictionaries) to disk as .json files.
- **Pause menu** containing tabs: Quests, Inventory, and Settings (NOTE: only the Quests tab is hooked up to game data, the others do not change in-game settings).
- **Free assets** from a range of creators, including character models/animations, terrain textures, and UI elements (see CREDITS.md for a full list).

## When will the series be finished / where is the finished demo project?

I will continue updating the project while tutorials are released, the last of which is likely several months away. I am also planning to continue working on the overall project afterwards to add any further ideas and issues/requests that arise. 

The up-to-date repository is currently **private** due to its instability and constant updates - if you would like access anyway, and to support development, you can do so via my [Patreon](https://www.patreon.com/c/FriendlyCosmonaut). Otherwise, towards the very tail end of the tutorial series, I will make the finished demo repository **public** and accessible to everyone. 

## Credits and License

I very much encourage you to peruse the project at your leisure! The contents are licensed under the [MIT License](https://github.com/friendlycosmonaut/3d-adventure-game-with-godot). That means you're very welcome to use its contents for anything you like, including commercially.

Note that this project uses free assets from a variety of creators; please refer to [CREDITS.md](https://github.com/friendlycosmonaut/3d-adventure-game-with-godot/blob/main/LICENSE) for a comprehensive list and links. If you make use of any of their assets, please ensure you give credit and adhere to their licenses.
