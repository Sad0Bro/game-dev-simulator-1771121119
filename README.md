# Game Dev Simulator
## Description
Game Dev Simulator is a game that simulates the game development process, allowing players to experience the challenges and rewards of creating their own games. The game is built using C# and provides a realistic simulation of the game development cycle, from concept to launch.

## Features
* Simulate game development projects with varying complexities and deadlines
* Manage team members with unique skills and strengths
* Balance budget and resources to ensure project success
* Make key decisions that impact the game's quality, timeline, and budget
* Analyze metrics and feedback to improve future projects

## Tech Stack
* Programming Language: C# (.NET 6.0)
* Game Engine: Unity (2022.1.0f1)
* Database: SQLite (for storing game data and metrics)

## Installation Instructions
To run the Game Dev Simulator, follow these steps:
1. Install the .NET 6.0 SDK from the official Microsoft website
2. Install Unity Hub and add the 2022.1.0f1 version to your installation
3. Clone the repository using `git clone https://github.com/your-username/GameDevSimulator.git`
4. Open the project in Visual Studio and restore NuGet packages
5. Build and run the project using `dotnet run` or the Unity editor

## Usage Examples
To start a new game, simply run the project and follow the in-game tutorial. You can also load a saved game by selecting the "Load Game" option from the main menu.

Example code snippet for creating a new game project:
```csharp
GameProject project = new GameProject("My Game", 100000, 6);
project.TeamMembers.Add(new TeamMember("John Doe", "Designer", 80));
project.Tasks.Add(new Task("Design Game Concept", 5, 1000));
```

## Project Structure
The project is organized into the following folders:
* `GameDevSimulator`: The main project folder
* `Assets`: Unity assets, including 3D models, textures, and audio files
* `Data`: SQLite database files and schema
* `GameLogic`: C# code for game logic, including project management and simulation
* `UI`: Unity UI components and scripts

## Configuration
To configure the game settings, edit the `appsettings.json` file in the `GameDevSimulator` folder. You can adjust settings such as game speed, difficulty level, and starting budget.

## Testing Instructions
To run unit tests, use the `dotnet test` command in the terminal. To run integration tests, use the Unity test runner.

## Future Improvements
* Implement a multiplayer mode for competing against other players
* Add more complex game mechanics, such as market trends and player feedback
* Improve the game's UI and user experience

## Contributing Guidelines
To contribute to the Game Dev Simulator, follow these steps:
1. Fork the repository and create a new branch
2. Make changes and commit them with a descriptive commit message
3. Open a pull request against the main branch
4. Ensure your code follows the project's coding standards and is thoroughly tested

## License
The Game Dev Simulator is licensed under the MIT License. See the LICENSE file for more information.