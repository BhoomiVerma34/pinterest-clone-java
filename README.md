# pinterest-clone-java 
# Pinterest Clone Java

This is a simple **Pinterest Clone** built in **Java**. The project is designed for beginners to understand how a social image-sharing platform works. It uses basic Java classes and in-memory data structures.

## Features

* Add Users
* Add Pins (Images)
* Show all Users
* Show all Pins (Pinterest-style feed)
* Simple login system
* Comment on pins
* Like pins

## Project Structure

```
Main.java          // Entry point
Server.java        // Mock server
Router.java        // Routes
Database.java      // In-memory database
User.java          // User model
Pin.java           // Pin model
PinController.java // Manage pins
UserController.java // Manage users
MainMenu.java      // CLI menu for testing
ImageService.java  // Validate image URLs
Auth.java          // Simple login
Feed.java          // Show all pins feed
Comment.java       // Comment on pins
Like.java          // Like pins
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/pinterest-clone-java.git
```

2. Open the project in **VS Code**, **IntelliJ**, or **any Java IDE**.

3. Compile and run **MainMenu.java** to test the application:

```bash
javac *.java
java MainMenu
```

4. Use the menu to add users, pins, comments, and likes.

## Notes

* This is a beginner-friendly project using **in-memory storage** (no database).
* Image URLs are just strings; no real image upload.
* You can expand this project with **file storage**, **database integration**, or **GUI**.

## License

This project is open-source. Feel free to use and modify it.
