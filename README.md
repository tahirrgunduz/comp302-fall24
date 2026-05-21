

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




---

## 🕹️ Features

### 1. Main Menu
* **Start Game:** Launch the dynamic gameplay screen instantly.
* **Load Game:** Resume your adventure from where you left off using state persistence.
* **Help:** View clear, detailed instructions on game mechanics and controls.
* **Exit:** Securely close the application.

### 2. Gameplay & Mechanics
* **Player Movement:** Responsive grid-based navigation using arrow keys.
* **Autonomous Monsters:** Dynamic enemy entities equipped with unique behaviors and AI movement logic.
* **Interactive Items:** Collectible objects scattered throughout the dungeon to assist player progression.
* **Game State Control:** Pause and resume the game seamlessly at any point via dedicated UI buttons.

### 3. Help & Game Over Screens
* **Help Menu:** Comprehensive guide detailing control layouts and core objectives, with smooth navigation back to the Main Menu.
* **Game Over Screen:** Triggers dynamically when the countdown timer reaches zero or the player depletes all available lives.

---

## 🛠️ Tech Stack

* **Language:** Java 8+
* **Framework/Library:** Java Swing / AWT
* **Design Patterns:** Strategy Pattern
* **Persistence:** Java Serialization

---

## ⚙️ Installation & Setup

### Prerequisites
* **Java:** JDK 17 or higher installed.
* **IDE/Environment:** IntelliJ IDEA, Eclipse, or VS Code.

---

### Steps
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/tahirrgunduz/comp302-fall24.git](https://github.com/tahirrgunduz/comp302-fall24.git)
   cd comp302-fall24
2. Open the project folder in your preferred IDE.
3. Build and run the application using the Main.java class as the entry point.


---

## 📂 Project Structure

```text
src/main/java/org/firstgame
├── assets          # Visual assets, textures, and custom fonts
├── entities        # Core game entities (Player, Monsters, Items)
├── properties      # Utility classes managing constants and configuration properties
├── ui              # GUI components (GameWindow, MainMenu, HelpMenu)
└── Main.java       # Application entry point
```

---

## ⌨️ Controls

<b>Arrow Keys :</b> Move the player character up, down, left, or right.

<b>Pause Button :</b> Halt game progression and freeze entity updates.

<b>Resume Button:</b> Continue the gameplay from the paused state.




👥 Contributors

Tahir Gündüz - Junior Computer Engineer Student
Anıl Kaan Topçu - Junior Computer Engineer Student
Ferhat Tekin - Junior Computer Engineer Student




