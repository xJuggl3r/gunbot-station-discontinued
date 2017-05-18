## Welcome, T+, to Easy Gun | Special Ammo for yout GUNBOT ^^

V. 0.2

### This short guide will brief instruct you about Easy Gun workings.

### 1 - Connecting to the server

In Mac, you’ll use **Terminal** to login:

**ssh root@xxx.xxx.xxx.xxx**  <-- your ip

To save a remote connection (so that you don’t have to type in the command every time):

1.  Select Shell then New Remote Connection… from the top menu
2.  Under the Server column, click on the + icon to add a new connection.
3.  Enter the hostname when prompted by the dialog.
4.  Enter your username (root) in the User field and click Connect_._

_![Saving a remote connection](https://i.gyazo.com/59ccac1763fcb3eb61a54fd3b0a6f4b0.png)_

The terminal will ask you the password. Copy it and paste it with right click. **No characters will be displayed**. Press enter.

![](https://i.gyazo.com/1683800f9cf69cb739ab437298cb4ed5.png)

You will receive a welcome message from the server:

![](https://i.gyazo.com/ba2de1fe5cdc2396d58ac33dc94e5086.png)

For manipulating files, Fetch is a good alternative. Its available freely at [http://webstore.illinois.edu/](http://webstore.illinois.edu/)

1.  Double-click on the Fetch dog icon in your Applications folder.

2.  The connection dialog box opens. Fill in the **Hostname:**, **Username:**, and **Password:** boxes with the name of the machine you’re connecting to, your login ID on that machine, and your password on that machine.  
    In the figure, example1 is logging into [tigger.uic.edu](http://tigger.uic.edu) and her NetID is example1.  
    The **Password:** is her ACCC common password.  
    Select **SFTP** from the dropdown list, and click **Connect**.

    ![](https://i.gyazo.com/8bae6446b27f142c44d0e7ba0649027e.png)

3.  If this is a connection that you will want to use again, click the heart icon at the end of the Hostname: line before you click Connect, and click Make Shortcut in the small dialog box that opens. This opens another dialog box where you enter the name for the shortcut. The default name for the shortcut will be the host name. If you also click Make this the default shortcut, it will be opened by default for you when you open Fetch. Click OK to create the shortcut. The shortcuts are listed in Fetch’s other screen, Fetch Shortcuts, which is at the top left of your desktop, where you can delete or edit them. You can use them from the heart dialog box.

4.  Then example’s home directory on tigger will be displayed in Fetch’s screen:

    ![](https://i.gyazo.com/113f2cb24209b545843054c2444b6ec8.png)

5.  You can highlight a file and click Get to download it, or click Put to open up a Mac file dialog box to select a file to upload. But it’s easier to double-click on the name of a directory that you want to open, double-click the name of a file that you want download, and drag and drop a file from your Mac to the Fetch screen to upload it or vice versa  
    .

6.  To change a file on the server’s permissions or to delete it, Control-click on its name, and select Get Info or Delete item respectively. To change the permissions, click in the type of permissions you want to give and click Apply.

## 2\. Knowing Easy Gun

Easy Gun is design to make the pair management a painless task. Although still in an early version, it already counts with some great features like:

*   Controllable by mouse
*   Easy pair setup (autostart still not available in this version)
*   Auto Save
*   Best currencies based on 24h volume change
*   Simple Fees calculator
*   Simple Profit calculator
*   Easy pair start

### 2.1 Starting the system

After logged in the server, you'll want to access Gunbot control panel. For that, type **gunbot** and **press enter**:

In your case, since the system is already set up with some pairs being executed, you will see a screen like this:

![](https://i.gyazo.com/a2af9131667185ad75822caef04f3c03.png)

Here we can see the hardware monitor, the volume change of some coins and a welcome message. In the top we can find the menu, which will be covered in details later on.

### 2.2 Basic Commands - Moving around

<span style="color: #ff0000;">You can use your mouse all the time</span>. Some limitations, like copy and paste data, still apply and will be adressed in a later update.

To **move around the tabs, just click on the selected one**.

Easy Gun is based in Tmux, so the keyboard commands consist in a PREFIX followed by a Charater. The Prefix is **Ctrl+A**

To <span style="color: #ff0000;">move to the next tab</span>, type Prefix + N, or **CTRL+A** and then '**n**'

To <span style="color: #ff0000;">move to the previous tab</span>, **CTRL+A** and then '**p**'

To <span style="color: #ff0000;">move to a chosen tab</span>, **CTRL+A** and then '**its correspondent number**'. Ex: **CRTL+A 0** takes to the Stats window.

To <span style="color: #ff0000;">view a list of available windows</span>. press **CTRL+A** and then '**w**'. Left click or use keybord arrows to move to desired window and press Enter. You can also type the correspondent number and press Enter:

![](https://i.gyazo.com/db313a89018e26120e33880f5c767dbf.png)

To<span style="color: #000000;"> **move around panes**</span> - or the small windows inside the big one - press **CRTL+A** followed by **UP, DOWN, LEFT or RIGHT**. You can also directly click in the chosen pane. Right click will distinguish it from the others.