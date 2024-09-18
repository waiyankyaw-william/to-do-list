# To do List with Vanilla Javascript

This To Do List web application allows users to manage their tasks using a simple interface. Here's a brief description of the main features and functionalities:

1. **Adding Tasks**:

    - Users can type a task into the input field and click the "Add" button to add it to the to-do list.
    - Pressing "Enter" while typing in the input field also adds the task to the list.

2. **Displaying Tasks**:

    - Tasks are displayed in a list format. There are two sections: one for pending tasks and one for completed tasks.
    - Each task is displayed with options to edit, delete, or mark as complete.

3. **Editing Tasks**:

    - Users can click the edit icon (pencil) next to a task to modify its text. A prompt will appear allowing the user to enter the new text.
    - The edited task is updated in the list and stored in local storage.

4. **Deleting Tasks**:

    - Users can click the delete icon (trash can) next to a task to remove it from the list.
    - The task is removed from the DOM and also from local storage.

5. **Marking Tasks as Complete**:

    - Users can click the checkmark icon next to a task to mark it as complete.
    - Completed tasks move to the "done" section, which has a faded appearance to differentiate from pending tasks.
    - The task is updated in local storage to reflect its completed status.

6. **Clearing Completed Tasks**:

    - Users can click the "Clear" link in the navigation bar to remove all completed tasks from the "done" section.
    - The completed tasks are also removed from local storage.

7. **Task Counter**:

    - The number of pending tasks is displayed in a badge in the navigation bar.
    - This counter updates dynamically as tasks are added, edited, or deleted.

8. **Local Storage Integration**:
    - Tasks are saved in the browser's local storage, allowing them to persist across page reloads.
    - When the page loads, tasks are retrieved from local storage and displayed in their respective sections (pending or completed).

The UI includes Bootstrap for styling and FontAwesome for the icons, providing a clean and modern look to the application. This project is part of classs projects to apply the knowledge of Javascript in a real-world scenario.
