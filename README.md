# Event-Manager
✨Description
The Event Manager is a desktop application built with Java Swing that allows users to create, edit, delete, search, and manage university events.  It provides a clean, user‑friendly interface with styled panels and buttons, making event management simple and intuitive. Events are stored in a text file for persistence.

✨Technologies Used
- Java SE (Core language features, OOP principles)
- Java Swing (GUI components, layouts, event handling)
- AWT (Colours, fonts, borders, layouts)
- File I/O (BufferedReader, PrintWriter for saving/loading events)
- Java Time API (LocalDate, DateTimeFormatter for date handling)

✨Features
- Add new events with name, date, and description
- Edit existing events directly from the list
- Delete events with confirmation prompts
- Search events by date (YYYY‑MM‑DD format)
- Persistent storage in events.txt
- Styled UI with custom borders, colours, and fonts
- Auto‑generated unique event IDs for tracking

✨How it was built
- Designed the Event class to encapsulate event details (name, date, description, ID).
- Implemented EventManager GUI using Swing components (JFrame, JPanel, JList, JTextField, JTextArea).
- Added event handling with ActionListener and ListSelectionListener.
- Integrated file persistence to save and load events from events.txt.
- Applied refactoring for cleaner code (e.g., using enum for dayparts, structured borders, reusable button creation).
- Focused on user experience with styled panels, consistent fonts, and intuitive layout.

✨What I learned
- How to build a desktop GUI application with Java Swing.
- Best practices for event handling and state management in GUIs.
- Importance of data persistence and handling file I/O safely.
- Using Java Time API for reliable date parsing and formatting.
- Refactoring for maintainability (e.g., avoiding string inconsistencies with enums).
- Designing a user‑friendly interface with layout managers and custom styling.

✨How to run project 
- Clone the repository
- Compile the project
- Run the application -> java PrimeProgrammers.kmhnp.EventManager
- Add, edit, delete, and search events directly from the GUI. Events will be saved in events.txt

✨Live Video
https://github.com/user-attachments/assets/d0485d15-1243-440e-86be-e2768dab5271



