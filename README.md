# CodeFellas
# Study Space Management System

A JavaFX-based  Study Space Management System where users can search for available spaces, book spaces, and pay for spaces. Admin manages space and booking details.

## Built with:

•	JavaFX

•	MySQL

•	Scene Builder


## Installation

1. Clone the repository into your local machine
    
    ```bash
    git clone git@github.com:BhawnaBassarmalani/CodeFellas.git
    ```

2. Download [JavaFX SDK](https://gluonhq.com/products/javafx/) and [MySQL](https://dev.mysql.com/downloads/installer/)

3. Configure MySQL and open MySQL Workbench. Import the database 'space'
>**space.sql** file as well as the **mysql connector jar** file can be found in the lib_db folder.
4. Open the project in IDE (Eclipse). Go to File -> Open Projects from File System-> Import Source and sellect your project from directory.

5. Then go to File -> Properties -> Libraries->ModulePath -> add the JavaFX SDK as a library to the project.  Also add the MySQL connector jar file to the project.

6. Add VM options.  click on Run -> Edit Configurations and add these VM options `--module-path "path to your javafx sdk lib folder eg. \path\to\javafx-sdk-17.0.1\lib" --add-modules javafx.controls,javafx.fxml`
7. Run the application (Main.java)

For more details and other IDE options, please refer to [this site](https://openjfx.io/openjfx-docs/).




## UI Screenshots

