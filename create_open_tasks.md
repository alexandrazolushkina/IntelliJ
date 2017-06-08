# Creating Local Tasks and Opening Tracker Tasks

* [Creating Local Tasks](https://github.com/alexandrazolushkina/IntelliJ/blob/master/create_open_tasks.md#creating-local-tasks)
* [Opening Tracker Tasks](https://github.com/alexandrazolushkina/IntelliJ/blob/master/create_open_tasks.md#opening-tracker-tasks)
* [Viewing Closed Tasks](https://github.com/alexandrazolushkina/IntelliJ/blob/master/create_open_tasks.md#viewing-closed-tasks)
* [Opening a Task for the First Time](https://github.com/alexandrazolushkina/IntelliJ/blob/master/create_open_tasks.md#opening-a-task-for-the-first-time)
***
## Creating Local Tasks

In IntelliJ IDEA, you can create local tasks that are not displayed in your issue tracker.
To create local tasks:
1. Open the **Open Task** dialog: 
* From the main menu, select **Tools** > **Tasks & Contexts** > **Open Task**
* Press `Shift+Alt+N`
* Click the tasks combo on the main toolbar
2. In the **Enter task** name pop-up window, choose **Create New Task**, or just type a task name. 

In the tasks combo, local tasks are marked with the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/local_task.png) icon, and always have the white background color.  

## Opening Tracker Tasks 

Tracker tasks are loaded to your IntelliJ IDEA once you connect it to your issue tracker. 

To open a tracker task:
1. Open the list of available tasks:
* Navigate to **Tools** > **Tasks & Contexts** > **Open Task**, or
* Click the tasks combo on the toolbar.
2. In the **Open Task** dialog, select the necessary task.

Tracker tasks are marked with the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/tracker_task.png) icon in the tasks combo. They have the light-purple background color until they are opened in IntelliJ IDEA. After a tracker issue is opened in IntelliJ IDEA, its background color changes to white.

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/open_tasks.png)

## Viewing Closed Tasks

You can force IntelliJ IDEA to display already closed tasks. 

A _closed local task_ is a task that is not associated with a changelist provided that the entire project or the affected directory is under version control. 

For more information, refer to [Associating a Project Root with a Version Control System](https://www.jetbrains.com/help/idea/associating-a-project-root-with-a-version-control-system.html) and 
[Associating a Directory with a Specific Version Control System](https://www.jetbrains.com/help/idea/associating-a-directory-with-a-specific-version-control-system.html).

A _closed tracker task_ is a tracker task that has the closed status in your issue tracker. 

To view closed tasks, select the **Include closed tasks** check box or press `Shift+Alt+N`.

Closed tasks will be light-colored on the list. 

## Opening a Task for the First Time 

When you open a tracker task or local task for the first time, the **Open Task** dialog will prompt you to change task configuration: 

**Update issue information** — (available only for tracker tasks) select this check box if you want to update issue state and then select a new task state from the drop-down list.

**Clear current context** — select this check box if you want to clear the context associated with this task.

**VCS operations** (available only when version control is enabled in your project)

**Create branch <branch name> from <base branch name>** — select this check box to create a new branch from the existing one.

**Use branch** — select this check box to use the existing branch.

**Create changelist** — select this check box to have IntelliJ IDEA create a new changelist for the specified task. By default, the text field shows the issue tracker item's description. 

[IMG]


***

See next: [Switching Between Tasks](https://github.com/alexandrazolushkina/IntelliJ/blob/master/switch_tasks.md#switching-between-tasks)

Go back to: [Tasks in IntelliJ IDEA](https://github.com/alexandrazolushkina/IntelliJ/blob/master/tasks_in_idea.md)
