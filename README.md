# Project Documentation

## Overview
This project includes detailed system architecture diagrams created with PlantUML. Follow the instructions below to set up your environment and view the diagrams.

## Prerequisites
Ensure you have the following installed on your system:
- Java (required for PlantUML)
- Visual Studio Code (VSCode)
- Graphviz (required for rendering PlantUML diagrams)

## Installation Instructions

### Step 1: Install Java
If you do not have Java installed, you can download and install it from the [official website](https://www.java.com/en/download/).

### Step 2: Install Graphviz
Download and install Graphviz from the [official website](https://graphviz.org/download/).

### Step 3: Set Up PlantUML in Visual Studio Code

1. **Install PlantUML Extension:**
   - Open Visual Studio Code.
   - Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
   - Search for "PlantUML" and click Install on the PlantUML extension.

2. **Configure PlantUML:**
   - Ensure that Visual Studio Code recognizes the Graphviz installation. You might need to set the path to the Graphviz dot executable. Add the following settings to your `settings.json` file (found in `.vscode` folder or by searching "settings.json" in VSCode):
     ```json
     "plantuml.java": "C:\\path\\to\\java.exe",
     "plantuml.dot": "C:\\path\\to\\dot.exe"
     ```
   - Replace `C:\\path\\to\\java.exe` and `C:\\path\\to\\dot.exe` with the actual paths to your Java and Graphviz dot executables.

### Step 4: Viewing Diagrams

1. **Open the PlantUML File:**
   - Open the desired `.puml` file in Visual Studio Code.

2. **Render the Diagram:**
   - Press `Alt+D` to render the diagram in the PlantUML preview window. Alternatively, you can right-click on the file and select "PlantUML: Preview Current Diagram."


---

If you have any questions  please contact the project me: mugao.dev@gmail.com/ +254743552330 on whatsapp.

Happy diagramming!
