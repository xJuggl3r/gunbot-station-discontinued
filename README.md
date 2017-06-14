## Welcome to Easy Gun | Special Ammo for yout GUNBOT ^^

V. 0.2

### This short guide will brief instruct you about Easy Gun workings.

## 1 - Connecting to the server

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

### 2.3 Creating Windows and Panes

To start more more pairs, you will need to create room for them. While this feature is not automated, here are the commands:

**Create a new window** pressing **CTRL+A c** 

**Create a new vertical pane** pressing **CRTL+A | **(the character above '\' backslash)

**Create a new horizontal pane** pressing **CTRL+ -** (minus)

#### In order to make it easier, **use the following commands to make a new pairs window**:

#### **CTRL+A c**, **CTRL+A -**, **CTRL+A -**, **CTRL+A -**, **CTRL+A ALT+5**

This will generate a window like this:

![](https://i.gyazo.com/7cf1540326639e534529f252b95eade3.png)

**OBS: **According to your screen size, 6 panes can be added instead of four. The default number assures that all pair data will be displayed in the pane. 

## 4. Creating and Starting Pairs

EasyGun counts with a Pair Creator. To start it, type **pairs** and press **Enter**:

![](https://i.gyazo.com/4675c7157af13c5e809cf9d1683f9560.png)

Choose the exchange by pressing its corresponding number and press Enter.

Populate the pairs you want to run. Choose 4 pairs with the same setup:

![](https://i.gyazo.com/423ba58a85d5e303a47c3497e2ccef11.png)

After pressing Enter, choose the desired strategies for buying and selling. A confirmation will be prompted. You can scroll the pane and check the info. If everythin is ok, press Y and Enter to save the pairs:

![](https://i.gyazo.com/b478d5500bd7a6e6bea2d37d523a078a.png)

 For now, press n to autostart pairs:

![](https://i.gyazo.com/13a621958915c7629b94588fa192b7ec.png)

Now, in each pane, type the corresponding pair and press Enter.

In this case, the command would be:

polo_ETC

polo_ETH

polo_FCT

polo_XRP

Now the four pairs are running.

#### TIP: Rename the windows for better management with CTRL+A ,

The status bar will change. Delete the content and type the new one and press Enter:

![](https://i.gyazo.com/fce7315a039f2e46a8500ab5b1111dc8.png)

To add more pairs, create a new window and panes, run the Pair Generator and repeat the process.

## 5\. Easy-Gun Tools

For your convenience, the system offers some tools to help you with Poloniex-related information. Below are the current features and their commands. Please observe that for private info, a brand new API key will be needed. Please no dot enable trading or withdrawal features.

### 5.1 Anapolo

Displays the coins with highest volume change during a period of time ranging from 1 week to 1 hour. Very useful now that this feature is not available in GB 3.2.  
Command: **anapolo**

**![](https://i.gyazo.com/59e3b7b1a5066def976658b315762880.png)**

### 5.2 Know your Fees

Lists how much fee you have paid for each coin you have traded, displaying the total amount in BTC;  
Command: **fees**

![](https://i.gyazo.com/796255e7a7c04d8f19dc6e1d91bdbd4a.png)

### 5.3 Profits and Overview

These ctools displays the current status of the account, in a simple or detailed view.  
Command: **profits**

![](https://i.gyazo.com/8f10957ea984168023ed23317e01987a.png)

Command: **overview**

![](https://i.gyazo.com/c5ef39f5c3767d610db2761fff638f55.png)

More features will be added according to the next releases.

_Send your feedback to @criptonauta in Telegram or PM me at [https://gunthy.org](https://gunthy.org)_