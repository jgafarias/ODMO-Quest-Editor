# XML Quest Editor

This is a quest editor for XML files. It provides a graphical interface to view, edit, and manage quest data simply and intuitively, making it ideal for projects that use the `Quest.xml` structure.

The editor is designed to be lightweight and efficient, simplifying the management of game content in the `Quest.xml` file.

# Demo

https://github.com/user-attachments/assets/59574f58-25fa-4960-a39f-4f48d9e065b1

---

## Features

* **Visual Editing:** Modify fields such as Title, Body, Level, and quest rewards directly within the interface.
* **Dynamic Reward Management:** Flexibly add, edit, or remove rewards, including EXP, Bits (money), and items.
* **Quick Search:** Find quests easily using the search bar, filtering by ID or Title.
* **Pagination:** Navigate through large lists of quests in an organized manner, with 50 quests per page.
* **Save Changes:** Modifications are first saved to the application's memory and can then be written to the `Quest.xml` file with a single click.
* **Quest Deletion:** Remove unwanted quests directly from the user interface.
* **Modern Interface:** The editor uses a dark theme and a clean design, providing a pleasant user experience.

---

## How to Use

1.  After using the **BIN - XML CONVERTER**, take the `Quest.XML` file and place it in the `XML` folder of the Quest Editor.
2.  Run `Quest Editor.exe`.
3.  Modify the desired quest. Click the green icon to save the changes (the quest will close) and then save the XML file using the yellow button at the top.
4.  Take the `Quest.XML` file and convert it to a `.bin` file using the **BIN - XML CONVERTER**. Use the **DB Importer** to save the changes to the database.
5.  Generate the new `Pack 03` and place it in the `data` folder of the client you are using.
