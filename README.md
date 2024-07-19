# Media Player Project

This project is a simple media player application developed using JavaFX. The media player supports various media formats and offers a user-friendly interface for playing, pausing, and managing media files.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features

- Play audio and video files.
- Pause and resume playback.
- Simple and intuitive user interface.
- Support for multiple media formats.
- Volume control.
- Progress bar to track media playback.

## Requirements

- Java Development Kit (JDK) 11 or higher.
- JavaFX SDK.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Abdelaziz79/media-player.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd media-player
   ```

3. **Download and install JavaFX SDK:**

   Follow the instructions on the [JavaFX official website](https://openjfx.io/) to download and set up JavaFX.

4. **Set up your IDE:**

   If you are using an IDE like IntelliJ IDEA or Eclipse, configure it to use the JavaFX SDK. Refer to your IDE's documentation for detailed setup instructions.

## Usage

1. **Run the application:**

   You can run the application from your IDE by running the `Main` class located in the `src/mediaplayer` directory.

   Alternatively, you can compile and run the application from the command line:

   ```sh
   javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml src/mediaplayer/Main.java
   java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml mediaplayer.Main
   ```

2. **Load and play media files:**

   Use the interface to open media files and control playback.

## Project Structure

```
media-player/
├── src/
│   └── mediaplayer/
│       ├── MediaPlayer.java
│       ├── FXMLDocument.fxml
│       ├── FXMLDocumentController.java
│       
├── README.md
└── ...
```

- `MediaPlayer.java`: The main entry point of the application.
