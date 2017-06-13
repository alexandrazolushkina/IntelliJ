# Working with Tasks

#### Switching Between Tasks

After you have opened the necessary tasks, you can easily switch between them. 
To switch to another task, do one of the following:

* From the main menu, select **Tools** > **Tasks & Contexts** > **Switch Task** and then select the necessary task from the list.
* Click the tasks combo in the main toolbar, select the necessary task from the list. Then, click the right-arrow and select **Switch to**. 
* Use the **ALT**+**SHIFT**+**T** shortcut. 

Note that a task can be opened in a separate context. This will let you work with tasks and switch between them without mixing the changes that were made between both tasks. For more information, refer to ![Working with Contexts in IntelliJ IDEA](https://github.com/alexandrazolushkina/IntelliJ/edit/master/working_with_contexts.md).

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/manage_tasks.png)

***
#### Viewing Task Description

When you are choosing a task to switch to, the list in the **Switch to** task pop-up window shows only IDs of tasks and their summaries. This information is not always sufficient, because it reflects neither the steps that lead to the problem nor the related discussion.

You can learn more about your current task in two ways.

* View the description of a task in a pop-up window:<br>
  From the main menu, select **Tools** > **Tasks & Contexts** > **Show '_task ID_' Description**.

* Open a task in the browser and view both the issue description and all the comments on it:<br>
  From the main menu, select **Tools** > **Tasks & Contexts** > **Open '_task ID_' in Browser**. 

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/show_description.png)
  
***
#### Editing Tasks

In IntelliJ IDEA, you can edit task summary, change a branch associated with this task and select another changelist. 

To modify task details, open the **Edit Task** dialog:

* From the main menu, select **Tools** > **Tasks & Contexts** > **Edit _task_name_**.
* Click the tasks combo in the main toolbar, select the necessary task from the list. Then, click the right-arrow and select **Edit**.

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/edit_task.png)

***
#### Closing Tasks

Once you have finished your work on the task, your can close the task, commit the changes and merge the newly created branch, if you require. 

To close a task, navigate to **Tools** > **Tasks & Contexts** > **Close Active Task** (or press **ALT**+**SHIFT**+**W**). 


This will close the current context in the IDE. Select the necessary check boxes to commit changes and, optionally, merge the branch that was created.

For tracker tasks, you can also change their state. The new state will be propagated to your issue tracker. 

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/closing_tasks.png)


***

#### Deleting Tasks

If you do not need a task to appear in your IntelliJ IDEA, you can remove it from the list of tasks.

To delete a task:

1. Click the tasks combo on the main toolbar.
2. Select one or more tasks you want to delete. 
   Use **SHIFT** (for adjacent items) or **CTRL** (for non-adjacent items) keys for multiple selection.
3. Click the right-arrow button, and select **Remove**.

When you are deleting tracker tasks, you remove them from the IDE. They will remain in your issue tracker. Local tasks in this case will be completely removed, since they are not connected to your issue tracker. 

***

##### See also 

![Working with Contexts in IntelliJ IDEA](https://github.com/alexandrazolushkina/IntelliJ/blob/master/working_with_contexts.md)

***

Go back to ![Home Page](https://github.com/alexandrazolushkina/IntelliJ/blob/master/README.md)
