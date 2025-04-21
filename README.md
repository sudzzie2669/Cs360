# Cs360
App Summary
The mobile app I developed was designed to help users manage and track data in a convenient, user-friendly way. The core goal was to allow users to log in, view and manage items in a database, and receive SMS notifications for specific triggers like low inventory or important updates. This app was created with user-centered design in mind, focusing on simplicity, ease of use, and accessibility.

Screens and Features
To meet user needs, I implemented three main screens: a login screen, a data display screen, and an SMS permissions/notification screen.

The login screen included input fields for username and password, a "Log In" button, and a "Create Account" button for new users.

The data display screen featured a table layout to view data, a button to add new entries, and individual delete buttons to remove rows.

The SMS notification screen prompted the user for SMS permissions and handled notifications based on data conditions.

Each screen was designed with usability in mind—clear layouts, intuitive flow, proper grouping, and feedback cues like Toast messages. I also followed Android’s material design guidelines to ensure a familiar and effective UI experience.

Development Approach
I approached the development process by first laying out the XML UI components for each screen, then building the Java logic to support functionality. I used modular coding techniques like separating database operations into a DatabaseHelper class and using built-in Android features (like SmsManager, Toast, and TableLayout) to keep the code organized and maintainable. These strategies made debugging and future updates much easier.

Testing and Functionality
I tested each feature individually—starting with login validation, then database CRUD operations, and finally SMS functionality. I used emulator testing for basic UI flow and SMS permissions. This step was crucial in identifying issues like missing imports, manifest permissions, and runtime errors. Testing helped ensure my code worked as expected and that users wouldn’t encounter broken or confusing behavior.

Challenges and Innovation
One major challenge I faced was dynamically updating the table view in the data screen. I had to research and test different ways to create rows programmatically and bind delete functions to each one. I overcame this by iterating through data from the SQLite database and adding views with listeners at runtime, which improved the app's interactivity.

Areas of Success
I was particularly successful in integrating the database and SMS functionality with the UI. It showed my ability to connect different components—UI, backend, and device features—into a cohesive app. This project helped me strengthen my knowledge of Android Studio, Java, SQLite, and real-world mobile app development.
