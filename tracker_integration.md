# Enabling Integration with Issue Tracking Systems

You can bind your account in an issue tracker to your project IntelliJ IDEA and work with issues directly from IntelliJ IDEA. 

IntelliJ IDEA supports integration with the majority of existing issue trackers. It also allows you to connect to a generic issue tracker, if you require. 

The process of integration is rather simple and consists of 3 steps:
1. Checking if the **Task Manager** plugin is installed. This plugin is required if you want to work with tasks. 
2. Specifying connection details. 
3. (_Optionally_) Configuring automatic updates of issues from your issue tracker.

#### Supported Issue Tracking Systems

IntelliJ IDEA supports integration with the following issue tracking systems:

* [Jira](https://www.atlassian.com/software/jira)
* [YouTrack](https://www.jetbrains.com/youtrack/)
* [Lighthouse](http://lighthouseapp.com/)
* [PivotalTracker](https://www.pivotaltracker.com/)
* [Redmine](http://www.redmine.org/)
* [Trac](https://trac.edgewall.org/)
* [FogBugz](http://www.fogcreek.com/fogbugz/)
* [Mantis](http://www.mantisbt.org/)
* [Generic server](https://www.jetbrains.com/help/idea/configuring-generic-task-server.html)
* [Asana](https://asana.com/)
* [Assembla](https://www.assembla.com/projects)
* [Sprint.ly](http://sprint.ly/)
* [Trello](https://trello.com/)
* [Gitlab](https://about.gitlab.com/)
* [Bugzilla](https://www.bugzilla.org/)
* [GitHub](https://github.com/)
 
### Enabling the Task Manager Plugin

Before connecting your issue tracker account to your project, make sure that the **Task Management** plugin is enabled. 
The plugin is bundled with IntelliJ IDEA, and it is usually enabled by default after IntelliJ IDEA installation. 

To check if the plugin is on:

1. Navigate to **File** > **Settings** > **Plugins**. 
2. Locate the **Task Manager** plugin and make sure that the check box next to it is selected. 

  ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/task_manager_plugin.png)

### Enabling Integration with Issue Tracking Systems

To enable integration with an issue tracking system:

1. Access the **Servers** dialog box. Use any of the listed ways: 
* Navigate to **File** > **Settings** > **Tools** > **Tasks** > **Servers**. 
* Navigate to **Tools** > **Tasks & Contents** > **Configure Servers**.
* Navigate to Tools > Tasks & Contents > Open Task (or press Alt + Shift +N) and click the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/icon.png) icon.
* Click the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/icon.png) icon on the toolbar and select **Tools** > **Tasks** > **Servers**.
2. Click the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/add.png) icon, or press **ALT** + **INSERT**, and select the necessity issue tracker form the list.

> **If a server is not trusted, IntelliJ IDEA shows a dialog box suggesting you to accept the server, or reject it. If you accept the server as trusted, IntelliJ IDEA writes its certificate to the trust store. This dialog will not be displayed the next time you connect to the server.**

3. In the Servers dialog box, enter connection details. Here is an example for YouTrack:

    **Server URL** — enter the URL address of your issue tracking server.<br>
    **Usermame** and **Password** — specify your issue tracker account credentials. These credentials will be different for different issue tracking systems.<br>
    **Search** — specify rules according to which IDEA will choose which issues to display.<br>
    
    **Share URL**— select the Share URL check box to allow access to the specified server for other members of your team.<br>
    **Use proxy** — (optionally) select this check box and specify the proxy if you want to access the server via proxy.<br>
For more information on how to configure proxy, refer to [HTTP Proxy](https://www.jetbrains.com/help/idea/2017.1/http-proxy.html) .<br>

Click ****Test**** to make sure connection details are correct.<br>

Each issue tracker may require its own set of data to establish a connection. 
  
 For more information on how to establish a connection with a generic tracker, refer to [Configuring Generic Task Server](https://www.jetbrains.com/help/idea/configuring-generic-task-server.html).

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/server_settings.png)

> _Sasha's comment: Here must be a description of how to connect to other trackers, 'cause required connection details differ for different trackers._ 

### Synchronizing IDEA and your Issue Tracker

Optionally, you can configure synchronization parameters between IntelliJ IDEA and your issue tracking system. 

This will force IntelliJ IDEA to connect to your issue tracking system according to the specified frequency and refresh cached issues.
1. Open the **Settings** dialog. <br>
    To do so, navigate to **File** > **Settings**, or click the ![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/icon.png) icon on the toolbar.<br>
2. Select **Tasks** from the menu on the left.<br>
3. Select the **Enable issue cache** check box and specify cache settings.

When you need to switch to a task, the up-to-date information will be already at your disposal, so you do not need to wait until IntelliJ IDEA establishes connection with the tracker and retrieves the information.


> **This configuration is especially recommended when working with rather "slow" issue tracking systems.** 

![](https://github.com/alexandrazolushkina/IntelliJ/blob/master/enable_issue_cache_img.png)

After connection between IntelliJ IDEA and your issue tracker is established, you can [start working with issues](https://github.com/alexandrazolushkina/IntelliJ/blob/master/managing_tasks.md) from the IntelliJ IDEA interface. 

***

Go back to ![Home Page](https://github.com/alexandrazolushkina/IntelliJ/blob/master/README.md)
