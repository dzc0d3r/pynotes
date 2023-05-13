# Let's talk about what you need ?

Before we continue forward together, let's talk about what you need :grin:. 

The first important thing is obviously determination and persistency :muscle: this is the case not just for learning Python or any programming language but for acquiring any skill in life, my advice for you is to never quit no matter how difficult things get. Have always faith and discipline .. learn and code everyday even if it's a little as a single line of code :innocent:  

## Prerequisites
After our little motivation speech let's discuss what prerequisites you need to start coding in python :


- [Download and install Python](#download-and-install-python)
- [Text Editor or Fully Edged IDE](#text-editor-ide) 
- [Python VSCode Extension](#python-extension-for-visual-studio-code)
- [Dealing with command line (Windows)](#dealing-with-command-line-windows)
- [Knownledge in Programming](#knownledge-in-programming)

<!-- - Path Knowledge  
talk about different paths you can choose after learning python basics like web dev , desktop apps, extend it in an extra article  etc 

-->


> Although i'm using a Linux Distribution, i will explain the steps on Windows too .. for MAC users just go buy a Python Course lol :stuck_out_tongue_winking_eye: ... just kidding i will explain the steps on MacOS too :satisfied:


### Download and install Python

Obviously if you want to use python, you need python to be installed on your system.
Installing Python on Windows, macOS, and Linux is relatively straightforward.

#### For Windows users

##### 1 - Download python
Head over to the download page on [Python official Website](https://www.python.org/downloads/){:target = "_blank"}, next click on the yellow button where it says Download python xxx, the download will start as soon as you click on the donwload button. 


##### 2 - Run the Installer
After you have downloaded the installer, locate the file on your computer and double-click it to run it.

The installer will guide you through the installation process. On the first screen, you will see an option to "Add Python to PATH." Make sure this option is selected, as it will make it easier to use Python from the command line.

##### 3 - Verify the Installation
Once the installation is complete, you can verify that Python is installed by opening a command prompt and typing python. This should launch the Python interpreter, and you should see a message indicating the version of Python you have installed.



#### For Linux users

Most Linux distributions come with Python pre-installed, the first thing you need to do is to verify the version present on your system.. to do this open a terminal and type the following command :

```bash 
python --version

```

<!-- if the version is old or you want to use a more recent version of python.

the read this articles 

ok i'll be adding a sections called Extras where i can add more detailed informations on different subjects and topics-->


#### For MacOS users 
##### 1 - Install Xcode Command Line Tools
Before you can install Python on macOS, you need to install the Xcode Command Line Tools. To do this, open a terminal and type the following command:

``` bash 

xcode-select --install

```
This will prompt you to install the Command Line Tools. Follow the instructions to complete the installation.

##### 2 - Install Homebrew 
Next, you will need to install Homebrew, which is a package manager for macOS. To install Homebrew, open a terminal and type the following command:


``` bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

##### 3 - Insatll python 
With Homebrew installed, you can now install Python by typing the following command in the terminal:

```bash
brew install python
```
##### 4 -  Verify the Installation 
Once the installation is complete, you can verify that Python is installed by opening a terminal and typing ```python3```. This should launch the Python interpreter, and you should see a message indicating the version of Python you have installed.



### Text editor / IDE
I highly recommend using [Visual Studio Code](https://code.visualstudio.com/){:target = "_blank"}, as it is a very popular coding editor used by millions of developers around the world, it has rapidly gained popularity among them, ranking as the most popular development environment overall in [Stack Overflow’s 2019 Developer Survey](https://insights.stackoverflow.com/survey/2019){:target = "_blank"}. you can read more here on [why vscode](https://code.visualstudio.com/docs/editor/whyvscode){:target = "_blank"}.

If you want a fully edged IDE then i would recommend to use [PyCharm](https://www.jetbrains.com/pycharm/){:target = "_blank"}.


#### Installation proccess on Windows
##### 1 - Download Visual Studio Code 
- Go to the [official Visual Studio Code website](https://code.visualstudio.com/){:target = "_blank"}.
- Click on the "Download for Windows" button to download the installer.

##### 2 - Run the Installer
- Once the installer is downloaded, double-click on it to start the installation process.
- The installer will open a window. Click on the "Next" button to proceed.
- On the "Select Additional Tasks" screen, leave the default options checked and click on the "Next" button.
- On the "Select Start Menu Folder" screen, leave the default options checked and click on the "Next" button.
- On the "Select Additional Tasks" screen, leave the default options checked and click on the "Install" button.
- Wait for the installation process to complete.

##### 3 - Open Visual Studio Code
- Once the installation is complete, click on the "Finish" button to close the installer.
- Open Visual Studio Code by double-clicking on the desktop shortcut or searching for it in the Start menu.

#### Installation proccess on Linux
##### 1 - Using snap to install vscode
For Linux i would suggests using `snap` to install vscode. just make sure that snap is pre-installed and ready to go on your system, this is the case for Solus, Manjaro, Ubuntu, and most Ubuntu Flavors.


Of course you can downlaod the `deb` or `rpm` file and install it that way.. or better yet use your default package manager like `apt` if you are on Ubuntu for example, but for simplicity sake let's agree on using `snap` instead.


To install visual studio code using snap, open a terminal and run the following command : 

``` bash 
sudo snap install code --classic

```

##### 2 - verify the installation 
After the installation is complete, run the following command to launch vscode :

```bash 
code 
```
You can search for code and run it on your application menu depending on what desktop environment you're using.
<!-- 
again i will add an extra section to expalin more, but for now i'm on a hurry
 -->

#### Installation Proccess on MacOS
##### 1 - Download Visual Studio Code

- Go to [the official Visual Studio Code website](https://code.visualstudio.com/){:target = "_blank"}.
- Click on the "Download for Mac" button to download the installer.

##### 2 - Run the Installer

- Once the installer is downloaded, double-click on it to start the installation process.
- The installer will open a window. Drag the Visual Studio Code icon to the "Applications" folder to install it.
- Wait for the installation process to complete.

##### 3 -  Open Visual Studio Code

- Once the installation is complete, open the "Applications" folder.
- Double-click on the Visual Studio Code icon to launch the application.


#### Python extension for Visual Studio Code


The Python extension for VS Code by Microsoft is a powerful tool for Python developers of all levels. 

Its rich language support, debugging capabilities, and code navigation tools can help you write and debug code more efficiently. 

Additionally, its support for testing frameworks, linting, and the integrated terminal can make your workflow more streamlined and productive. this extension is definitely worth checking out.

##### 1 - Installation
Installing the Python extension for VS Code is simple.

- Open VS Code.
- Click on the "Extensions" icon on the left-hand side of the window (or press ++ctrl+shift+x++ ).
In the search bar, type "Python".
- Click on the "Install" button next to the Python extension.

Once the installation is complete, you'll be prompted to reload VS Code. Click the "Reload" button to complete the installation process.


#### Dealing with command line (Windows)
For Windows users, since we'll be using the command prompt a lot. it's better to use a console emulator for Windows, i would recommend using Cmder, as it is popular among Windows users who want an improved command-line interface experience. 

It is an open-source project that provides a powerful and customizable console experience that includes tabbed interface, command-line syntax highlighting, and customizable hotkeys.. etc 

##### Insallation
- Go to [the Cmder website](https://cmder.app/){:target = "_blank"}.
- Scroll down to the "Download" section and click on the "Download Full" button to download the latest version of Cmder.
- Once the download is complete, extract the contents of the downloaded ZIP file to a directory of your choice. You can do this by right-clicking on the ZIP file and selecting "Extract All..." from the context menu.
- Move the folder to `C:\Program Files`.
- Open the cmder folder .. Double-click on the Cmder.exe file to launch the application.

##### Create a Shortcut

- Right-click on the Cmder.exe file and select "Create shortcut" from the context menu.
- copy the newly creaated shortcut to the Desktop.


#### Knownledge in Programming
Before we move on .. i would really suggest to you learning the very basics in programming, One great resource to acquire such knowledge is CS50 By Harvard University, you can find the full lectures on Youtube (just search for cs50 harvard on youtube.) 


<!-- add an article about this in extras  -->