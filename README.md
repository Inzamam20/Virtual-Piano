# Virtual-Piano
Piano Application implemented in Java, utilizing Java Sound API and MiDi Library for enhanced musical experience.
You can use this application to play, record, and explore various tunes on a virtual piano.

## Features

- You can make your own account for saving your settings or play without account.
- The app features both a white mode and dark mode for eye relief.
- You can play using both mouse and keyboard.
- You can change the key bindings for each note.
- You play a mini-game and see your score at the end.
- You can setup a global chat using the database key api and talk with people using the same app.
- You can change your account password and preferences.
- You can type "hundred" on the menu to turn the piano into drums :D
- You can record your audio and set a predefined path where the audio file will be saved.
- There is a frequency tuner to emulate a full piano.
- You can play game where the instructions will be given to play a specific song.
- You can see your score and also the global score made by others.

## Getting Started

Follow these instructions to run the project on your local machine.

### Prerequisites

Before running the project, ensure you have the following set up:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) installed.
- JavaFX
- Scene Builder
- [MySQL Workbench](https://www.mysql.com/products/workbench/) (for database configuration).


### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Inzamam20/Virtual-Piano.git

2. Update the mySettings.java file:
     * Set the absolute path for the logo.png file located inside the resources/images directory.
     * Set the recording path to a directory of your choice, where you want to save your recorded tunes.

3. Database Configuration:
     * Use MySQL Workbench to import and sync the database. You can find the database file in the **`libs/Database`** folder as **`Piano_Application.sql`**.
     * Alternatively, create a piano_application schema and create the necessary tables by following the SQL file in your own database.

4. Update the database connection settings:
     * Open the **`SQL.java`** file and update the database username, password, URL, and class names according to your database configuration.


## Demo

Check out a short demo of the Virtual Piano:

[![Virtual Piano Demo](https://img.youtube.com/vi/JlSNM7Z-yx4/0.jpg)](https://youtu.be/JlSNM7Z-yx4)