# Creating Local Tasks and Opening Tracker Tasks

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
* the tasks combo on the toolbar.
The **Open Task** dialog will appear. 
2. Select the necessary task.

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

***

See next: Switching Between Tasks
