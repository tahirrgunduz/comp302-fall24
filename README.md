

# Rogue-Like Dungeon Adventure Game - COMP302_project-fall24

A 2D procedural dungeon crawler game built with Java, focusing on software architecture patterns, dynamic gameplay mechanics, and object-oriented design.



<table align="center">
  <tr>
    <td><img src="https://github.com/user-attachments/assets/22e30f88-f75b-49e2-8bac-b3e625154a49" style="width:420px; height:265px; object-fit:cover;" alt="Game Menu"/></td>
    <td><img src="https://github.com/user-attachments/assets/b1bef9f9-bd5e-4784-b186-d1400a683fd8" style="width:420px; height:265px; object-fit:cover;" alt="Gameplay 1"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/9254515a-e256-425e-a6e7-295dc0eab891" style="width:420px; height:265px; object-fit:cover;" alt="Gameplay 2"/></td>
    <td><img src="https://github.com/user-attachments/assets/a82b68c6-d0f9-4496-bb92-a3b2a9a1b2f1" style="width:420px; height:265px; object-fit:cover;" alt="Gameplay 3"/></td>
  </tr>
</table>



## Key Features & Architecture
* **Design Patterns:** Implemented the **Strategy Design Pattern** to manage diverse monster behaviors and dynamic movement algorithms.
* **Game State Persistence:** Utilized **Java Serialization** to allow players to seamlessly save and load their progress.
* **Interactive GUI:** Developed an interactive 2D user interface with real-time grid rendering, inventory systems, and smooth movement handling.
* **Core Mechanics:** Features autonomous enemy AI, item collection systems, and dynamic grid-based movement.


### Features


1. Main Menu

Start Game: Launch the game and transition to the gameplay screen.

Help: View instructions on how to play the game.

Exit: Close the application.



2. Gameplay

Player Movement: Use arrow keys to navigate the player character.

Monsters: Dynamic enemy characters with unique behaviors.

Items: Collectible objects to help the player progress.

Pause/Resume: Pause and resume the game using dedicated buttons.

3. Help Menu

Detailed instructions on game controls and objectives.

Navigation back to the Main Menu.

4. Game Over Screen

Displays when the player fails to complete the game within the allotted time or loses all lives.









Installation

Prerequisites

Java 17 or higher: Ensure you have Java Development Kit (JDK) installed.

IDE or Command-Line Tool: Recommended IDEs include IntelliJ IDEA, Eclipse, or VS Code.

Steps

Clone the repository or download the project zip file.

Open the project in your preferred IDE.

Build and run the project using the Main class as the entry point.



# Clone the repository
git clone https://github.com/your-repo/rokue-like-game.git
cd rokue-like-game

# Run the project (if using command line)
javac -d bin src/**/*.java
java -cp bin org.firstgame.Main










Project Structure


src/main/java/org/firstgame
├── assets            # Contains game assets such as images and fonts
├── entities          # Defines game objects like Player, Monsters, and Items
├── properties        # Utility classes for game constants and properties
├── ui                # GUI components including GameWindow, MainMenu, and HelpMenu
└── Main.java         # Entry point of the application











Controls

Arrow Keys: Move the player character.

Pause Button: Pause the game.

Resume Button: Resume the game.






Development

Technologies Used

Java: Primary programming language.

Swing: For GUI design.

AWT: For graphics rendering.

Maven/Gradle (optional): For project build and dependency management.

Key Concepts Implemented

Object-Oriented Programming (OOP)

Design Patterns (Singleton, Factory, etc.)

Model-View Separation Principle







Contribution Guidelines

Fork the repository and create a feature branch.

Make your changes and write clear commit messages.

Submit a pull request with a detailed description of your changes.




