# Virtual-Piano
Piano Application implemented in Java, utilizing Java Sound API and MiDi Library for enhanced musical experience.
You can use this application to play, record, and explore various tunes on a virtual piano.

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
   git clone https://github.com/yourusername/your-repo.git](https://github.com/Inzamam20/Virtual-Piano.git)](https://github.com/Inzamam20/Virtual-Piano.git

2. Update the mySettings.java file:
     * Set the absolute path for the logo.png file located inside the resources/images directory.

3. Database Configuration:
     * Use MySQL Workbench to import and sync the database. You can find the database file in the **`libs/Database`** folder as **`Piano_Application.sql`**.
     * Alternatively, create a piano_application schema and create the necessary tables by following the SQL file in your own database.

4. Update the database connection settings:
     * Open the **`SQL.java`** file and update the database username, password, URL, and class names according to your database configuration.
