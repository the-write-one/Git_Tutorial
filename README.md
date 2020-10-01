# Introduction

This tutorial is intended for novice Git users and guides you through the step-by-step Git Setup wWzard. You will need to install Git use the command line tool. The following equipment and tools are used:

1. Chrome browser (version 85.0.4183.121).
You can use a browser of your choice to download Git.
  
2. Windows 10™ operating system.

3. Git Setup (version 2.38.0).
This will automatically download when your run the executable file.

# Installing Git for Windows

1. Open a browser and go to [https://git-scm.com/download/win](https://git-scm.com/download/win) to download Git.

2. Select the hyperlink applicable to your system setup. This tutorial uses the **64-bit Git for Windows Setup** hyperlink.
An executable (.exe) file appears in the lower left corner of your browser window. 

3. Click the .exe file to start the Git Setup Wizard. 

# Configuring Git Through the Git Setup Wizard

This section is guides you through the Git Setup wizard in explicit detail. If you are already familiar with the Git proceed throught.

1. Accept the **GNU General Public License** on the **Information** screen and click **Next**.

<img src="images/1_GNU_Public_License.png" width="300"/>

2. Select the where you want to install Git and click **Next**. Click the **Browse** button to customize the installation location. By default, Git will install on your local drive.

<img src="images/2_Select_Destination_Location.png" width="300"/>

3. Check the components you want to install on the **Select Components** screen and click **Next**. 
The recommended defaults are already selected. For quick access to Git, install all the icons to your desktop.

<img src="images/3_Select_Components.png" width="300"/>

4. Click the drop-down menu and select the default editor you want Git to use and click **Next**.
Which text editor to use? It is a personal preference. If you are unfamiliar with text editors, use one such as Notepad ++ . Text editors like Vim or Emacs are very powerful, but require a steep learning curve.

<img src="images/5_Choosing_Default_Editor.png" width="300"/>
 
5. Select where Git Setup places the Git program shortcuts and click **Next.** Select **Browse** to customize the folder location for the shortcuts.

<img src="images/4_Select_Start_Menu_Folder.png" width="300"/>

6. Choose how you would like to use Git from the command line in the **Adjusting your PATH environment** screen and click **Next**.
The recommended option is to select **Git from the command line and also from 3rd-party software**.

<img src="images/6_Ajusting_Path_Environment.png" width="300"/>
 
7. Select which SSL/TLS library you want Git to use for HTTPS connections and click **Next**.
SSL/TLS libraries use certificates to validate secure communications between web browsers and servers.

<img src="images/7_Choosing_HTTPS_Transport.png" width="300"/>

8. Select which terminal emulator you want to use with your Git Bash and click **Next**.
Terminal emulators enable a machine to connect to and communicate with another machine using a command-line or graphical interface.

 <img src="images/9_Configuring_Terminal_Emulator.png" width="300"/>

9. Choose the default behavior of git pull and click **Next**.

<img src="images/10_Choose_Default_Behavior.png" width="300"/>

10. Configure how Git treats line endings in a text file. By default, **Checkout Window-style, commit Unix-style line endings** is selected. 
This relates to the way data is formatted and changing this option may cause problems.
    - Windows checkout style uses menus and the Unix style uses a line feed.
     
<img src="images/8_Configure_Line_Ending_Conversations.png" width="300"/>

10. Choose a credential helper and click **Next**.
The credential helpers are externals programs from which Git can request both usernames and passwords. These are used so you don't have to type in a username and password every time when accessing a program. Credential helpers can cache your credentials in memory for a short period of time or store keeps credentials indefinitely on disk.

<img src="images/11_Choose_Credential_Helper.png" width="300"/>
   
11. Choose to enable configure extra features and click **Next**. By default, **Enable file system caching** is selected. Enabling system caching provides a significant performance boost.
 **Enable symbolic links** requires permissions. Symbolic links make sure files are in consistent places without moving or copying the original. Multiple copies of the same file can exist in different places, but only one file is referenced.

<img src="images/12_Configuring_Extra_Options.png" width="300"/>
 
12. Choose to configure experimental bleeding-edge features and click **Install**. For novice Git users this feature is not recommended. Bleeding-edge features relates to the latest innovative technologies or software builds, which can result in an unstable environment.

 <img src="images/13_Configuring_Experimental_Options.png"" width="300"/>

13. Wait while Setup the extracts files to install Git on your computer. When installation is complete the wizard forwards you to the next screen. Click **Next** to exit the Git Setup Wizard.

<img src="images/14_Installing.png" width="300"/>

14. Verify the settings on the ** Completing the Git Setup Wizard** screen and
select **Launch Git Bash** and **View Release Notes**. Git Bash is the command line utility you will need to communicate with Git.

<img src="images/15_Completing_Git_Setup_Wizard.png" width="300"/>


Congratulations! You have successfully installed Git.

# Resources
The following are extra resources to help you through the installation process. 
1. Installing Git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
2. How to Install Git on Windows: https://phoenixnap.com/kb/how-to-install-git-windows


