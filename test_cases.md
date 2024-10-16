# Test Cases for To-Do List Application

## Test Case 1: Add a New Task
- **Test Case ID**: TC001
- **Test Objective**: Verify that a user can successfully add a new task.
- **Precondition**: The application is open, and the "to-do" input field is empty.
- **Test Steps**:
  1. Navigate to the "to-do" input field.
  2. Enter the task name **"Buy groceries"**.
  3. Press the "Enter" key.
- **Expected Result**: The task "Buy groceries" is added to the list, and the input field is cleared.
- **Actual Result**: The task was successfully added, and the input field cleared.
- **Status**: Pass

## Test Case 2: Mark a Task as Completed
- **Test Case ID**: TC002
- **Test Objective**: Verify that a user can mark a task as completed.
- **Precondition**: There is at least one task in the to-do list.
- **Test Steps**:
  1. Navigate to the list of tasks.
  2. Check the checkbox next to **"Buy groceries"**.
- **Expected Result**: The task is marked as completed (should show a strike-through).
- **Actual Result**: The task was successfully marked as completed with a strike-through.
- **Status**: Pass

## Test Case 3: Delete a Task
- **Test Case ID**: TC003
- **Test Objective**: Verify that a user can delete a task from the list.
- **Precondition**: There is at least one task in the to-do list.
- **Test Steps**:
  1. Navigate to the list of tasks.
  2. Click the **"Delete"** button (or icon) next to **"Buy groceries"**.
- **Expected Result**: The task is removed from the list.
- **Actual Result**: The task was successfully deleted from the list.
- **Status**: Pass

## Test Case 4: Edit a Task
- **Test Case ID**: TC004
- **Test Objective**: Verify that a user can edit an existing task.
- **Precondition**: There is at least one task in the to-do list.
- **Test Steps**:
  1. Navigate to the task **"Buy groceries"**.
  2. Double-click on the task name.
  3. Change the task name to **"Buy groceries and fruits"** and press "Enter."
- **Expected Result**: The task name is updated in the list.
- **Actual Result**: The task name was successfully updated to "Buy groceries and fruits."
- **Status**: Pass

## Test Case 5: Filter Tasks by Status
- **Test Case ID**: TC005
- **Test Objective**: Verify that the filtering options (all, active, completed) work correctly.
- **Precondition**: There are tasks with different statuses in the list.
- **Test Steps**:
  1. Navigate to the filter options (All, Active, Completed).
  2. Select "Active."
  3. Verify that only active tasks are displayed.
  4. Select "Completed."
  5. Verify that only completed tasks are displayed.
  6. Select "All."
- **Expected Result**: The list updates to show tasks based on the selected filter.
- **Actual Result**: The filter options worked as expected, showing tasks based on the selection.
- **Status**: Pass
