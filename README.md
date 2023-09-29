# kanban-task-management-app

## Overview

Users should be able to:

- Adapt to the app's layout based on their device's screen size.
- Observe hover states for interactive page elements.
- Perform CRUD operations on boards and tasks.
- Receive validation feedback when creating/editing boards and tasks.
- Complete subtasks and transfer tasks between columns.
- Toggle the visibility of the board sidebar.
- Drag and drop tasks

Expected Behaviour:

- Boards
  - Selecting different boards in the sidebar switches to the chosen board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Accessing the "Edit Board" option in the dropdown menu opens the "Edit Board" modal for making changes.
  - Columns can be added or removed within the Add/Edit Board modals.
  - Deleting a board also removes its associated columns and tasks, requiring confirmation.

- Columns
  - Before adding tasks, a board must have at least one column. If there are no columns, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal for adding columns.
- Tasks
  - Adding a new task automatically places it at the bottom of the relevant column.
  - Updating a task's status moves it to the appropriate column.


### Built with

- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- Drag and Drop API
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

### Plans to improve this project: 

- Adding Typescript
- improving prettier config

