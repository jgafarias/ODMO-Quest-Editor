# XML Quest Editor

This is an XML quest editor created with the Flet library. It offers a graphical interface to view, edit, and manage quest data in a simple and intuitive way, making it ideal for projects that use the `Quest.xml` file structure.

The editor is designed to be lightweight and efficient, simplifying the management of game content in the `Quest.xml` file.

[🔗 View video demonstration](https://github.com/user-attachments/assets/59574f58-25fa-4960-a39f-4f48d9e065b1)

---

## Features

* **Visual Editing:** Modify fields such as Title, Body, Level, NPC ID, quest type, and define goals, rewards, and conditions directly within the interface.
* **Dynamic Management:** Flexibly add, edit, or remove rewards (such as EXP, Bits, and items) and goals.
* **Automatic Folder Creation:** Upon startup, the editor checks if the `XML` folder exists and creates it automatically if necessary, preventing file not found errors.
* **Quick Search:** Find quests easily using the search bar, filtering by ID or Title.
* **Pagination:** Navigate through large lists of quests in an organized manner, with 50 quests per page.
* **Save Changes:** Modifications to a single quest are first saved to the application's memory by clicking the green save icon. Then, all changes can be written to the `Quest.xml` file with a single click of the "Save XML" button.
* **Quest Deletion:** Remove unwanted quests directly from the user interface.
* **Modern Interface:** The editor uses a dark theme and a clean design, providing a pleasant user experience.

---

## How to Use

1.  After using the **BIN - XML CONVERTER**, take the `Quest.XML` file and place it in the Quest Editor's `XML` folder. If the folder does not exist, it will be created automatically upon running the editor.
2.  Run `Quest Editor.exe`.
3.  Modify the desired quest. Click the green "Save Changes" icon to save the quest's changes to memory, and then click the "Save XML" button at the top to save all memory changes to the `Quest.xml` file.
4.  Take the modified `Quest.XML` file and convert it to a `.bin` file using the **BIN - XML CONVERTER**. Use the **DB Importer** to save the changes to the database.
5.  Generate the new `Pack 03` and place it in the `data` folder of the client you are using.
