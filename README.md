# Godot 2D Platformer

Made by Brian Mohamad Safiudin


## What is it?
This project was created to gain experience in the C# Godot environment for the 2D Platform genre and to prove to myself that I can make a complete game. I hope in making this open source that others will also learn some things that I have learned.

The project will be considered complete when there is around 2 to 3 hours of fun and memorable content. Some of the major goals of the project include getting multiplayer to a playable state and making the code as flexible and as readable as possible.

## Roadmap
- Use Godot scenes instead of one big master node handling all scene nodes. This will allow for easier testing of inidivual scenes in the future.
- Wrap my head around the current codebase. Make the code look nicer. Make it less confusing to the reader.
- Figure out why "Load First Level" option is not working as intended. (First level is loaded but map screen is hiding the level)
- Tinker with the player movement more to get that more snappier platformer like feel.
- Introduce new water tiles.

## Project Setup
1. Install the latest Godot 4 C# release
2. Install [.NET SDK 6.0](https://dotnet.microsoft.com/en-us/download)
3. Install [.NET Framework 4.7.2](https://duckduckgo.com/?q=.net+framework+4.7.2)
4. In `Godot Editor > Editor Settings > Mono > Builds`: Make sure `Build Tool` is set to `dotnet CLI`

### Assets
- Most assets (art / audio) are under the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/) from [Open Game Art](https://opengameart.org/)
- Some of the audio is from [Mixkit](https://mixkit.co/free-sound-effects/game-over/) under the Mixkit license
- The networking library [ENet-CSharp](https://github.com/SoftwareGuy/ENet-CSharp) is under the [MIT license](https://github.com/SoftwareGuy/ENet-CSharp/blob/master/LICENSE)
