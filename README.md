# Task-Manager
A JavaFX-based task scheduler app with save/load functionality.

## Features

Add tasks with:
- **Title**
- **Deadline** (number)
- **Priority** (1 = High, 2 = Medium, 3 = Low)

- Save your tasks to a file for later use.  
- Load tasks from a file to continue where you left off.  
- Simple, intuitive JavaFX user interface.

## Screenshots:
![image](https://github.com/user-attachments/assets/f3cc3665-1a8e-430c-82be-d5cb5718639b)
## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/ObaidullahDarwishi/Task-Manager.git
   cd Task-Manager

2. Compile the Java files (adjust src/ and bin/ to your folders):
   javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls -d bin src/*.java

3. Run the app:
   java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls -cp bin TaskAppGUI

4. Replace /path/to/javafx-sdk/lib with the actual path to your JavaFX SDK on your computer.

   For example, on Windows:
   C:/javafx-sdk-20/lib
   
